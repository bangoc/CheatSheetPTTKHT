Chương 1. giới thiệu phân tích và thiết kế hệ thống
---------------------------------------------------

<br />*1.1. Hãy kể tên các pha cơ bản trong vòng đời phát triển hệ thống? Sản phẩm chính của mỗi pha là gì?*
<br />*1.12. Vẽ sơ đồ phát triển hệ thống theo phương pháp thác đổ? Ưu/nhược điểm của phương pháp này?*
<br />*1.18. Ca sử dụng là gì?*
<br />*1.20. UML là gì?*
<br />*1.21. OMG là tổ chức gì?*
<br />*1.22. Các biểu đồ cấu trúc được sử dụng cho mục đích gì? Hãy kể tên các loại biểu đồ cấu trúc?*
<br />*1.23. Các biểu đồ hành vi được sử dụng cho mục đích gì? Hãy kể tên các loại biểu đồ hành vi?*
<br />*1.24. Giải thích các nguyên tắc Use-Case driven, architecture centric, Iterative and Incremental đối với OOSAD?*

Chương 4. Xác định yêu cầu
--------------------------

<br />*4.2. Vì sao phải nghiên cứu hệ thống hiện có khi xây dựng hệ thống mới?*
<br />*4.6. Phân tích bề nổi và phân tích nguồn gốc khác nhau như thế nào? Ưu điểm? Nhược điểm? Tình huống sử dụng?*

Chương 5. Mô hình hóa chức năng
-------------------------------

<br />*5.2. Sử dụng các biểu đồ hoạt động để xây dựng mô hình nghiệp vụ có ý nghĩa gì đối với OOSAD?*
<br />*5.8. Hãy giải thích các mối quan hệ giữa các thành phần của biểu đồ ca sử dụng (use case)?*
<br />*5.9. Hãy định nghĩa khái niệm tác nhân và khái niệm ca sử dụng?*
<br />*5.21. Ca sử dụng được thiết lập ở góc nhìn nào? Vì sao?*

Bài tập
=======
**E.** Vẽ biểu đồ hoạt động, tạo tập mô tả ca sử dụng, và vẽ biểu đồ ca sử dụng cho hệ thống phòng khám nha khoa, có thể bỏ qua luồng sự kiện trong mỗi ca sử dụng.
Mỗi bệnh nhân mới lần đầu đến phòng khám cần điền một form thông tin gồm có: tên, địa chỉ, số điện thoại, lịch sử thăm khám. Thông tin này được lưu trong CSDL bệnh nhân. Khi bệnh nhân gọi điện để thay đổi lịch khám, hoặc đặt lịch khám, lễ tân kiểm tra lịch hẹn để tìm thời gian phù hợp. Nếu tìm được thời gian phù hợp, lễ tân thực hiện đặt lịch hẹn. Nếu bệnh nhân là bệnh nhân mới, chỉ một phần thông tin bệnh nhân được điền vào, thông tin còn thiếu sẽ được bổ xung khi bệnh nhân đến phòng khám. Lịch hẹn thường được đặt trước, vì vậy lễ tân thường gửi email nhắc nhở bệnh nhân trước lịch khám 5 ngày.
**H.** Vẽ biểu đồ hoạt động , xác định tập mô tả chi tiết ca sử dụng, và vẽ biều đồ ca sử dụng cho hệ thống đăng ký online của trường đại học. Hệ thống cần cho phép cán bộ của bộ môn khảo sát các khóa học thuộc quản lý của bộ môn mình, thêm, xóa, và thay đổi thông tin khóa học (v.d., số lượng đăng ký tối da). Hệ thống phải cho phép sinh viên kiểm tra các khóa học hiện có, thêm và xóa khóa học khỏi lịch học, và kiểm tra các khóa đã tham gia. Cán bộ mỗi bộ môn  có thể in các báo cáo về khóa học và danh sách sinh viên tham gia vào khóa học đó.  Hệ thống phải đảm bảo rằng không có sinh viên nào đăng ký quá nhiều khóa học và sinh viên chưa đóng học phí thì không được phép đăng ký (giả sử dữ liệu lệ phí được quản lý bởi phòng tài chính của trường đại học, hệ thống đăng ky có quyền truy cập nhưng không được thay đổi).

Chương 6. Mô hình hóa cấu trúc
------------------------------

<br />*6.1. Trình bày quy cách ghi số lượng trong mối quan hệ giữa hai lớp?*
<br />*6.3. Lớp liên kết (association class) là gì?*
<br />*6.6. Trình bày quy cách ghi giới hạn truy cập trên biểu đồ lớp?*
<br />*6.7. Giải thích các mối quan hệ giữa các lớp trên biều đồ lớp?*
<br />*6.8. Trình bày quy cách ghi hướng đọc của mối quan hệ trên biểu đồ lớp?*

Bài tập
=======

**A)** Vẽ biểu đồ lớp cho các lớp sau:
Movie(title, producer, length, director, genre)
Ticket (price, adult or child, showtime, movie)
Patron (name, adult or child, age)
**B)** Vẽ biểu đồ đối tượng cho biểu đồ lớp ở mục A
**C)** Vẽ biểu đồ lớp cho các lớp sau, giả sử các thực thể nằm trong hệ thống thanh toán tiền cho bệnh nhân, chỉ đưa vào các thuộc tính phù hợp với tình huống này:
Patient (age, name, hobbies, blood type, occupation,
insurance carrier, address, phone)
Insurance carrier (name, number of patients on plan, address, contact name, phone)
Doctor (specialty, provider identification number, golf, handicap, age, phone, name)
**D)** Vẽ biểu đồ đối tượng cho biểu đồ lớp ở mục B
**F)** Vẽ biểu đồ lớp cho mỗi tình huống sau:
*1.* Đối với bệnh nhân mới, trong lần thăm khám đầu tiên, bệnh nhân mới điền mẫu thông tin bệnh nhân gồm có: tên, địa chỉ, số điện thoại và công ty bảo hiểm. Thông tin bệnh nhân sau đó được lưu trong tệp thông tin bệnh nhân. Một bệnh nhân chỉ được mua bảo hiểm ở một công ty bảo hiểm, và chỉ bệnh nhân có bảo hiểm mới được đăng ký khám bệnh với bác sỹ. Mỗi lần bệnh nhân đến khám bệnh, thông tin khám bệnh sẽ được gửi đến công ty bảo hiểm để thanh toán. Thông tin gửi đến công ty bảo hiểm gồm có: ngày khám, mục đích, chi phí. Một bệnh nhân được gửi hai thông báo trong một ngày.
*2.* Bang Georgia muốn thiết kế hệ thống thông tin theo dõi nhà nghiên cứu trong bang. Thông tin quan tâm gồm có: Họ tên, học hàm, học vị, chức vụ, tên trường đại học, lĩnh vực nghiên cứu. Mỗi nhà nghiên cứu chỉ được gắn với một cơ sở nghiên cứu, một nhà nghiên cứu có thể có nhiều lĩnh vực nghiên cứu.

Chương 7. Mô hình hóa hành vì
----------------------------
  
<br />*7.6. Hãy mô tả các thành phần cơ bản của biểu đồ trình tự?*
<br />*7.9. Hãy mô tả các thành phần cơ bản của biểu đồ giao tiếp?*
<br />*7.10. Quy cách trình bày thứ tự của các thông điệp trên biểu đồ giao tiếp?*
<br />*7.17. Mô tả đặc điểm của những lớp cần xây dựng biểu đồ máy trạng thái?*

Chương 8. Chuyển sang thiết kế
------------------------------

<br />*8.14. Custom development design là gì? Ưu điểm? Nhược điểm? Tình huống sử dụng?*
<br />*8.15. Các vấn đề có thể phát sinh khi sử dụng các gói phần mềm có sẵn? Phương hướng giải quyết những vấn đề này?*
<br />*8.18. Outsourcing là gì? Ưu điểm? Nhược điểm? Các tình huống không nên áp dụng?*

Chương 10. Thiết kế lớp quản lý dữ liệu
---------------------------------------

<br />*10.1. Kể tên bốn bước thiết kế lưu trữ dữ liệu?*
<br />*10.19. Hãy giải thích hai chiều hướng tối ưu hóa CSDL quan hệ?*
<br />*10.21. Mô hình thỏa mãn các yêu cầu của ba dạng chuẩn hóa có những đặc điểm gì?*
<br />*10.22. Khi nào gỡ chuẩn hóa thì tốt hơn? Nêu một ví dụ?*
