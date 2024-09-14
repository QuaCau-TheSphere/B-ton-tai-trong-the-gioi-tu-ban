---
share: true
created: 2024-06-28T23:05
updated: 2024-09-14T20:31
alias:
  - Quản lý nhóm nhân viên ảo
  - Nhân viên công ty vì muốn chạy chỉ tiêu nên sẵn sàng mua cho bạn
---

Ví dụ, đây là yêu cầu công việc của một nhân viên bán hàng trong VNPAY:
- Chụp hình chấm công mỗi sáng vào 8h30
- [[Công ty không quan tâm dữ liệu cửa hàng do nhân viên gửi về có bị trùng lặp hay không|Thêm dữ liệu 10 khách hàng tiềm năng lên cơ sở dữ liệu chung mỗi ngày trong 30 ngày đầu]]
- Giới thiệu sản phẩm tới khách hàng tiềm năng
- Viết hợp đồng
- Gắn mã
- Chăm sóc khách hàng
- Tạo được 10 hợp đồng mỗi tháng

Đầu tiên, một người sẽ đóng vai trò [[Làm nhân viên ảo]] của công ty. Các công việc thực sẽ do những người khác đảm nhiệm.

Khó khăn:
- Tìm được các chủ cửa hàng chấp nhận trả tiền cho mình
- Tìm được nhiều tài khoản ngân hàng khác chủ

Liên hệ:: [[Nguyễn Hữu Lộc|Nguyễn Hữu Lộc – 0783865410]]

```dataview
LIST rows.file.link
FROM "📐 Dự án/Chạy chỉ tiêu cho nhân viên các công ty/Chạy chỉ tiêu cho nhân viên các công ty trung gian thanh toán" 
WHERE file.name!=this.file.name
GROUP BY split(file.folder, "/")[3]
```

