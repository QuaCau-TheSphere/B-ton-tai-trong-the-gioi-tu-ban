---
share: true
created: 2024-12-24T21:48
updated: 2025-01-13T09:53
---
```dataview
LIST rows.file.link
FROM "📜Tài nguyên"
group by split(file.folder, "/" )[1]
```