# Quy trình nhận và phê duyệt giáo án
Quy trình nhận và phê duyệt giáo án

# 1. Chuẩn bị
- 1 tài khoản Office 365 có license A1 hoặc cao hơn.
- Tài liệu: https://github.com/Office365VietNam-info/Phe-duyet-giao-an

# 2. Kiến trúc xử lý
![alt text](https://github.com/Office365VietNam-info/Phe-duyet-giao-an/blob/main/Architecture/Architecture.png?raw=true)

# 3. Các bước làm
a. Tạo Forms
Tạo Forms để nhận kết quả dự thi, forms mẫu như hình bên dưới:
![alt text](https://github.com/Office365VietNam-info/Phe-duyet-giao-an/blob/main/Images/Forms.png?raw=true)

Video hướng dẫn:
[![Watch the video](https://img.youtube.com/vi/NHzyIHOkm1k/maxresdefault.jpg)](https://youtu.be/NHzyIHOkm1k)

c. Tạo trang Sharepoint site
Tạo 1 trang SharePoint site để lưu thông tin đăng ký từ forms và lưu sản phẩn dự thi.
Tạo SharePoint list: 
- Tổng hợp giáo án.
- Tổ chuyên môn Toán, Văn.
Mẫu các cột thông tin cần thiết tại https://github.com/Office365VietNam-info/Phe-duyet-giao-an/tree/main/SharePoint

Video hướng dẫn:
[![Watch the video](https://img.youtube.com/vi/ESS-wGbG1Tw/maxresdefault.jpg)](https://youtu.be/ESS-wGbG1Tw)

c. Tạo nhóm trên Teams
Tạo 1 nhóm trên Teams có các kênh:
- Thông báo(chế độ: standard): để gửi thông báo khi có sản phẩm dự thi được nộp.
- Tổng hợp giáo án(chế độ: private): để lưu thông tin giáo án đã nộp và duyệt.
- Các kênh **Tổ chuyên môn Toán, Văn** (chế độ: private): để lưu thông tin giáo án đã nộp duyệt cho tổ trưởng tổ chuyên môn.
Mẫu tham khảo như hình dưới:
![alt text](https://github.com/Office365VietNam-info/Phe-duyet-giao-an/blob/main/Images/Teams.png?raw=true)

Video hướng dẫn:
[![Watch the video](https://img.youtube.com/vi/17Vnce8bR3U/maxresdefault.jpg)](https://youtu.be/17Vnce8bR3U)

d. Cập nhật các gói PowerAutomate
- Cập nhật flow: Nộp giáo án

Video hướng dẫn:
[![Watch the video](https://img.youtube.com/vi/qSfdUHt7OLw/maxresdefault.jpg)](https://youtu.be/qSfdUHt7OLw)

- Cập nhật flow: Chép tập tin và thư mục quản lý chung

Video hướng dẫn:
[![Watch the video](https://img.youtube.com/vi/o_dVGseGH_0/maxresdefault.jpg)](https://youtu.be/o_dVGseGH_0)

- Tổng hợp thông tin phê duyệt giáo án tổ chuyên môn Toán???

Video hướng dẫn:
[![Watch the video](https://img.youtube.com/vi/_tmOmCL8t0s/maxresdefault.jpg)](https://youtu.be/o_dVGseGH_0)

- Tổng hợp thông tin phê duyệt giáo án tổ chuyên môn Văn

Video hướng dẫn:
[![Watch the video](https://img.youtube.com/vi/lKPZ4Go5cXg/maxresdefault.jpg)](https://youtu.be/lKPZ4Go5cXg)

- Kiểm thử và chỉnh sửa

Video hướng dẫn:
[![Watch the video](https://img.youtube.com/vi/ruFBcRq13ro/maxresdefault.jpg)](https://youtu.be/ruFBcRq13ro)

- Phân quyền bổ sung
[![Watch the video](https://img.youtube.com/vi/smzWwlMVOF0/maxresdefault.jpg)](https://youtu.be/smzWwlMVOF0)


Chúc các bạn thành công và có thể tùy chỉnh để có thể áp dụng cho nhiều mục đích khác trong tổ chức!
