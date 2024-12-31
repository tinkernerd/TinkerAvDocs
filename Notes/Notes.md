```dataview  
TABLE WITHOUT ID
link(file.path, title) AS "Note", type AS "Type", dateCreated AS "Date Created", file.mtime AS "Last Modified", status AS "Status"
FROM "Notes"
WHERE contains(category, "Aviation") AND type != "Dashboard"
SORT title ASC
```

```dataview  
TABLE WITHOUT ID
link(file.path, title) AS "Note", type AS "Type", dateCreated AS "Date Created", file.mtime AS "Last Modified", status AS "Status"
FROM "Notes"
WHERE type != "Dashboard" AND contains(book, "AIM")
SORT title ASC
```
## Class Notes
### Chapter 1
```dataview  
TABLE WITHOUT ID  
link(file.path, title) AS "Note", type as Type, dateCreated as "Date Created", file.mtime AS "Last modified", status as Status, chapter as "Volume/Chapter"
FROM #classnotes AND "Notes"
WHERE contains(category, "Aviation")
SORT title ASC
```
  
