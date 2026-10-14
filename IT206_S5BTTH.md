# **Phần A — Thiết kế vận hành Scrum**

1\. Độ dài Sprint: Chọn sprint 2 tuần, vì dự án cần giải quyết yêu cầu từ 3 bộ phận tương ứng với 3 sprint, 1 sprint cuối để xử lý thay đổi về mặt yêu cầu và lỗi phát sinh nếu có

2\. Phân công vai trò

| Vai trò | Trách nhiệm |
| ----- | ----- |
| Product Owner | Quản lý, sắp xếp ưu tiên Backlog |
| Scrum Master | Hướng dẫn Scrum, giải quyết trở ngại |
| Development Team | Phân tích, lập trình, kiểm thử |

3\. Sự kiện Scrum: Sprint Review giúp nhóm nhận phản hồi, thể hiện trụ cột Thanh tra và Thích nghi

# **Phần B — Product Backlog và MoSCoW**

1.  Product Backlog

| Hạng mục | Ưu tiên |
| :---: | :---: |
| Tích điểm sau thanh toán | Must |
| Thu hồi điểm khi hủy/hoàn đơn | Must |
| Đổi điểm lấy giảm giá | Must |
| Tự động trừ điểm hết hạn | Must |
| Xem số dư, lịch sử điểm | Should |
| Thông báo điểm sắp hết hạn | Should |
| Gợi ý ưu đãi cá nhân | Could |
| Bảng xếp hạng khách hàng | Won't |

2. Sprint 1: Chọn 4 hạng mục Must và 2 hạng mục Should đầu tiên phù hợp nguồn lực

# **Phần C — Acceptance Criteria và DoD**

1\. User Story: Tích điểm

- AC1: Given đơn hàng 100.000đ thanh toán thành công, When hệ thống ghi nhận thanh toán, Then khách được cộng 10 điểm  
- AC2: Given khách đã được cộng 10 điểm, When đơn hàng bị hủy, Then hệ thống thu hồi 10 điểm  
- AC3: Given đơn hàng thanh toán thất bại, When hệ thống xử lý, Then khách không được cộng điểm

2\. Definition of Done

- Code được review trước khi merge  
- Kiểm thử đơn vị và tích hợp đạt yêu cầu  
- Chạy trên staging, không còn lỗi nghiêm trọng

# **Phần D — Xử lý thay đổi**

1\. Quy trình: PO đánh giá yêu cầu, cập nhật Backlog; nhóm không tự ý thay đổi Sprint Goal. Nếu Sprint Goal không còn phù hợp, PO có thể hủy Sprint

2\. Ảnh hưởng:

- Backlog: Cập nhật tỷ lệ 100 điểm \= 25.000đ  
- AC: Sửa tiêu chí đổi điểm theo tỷ lệ mới  
- DoD: Giữ nguyên vì tiêu chuẩn chất lượng không thay đổi

