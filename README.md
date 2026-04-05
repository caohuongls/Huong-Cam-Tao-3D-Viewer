# Hướng Dẫn Sử Dụng Hương Cam Táo 3D Viewer

---

## I. Upload File từ Máy Tính và lấy link - Tương tự Dentalshare Exocad

Để đưa file từ phần mềm thiết kế (Exocad) lên hệ thống, bạn sử dụng công cụ **Huong Cam Tao Viewer**.


   1. Tải và mở file `Huong_Cam_Tao_Viewer.exe` trên máy tính. Lưu file ở 1 vị trí cố định trên máy tính, ưu tiên tạo 1 thư mục riêng để chứa các thông tin config.
   2. Cấu hình
   
      <img width="523" height="765" alt="image" src="https://github.com/user-attachments/assets/7ae3420d-00dc-4aa5-bf79-0894e9fb2a7c" />
   
      Nhập các trường thông tin:
      - **Server Address**: Địa chỉ web của hệ thống (mặc đinh hiện tại là: `https://caohuongls.pythonanywhere.com`). Trong  tương lai sẽ điều chỉnh lại nếu cần.
      - **Username/Password**: Tài khoản được cung cấp. Tài khoản thử nghiệm: demo/12345
      - **Watch Folder**: Chọn thư mục chứa các file thiết kế của bạn (thường là thư mục CAD-Data của Exocad).
      - **Sync Start Date**: Chọn ngày bắt đầu đồng bộ (các file  html cũ trước ngày này sẽ không bị đẩy lên).
      - **Auto Start with windows**: Cho chương trình khởi đọng cùng window hay không.
   
   
   3. Vận hành
   - Sau khi thiết lập, công cụ sẽ chạy ẩn dưới thanh Taskbar (biểu tượng logo Cam Táo) và sẽ tự động xử lý
   - Khi muốn gửi file để xem trước. Trong Exocad Vào mục **Tool - Export html** . Lưu file **html** vào thư mục bên trong dự án Exocad đang làm. Lưu ý: Tên file sẽ là tiêu đề của dự án.
   - Phần mềm sẽ xử lý file html vừa lưu. Trung bình dưới 10s sẽ có thông báo gửi về và cung cấp đường dẫn link và tự động lưu link vào bộ nhớ tạm.


       <img width="361" height="179" alt="image" src="https://github.com/user-attachments/assets/a8179266-b20d-44fc-979b-c7bc3e12d4c8" />
   
   - Lấy link chia sẻ : nhấn chuột phải vào biểu tượng dưới **Taskbar** -> **Lịch sử Upload** để copy lại các link đã upload.



     <img width="503" height="418" alt="image" src="https://github.com/user-attachments/assets/684dce24-be11-4320-970e-8308a9b03896" />


   
---

## II. Đăng Nhập website
Với các bác muốn tùy chỉnh chuyên sâu thì cần đăng nhập website để thực hiện các tính năng nâng cao khác
   - Quản lý các file đã upload
   - Thêm thủ công các file html/stl/obj vào dự án khi cần thiết ( do hiện tại công cụ chỉ hỗ trợ Upload tự động html)
     <img width="1825" height="631" alt="image" src="https://github.com/user-attachments/assets/26a56dd0-ae50-40b5-a930-3f3000d42ae5" />
---

## III. Sử Dụng Trên Giao Diện Mobile/PC
<img width="482" height="790" alt="image" src="https://github.com/user-attachments/assets/eacb84c7-1e65-462c-af57-f41105d6fca6" />

Giao diện được tối ưu hóa hoàn toàn cho màn hình cảm ứng,PC tương tự Exocad Webview nhưng xịn xò hơn :))

### Thao tác điều khiển 3D (Trên mobile): Về cơ bản giống Exocad Webview.
- **Xoay quanh tâm**: Dùng 1 ngón tay di chuyển trên màn hình.
- **Phóng to/Thu nhỏ**: Dùng 2 ngón tay chụm/mở (Pinch to zoom).
- **Xoay tròn**: Dùng 2 ngón tay xoay
- **Di chuyển** : Nhấn giữ 2 ngón

### Một số tính năng chính: 
<img width="1080" height="176" alt="image" src="https://github.com/user-attachments/assets/7d883265-fce0-4b1d-a143-e9bd8d1bcf3f" />

- **Bảng điều khiển (Layers)**: Nhấp vào biểu tượng  ở góc trái màn hình để hiện/tắt danh sách các thành phần.
- **Thanh điều hướng** : Hỗ trợ trong quá trình xoay hình. Tương thích với hệ trục tọa độ máy Shinning3D khi căn chỉnh đúng.
- **Chia sẻ**: Sao chep link gửi cho người khác không cần đăng nhập.
- **Chuyển đổi texture** : Bật/Tắt texture trong trường hợp mẫu hàm có màu.
- **Chụp màn hình**: Chụp góc nhìn hiện tại lưu vào bộ nhớ đệm
- **Thêm file**: Bổ sung thêm file. Hỗ trợ định dạng : `html`, `stl`,`obj` .
---

## IV. Một Số Lưu Ý Quan Trọng

- **Thời gian lưu trữ**: Để tối ưu bộ nhớ server, các mẫu hàm sẽ được **tự động xóa sau 7 ngày** kể từ ngày upload. Hãy đảm bảo bạn đã hoàn tất công việc trước thời hạn này.
- **Định dạng hỗ trợ**: Hệ thống hoạt động tốt nhất với file `.html` (lấy từ Exocad), `.stl` và `.obj`.
---
 © 2026 Hương Cam Táo 3D Viewer 
