## Change timestamp note name and folder
```
<%+ dir = '/🧩 Resources/⏰ Timestamps/' + moment(tp.file.title,'YYYY-MM-DD').format('YYYY') + '/' + moment(tp.file.title,'YYYY-MM-DD').format('MM[-]MMMM') + '/' + moment(tp.file.title,'YYYY-MM-DD').format('YYYY[-]MM[-]DD[-]dddd') %>
<%+ console.log(dir) %>
<%+* if (!tp.file.exists(dir)) { await this.app.vault.createFolder(dir) } %>
<%+ await tp.file.move(dir) %>
```