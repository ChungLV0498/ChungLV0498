# Lê Văn Chung

**Kỹ Sư Phần Mềm (Full-Stack) | Kỹ Sư Hệ Thống Nhúng & IoT | Tự Động Hóa Quy Trình**

[Email: chunglv04@gmail.com](mailto:chunglv04@gmail.com) | [Dự án thực tế: hanngu24h.com](https://hanngu24h.com) | [GitHub: ChungLV0498](https://github.com/ChungLV0498)

---

## Tóm Tắt Chuyên Môn

Kỹ sư phần mềm và phần cứng với kinh nghiệm thực chiến đa lĩnh vực: từ lập trình vi điều khiển, thiết kế hệ thống kiểm thử tự động trên dây chuyền sản xuất thiết bị điện tử, đến phát triển ứng dụng web quy mô lớn và xây dựng hệ thống tự động hóa nội dung đa kênh.

- **Hệ thống nhúng & IoT công nghiệp**: Thiết kế đồ gá kiểm thử, tự động hóa nạp firmware, đo kiểm chu kỳ sạc/xả pin và kiểm tra thông số âm thanh cho các thiết bị điện tử tiêu dùng.
- **Phát triển Web Full-Stack**: Sáng lập và vận hành nền tảng giáo dục trực tuyến **hanngu24h.com** phục vụ hơn 10.000 lượt truy cập hàng tháng, tích hợp luyện thi HSK tương tác và công nghệ nhận diện phát âm.
- **Hệ thống tự động hóa media**: Thiết kế và vận hành cụm hệ thống tự động biên tập video, tổng hợp giọng nói AI (Neural TTS đa ngôn ngữ) và phân phối nội dung tự động qua VPS cho hơn 50 kênh YouTube.
- **Phần mềm quản trị doanh nghiệp**: Xây dựng hệ thống quản lý bán hàng (POS), định giá vàng theo thời gian thực và quản trị kho vận cho chuỗi bán lẻ kim hoàn.

---

## Năng Lực Kỹ Thuật

| Lĩnh Vực | Công Nghệ & Công Cụ Chủ Đạo |
|---|---|
| **Ngôn ngữ lập trình** | Python, JavaScript (ES6+), PHP, C/C++, SQL |
| **Giao diện & Web** | HTML5, CSS3, Three.js / WebGL, HTML5 Canvas, Electron, Bootstrap |
| **Backend & Cơ sở dữ liệu** | Node.js, PHP REST API, SQLite, MySQL, Nginx, Apache |
| **Hệ thống nhúng & IoT** | ESP32, Arduino, UART/RS232, I2C, SPI, LoRa, Đo kiểm pin tự động |
| **Xử lý âm thanh & Video** | FFmpeg, Neural TTS (Tiếng Việt / Trung / Anh), Whisper STT, PySide6 / Qt |
| **Hệ thống & Vận hành** | Linux (Ubuntu Server), Git, Quản trị cụm VPS, CI/CD tự động |

---

## Các Dự Án Tiêu Biểu

### 1. Nền Tảng Học Tiếng Trung Trực Tuyến — hanngu24h.com
- **Mô hình**: Hệ thống Web giáo dục phục vụ học tập và luyện thi chứng chỉ HSK từ cấp độ 1 đến 6.
- **Kiến trúc**:
  - Giao diện người dùng tối ưu hóa tốc độ tải trang, không phụ thuộc framework nặng.
  - Backend PHP xử lý chấm điểm trắc nghiệm tự động trên máy chủ, bảo mật chống gian lận.
  - Tích hợp công cụ luyện phát âm, thẻ từ vựng thông minh (Spaced Repetition) và tra cứu ngữ pháp.
  - Cơ chế Server-Side Rendering (SSR) tự động chuẩn hóa dữ liệu có cấu trúc (Schema.org), tối ưu hóa công cụ tìm kiếm (SEO).
- **Địa chỉ truy cập**: [https://hanngu24h.com](https://hanngu24h.com)

---

### 2. Hệ Thống Bốc Thăm & Vòng Quay May Mắn 3D — lucky-spin-game
- **Mô hình**: Ứng dụng web đồ họa 3D thời gian thực phục vụ sự kiện, hội nghị và tiệc tất niên doanh nghiệp.
- **Đặc điểm kỹ thuật**:
  - Render khối cầu 3D tương tác mượt mà bằng HTML5 Canvas và TagCanvas, cho phép kéo xoay theo quán tính vật lý.
  - Giao diện song ngữ Việt - Trung, hỗ trợ chia nhiều hạng mục giải thưởng và số lượng người trúng tùy biến.
  - Hiệu ứng pháo giấy canvas-confetti, âm thanh đồng bộ và lưu trữ trạng thái người trúng giải vào LocalStorage chống mất dữ liệu khi tải lại trang.
- **Trải nghiệm trực tiếp**: [https://chunglv0498.github.io/lucky-spin-game/](https://chunglv0498.github.io/lucky-spin-game/)
- **Mã nguồn**: [ChungLV0498/lucky-spin-game](https://github.com/ChungLV0498/lucky-spin-game)

---

### 3. Cụm Hệ Thống Tự Động Hóa Sản Xuất & Đăng Tải Video (50+ Kênh)
- **Mô hình**: Dây chuyền khép kín từ khâu thu thập kịch bản, lồng tiếng nhân vật, dựng phim đến xuất bản lên YouTube.
- **Các thành phần cốt lõi**:
  - **autoup-orchestrator**: Máy chủ điều phối trung tâm lập lịch render, phân bổ tài nguyên và kiểm tra nhịp tim (heartbeat) của các máy trạm.
  - **autoup-render-station**: Trạm dựng video hàng loạt tận dụng tăng tốc phần cứng GPU (NVIDIA NVENC/CUDA) và tự động đóng gói file gửi lên VPS.
  - **autoup-vps-uploader**: Daemon chạy nền trên cụm Linux VPS nhận gói media, xác thực OAuth2 an toàn và tự động phát hành video theo lịch.
  - **voxcraft-tts**: Động cơ tổng hợp giọng đọc neural đa giọng đọc (Bắc, Nam, tiếng Trung, tiếng Anh) có khả năng ngắt nghỉ và kiểm soát biểu cảm.

---

### 4. Hệ Thống Kiểm Thử & Nạp Firmware Thiết Bị Điện Tử Tiêu Dùng
- **Mô hình**: Bộ công cụ tự động hóa kiểm soát chất lượng (QA) phục vụ dây chuyền sản xuất thiết bị âm thanh và IoT.
- **Các thành phần cốt lõi**:
  - **battery-charge-tool**: Công cụ kiểm tra độ bền pin, tự động điều khiển chu kỳ sạc/xả qua giao tiếp serial, thu thập đồ thị suy hao dung lượng (mAh) và nhiệt độ.
  - **beats-pro-fit-tester**: Kịch bản kiểm thử chức năng tự động cho tai nghe không dây, đo lường tốc độ kết nối Bluetooth, độ phản hồi phím bấm và kiểm tra thanh ghi vi mạch.
  - **efa-setup**: Bộ cài đặt tự động cấu hình mạng, định tuyến subnet công nghiệp và cài đặt driver phục vụ các trạm kiểm tra trên chuyền sản xuất.

---

### 5. Giải Pháp Quản Lý Bán Hàng & Bảng Giá Vàng BGV
- **Mô hình**: Hệ thống quản lý toàn diện dành cho doanh nghiệp kinh doanh vàng bạc đá quý.
- **Các thành phần cốt lõi**:
  - **bgv-api-server**: Backend RESTful quản lý biến động giá thị trường, tồn kho và danh mục sản phẩm.
  - **bgv-tv-box**: Ứng dụng Android chạy trên TV showroom, hiển thị bảng giá vàng điện tử cập nhật tự động theo thời gian thực.
  - **gold-app-desktop**: Phần mềm máy trạm cho thu ngân tính toán tiền công, độ tuổi vàng và in hóa đơn mua bán.

---

## Thống Kê Hoạt Động

[![Thống kê GitHub](https://github-readme-stats.vercel.app/api?username=ChungLV0498&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)](https://github.com/ChungLV0498)
[![Ngôn ngữ sử dụng](https://github-readme-stats.vercel.app/api/top-langs/?username=ChungLV0498&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)](https://github.com/ChungLV0498)

---

Liên hệ công việc: [chunglv04@gmail.com](mailto:chunglv04@gmail.com) | Hà Nội, Việt Nam
