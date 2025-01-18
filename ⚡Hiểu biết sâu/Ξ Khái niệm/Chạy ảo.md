---
share: true
created: 2024-09-30T12:08
updated: 2025-01-13T09:35
---
```dataview
LIST rows.file.link
WHERE contains(khái-niệm, [[]])
GROUP BY split(file.folder, "/")[3]
```