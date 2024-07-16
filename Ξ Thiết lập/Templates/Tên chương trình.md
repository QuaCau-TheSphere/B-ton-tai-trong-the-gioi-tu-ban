---
share: true
created: 2023-09-05T16:17
updated: 2024-07-17T01:07
---
```dataview
list without id split(file.folder, "/" )[3] + ": " + file.link
from "" 
where contains(file.outlinks,[[]])
where file.name != "Sơ đồ giữa các chương trình về quản lý chi tiêu cá nhân" 
```