# Cốc nào có bóng? — Dự án Android APK

Dự án Android WebView hoàn chỉnh được tạo từ file HTML của bạn.

## Thông số đóng gói
- Tên ứng dụng: Cốc nào có bóng?
- Package ID: vn.game.cocnaocobong
- Phiên bản: 1.0.0 (versionCode 1)
- Android hỗ trợ: API 24+ (Android 7.0 trở lên) đến API 34

## Cách 1: Build thành file .apk miễn phí trên GitHub (không cần cài Android Studio)
1. Giải nén file ZIP này thành một thư mục.
2. Tạo một repository mới trên GitHub và tải toàn bộ các file trong thư mục lên (lưu ý giữ nguyên thư mục `.github/workflows/build-apk.yml`).
3. Mở tab **Actions** trên GitHub -> chọn workflow **Build Android APK** -> nhấn **Run workflow** (hoặc tự chạy sau khi push).
4. Sau khoảng 2 phút, tải file **coc-nao-co-bong-apk.zip** ở mục Artifacts, giải nén để lấy **app-debug.apk** và cài lên điện thoại Android.

## Cách 2: Build trực tiếp bằng Android Studio
1. Mở thư mục này bằng **Android Studio**.
2. Chờ Gradle đồng bộ xong.
3. Chọn **Build > Build Bundle(s) / APK(s) > Build APK(s)** để xuất file `.apk`.
