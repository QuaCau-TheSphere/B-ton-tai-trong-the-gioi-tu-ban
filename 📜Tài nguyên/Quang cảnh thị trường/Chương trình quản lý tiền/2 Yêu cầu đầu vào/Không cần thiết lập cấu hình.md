---
share: true
created: 2023-09-05T16:17
updated: 2024-07-27T18:33
---
Phù hợp cho nhu cầu:: 
Đáp ứng yêu cầu:: 

Đáp ứng cho việc:
```dataview
list without id file.link + " (" + substring(split(file.folder, "/" )[3], 2) + ")" 
from "📜Tài nguyên/Quang cảnh thị trường/Chương trình quản lý tiền" 
where contains(file.outlinks,[[]])
where file.name != "Chương trình quản lý tiền" 
```
