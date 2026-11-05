# BÁO CÁO BÀI TẬP / ĐỒ ÁN

## THÔNG TIN SINH VIÊN
- **Họ và tên:** Nguyễn Khánh Đức
- **Mã số sinh viên:** 24810320072
- **Lớp:** D19QTANM1
- **Tên môn học:** Lập trình C# / Windows Forms
- **Tên bài tập:** BÀI 6.2: HỆ THỐNG QUẢN LÝ NHÂN SỰ & TÍNH LƯƠNG (HRM &
PAYROLL SYSTEM)

---

## KẾT QUẢ THỰC HÀNH

- Giao diện chính
<img width="1550" height="935" alt="Screenshot 2026-11-05 152113" src="https://github.com/user-attachments/assets/6baa9bc8-b753-4b6c-99d5-b1b407b54396" />

- Xác nhận thời gian chấm công + OT của nhân viên
<img width="1549" height="931" alt="Screenshot 2026-11-05 152724" src="https://github.com/user-attachments/assets/103897fa-f228-44cd-9638-61826c879ff1" />

- Tính tổng lương nhân viên
<img width="1553" height="931" alt="Screenshot 2026-11-05 152735" src="https://github.com/user-attachments/assets/18fb4b76-edc8-47b7-9224-91d610188c13" />

## HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY DỰ ÁN:
1. **Khởi tạo CSDL**:
   - Mở file `Database.sql` có sẵn trong thư mục dự án bằng SQL Server Management Studio (SSMS) hoặc Visual Studio.
   - Chạy toàn bộ script (Execute) để tự động tạo CSDL `HRMDB` cùng các bảng và dữ liệu mẫu.

2. **Cấu hình chuỗi kết nối**:
   - Mở file `Dbhelper.cs`.
   - Kiểm tra và đổi lại `Data Source` cho khớp với tên SQL Server trên máy chấm (Mặc định đang để kết nối tới `(localdb)\MSSQLLocalDB`).

3. **Chạy chương trình**:
   - Nhấn **F5** (hoặc nút Start) trên Visual Studio để chạy hệ thống.
