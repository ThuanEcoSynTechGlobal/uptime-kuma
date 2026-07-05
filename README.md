# Uptime Kuma — Giám sát Uptime & Trạng thái Dịch vụ

> Fork cá nhân bởi [ThuanEcoSynTechGlobal](https://github.com/ThuanEcoSynTechGlobal)  
> Dự án gốc: [louislam/uptime-kuma](https://github.com/louislam/uptime-kuma)  
> README gốc: [English](https://github.com/louislam/uptime-kuma/blob/master/README.md)

## Giới thiệu

**Uptime Kuma** là công cụ giám sát uptime tự lưu trữ (self-hosted) với giao diện web đẹp mắt, cho phép theo dõi trạng thái hoạt động của các dịch vụ, website, API và nhận cảnh báo khi có sự cố.

## Tính năng chính

- ⏱ Giám sát đa giao thức: HTTP(s), TCP, Ping, DNS, Push, Docker...
- 🔔 Cảnh báo đa kênh: Telegram, Email, Webhook, Slack, Discord, Zalo, SMS...
- 📈 Biểu đồ uptime: xem lịch sử hoạt động 24/7, 30 ngày, 1 năm
- 🌐 Trang trạng thái công khai: tạo status page cho khách hàng
- 🔄 Kiểm tra SSL/TLS Certificate
- 🐳 Triển khai Docker: siêu nhẹ, chạy trong 1 phút
- 🔒 Xác thực: hỗ trợ đăng nhập, 2FA

## Triển khai nhanh

```bash
docker run -d -p 3001:3001 \
  -v uptime-kuma:/app/data \
  --name uptime-kuma \
  louislam/uptime-kuma:latest
```

## README tiếng Việt

Đây là bản README tiếng Việt do cá nhân tôi thực hiện để dễ tra cứu và sử dụng. Tài liệu gốc bằng tiếng Anh đầy đủ hơn vui lòng xem tại repo chính.

🌐 https://github.com/ThuanEcoSynTechGlobal