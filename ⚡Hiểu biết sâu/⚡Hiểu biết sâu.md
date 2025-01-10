---
share: true
created: 2024-12-24T21:45
updated: 2024-12-24T21:47
---
```dataview
LIST rows.file.link
FROM "⚡Hiểu biết sâu"
group by split(file.folder, "/" )[1]
```