# Ghi chú phiên bản — BELLATOR Control Center 2026 English R2 (N176)

**Phiên bản:** English R2 — OEM `2.0.2.1161`  
**Thiết bị đã kiểm thử:** Lecoo Bellator N176 (đời 2025), AMD Ryzen 9 8940HX  
**Tình trạng:** Bản tùy chỉnh không chính thức  
**Ghi công:** Tác giả sử dụng **Rea** trong quá trình phát triển.

> [!IMPORTANT]
> **Mới kiểm thử thực tế trên 01 máy Bellator N176 (2025). Chưa kiểm thử trên N176B, N176C, N176 có CPU/BIOS khác hoặc bất kỳ mã máy nào khác.** Không được suy diễn khả năng tương thích từ tên dòng máy.

## Những thay đổi được ghi nhận ở bản R2

- Chuyển các phần giao diện cài đặt, giới thiệu, phản hồi, menu và tài nguyên khởi động sang tiếng Anh.
- Trang Hỗ trợ tiếng Anh có tài nguyên dành cho N176 phân phối ở thị trường Trung Quốc.
- Giao diện chính tiếng Anh với các chế độ Quiet, Balanced, Beast và Battle.
- Điều khiển quạt qua tiến trình riêng `BellatorFanHost.exe` và kiểm tra tính hợp lệ của lệnh.
- Chỉnh giới hạn tốc độ quạt riêng cho từng chế độ và khôi phục mặc định.
- Điều khiển máy ở chế độ cục bộ không bắt buộc đăng nhập Lenovo.
- Steam Boost hiển thị rõ yêu cầu đăng nhập Lenovo ID.

## Phạm vi kiểm thử do tác giả cung cấp

- Đã thử cài mới, nâng cấp và gỡ cài đặt trên Windows giao diện tiếng Anh (en-US).
- **Chỉ 01 máy vật lý:** N176 / Ryzen 9 8940HX / RTX 5060 / BIOS `N176DRLKV2727`.
- Báo cáo có các bài thử về chế độ quạt, điều chỉnh RPM, độ ổn định chuyển trang và từ chối lệnh không hợp lệ.
- Chi tiết: [Hướng dẫn R2](docs/Huong-dan-R2.txt) và [kết quả kiểm thử R2](docs/Kiem-thu-R2.json).
- **Chưa có kết quả kiểm thử độc lập trên máy thứ hai hoặc cấu hình khác.**

## Các giới hạn hiện tại

- Chưa xác minh tương thích với các mã máy khác hoặc các biến thể BIOS/CPU khác.
- Chưa xác minh chức năng giới hạn sạc ở mức 80%.
- Một số nội dung trực tuyến vẫn do máy chủ hãng quản lý.
- Bộ cài tùy chỉnh không có chữ ký số của nhà sản xuất.
- Repository hiện là nơi lưu tài liệu, ảnh và thông tin xác minh; không chứa mã nguồn ứng dụng hoặc bộ cài EXE trong các thư mục mã nguồn.

**SHA-256 đã được cung cấp cho bộ cài R2:**

`8633AB20765C1CD4BCD98292303CA5727FEED2031FBD4590D0A8F5F44CA05CA0`

> Chỉ phát hành EXE khi có quyền phân phối các thành phần OEM đi kèm và khi mã SHA-256 của EXE thực tế khớp với thông tin công bố.
