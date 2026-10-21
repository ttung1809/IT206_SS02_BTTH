# KẾ HOẠCH VẬN HÀNH AGILE CHO DỰ ÁN GREENMART

Đơn vị thực hiện: TechViet Khách hàng: GreenMart – chuỗi 30 siêu thị Thời gian lập kế hoạch: 6 tuần đầu Phương pháp: Agile với khung làm việc Scrum

## 1. Lý do chọn Agile thay vì Waterfall

### 1.1. Hạn chế của Waterfall trong dự án GreenMart

GreenMart đang chuyển từ hệ thống quản lý bán hàng truyền thống sang bán hàng đa kênh, bao gồm tìm kiếm sản phẩm, đặt hàng online và thanh toán. Trong quá trình triển khai, khách hàng có thể thay đổi thứ tự ưu tiên hoặc bổ sung yêu cầu theo tình hình kinh doanh thực tế.

Nếu tiếp tục dùng Waterfall:

- Yêu cầu cứng nhắc: Các yêu cầu được chốt từ đầu nên việc thay đổi giữa dự án có thể buộc đội sửa lại thiết kế và mã nguồn.
- Phản hồi muộn: Khách hàng chỉ xem sản phẩm ở cuối dự án, khiến lỗi hoặc điểm chưa phù hợp bị phát hiện muộn.
- Rủi ro cao: Khi tính năng không đáp ứng nhu cầu thực tế, chi phí sửa đổi và nguy cơ chậm tiến độ tăng lên.

### 1.2. Agile khắc phục như thế nào?

Agile chia công việc thành các vòng phát triển ngắn. Sau mỗi vòng, đội tạo ra một phần sản phẩm có thể kiểm tra, nhận phản hồi từ GreenMart và điều chỉnh kế hoạch tiếp theo.

| Tiêu chí            | Waterfall                   | Agile                             |
| ------------------- | --------------------------- | --------------------------------- |
| Quản lý yêu cầu     | Chốt phần lớn từ đầu        | Có thể cập nhật ưu tiên liên tục  |
| Phản hồi khách hàng | Chủ yếu ở cuối dự án        | Sau mỗi Sprint                    |
| Phát hiện vấn đề    | Có thể muộn                 | Sớm hơn qua kiểm tra thường xuyên |
| Bàn giao sản phẩm   | Thường tập trung cuối dự án | Tạo Increment qua từng Sprint     |

Kết luận: GreenMart nên áp dụng Agile vì yêu cầu bán hàng đa kênh có thể thay đổi theo thực tế kinh doanh. Agile giúp đội ưu tiên đúng giá trị, kiểm tra sản phẩm sớm và giảm rủi ro phải làm lại nhiều phần.

## 2. Nguyên tắc làm việc theo 4 giá trị Agile Manifesto

Đội sẽ chuyển từ cách làm thiên về quy trình, tài liệu và kế hoạch cứng nhắc sang cách làm chú trọng giao tiếp, sản phẩm thực tế, hợp tác và thích ứng.

| Thói quen hiện tại                                                                    | Giá trị Agile bị đi ngược                        | Cách làm mới đề xuất                                                                                                                                                         |
| ------------------------------------------------------------------------------------- | ------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Cả đội chỉ trao đổi qua bình luận trên phần mềm, gần như không họp trực tiếp          | Cá nhân và sự tương tác hơn quy trình và công cụ | Daily Scrum 15 phút mỗi ngày; trao đổi trực tiếp khi có vướng mắc, dùng công cụ để ghi lại quyết định và tiến độ.                                                            |
| Viết tài liệu đặc tả rất chi tiết trước, chỉ trình diễn sản phẩm một lần ở cuối dự án | Phần mềm chạy được hơn tài liệu đầy đủ           | Xây dựng và trình diễn Increment cuối mỗi Sprint; chỉ viết tài liệu cần thiết để phát triển, kiểm thử và vận hành.                                                           |
| Hợp đồng tính phí và bắt chờ 2 tuần phê duyệt mỗi khi khách muốn đổi yêu cầu          | Cộng tác với khách hàng hơn đàm phán hợp đồng    | Làm việc thường xuyên với đại diện GreenMart; PO cập nhật thứ tự Product Backlog. Những thay đổi ảnh hưởng phạm vi hợp đồng, chi phí hoặc pháp lý vẫn cần phê duyệt phù hợp. |
| Khi thực tế khác với kế hoạch, đội vẫn làm đúng theo kế hoạch đã duyệt ban đầu        | Đáp ứng với sự thay đổi hơn tuân theo kế hoạch   | Đánh giá dữ liệu và phản hồi sau mỗi Sprint, điều chỉnh Product Backlog và kế hoạch Sprint tiếp theo khi cần.                                                                |

Lưu ý: Agile không có nghĩa là bỏ tài liệu, bỏ hợp đồng hoặc họp liên tục. Đội vẫn quản lý tài liệu, chất lượng và cam kết, nhưng không để chúng cản trở việc tạo ra giá trị thực tế cho khách hàng.

## 3. Khung Scrum cho GreenMart

### 3.1. Chọn độ dài Sprint

Đội chọn Sprint cố định 2 tuần. Trong 6 tuần đầu, đội dự kiến thực hiện 3 Sprint liên tiếp.

### Lộ trình 6 tuần

### Sprint 1

Tuần 1–2

Tìm kiếm sản phẩm

Xây dựng bản tìm kiếm và hiển thị sản phẩm cơ bản.

### Sprint 2

Tuần 3–4

Đặt hàng online

Xây dựng luồng đặt hàng cơ bản, tiếp nhận phản hồi từ Sprint 1.

### Sprint 3

Tuần 5–6

Hoàn thiện luồng mua hàng

Tích hợp giỏ hàng, thanh toán thử nghiệm và cải tiến theo phản hồi.

Đây là kế hoạch dự kiến, không phải cam kết rằng mọi tính năng đều hoàn thành đúng thời hạn. Phạm vi từng Sprint được xác định theo năng lực thực tế của đội.

### 3.2. Gắn Sprint với 3 trụ cột Scrum

| Trụ cột                  | Cách áp dụng tại GreenMart                                                                                                       |
| ------------------------ | -------------------------------------------------------------------------------------------------------------------------------- |
| Minh bạch (Transparency) | Công khai Product Backlog, Sprint Goal, trạng thái công việc, tiêu chí hoàn thành và các vấn đề đang gặp phải.                   |
| Thanh tra (Inspection)   | Kiểm tra tiến độ hằng ngày, kiểm thử liên tục và đánh giá Increment với khách hàng vào cuối Sprint.                              |
| Thích nghi (Adaptation)  | Điều chỉnh cách làm ngay khi phát hiện sai lệch; cập nhật thứ tự Product Backlog và kế hoạch Sprint tiếp theo dựa trên phản hồi. |

Vì sao chọn Scrum thay vì Waterfall? Scrum cung cấp nhịp làm việc cố định, vai trò rõ ràng và các sự kiện kiểm tra, điều chỉnh thường xuyên. Nhờ vậy, GreenMart có thể nhìn thấy sản phẩm từng phần thay vì phải chờ đến cuối dự án mới đánh giá.

## 4. Phân vai Scrum Team

Đội có 6 thành viên: Long, Hoa, An, Bình, Chi và Dung. Phân công đề xuất như sau.

| Vai trò            | Thành viên          | Trách nhiệm và quyền quyết định                                                                                                                                                                                                              |
| ------------------ | ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Product Owner (PO) | Long                | Chịu trách nhiệm tối đa hóa giá trị sản phẩm, quản lý và sắp xếp thứ tự Product Backlog. Long quyết định thứ tự ưu tiên trong phạm vi mục tiêu và các ràng buộc đã thống nhất; không tự quyết định cách triển khai kỹ thuật thay Developers. |
| Scrum Master (SM)  | Hoa                 | Chịu trách nhiệm thiết lập Scrum đúng cách, hỗ trợ đội tự quản lý, hướng dẫn các sự kiện và xử lý trở ngại. Hoa quyết định cách hỗ trợ quy trình trong phạm vi vai trò; không tự phân việc hoặc ép đội nhận thêm phạm vi.                    |
| Developers         | An, Bình, Chi, Dung | Cùng chịu trách nhiệm tạo Increment đáp ứng Definition of Done. Đội quyết định cách thực hiện công việc, cách tổ chức kỹ thuật và điều chỉnh kế hoạch hằng ngày; không tự ý thay đổi Sprint Goal hoặc cam kết phạm vi với khách hàng.        |

Phân công chuyên môn trong Developers:

- An: phát triển chức năng tìm kiếm sản phẩm.
- Bình: phát triển API và xử lý dữ liệu sản phẩm.
- Chi: phát triển giao diện hiển thị sản phẩm.
- Dung: kiểm thử chức năng, kiểm thử tích hợp và hỗ trợ tự động hóa kiểm thử.

Các phân công chuyên môn trên là dự kiến; Developers có thể phối hợp và thay đổi cách chia việc để đạt Sprint Goal.

Lưu ý: Dung là Tester nhưng trong Scrum vẫn thuộc nhóm Developers. Scrum không quy định một vai trò Tester độc lập trong Scrum Team.

## 5. Artifacts và lịch sự kiện Scrum

### 5.1. Product Backlog

Product Backlog là danh sách công việc sản phẩm được sắp xếp theo mức độ ưu tiên. PO chịu trách nhiệm quản lý hiệu quả danh sách này.

| Ưu tiên | Hạng mục                 | Mô tả                                   | Giá trị mang lại                             |
| ------- | ------------------------ | --------------------------------------- | -------------------------------------------- |
| 1       | Tìm kiếm sản phẩm        | Tìm theo tên hoặc từ khóa               | Giúp khách nhanh chóng tìm được hàng cần mua |
| 2       | Xem chi tiết sản phẩm    | Hiển thị giá, mô tả, tồn kho            | Hỗ trợ quyết định mua hàng                   |
| 3       | Đặt hàng online          | Tạo đơn hàng từ sản phẩm đã chọn        | Mở rộng kênh bán hàng trực tuyến             |
| 4       | Giỏ hàng                 | Thêm, xóa, cập nhật số lượng            | Cho phép khách chuẩn bị đơn hàng             |
| 5       | Quản lý tồn kho          | Kiểm tra số lượng có thể bán            | Hạn chế bán vượt tồn kho                     |
| 6       | Thanh toán trực tuyến    | Tích hợp phương thức thanh toán phù hợp | Hoàn thiện trải nghiệm mua hàng              |
| 7       | Quản lý trạng thái đơn   | Theo dõi đơn đã tạo, xác nhận, hoàn tất | Hỗ trợ khách và nhân viên vận hành           |
| 8       | Báo cáo bán hàng đa kênh | Tổng hợp đơn hàng và doanh thu          | Hỗ trợ quản lý kinh doanh                    |

Thứ tự trên là ưu tiên ban đầu để lập kế hoạch. PO có thể thay đổi thứ tự dựa trên phản hồi của GreenMart, giá trị kinh doanh, rủi ro và sự phụ thuộc giữa các hạng mục.

### 5.2. Sprint Backlog và Sprint Goal của Sprint 1

Sprint 1 kéo dài 2 tuần.

Sprint Goal: Giúp khách hàng tìm kiếm và xem thông tin sản phẩm trên hệ thống GreenMart để kiểm chứng trải nghiệm mua sắm trực tuyến cơ bản.

| Hạng mục Sprint 1      | Công việc chính                                      | Tiêu chí hoàn thành dự kiến                   |
| ---------------------- | ---------------------------------------------------- | --------------------------------------------- |
| Tìm kiếm sản phẩm      | Xây dựng giao diện tìm kiếm và API                   | Nhập từ khóa, trả về sản phẩm phù hợp         |
| Xem chi tiết sản phẩm  | Hiển thị tên, giá, mô tả, tồn kho                    | Thông tin được lấy từ dữ liệu hệ thống        |
| Kiểm thử chức năng     | Kiểm thử tìm kiếm và chi tiết sản phẩm               | Các kiểm thử cần thiết đạt yêu cầu            |
| Tích hợp và trình diễn | Kết nối giao diện với API, triển khai bản thử nghiệm | Khách hàng có thể thao tác trên bản chạy được |

Sprint Backlog gồm Sprint Goal, các Product Backlog Item được chọn và kế hoạch thực hiện do Developers xây dựng, cập nhật trong Sprint. Danh sách trên là phạm vi dự kiến; đội sẽ xác nhận sau Sprint Planning.

### 5.3. Increment mong đợi cuối Sprint 1

Increment là phần sản phẩm có giá trị, tích hợp với phần đã có và đáp ứng Definition of Done.

Đến cuối Sprint 1, đội mong đợi có một bản GreenMart chạy được với các khả năng:

- Người dùng mở được trang danh sách sản phẩm.
- Người dùng tìm sản phẩm bằng từ khóa.
- Người dùng xem được thông tin chi tiết của sản phẩm.
- Các chức năng đã hoàn thành được kiểm thử, tích hợp và đáp ứng Definition of Done.
- Khách hàng có thể trực tiếp thao tác trong Sprint Review và đưa ra phản hồi.

Đội không tuyên bố tính năng đã hoàn thành nếu chỉ có giao diện minh họa hoặc mã nguồn chưa tích hợp, kiểm thử đầy đủ theo Definition of Done.

### 5.4. Lịch 5 sự kiện Scrum

| Sự kiện              | Thời điểm                                 | Mục đích                                                                                   |
| -------------------- | ----------------------------------------- | ------------------------------------------------------------------------------------------ |
| Sprint               | Tuần 1–2                                  | Bao trùm toàn bộ thời gian phát triển để tạo Increment có giá trị.                         |
| Sprint Planning      | Ngày đầu Sprint 1                         | Thống nhất vì sao Sprint có giá trị, sẽ làm gì và dự kiến thực hiện như thế nào.           |
| Daily Scrum          | Hằng ngày, 15 phút                        | Developers kiểm tra tiến độ hướng tới Sprint Goal và điều chỉnh kế hoạch trong ngày.       |
| Sprint Review        | Ngày cuối Sprint 1                        | Cùng GreenMart xem xét kết quả, thảo luận thay đổi thị trường và cập nhật Product Backlog. |
| Sprint Retrospective | Sau Sprint Review, trước Sprint tiếp theo | Đội xem xét chất lượng, cách phối hợp và thống nhất cải tiến cho Sprint sau.               |

Với Sprint 2 tuần, Sprint Planning tối đa 4 giờ, Sprint Review tối đa 2 giờ và Sprint Retrospective tối đa 1,5 giờ theo hướng dẫn Scrum Guide. Daily Scrum kéo dài 15 phút. Đây là giới hạn thời lượng tối đa, không phải yêu cầu phải sử dụng hết thời gian.

## 6. Xử lý tình huống thay đổi

### Tình huống 1: Giữa Sprint, GreenMart muốn ưu tiên đặt hàng online

Vấn đề: PO nhận được yêu cầu chuyển ưu tiên từ tìm kiếm sản phẩm sang đặt hàng online ngay giữa Sprint 1.

Cách xử lý:

1. Tiếp nhận yêu cầu: Long ghi nhận nhu cầu, làm rõ giá trị kinh doanh, mức độ khẩn cấp và lý do GreenMart muốn thay đổi.
2. Đánh giá ảnh hưởng: Long trao đổi với Developers về phụ thuộc kỹ thuật, khối lượng công việc và ảnh hưởng đến Sprint Goal.
3. Cập nhật Product Backlog: Long có thể đưa hạng mục đặt hàng online lên vị trí ưu tiên cao hơn cho kế hoạch tiếp theo.
4. Bảo vệ Sprint Goal: Developers tiếp tục hướng tới mục tiêu tìm kiếm và xem sản phẩm. Đội không tự ý nhồi thêm toàn bộ chức năng đặt hàng vào Sprint hiện tại.
5. Thỏa thuận khi cần thay đổi phạm vi: Nếu có thể đáp ứng yêu cầu mà không gây nguy hiểm cho Sprint Goal, PO và Developers có thể thương lượng lại phạm vi Sprint Backlog. Nếu Sprint Goal trở nên lỗi thời, chỉ PO mới có quyền hủy Sprint theo Scrum.

Kết quả mong đợi: GreenMart được lắng nghe và yêu cầu mới được ưu tiên minh bạch, nhưng đội không phải liên tục phá vỡ Sprint đang thực hiện.

### Tình huống 2: Đến Sprint Review, một tính năng vẫn chưa hoàn thành

Giả sử chức năng tìm kiếm sản phẩm chưa đáp ứng đầy đủ tiêu chí hoàn thành.

Cách xử lý:

- Trung thực khi trình diễn: Đội thông báo rõ chức năng chưa hoàn thành; không trình bày nó như một Increment hoàn chỉnh.
- Không tính là Done: Hạng mục chưa đáp ứng Definition of Done không được tính là hoàn thành và không được đưa vào Increment chỉ để đủ kế hoạch.
- Thu thập phản hồi: Đội có thể trình diễn những phần đã hoàn thành, nếu chúng có thể hoạt động độc lập và không gây hiểu lầm về trạng thái thực tế.
- Cập nhật Product Backlog: PO cùng đội đánh giá phần việc còn lại, xem xét mức độ ưu tiên và quyết định thời điểm thực hiện tiếp.
- Cải tiến quy trình: Trong Sprint Retrospective, đội tìm nguyên nhân như ước lượng chưa phù hợp, phụ thuộc kỹ thuật hoặc kiểm thử quá muộn để đưa ra biện pháp phòng ngừa.

Kết quả mong đợi: Khách hàng nắm được tình trạng thực tế, đội giữ được tính minh bạch và chất lượng sản phẩm, đồng thời có kế hoạch rõ ràng cho phần việc chưa hoàn thành.

## 7. Kết luận chung

Kế hoạch vận hành Agile cho GreenMart sử dụng Scrum với Sprint cố định 2 tuần trong 6 tuần đầu. Nhóm áp dụng bốn giá trị Agile để cải thiện giao tiếp, nhận phản hồi sớm, hợp tác với khách hàng và thích ứng với thay đổi.

Ba yếu tố quan trọng nhất để triển khai thành công là:

1. Ưu tiên theo giá trị: PO sắp xếp Product Backlog theo nhu cầu thực tế của GreenMart.
2. Minh bạch và chất lượng: Mỗi Sprint tạo Increment đáp ứng Definition of Done.
3. Cải tiến liên tục: Sprint Review giúp điều chỉnh sản phẩm, còn Sprint Retrospective giúp cải thiện cách làm việc của đội.

Với cách vận hành này, TechViet có thể giảm rủi ro làm sai nhu cầu, phát hiện vấn đề sớm và từng bước đưa hệ thống bán hàng đa kênh vào sử dụng thay vì chờ đến cuối dự án mới nhận phản hồi.