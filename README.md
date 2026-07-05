# 📊 Uptime Kuma — Giám sát Uptime & Trạng thái Dịch vụ

> **Fork bởi ThuanEcoSynTechGlobal** | Dự án gốc: [louislam/uptime-kuma](https://github.com/louislam/uptime-kuma)

## Giới thiệu

**Uptime Kuma** là công cụ giám sát uptime tự lưu trữ (self-hosted) với giao diện web đẹp mắt, cho phép theo dõi trạng thái hoạt động của các dịch vụ, website, API và nhận cảnh báo khi có sự cố.

## Tính năng chính

- ⏱ **Giám sát đa giao thức**: HTTP(s), TCP, Ping, DNS, Push, Docker, v.v.
- 🔔 **Cảnh báo đa kênh**: Telegram, Email, Webhook, Slack, Discord, Zalo, SMS...
- 📈 **Biểu đồ uptime**: xem lịch sử hoạt động 24/7, 30 ngày, 1 năm
- 🌐 **Trang trạng thái công khai**: tạo status page cho khách hàng
- 🔄 **SSL/TLS Certificate**: kiểm tra hạn chứng chỉ SSL
- 🐳 **Triển khai Docker**: siêu nhẹ, chạy trong 1 phút
- 🔒 **Xác thực**: hỗ trợ đăng nhập, 2FA
- 🌙 **Dark mode**: giao diện tối sáng

## Triển khai nhanh

```bash
docker run -d -p 3001:3001 \
  -v uptime-kuma:/app/data \
  --name uptime-kuma \
  louislam/uptime-kuma:latest
```

## Mục đích fork

Phục vụ giám sát hệ thống IoT, server nội bộ trong các dự án nông nghiệp công nghệ cao của ThuanEcoSynTechGlobal.

## Liên hệ

🌐 https://github.com/ThuanEcoSynTechGlobal