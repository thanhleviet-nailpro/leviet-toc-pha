# Gia phả họ Lê Viết — Phú Ngạn, Huế

Ứng dụng gia phả chạy bằng React + Vite.

## Chạy trên máy

1. Cài Node.js bản LTS.
2. Mở terminal tại thư mục dự án.
3. Chạy `npm install`.
4. Chạy `npm run dev` và mở địa chỉ Vite hiện trong terminal.

## Dữ liệu và sao lưu

- Dữ liệu thành viên, tin tức, lịch phụng tu và lịch trùng tu được lưu tự động trong trình duyệt (localStorage) trên thiết bị đang sử dụng.
- Dùng **Sao lưu dữ liệu** để tải file JSON sao lưu.
- Dùng **Nhập bản sao lưu** để phục hồi từ JSON. Việc nhập sẽ thay thế dữ liệu hiện có sau khi xác nhận.
- Sao lưu thường xuyên và giữ file JSON ở nơi an toàn. Dữ liệu localStorage không tự đồng bộ giữa các máy hoặc trình duyệt.


## Kiểm tra dự án

- `npm run build`: dựng bản production.
- `npm run lint`: kiểm tra lint.
- `npm run preview`: xem bản production local.
