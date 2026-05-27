# CHANGELOG

Update log
---

## [v0.2] - Bản phát hành tối ưu hiệu năng UI
Bản phát hành tập trung chuẩn hóa trải nghiệm người dùng, tinh chỉnh cú pháp hiển thị và đồng bộ hóa hệ thống thuật ngữ.

### Tối ưu hóa hiển thị giao diện (UI/UX)
- Chuẩn hóa quy tắc viết hoa theo định dạng Sentence Case thay cho Title Case cũ, áp dụng đồng bộ trên toàn bộ hệ thống tệp tin (ví dụ: chuyển đổi "Cài Đặt" thành "Cài đặt", "Tạo Thế Giới" thành "Tạo thế giới")[cite: 2].
- Rút gọn độ dài chuỗi ký tự dựa trên thuộc tính hiển thị của UI game, khắc phục triệt để hiện tượng tràn khung (overflow) và lỗi ngắt dòng trên các thiết bị di động (ví dụ: tối ưu hóa cụm "Không thể kết nối đến máy chủ" thành "Không thể kết nối")[cite: 2].
- Nâng cấp văn phong tự nhiên, loại bỏ các cấu trúc dịch thô (machine translation) sang thuật ngữ chuyên dụng (ví dụ: cấu trúc lại "Thoát ra Menu Chính" thành "Về menu chính", "Chế tạo Tên lửa" thành "Chế tạo tên lửa")[cite: 2].

### Thống nhất bộ từ (Unify Terms)
- Đồng bộ hóa các biến hành động xuất hiện lặp lại tại các phân mục nhằm đảm bảo tính nhất quán của cơ sở dữ liệu:
  - Build / Craft chuyển hoàn toàn thành "Chế tạo"[cite: 2].
  - Settings chuyển hoàn toàn thành "Cài đặt"[cite: 2].
  - Save / Load chuyển hoàn toàn thành "Lưu" / "Tải"[cite: 2].

### Sửa lỗi logic hiển thị (Bug Fixes)
- Khắc phục lỗi chính tả cú pháp và dấu tiếng Việt tồn đọng từ phiên bản tiền nhiệm (ví dụ: sửa lỗi "Góc nghiên" thành "Góc nghiêng")[cite: 2].
- Định hình lại cấu trúc các dòng thông số telemetry kép tránh xung đột hiển thị.

---

## [v0.1] - Bản phát hành khởi tạo (Alpha Release)
Xây dựng cấu trúc tệp tin bản dịch sơ bộ và ánh xạ dữ liệu chuỗi ký tự gốc.

### Tính năng cốt lõi
- Biên dịch hoàn chỉnh 100% các phân mục ngôn ngữ hệ thống dựa trên cấu trúc tệp tin mẫu Example.txt[cite: 2].
- Khởi tạo dữ liệu ngôn ngữ cho hệ thống menu chính, tùy chỉnh cấu hình, danh mục linh kiện cơ khí, bản đồ quỹ đạo, hệ thống thiên thể và nhật ký chuyến bay[cite: 2].
- Bảo toàn nguyên vẹn định dạng của các biến hệ thống (%value%, %speed%, %funds%) và các thẻ định dạng văn bản giàu tính năng (<size=...></size>), ngăn ngừa hoàn toàn nguy cơ xung đột gây crash engine[cite: 2].
- Việt hóa danh xưng hệ thống hành tinh, vệ tinh tự nhiên trong Hệ Mặt Trời và các mốc địa danh bề mặt (Landmarks) phục vụ cấu trúc chế độ Thử thách (Challenges)[cite: 2].
