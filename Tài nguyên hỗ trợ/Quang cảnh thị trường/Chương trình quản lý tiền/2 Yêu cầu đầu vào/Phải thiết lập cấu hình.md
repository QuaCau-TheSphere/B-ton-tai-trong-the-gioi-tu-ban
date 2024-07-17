---
share: true
created: 2023-09-05T16:17
updated: 2024-07-18T01:11
---
Yêu cầu đầu vào:: [[Có thể dành thời gian nghiên cứu]]
```dataview
list without id split(file.folder, "/" )[3] + ": " + file.link
from "Tài nguyên hỗ trợ/Quang cảnh thị trường/Chương trình quản lý tiền" 
where contains(file.outlinks,[[]])
where file.name != "Chương trình quản lý tiền" 
```