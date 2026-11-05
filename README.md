# BELLATOR Control Center 2026 — Bản tiếng Anh R2 dành cho N176

**Phát triển với sự hỗ trợ của Rea** (theo thông tin từ tác giả dự án).

Đây là **bản Việt hóa tài liệu giới thiệu cho phiên bản phần mềm được chuyển giao diện sang tiếng Anh (English R2)**, dựa trên **BELLATOR Control Center 2026**, dành cho laptop **Lecoo Bellator N176 (đời 2025)**. Đây là dự án tùy chỉnh **không chính thức**.

> [!IMPORTANT]
> **Ứng dụng là BELLATOR Control Center 2026; năm 2025 là đời máy N176 được thử nghiệm, không phải năm phát hành của ứng dụng.**
>
> **Hiện chỉ mới kiểm thử thực tế trên 01 máy Bellator N176 (2025), CPU AMD Ryzen 9 8940HX. CHƯA thử nghiệm trên bất kỳ mã máy hoặc biến thể cấu hình nào khác.**
>
> Không thể khẳng định phần mềm hoạt động an toàn hoặc tương thích với N176B, N176C, các bản N176 có CPU/BIOS khác hay các dòng Lenovo/Lecoo khác.

![Giao diện chính BELLATOR Control Center 2026 — English R2](screenshots/Giao-dien-R2.png)

## Giới thiệu dự án

Dự án là bản tùy chỉnh giao diện **tiếng Anh** của phần mềm BELLATOR Control Center 2026 dành cho máy N176 đã nêu. Tác giả sử dụng **Rea** trong quá trình phát triển bản English R2.

Mục tiêu là chuyển các phần giao diện sang tiếng Anh, đồng thời giữ lại các tính năng điều khiển phần cứng gốc tương ứng với máy đã kiểm thử. Dự án này **không phải phần mềm chính thức do Lenovo, Lecoo hoặc Bellator phát hành**.

Repository hiện chứa tài liệu hướng dẫn, báo cáo kiểm thử, mã SHA-256 và ảnh chụp màn hình; **không chứa mã nguồn ứng dụng hoặc file cài đặt EXE trong các thư mục mã nguồn**. Nếu có bộ cài được phép phân phối, bộ cài sẽ được đăng riêng tại mục **Releases**.

## Thiết bị đã kiểm thử

| Hạng mục | Thông tin của máy đã kiểm thử |
| --- | --- |
| Dòng máy | **Lecoo Bellator N176 (2025)** |
| Bộ xử lý | AMD Ryzen 9 8940HX |
| Card đồ họa | NVIDIA GeForce RTX 5060 Laptop GPU |
| BIOS | `N176DRLKV2727` |
| Phần mềm | BELLATOR Control Center **2026**, English R2 |
| Phiên bản OEM tương ứng | `2.0.2.1161` |
| Số máy kiểm thử thực tế | **01 máy** (theo báo cáo R2 do tác giả cung cấp) |

### Tình trạng tương thích

- **Đã kiểm thử:** Bellator N176 (2025), Ryzen 9 8940HX, RTX 5060, BIOS `N176DRLKV2727`.
- **Chưa kiểm thử:** Bellator N176B, N176C, các biến thể N176 dùng CPU hoặc BIOS khác, và **tất cả dòng máy khác**.
- **Không có cơ sở bảo đảm** bản tùy chỉnh sẽ hoạt động trên máy chưa kiểm thử. Không cài đặt khi thiết bị không khớp cấu hình đã xác minh.

## Các tính năng được ghi nhận ở bản English R2

- Chuyển giao diện chính, phần cài đặt, giới thiệu, phản hồi, hỗ trợ và một số tài nguyên sang **tiếng Anh**.
- Các chế độ hiệu năng: **Quiet / Balanced / Beast / Battle** (Yên tĩnh / Cân bằng / Hiệu năng cao / Chiến đấu).
- Hiển thị tốc độ quạt thực tế, chỉnh **giới hạn tốc độ quạt** theo từng chế độ, mỗi bước **100 RPM**, và **Restore defaults** (khôi phục mặc định).
- Các chức năng GPU, phím chức năng, bàn di chuột theo khả năng hỗ trợ của ứng dụng và phần cứng gốc.
- Sử dụng chức năng điều khiển máy ở chế độ cục bộ mà không cần đăng nhập Lenovo.
- **Steam Boost** vẫn yêu cầu tài khoản Lenovo và quyền truy cập dịch vụ của hãng.

**Các giới hạn cần biết:** Chưa bổ sung chế độ giới hạn sạc 80% vì chưa xác minh được lệnh BIOS phù hợp. Một số nội dung trực tuyến vẫn do máy chủ hãng cung cấp. Mức RPM điều chỉnh là **giới hạn tối đa**, không phải lệnh ép quạt quay cố định liên tục. Xem [hướng dẫn bản R2](docs/Huong-dan-R2.txt) để biết thêm chi tiết.

## Hình ảnh giao diện

### Giao diện chính — BELLATOR 2026 English R2

![Giao diện chính bản tiếng Anh R2](screenshots/Giao-dien-R2.png)

### Trang hỗ trợ — bản English R2

![Giao diện trang hỗ trợ tiếng Anh](screenshots/Support-R2.png)

### Giao diện bản 1.1.5 tiếng Anh — ảnh tham khảo

![Giao diện BELLATOR 1.1.5 tiếng Anh](screenshots/Giao-dien-tieng-Anh.png)

> Ảnh của bản **1.1.5** chỉ để tham khảo, không phải giao diện của bản **2026 R2**.

## Hướng dẫn cài đặt

1. **Kiểm tra đúng dòng máy N176 (2025), CPU và BIOS** theo bảng thiết bị đã kiểm thử.
2. Khi có bản phát hành hợp lệ, tải tệp `BELLATOR-2026-N176-English-R2-Setup.exe` tại mục [Releases](https://github.com/bmint31/BELLATOR-Control-Center-2026-N176/releases).
3. Kiểm tra mã **SHA-256** của bộ cài trong PowerShell:

   ```powershell
   Get-FileHash ".\BELLATOR-2026-N176-English-R2-Setup.exe" -Algorithm SHA256
   ```

   Mã SHA-256 được ghi trong tài liệu đã cung cấp:

   ```text
   8633AB20765C1CD4BCD98292303CA5727FEED2031FBD4590D0A8F5F44CA05CA0
   ```

   **Nếu mã không trùng khớp, không sử dụng tệp đó với thông tin xác minh này.**
4. Đọc [hướng dẫn cài đặt và sử dụng R2](docs/Huong-dan-R2.txt), sau đó mới chạy bộ cài với quyền quản trị.
5. Dùng bộ sạc chính hãng khi chọn các chế độ yêu cầu nguồn AC; không mở đồng thời nhiều ứng dụng điều khiển phần cứng có thể xung đột.

**Về kiểm thử:** Tài liệu do tác giả cung cấp ghi nhận đã thử các thao tác cài/gỡ, chuyển chế độ, điều chỉnh quạt và chuyển trang trên **01 máy N176 phù hợp**. Những kết quả đó **chưa phải kiểm thử độc lập trên các dòng máy khác**. Bộ cài tùy chỉnh cũng **không có chữ ký số của nhà sản xuất**.

## Tài liệu và tệp trong repository

| Đường dẫn | Nội dung |
| --- | --- |
| `docs/Huong-dan-R2.txt` | Hướng dẫn tiếng Việt cho bản 2026 English R2, cấu hình áp dụng và các giới hạn |
| `docs/Huong-dan.txt` | Tài liệu tiếng Việt cho bản 1.1.5 tiếng Anh trước đó |
| `docs/Kiem-thu-R2.json` | Báo cáo kết quả kiểm thử R2 do tác giả cung cấp |
| `docs/SHA256-R2.txt` | Mã SHA-256 của bộ cài R2 |
| `docs/SHA256.txt` | Mã SHA-256 của bộ cài tiếng Anh 1.1.5 |
| `screenshots/` | Ảnh giao diện các phiên bản do tác giả cung cấp |
| `RELEASE_NOTES.md` | Ghi chú thay đổi của bản English R2 |

## Lưu ý về an toàn, bản quyền và phân phối

- Đây là **dự án tùy chỉnh không chính thức**, không đại diện cho Lenovo, Lecoo hoặc Bellator.
- Tên thương hiệu, biểu tượng và thành phần chương trình gốc thuộc về chủ sở hữu tương ứng.
- **Chỉ được công khai hoặc phân phối lại bộ cài, thư viện và thành phần sở hữu độc quyền khi có quyền hoặc sự cho phép phù hợp.**
- Phần mềm can thiệp vào chế độ hiệu năng và điều khiển phần cứng. Chỉ dùng trên cấu hình đã được kiểm thử, sao lưu dữ liệu quan trọng và giữ phương án khôi phục phần mềm gốc.
- Không có bảo đảm về khả năng hoạt động trên các mẫu máy chưa thử nghiệm.

---

**Tóm tắt:** Dự án giới thiệu **BELLATOR Control Center 2026 — English R2** cho **Bellator N176 đời 2025**. Hiện mới có kết quả kiểm thử trên **01 máy N176**, **chưa kiểm thử những mã máy khác**. Xem thêm [tài liệu hướng dẫn](docs/Huong-dan-R2.txt) và [ghi chú phiên bản](RELEASE_NOTES.md).
