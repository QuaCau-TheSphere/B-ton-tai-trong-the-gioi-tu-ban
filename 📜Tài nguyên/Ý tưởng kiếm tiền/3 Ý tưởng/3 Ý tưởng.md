---
share: true
created: 2023-11-24T16:59
updated: 2024-09-16T20:52
alias:
  - Kiếm tiền nhanh Kiếm dự án thuê ngoài Mở các buổi chia sẻ lớp học ngắn buổi huấn luyện Làm nhân viên ăn lương Đầu tư kinh doanh bán hàng Tạo lợi nhuận
  - Một số ý tưởng kiếm tiền
  - Kiếm tiền từ các hoạt động của Quả Cầu
  - Tạo sinh kế, thu nhập, dòng tiền
description: Kiếm tiền từ các hoạt động của Quả Cầu
---
# Một số ý tưởng kiếm tiền
## Công việc thời vụ
```dataview
Table yêu-cầu-đầu-vào as "Yêu cầu đầu vào"
FROM "📜Tài nguyên/Ý tưởng kiếm tiền/3 Ý tưởng/Công việc thời vụ" 
WHERE file.name != this.file.name
```

## Các buổi chia sẻ, lớp học, khoá đào tạo, buổi huấn luyện
Nếu bạn kiếm được người sẵn sàng trả tiền để được hướng dẫn những cái này thì bạn sẽ được nhận toàn bộ số tiền họ trả.
```dataview
Table yêu-cầu-đầu-vào as "Yêu cầu đầu vào"
FROM "📜Tài nguyên/Ý tưởng kiếm tiền/3 Ý tưởng/Các buổi chia sẻ, lớp học, khoá đào tạo, buổi huấn luyện" 
WHERE file.name != this.file.name
```

## Gia công giải pháp
Đây là các giải pháp đã được đặt hàng. Nếu bạn kiếm được người sẵn sàng trả tiền để được có những cái này thì chúng ta sẽ cùng thoả thuận số tiền mỗi người được nhận. 
```dataview
Table yêu-cầu-đầu-vào as "Yêu cầu đầu vào"
FROM "📜Tài nguyên/Ý tưởng kiếm tiền/3 Ý tưởng/Gia công giải pháp" 
WHERE file.name != this.file.name
```

## Tự kinh doanh, đầu tư, bỏ vốn
```dataview
Table yêu-cầu-đầu-vào as "Yêu cầu đầu vào"
FROM "📜Tài nguyên/Ý tưởng kiếm tiền/3 Ý tưởng/Tự kinh doanh, đầu tư" 
WHERE file.name != this.file.name
SORT yêu-cầu-đầu-vào desc
```


## Nơi thảo luận
Tất cả các chủ đề có nhãn "💸Tiền bạc":
![](https://i.imgur.com/4rJvMNB.png)