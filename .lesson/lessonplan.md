# Lesson plan
  
---

CSS should look something like this:

```
.container {
  display: grid;
  grid-template-areas:
      ". alert" 
      "header header"
      "sidebar content"
      "footer footer";
  grid-template-columns: 1fr 3fr;
  grid-auto-rows: auto;
  gap: 20px;
}

header {
  grid-area: header;
}

article {
  grid-area: content;
}

aside {
  grid-area: sidebar;
}

footer {
  grid-area: footer;
}

.alert {
  grid-area: alert;
}
```