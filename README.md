# Hướng Dẫn Sử Dụng Hương Cam Táo 3D Viewer

---

## 1. Upload File từ Máy Tính - Tương tự Dentalshare Exocad

Để đưa file từ phần mềm thiết kế (Exocad) lên hệ thống, bạn sử dụng công cụ **Huong Cam Tao Sync**.


### Bước 1: Cấu hình ban đầu
1. Tải và mở file `Huong_Cam_Tao_Sync.exe` trên máy tính.Lưu file ở 1 vị trí cố định, ưu tiên tạo 1 thư mục riêng để chứa các thông tin config.
2. Cấu hình

   <img width="523" height="765" alt="image" src="https://github.com/user-attachments/assets/7ae3420d-00dc-4aa5-bf79-0894e9fb2a7c" />

   Nhập các trường thông tin:
   - **Server Address**: Địa chỉ web của hệ thống (mặc đinh hiện tại là: `https://caohuongls.pythonanywhere.com`). Trong  tương lai sẽ điều chỉnh lại nếu cần.
   - **Username/Password**: Tài khoản được cung cấp. Tài khoản thử nghiệm: demo/12345
   - **Watch Folder**: Chọn thư mục chứa các file thiết kế của bạn (thường là thư mục CAD-Data của Exocad).
   - **Sync Start Date**: Chọn ngày bắt đầu đồng bộ (các file cũ trước ngày này sẽ không bị đẩy lên).
   - **Auto Start with windows**: Cho chương trình khởi đọng cùng window hay không.


3. Vận hành
- Sau khi thiết lập, công cụ sẽ chạy ẩn dưới thanh Taskbar (biểu tượng logo Cam Táo).
- Khi muốn gửi file để xem trước. Vào mục Tool - Export html . Lưu file vào thư mục bên trong dự án Exocad đang làm.
- Mỗi khi xuất hiện file html mới trong Exocad, công cụ sẽ tự động nhận diện và tải lên server. Trung bình dưới 10s sẽ có thông báo gửi về và cung cấp đường dẫn link và tự động lưu link vào bộ nhớ tạm. <img width="361" height="179" alt="image" src="https://github.com/user-attachments/assets/a8179266-b20d-44fc-979b-c7bc3e12d4c8" />

- Lấy link chia sẻ : nhấn chuột phải vào biểu tượng dưới **Taskbar** -> **Lịch sử Upload** để copy lại các link đã upload. <img width="503" height="418" alt="image" src="https://github.com/user-attachments/assets/684dce24-be11-4320-970e-8308a9b03896" />


---

## 2. Đăng Nhập website
Với các bác muốn tùy chỉnh chuyên sâu thì cần đăng nhập website để thực hiện các tính năng nâng cao khác
   - Quản lý các file đã upload
   - Thêm thủ công các file html/stl/obj khi cần thiết ( hiện tại chỉ hỗ trợ Upload tự động html)
     <img width="1825" height="631" alt="image" src="https://github.com/user-attachments/assets/26a56dd0-ae50-40b5-a930-3f3000d42ae5" />


---

## 3. Sử Dụng Trên Giao Diện Mobile/PC
<img width="482" height="790" alt="image" src="https://github.com/user-attachments/assets/eacb84c7-1e65-462c-af57-f41105d6fca6" />

Giao diện được tối ưu hóa hoàn toàn cho màn hình cảm ứng,pc giúp tư vấn cho bệnh nhân ngay trên pc hoặc máy tính bảng:

### Thao tác điều khiển 3D (Trên mobile): Về cơ bản giống Exocad Webview.
- **Xoay mô hình**: Dùng 1 ngón tay vuốt trên màn hình.
- **Phóng to/Thu nhỏ**: Dùng 2 ngón tay chụm/mở (Pinch to zoom).
- **Xoay**: Dùng 2 ngón tay xoay

### Giao diện và tính năng chính: tương tự Exocad Webview nhưng xịn xò hơn :))
- **Bảng điều khiển  (Layers)**: Nhấp vào biểu tượng "Lớp chồng" ở góc màn hình để hiện danh sách các thành phần.
- **Chia sẻ không cần phải đăng nhập**. Người nhận mở link là có thể xem trực tiếp trên trình duyệt
- **Thanh điều hướng** : Hỗ trợ trong quá trình xoay hình. Tương thích với hệ trục tọa độ máy Shinning3D khi căn chỉnh đúng.
---

## 5. ⚠️ Một Số Lưu Ý Quan Trọng

- **Thời gian lưu trữ**: Để tối ưu bộ nhớ server, các mẫu hàm sẽ được **tự động xóa sau 14 ngày** kể từ ngày upload. Hãy đảm bảo bạn đã hoàn tất công việc trước thời hạn này.
- **Định dạng hỗ trợ**: Hệ thống hoạt động tốt nhất với file `.html` (xuất bản từ Exocad), `.stl` và `.obj`.


---
*© 2026 Hương Cam Táo 3D Viewer - Giải pháp nha khoa kỹ thuật số toàn diện.*
