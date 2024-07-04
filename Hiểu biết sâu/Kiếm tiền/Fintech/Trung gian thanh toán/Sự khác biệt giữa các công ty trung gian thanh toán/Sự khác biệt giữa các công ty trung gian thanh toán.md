---
share: true
created: 2024-07-04T23:52
updated: 2024-07-05T00:33
---
# Khác biệt về sản phẩm
| Sản phẩm | Ví điện tử | Máy POS |
| -------- | ---------- | ------- |
| Momo     | ✔          | ❌      |
| VNPAY    | ✔          | ✔       |
| Smartpay | ✔          | ✔       |
| Ecopay   | ✔          |         |
Chính vì Momo không có máy POS còn VNPAY có máy POS, nên Momo tập trung vào sự tiện lợi với người mua hàng, còn VNPAY tập trung vào sự tiện lợi với người bán hàng. [[VNPAY tập trung vào những cửa hàng lớn đủ để có nhu cầu dùng máy POS]]

# Chính sách mở tài khoản cửa hàng
Các công ty đều có tặng loa

| Sản phẩm | Phí rút tiền về ngân hàng                      | Đặc điểm                                                                                                                                                                          | Đối tượng quan tâm tới những đặc điểm này                                                             |
| -------- | ---------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| Momo     | <li>≤ 10tr: miễn phí</li><li>> 10tr: 0.5%</li> | <li>Chỉ cần có sẵn tài khoản Momo</li><li>Tiền thấy ngay trong app</li>                                                                                                                                                     | Người dùng có sẵn tài khoản Momo và bán lẻ                                                            |
| VNPAY    | 0.8%                                           | <li>Không cần tạo tài khoản gì cả</li><li>Tạo Google Maps cho cửa hàng</li><li>Tiền thấy ngay trong app. Sau 1 ngày thì tự động về tài khoản ngân hàng</li><li>Liên thông được dữ liệu giữa QR và POS</li> | [[VNPAY tập trung vào những cửa hàng lớn đủ để có nhu cầu dùng máy POS\|Cửa hàng có nhiều nhân viên]] |
| Smartpay |                                                |                                                                                                                                                                                   |                                                                                                       |
| Ecopay   |                                                |                                                                                                                                                                                   |                                                                                                       |
Bản chất của cả Momo và VNPAY là đều cần căn cước + SĐT của người bán. Nhưng Momo hướng tới những người đã tạo app rồi, nên với những người này họ không thấy là mình phải đưa thông tin cá nhân khi đăng ký mở cửa hàng. Chứ thật ra Momo đã biết thông tin cá nhân của họ rồi.

```dataview
LIST rows.file.link
FROM "Hiểu biết sâu/Kiếm tiền/Fintech/Trung gian thanh toán/Sự khác biệt giữa các công ty" 
WHERE file.name!=this.file.name
GROUP BY split(file.folder, "/")[5]
```