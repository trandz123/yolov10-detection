1. Mục tiêu
Sử dụng một mô hình YOLOv10 (bản yolov10n.pt) đã được huấn luyện sẵn trên bộ dữ liệu COCO (80 lớp đối tượng).

Chạy mô hình trên một ảnh do người dùng tải lên.

Trực quan hóa kết quả bằng cách vẽ các khung viền (bounding box) và nhãn (label) lên các đối tượng được phát hiện.

2. Công nghệ sử dụng
Ngôn ngữ: Python

Nền tảng: Google Colab

Thư viện chính:

ultralytics: Framework để tải và chạy các mô hình YOLO.

OpenCV (cv2): Để xử lý, vẽ lên ảnh.

Matplotlib: Để hiển thị ảnh kết quả.

3. Cách hoạt động
Cài đặt thư viện ultralytics.

Tải mô hình yolov10n.pt từ ultralytics.

Cho phép người dùng tải ảnh lên từ máy tính.

Sử dụng hàm model.predict() để chạy nhận diện trên ảnh.

Lặp qua các kết quả, lấy tọa độ, độ tự tin và tên nhãn của từng đối tượng.
4. kết quả
![Kết quả nhận diện YOLOv10]()

Vẽ các thông tin này lên ảnh gốc và hiển thị kết quả.

4. Kết quả mẫu
