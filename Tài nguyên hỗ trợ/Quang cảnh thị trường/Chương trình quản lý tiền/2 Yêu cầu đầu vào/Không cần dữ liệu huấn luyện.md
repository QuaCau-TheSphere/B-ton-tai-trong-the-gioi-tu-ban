---
share: true
created: 2023-09-05T16:17
updated: 2024-07-17T16:44
---
Phù hợp cho nhu cầu:: 
Yêu cầu đầu vào:: [[Phải thiết lập cấu hình]]

Đáp ứng cho việc:
```dataview
list without id file.link + " (" + substring(split(file.folder, "/" )[3], 2) + ")" 
from "Tài nguyên hỗ trợ/Quang cảnh thị trường/Chương trình quản lý tiền" 
where contains(file.outlinks,[[]])
where file.name != "Chương trình quản lý tiền" 
```
