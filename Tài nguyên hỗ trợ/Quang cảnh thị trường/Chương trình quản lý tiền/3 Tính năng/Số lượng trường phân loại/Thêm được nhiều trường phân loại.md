---
share: true
created: 2023-09-05T16:17
updated: 2024-07-18T01:11
---
Yêu cầu đầu vào:: 
Đồng thời có thêm tính năng::
Loại chương trình:: [[Chương trình kế toán]], [[Template thu chi trên Excel]], [[Chương trình phân loại dữ liệu tự động]]

Đáp ứng cho nhu cầu hoặc tính năng:
```dataview
list
from "Tài nguyên hỗ trợ/Quang cảnh thị trường/Chương trình quản lý tiền" 
where contains(file.outlinks,[[]])
where file.name != "Chương trình quản lý tiền" 
```