# 🏛️ FlipArch (FlipOS V27) | Geometry Architect on Stellar

**FlipArch** là một ứng dụng phi tập trung (dApp) kết hợp giữa trình đọc PDF tương tác và công nghệ Blockchain Stellar. Dự án cho phép các kiến trúc sư và sinh viên thiết kế không chỉ vẽ đồ họa hình học trên tài liệu mà còn có thể **xác thực quyền sở hữu trí tuệ** ngay trên chuỗi khối.

---

## 📝 Thông tin dự án (Stellar Hackathon)

* **TÊN DỰ ÁN:** FlipArch
* **VẤN ĐỀ:** Các kiến trúc sư và sinh viên thiết kế hiện nay gặp khó khăn trong việc chứng minh quyền sở hữu đối với các bản vẽ nháp trên tài liệu PDF, dẫn đến rủi ro bị sao chép ý tưởng khi chia sẻ bản thảo.
* **GIẢI PHÁP:** dApp tích hợp công nghệ Stellar để "đóng dấu" (timestamp) bản vẽ. Bằng cách lưu trữ mã băm (hash) của tài liệu kèm chữ ký số của tác giả lên Ledger của Stellar, người dùng có thể xác lập quyền tác giả vĩnh viễn và không thể chối bỏ.

---

## 🛠️ Tính năng Stellar sử dụng

* **Soroban Smart Contracts:** Quản lý logic xác thực bản vẽ, lưu trữ mã Hash của tài liệu và thông tin tác giả.
* **Custom Tokens:** Phát hành chứng chỉ số (Certificate Token) đại diện cho mỗi bản thiết kế đã được xác thực.
* **Trustlines:** Đảm bảo tính an toàn khi chuyển giao quyền sở hữu bản vẽ giữa các bên (ví dụ: sinh viên và giảng viên).

---

## 👥 Người dùng mục tiêu
* **Sinh viên kiến trúc:** Bảo vệ đồ án môn học trước khi nộp bài.
* **Freelancers:** Gửi bản thảo cho khách hàng mà vẫn giữ được bằng chứng sở hữu gốc.
* **Kỹ sư xây dựng:** Ghi chú và xác thực các thay đổi bản vẽ kỹ thuật trực tiếp tại công trường.

---

## 💎 Tính năng cốt lõi (MVP)
**Giao dịch Duy nhất (The Single Transaction):**
Thực thi hàm `notarize_design(file_hash)` trên Soroban Smart Contract. Giao dịch này sẽ ghi lại vĩnh viễn dấu thời gian (Timestamp) và địa chỉ ví của người tạo bản vẽ lên mạng lưới Stellar, tạo thành một bằng chứng pháp lý kỹ thuật số.

---

## ⚖️ Tại sao chọn Stellar?

| Tiêu chí | Tài chính truyền thống | Ethereum / Khác | Stellar Network |
| :--- | :--- | :--- | :--- |
| **Chi phí** | Rất cao (Phí công chứng) | 5$ - 20$ (Gas fee) | **~0.00001$** |
| **Tốc độ** | Vài ngày làm việc | 2 - 15 phút | **~5 giây** |
| **Trải nghiệm** | Thủ tục giấy tờ phức tạp | Phức tạp cho người mới | **Mượt mà & Thân thiện** |

---

## 🖥️ Giao diện hệ điều hành (FlipOS V27)

Dự án mô phỏng một hệ điều hành chuyên dụng với các công cụ:
- **3D Page Flip:** Trải nghiệm đọc PDF như lật sách thật.
- **Geometry Tools:** Vẽ khối 2D/3D (Cube, Cylinder, Pyramid) trực tiếp trên trang.
- **System Apps:** Tích hợp máy tính (Calculator), kính lúp (Spyglass) và quản lý bộ nhớ IndexedDB.

---

## 🚀 Hướng dẫn khởi chạy

1. **Clone Repo:** `git clone https://github.com/your-username/fliparch-stellar.git`
2. **Mở index.html:** Chạy trực tiếp trên trình duyệt.
3. **Connect Wallet:** Sử dụng tiện ích mở rộng **Freighter** để ký giao dịch xác thực bản vẽ.

---
*Developed for Stellar Workshop 2026 - Geometry Meets Blockchain.*
