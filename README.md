# skillbridge_app

A new Flutter project.

## 🚀 Hướng Dẫn Chạy Dự Án

Dự án này là một ứng dụng Flutter. Dưới đây là các bước để chạy ứng dụng trên máy ảo Android (Pixel 7) mà bạn đã thiết lập.

### 1. Bật máy ảo Android (Emulator)
Bạn có thể bật máy ảo trực tiếp thông qua **Android Studio (Device Manager)** hoặc bật bằng dòng lệnh trong Terminal:
```bash
flutter emulators --launch Pixel_7
```
*(Lưu ý: Bạn có thể xem danh sách các máy ảo khả dụng bằng lệnh `flutter emulators`)*

### 2. Chạy Ứng Dụng
Sau khi máy ảo đã khởi động hoàn toàn (hoặc nếu bạn cắm thiết bị thật), mở Terminal ở thư mục gốc của dự án và chạy:
```bash
flutter run
```
Nếu có nhiều thiết bị đang bật cùng lúc (ví dụ: macOS, Chrome, Pixel_7), Flutter sẽ hỏi bạn muốn chạy trên thiết bị nào. Nhập số tương ứng với máy ảo Android (thường là `1` hoặc `2`) và nhấn **Enter**.

> **Mẹo nhanh:** Nếu bạn biết chính xác ID hiển thị của máy ảo lúc chạy (ví dụ `emulator-5554`), bạn có thể bỏ qua bước chọn thiết bị bằng cách:
> ```bash
> flutter run -d emulator-5554
> ```

### 3. Phím tắt hữu ích trong lúc chạy (`flutter run`)
Sau khi ứng dụng đang chạy ở Terminal, bạn có thể thực hiện các thao tác:
- Lôi chuột hoặc focus vào Terminal.
- Bấm **`r`** (thường) để **Hot Reload** (cập nhật giao diện ngay lập tức mà không mất state hiện hành khi bạn lưu code).
- Bấm **`R`** (viết hoa) để **Hot Restart** (khởi động lại ứng dụng hoàn toàn).
- Bấm **`q`** để thoát và dừng chạy ứng dụng.

---

### Tài liệu tham khảo của Flutter
Nếu bạn muốn tìm hiểu thêm về Flutter:
- [Learn Flutter](https://docs.flutter.dev/get-started/learn-flutter)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Online documentation](https://docs.flutter.dev/)
# skillbridge_app
