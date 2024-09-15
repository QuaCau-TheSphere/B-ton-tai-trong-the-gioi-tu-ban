---
share: true
created: 2023-09-05T16:17
updated: 2024-09-15T10:39
alias:
  - Mở các buổi chia sẻ lớp học ngắn buổi huấn luyện
  - Lập nhóm tổ chức các buổi chia sẻ hướng dẫn
  - Nhóm tổ chức các buổi chia sẻ hướng dẫn
  - Mentor mentee coach train
---
Yêu cầu đầu vào:: [[Có tên tuổi, uy tín, chứng nhận]]
Hình thức:: [[Chia sẻ, đào tạo, huấn luyện]]

```dataviewjs
const đdGhiChúThưMục = dv.current().file.path
const thưMụcHiệnTại = dv.current().file.folder
const dsTấtCảGhiChúĐượcLấy = dv.pages(`"${thưMụcHiệnTại}"`).file.link
const kếtQuả = dsTấtCảGhiChúĐượcLấy.filter(i=>i.path !== đdGhiChúThưMục)
dv.list(kếtQuả)
```