# Trình tạo Key & Tùy chỉnh MobaXterm 🚀

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Version](https://img.shields.io/badge/Version-v2.4-green.svg)
![Compatibility](https://img.shields.io/badge/Compatible-v20.X%20|%20v25.1%20|%20v25.2-orange)

> ⭐ **Hãy đánh dấu sao cho kho lưu trữ này nếu bạn thấy nó hữu ích!** ⭐

## Tổng quan

Một công cụ web hiện đại, thân thiện với người dùng để tạo khóa kích hoạt và tùy chỉnh MobaXterm, trình giả lập terminal tối ưu cho Windows với máy chủ X11 tích hợp, khách SSH và bộ công cụ mạng toàn diện.

![Ảnh chụp màn hình Trình tạo Key MobaXterm](https://d2bgqtsoaxm8w0.cloudfront.net/uploads/images/v2-4.png)

## Tính năng

- **✨ Giao diện hiện đại, sạch sẽ** - Thiết kế đáp ứng tối ưu cho cả máy tính và di động
- **🌓 Chế độ Sáng/Tối** - Chuyển đổi giữa các chủ đề chỉ với một cú nhấp
- **🔒 Hỗ trợ nhiều phiên bản** - Tạo key cho các phiên bản MobaXterm khác nhau
- **👥 Số lượng người dùng tùy chỉnh** - Chỉ định số lượng người dùng đồng thời
- **💾 Tải xuống chỉ với một cú nhấp** - Tải ngay file kích hoạt tùy chỉnh của bạn
- **🔧 Tùy chỉnh hoàn chỉnh** - Tạo cài đặt cá nhân hóa mà không cần công cụ tùy chỉnh chính thức
- **🖼️ Hỗ trợ logo tùy chỉnh** - Thay thế logo mặc định của MobaXterm bằng logo của bạn
- **📑 Quản lý Bookmarks** - Định nghĩa trước các hồ sơ kết nối SSH, FTP, v.v.
- **🔌 Tích hợp Plugin** - Bao gồm plugin trong cấu hình tùy chỉnh của bạn

## Tương thích

- Hoạt động với **MobaXterm phiên bản 20.X, 25.1 và 25.2**
- Hỗ trợ cả bản portable và bản cài đặt

## Hướng dẫn sử dụng

### Trình tạo Key

1. **Truy cập Trình tạo Key**: Vào [MobaXterm Key Generator](https://moba-xterm-keygen.vercel.app/)
2. **Điền vào biểu mẫu**:
   - Chọn phiên bản MobaXterm mong muốn
   - Nhập tên người dùng (chỉ chữ cái)
   - Chọn phiên bản MobaXterm (20.X hoặc 25.X)
   - Chỉ định số lượng người dùng
3. **Tải xuống**: Nhấp "Download Key" để lấy file Custom.mxtpro của bạn
4. **Kích hoạt**: Đặt file đã tạo vào thư mục cài đặt MobaXterm:
   ```
   C:\Program Files (x86)\Mobatek\MobaXterm
   ```

### Tùy chỉnh

1. **Chuyển sang Tab Customizer** trên giao diện web
2. **Cấu hình các cài đặt của bạn**:
   - **Banner**: Tạo thông điệp chào mừng cá nhân hóa
   - **Profile**: Cấu hình bash profile tùy chỉnh (tương tự /etc/profile trên Linux)
   - **Cài đặt**: Bật/tắt các tính năng của MobaXterm
   - **Logo**: Tải lên hình ảnh logo tùy chỉnh
   - **Bookmarks**: Tạo các kết nối định sẵn cho người dùng
   - **Plugins**: Thêm plugin MobaXterm tùy chọn (.mxt3)
3. **Tạo file cấu hình**: Nhấp "Generate Configuration File" để tải file cấu hình về
4. **Áp dụng cài đặt**: Sử dụng một trong hai cách dưới đây để áp dụng tùy chỉnh

### Trình hợp nhất cài đặt

1. **Chuyển sang Tab Custom Settings Merger**
2. **Tải lên các file**:
   - File key bản quyền của bạn (Custom.mxtpro)
   - File tùy chỉnh của bạn (MobaXterm customization.custom)
3. **Hợp nhất**: Tạo một file duy nhất chứa cả key và cài đặt tùy chỉnh
4. **Triển khai**: Sao chép file Custom.mxtpro đã hợp nhất vào thư mục cài đặt MobaXterm

## Hướng dẫn cài đặt

### Bước 1: Tải MobaXterm
Tải phiên bản mới nhất từ [trang chủ MobaXterm](https://mobaxterm.mobatek.net/download-home-edition.html).

### Bước 2: Tạo Key & Tùy chỉnh
Sử dụng công cụ của chúng tôi để:
1. Tạo key kích hoạt
2. Tùy chỉnh cài đặt (tùy chọn)
3. Hợp nhất key với file tùy chỉnh (tùy chọn)

### Bước 3: Kích hoạt MobaXterm
1. Tìm thư mục cài đặt MobaXterm:
   - **Đường dẫn mặc định**: `C:\Program Files (x86)\Mobatek\MobaXterm`
   - Hoặc nhấp chuột phải vào shortcut MobaXterm và chọn "Open file location"
2. Sao chép file `Custom.mxtpro` vào thư mục này
3. Khởi động MobaXterm - bản quyền và tùy chỉnh sẽ được áp dụng!

### Phương pháp tùy chỉnh thay thế

MobaXterm.exe có chế độ tùy chỉnh, truy cập bằng tham số "-customizer":

```
.\MobaXterm.exe -customizer
```

Công cụ chính thức này cũng cho phép bạn xuất cài đặt ra file "MobaXterm customization.custom". Trình tùy chỉnh trên web của chúng tôi cung cấp chức năng tương tự, trực tiếp trên trình duyệt.

## Khắc phục sự cố

1. **Kích hoạt không thành công?**
   - Đảm bảo bạn dùng đúng phiên bản (20.X, 25.1 hoặc 25.2)
   - Đảm bảo file nằm đúng vị trí
   - Kiểm tra tên file chính xác là `Custom.mxtpro`

2. **Lỗi khi tạo key?**
   - Đảm bảo đã điền đầy đủ các trường trong biểu mẫu
   - Tên người dùng chỉ chứa chữ cái (không dấu cách, số hoặc ký tự đặc biệt)
   - Thử làm mới trang và tạo lại

3. **Tùy chỉnh không áp dụng?**
   - Đảm bảo đã hợp nhất file tùy chỉnh với file key
   - Đảm bảo file hợp nhất tên chính xác là `Custom.mxtpro`
   - Thử khởi động lại MobaXterm sau khi đặt file vào thư mục cài đặt

## Chi tiết kỹ thuật

Công cụ này sử dụng xử lý phía client để tạo key bản quyền và file tùy chỉnh dựa trên thông tin bạn nhập. Mọi thứ được tạo trực tiếp trên trình duyệt - không có dữ liệu nào được gửi lên máy chủ, đảm bảo quyền riêng tư và bảo mật của bạn.

## Tuyên bố miễn trừ trách nhiệm

Công cụ này chỉ dành cho mục đích học tập. Hãy ủng hộ nhà phát triển bằng cách mua bản quyền cho mục đích thương mại.

## Phát triển

### Xây dựng với
- Vue.js
- Tailwind CSS
- JavaScript hiện đại

### Lịch sử phiên bản
- **v2.4** - Thêm đầy đủ chức năng tùy chỉnh MobaXterm
- **v2.3** - Thêm trình hợp nhất cài đặt tùy chỉnh
- **v2.2** - Chế độ tối và tối ưu hóa di động
- **v2.1** - Thêm hỗ trợ phiên bản 25.2
- **v2.0** - Thiết kế lại giao diện lớn
- **v1.0** - Phát hành ban đầu


---

⭐ [Đánh dấu sao cho kho lưu trữ này trên GitHub!](https://github.com/bibo318/MobaXterm-Active-GenKey) ⭐
