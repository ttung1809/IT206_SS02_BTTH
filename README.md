# BÀI TẬP TỔNG HỢP: TỪ BACKLOG CŨ ĐẾN BACKLOG CHUẨN

Dự án: GreenCart – Module Đánh giá & Nhận xét sản phẩm

## Phần A. Rà soát Backlog hiện tại

### 1. Đánh giá S1

S1 – Hợp lệ.

> As a customer, I want to rate a purchased product from 1 to 5 stars, so that I can share my satisfaction level.

S1 đáp ứng cấu trúc User Story: As a… I want… so that…

Đánh giá theo INVEST:

| Tiêu chí    | Đánh giá | Giải thích                                                                     |
| ----------- | -------- | ------------------------------------------------------------------------------ |
| Independent | Đạt      | Có thể triển khai chức năng chấm sao tương đối độc lập với các chức năng khác. |
| Negotiable  | Đạt      | Cách xử lý và chi tiết giao diện có thể được trao đổi, điều chỉnh.             |
| Valuable    | Đạt      | Giúp khách hàng thể hiện mức độ hài lòng với sản phẩm đã mua.                  |
| Estimable   | Đạt      | Phạm vi chấm sao từ 1–5 tương đối rõ, có thể ước lượng.                        |
| Small       | Đạt      | Phạm vi tập trung vào một hành động cụ thể.                                    |
| Testable    | Đạt      | Có thể kiểm tra khách hàng chọn và gửi mức sao hợp lệ từ 1 đến 5.              |

Kết luận: Giữ nguyên S1, bổ sung Acceptance Criteria khi chuẩn bị đưa vào Sprint.

### 2. Đánh giá S2

S2 hiện tại:

> Cho phép khách chấm sao, viết bình luận, đính kèm ảnh, gửi đánh giá, hệ thống kiểm duyệt nội dung, rồi hiển thị công khai lên trang sản phẩm.

S2 sai về cấp độ và chưa đạt INVEST.

Đây không phải một User Story đơn lẻ mà là một nhóm chức năng gồm nhiều hành vi và quy trình khác nhau.

| Tiêu chí / nguyên tắc | Vấn đề                                                                                              |
| --------------------- | --------------------------------------------------------------------------------------------------- |
| Independent           | Các phần như gửi đánh giá, kiểm duyệt và hiển thị có quan hệ phụ thuộc, chưa được phân tách rõ.     |
| Negotiable            | Phạm vi gộp quá nhiều chức năng khiến khó thương lượng thay đổi riêng từng phần.                    |
| Valuable              | Có nhiều giá trị khác nhau bị gộp vào cùng một Story, khó xác định mục tiêu chính.                  |
| Estimable             | Khó ước lượng chính xác vì bao gồm giao diện, tải ảnh, xử lý nội dung, kiểm duyệt và hiển thị.      |
| Small                 | Không đạt rõ ràng: một Story chứa quá nhiều công việc.                                              |
| Testable              | Có thể kiểm thử từng chức năng, nhưng tiêu chí nghiệm thu của Story tổng hợp chưa được xác định rõ. |
| Phân cấp Backlog      | Trộn nhiều User Story hoặc hành vi thuộc Feature viết đánh giá, kiểm duyệt và hiển thị đánh giá.    |

### 3. Vì sao không đưa S2 thẳng vào Sprint?

Nếu đưa S2 vào Sprint ngay, Developers khó xác định khối lượng công việc, tiêu chí hoàn thành và cách kiểm thử. Một số phần có thể hoàn thành trong khi phần khác chưa xong, khiến cả Story không đạt Definition of Done.

Cách xử lý đúng là tách S2 thành các User Story nhỏ hơn, mỗi Story có mục tiêu nghiệp vụ riêng, tiêu chí nghiệm thu rõ ràng và có thể ước lượng độc lập.

## Phần B. Hoàn thiện Backlog

### 1. Đặt tên Feature cho F2

F2 – Xem đánh giá sản phẩm

Mục tiêu: Cho phép khách hàng xem điểm trung bình và đọc những đánh giá đã được công khai để hỗ trợ quyết định mua hàng.

### 2. Viết User Story cho S3

Đề xuất S3 thuộc F1 – Viết đánh giá sản phẩm:

S3 – Viết bình luận đánh giá

> As a customer who has purchased a product, I want to write a text comment about the product, so that I can share detailed feedback about my experience.

Dịch nghĩa: Là khách hàng đã mua sản phẩm, tôi muốn viết bình luận bằng văn bản về sản phẩm để chia sẻ nhận xét chi tiết về trải nghiệm của mình.

| INVEST      | Đánh giá                                                                            |
| ----------- | ----------------------------------------------------------------------------------- |
| Independent | Có thể phát triển chức năng nhập và lưu bình luận riêng với tính năng đính kèm ảnh. |
| Negotiable  | Chi tiết giao diện và giới hạn độ dài bình luận có thể thỏa thuận.                  |
| Valuable    | Giúp khách hàng chia sẻ trải nghiệm cụ thể hơn điểm sao.                            |
| Estimable   | Phạm vi nhập và lưu văn bản tương đối rõ.                                           |
| Small       | Chỉ tập trung vào bình luận văn bản.                                                |
| Testable    | Có thể kiểm tra nhập bình luận hợp lệ và lưu thành công.                            |

### 3. Viết User Story thuộc F2

S4 – Xem điểm đánh giá trung bình

> As a customer browsing a product, I want to see its average star rating, so that I can quickly understand how other customers rate the product.

Dịch nghĩa: Là khách hàng đang xem sản phẩm, tôi muốn thấy điểm đánh giá sao trung bình để nhanh chóng hiểu những khách hàng khác đánh giá sản phẩm như thế nào.

| INVEST      | Đánh giá                                                                         |
| ----------- | -------------------------------------------------------------------------------- |
| Independent | Có thể xây dựng phần hiển thị điểm trung bình dựa trên dữ liệu đánh giá hiện có. |
| Negotiable  | Cách trình bày điểm số và số chữ số thập phân có thể điều chỉnh.                 |
| Valuable    | Giúp khách hàng đánh giá nhanh mức độ hài lòng chung.                            |
| Estimable   | Phạm vi tập trung vào tính toán và hiển thị điểm trung bình.                     |
| Small       | Chỉ tập trung vào một thông tin tổng hợp.                                        |
| Testable    | Có thể đối chiếu điểm hiển thị với dữ liệu đánh giá hợp lệ.                      |

### 4. Tách S2 thành các User Story đúng tầm

Từ S2 cũ, đề xuất ba User Story sau:

S2.1 – Đính kèm ảnh đánh giá

> As a customer who has purchased a product, I want to attach photos to my review, so that I can provide visual evidence of the product's condition or quality.

Dịch nghĩa: Là khách hàng đã mua sản phẩm, tôi muốn đính kèm ảnh vào đánh giá để cung cấp hình ảnh minh họa về tình trạng hoặc chất lượng sản phẩm.

S2.2 – Gửi đánh giá để kiểm duyệt

> As a customer who has written a review, I want to submit my review for moderation, so that it can be checked before being published publicly.

Dịch nghĩa: Là khách hàng đã viết đánh giá, tôi muốn gửi đánh giá để kiểm duyệt nhằm bảo đảm nội dung được kiểm tra trước khi công khai.

S2.3 – Hiển thị đánh giá đã được duyệt

> As a customer browsing a product, I want to see approved reviews on the product page, so that I can learn from other customers' experiences before purchasing.

Dịch nghĩa: Là khách hàng đang xem sản phẩm, tôi muốn đọc các đánh giá đã được duyệt trên trang sản phẩm để tham khảo trải nghiệm của người khác trước khi mua.

## 5. Backlog sau khi chuẩn hóa

| Cấp độ     | Mã   | Tên                             | Trạng thái    |
| ---------- | ---- | ------------------------------- | ------------- |
| Epic       | E1   | Đánh giá & Nhận xét sản phẩm    | Giữ nguyên    |
| Feature    | F1   | Viết đánh giá sản phẩm          | Đã có         |
| User Story | S1   | Chấm sao sản phẩm đã mua        | Hợp lệ        |
| User Story | S2.1 | Đính kèm ảnh đánh giá           | Tách từ S2 cũ |
| User Story | S2.2 | Gửi đánh giá để kiểm duyệt      | Tách từ S2 cũ |
| User Story | S2.3 | Hiển thị đánh giá đã được duyệt | Tách từ S2 cũ |
| User Story | S3   | Viết bình luận đánh giá         | Bổ sung       |
| Feature    | F2   | Xem đánh giá sản phẩm           | Bổ sung       |
| User Story | S4   | Xem điểm đánh giá trung bình    | Bổ sung       |

Có thể bổ sung thêm Story thuộc F2 để đọc danh sách đánh giá, xem chi tiết nhận xét hoặc lọc đánh giá theo số sao. Tuy nhiên, cần thống nhất phạm vi và tránh trùng lặp với Story hiển thị đánh giá đã duyệt.

Kết luận: Backlog mới phân biệt rõ Epic → Feature → User Story. S1 được giữ lại, S2 được tách thành ba Story có mục tiêu cụ thể, đồng thời bổ sung F2 và các Story phục vụ nhu cầu xem đánh giá. Trước khi đưa vào Sprint, từng Story vẫn cần Acceptance Criteria và được Developers xác nhận có thể hoàn thành theo Definition of Done.