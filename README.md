# baitap5.3
# BÁO CÁO BÀI TẬP / ĐỒ ÁN

## THÔNG TIN SINH VIÊN
- **Họ và tên:** Trần Xuân Thịnh
- **Mã số sinh viên:** 24810320263
- **Lớp:** D19QTANM1
- **Tên môn học:** Lập trình C# / Windows Forms
- **Tên bài tập:** BÀI BÀI TẬP 5.3: HỆ THỐNG QUẢN LÝ QUÁN CAFE & BÁN HÀNG (POSCAFE SYSTEM)

---

## KẾT QUẢ THỰC HÀNH

- Giao diện chính
<img width="1434" height="896" alt="GD" src="https://github.com/user-attachments/assets/c1afda1c-c5c1-49d0-879f-79443c327a52" />


- Giao diện khi chọn bàn và gọi món
<img width="1429" height="894" alt="cn1" src="https://github.com/user-attachments/assets/78d95f16-f6b3-401d-851a-42d07d12d987" />


- Giao diện xác nhận thanh toán tổng số tiền
<img width="1434" height="892" alt="CN" src="https://github.com/user-attachments/assets/f7104866-ca6b-4909-93bf-f4a7160b93dc" />


- Giao diện khi thanh toán xong, bàn có khách trở thành bàn trống
<img width="1436" height="901" alt="KQ" src="https://github.com/user-attachments/assets/3476a5cb-1c2b-4ba5-86dc-d111846b1ed6" />


## HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY DỰ ÁN:
1. **Khởi tạo CSDL**:
   - Mở file `Database.sql` có sẵn trong thư mục dự án bằng SQL Server Management Studio (SSMS) hoặc Visual Studio.
   - Chạy toàn bộ script (Execute) để tự động tạo CSDL `CafePOSDB` cùng các bảng và dữ liệu mẫu.

2. **Cấu hình chuỗi kết nối**:
   - Mở file `DBConnect.cs`.
   - Kiểm tra và đổi lại `Data Source` cho khớp với tên SQL Server trên máy chấm (Mặc định đang để kết nối tới `(localdb)\MSSQLLocalDB`).

3. **Chạy chương trình**:
   - Nhấn **F5** (hoặc nút Start) trên Visual Studio để chạy hệ thống.
