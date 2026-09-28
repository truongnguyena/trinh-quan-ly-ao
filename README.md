# Logistics OS — Demo UI/UX

Giao diện demo hệ thống **Quản lý Logistics / TMS / Freight Forwarding** — single-file HTML, không cần cài đặt, mở trực tiếp bằng trình duyệt.

## 📦 Hai bản trong repo

| File | Bản | Mô tả |
|---|---|---|
| [`index.html`](./index.html) | **v2 — Command Center (mới)** | Dark futuristic glassmorphism: Hero Command Center, KPI count-up + sparkline, Mission Detail, map placeholder, Command Palette (Ctrl+K), dark/light, dock cong + FAB hình cầu trên mobile |
| [`classic-v1.html`](./classic-v1.html) | **v1 — Classic (cũ)** | Giao diện sáng truyền thống — giữ lại để so sánh |

## 🚀 Chạy thử

Mở trực tiếp `index.html` bằng trình duyệt (double-click), hoặc:

```bash
python -m http.server 8931
# rồi mở http://localhost:8931/index.html
```

Đăng nhập demo: nút **Đăng nhập** (đã điền sẵn) → Dashboard.

## ✨ Tính năng demo

- **Dashboard Command Center** — KPI count-up + sparkline, Revenue Chart, Shipment Activity, Recent Orders, Critical Alerts
- **Đơn hàng** — lọc / tìm / sắp xếp, tạo đơn thật (tự tính cước), xuất CSV
- **Chi tiết đơn** — Mission Detail: hero trạng thái, map placeholder, tracking timeline, Customer/Driver Card, chứng từ, chi phí, đổi trạng thái theo workflow
- **Nhãn vận đơn** — QR + barcode, in nhãn
- **App tài xế** — luồng 6 bước: nhận chuyến → quét QR → chụp ảnh → ký nhận → hoàn tất
- **Tracking công khai** — tra cứu mã, timeline, POD
- **Báo giá** — bảng + modal PDF preview
- **Command Palette** — `Ctrl+K` tìm toàn cục
- **3 giao diện theo thiết bị** — Desktop 1440 / iPad 768 / Mobile 390 (dock cong + FAB hình cầu)
- **Dark / Light** — nút mặt trăng trên topbar

> ⚠️ Bản demo UI/UX: dữ liệu mẫu, chạy 100% client-side, chưa nối backend.

## 📄 License

Demo nội bộ — dùng để trình bày với khách hàng.
