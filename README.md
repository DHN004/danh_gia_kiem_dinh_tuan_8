# danh_gia_kiem_dinh_tuan_8


##  Mục tiêu bài thực hành
- Làm quen với công cụ kiểm thử API: Postman
- Thực hiện các thao tác với API: GET, POST, PUT, DELETE
- Hiểu được luồng hoạt động của RESTful API thông qua thử nghiệm với dịch vụ công khai `reqres.in`

---

##  Công cụ sử dụng
- **Postman** (phiên bản Desktop App)
- **GitHub** để lưu trữ bài thực hành
- **Public API** từ [https://reqres.in](https://reqres.in)

---

##  Các API đã thực hiện

### 1. [GET] Lấy danh sách người dùng
- **Endpoint:** `https://reqres.in/api/users?page=2`
- **Mô tả:** Gửi yêu cầu lấy danh sách người dùng trang 2
- **Kết quả:** Trả về danh sách 6 user cùng thông tin chi tiết

### 2. [POST] Thêm người dùng mới
- **Endpoint:** `https://reqres.in/api/users`
- **Body (JSON):**
```json
{
  "name": "Nguyen Van A",
  "job": "Student"
}
```
- **Kết quả:** Server phản hồi lại ID người dùng mới và thời gian tạo

### 3. [PUT] Cập nhật thông tin người dùng
- **Endpoint:** `https://reqres.in/api/users/2`
- **Body (JSON):**
```json
{
  "name": "Nguyen Van A",
  "job": "Intern Developer"
}
```
- **Kết quả:** Server phản hồi thời gian cập nhật thành công

### 4. [DELETE] Xóa người dùng
- **Endpoint:** `https://reqres.in/api/users/2`
- **Kết quả:** Server trả về mã trạng thái `204 No Content` xác nhận đã xóa

---

##  File đính kèm
- `postman_collection.json`: Collection chứa toàn bộ các API request đã thực hiện
- `images/`: Chứa các ảnh chụp màn hình minh họa

---

##  Tài liệu tham khảo
- [Video học Postman cho người mới bắt đầu](https://www.youtube.com/watch?v=MFxk5BZulVU)
- [Tài liệu chính thức của Postman](https://learning.postman.com/)
- [Trang API thử nghiệm miễn phí: reqres.in](https://reqres.in)

---

##  Kết luận
- Đã thực hiện thành công 4 loại API cơ bản bằng Postman
- Nắm được quy trình gửi yêu cầu và nhận phản hồi từ API REST
- Có thể ứng dụng Postman để test API trong các dự án phần mềm thực tế

---

