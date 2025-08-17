---
created: <% tp.file.creation_date() %>
---

# <% moment(tp.file.title,'YYYY-MM-DD').format("dddd, MMMM DD, YYYY") %>

<< [[<% tp.date.now("YYYY-MM-DD-dddd", -1, tp.file.title, "YYYY-MM-DD-dddd") %>]] | [[<% tp.date.now("YYYY-MM-DD-dddd", 1, tp.file.title, "YYYY-MM-DD-dddd") %>]]>>

---

# 📝 Notes
- 

---

### Notes created today

```dataview

List FROM "" WHERE file.cday = date("<%tp.date.now("YYYY-MM-DD")%>") SORT file.ctime asc

```

### Notes modified today

```dataview

List FROM "" WHERE file.mday = date("<%tp.date.now("YYYY-MM-DD")%>") SORT file.mtime asc

```

### Notes linked to today

```dataview 

List without id link(file.link, title) where contains(this.file.inlinks, file.link)

```