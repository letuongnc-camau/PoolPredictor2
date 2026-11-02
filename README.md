# Pool Predictor Android

Dự án Android native Kotlin khởi tạo theo file đặc tả được cung cấp.

## Mở và build
1. Giải nén project.
2. Mở thư mục `PoolPredictorAndroid` trong Android Studio.
3. Đồng bộ Gradle (cần Android SDK 35 và JDK 17).
4. Build > Build APK(s), hoặc chạy trên thiết bị Android.

## Lưu ý
Đây là bản mẫu hiển thị overlay dựa trên tọa độ mô phỏng. Nó chưa chụp màn hình,
chưa tự nhận diện bi và không đồng bộ dữ liệu vị trí từ game. Các tọa độ/góc trong
TrajectoryOverlayView là ví dụ minh họa. Cần bổ sung quy trình nhận diện ảnh (ví dụ
OpenCV) và giao diện hiệu chỉnh tọa độ nếu muốn predictor thực tế.
