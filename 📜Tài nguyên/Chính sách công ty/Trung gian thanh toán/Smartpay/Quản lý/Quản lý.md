---
share: true
created: 2023-09-05T16:17
<<<<<<< HEAD
updated: 2025-01-11T12:34
=======
updated: 2024-12-24T22:36
>>>>>>> b337a3e (struct: thêm ❝Tài liệu❞ và ❝Khách hàng❞ trong ❝📐 Dự án/Giúp nhau thoát nợ/❞)
---
ASM là viết tắt của *area sale manager*, nghĩa là *quản lý bán hàng khu vực*.
RSM là viết tắt của *regional sale manager*, nghĩa là *giám đốc kinh doanh vùng*.
[[Thuật ngữ]]
```dataviewjs
const đdGhiChúThưMục = dv.current().file.path
const thưMụcHiệnTại = dv.current().file.folder
const dsTấtCảGhiChúĐượcLấy = dv.pages(`"${thưMụcHiệnTại}"`).file.link
const kếtQuả = dsTấtCảGhiChúĐượcLấy.filter(i=>i.path !== đdGhiChúThưMục)
dv.list(kếtQuả)
```