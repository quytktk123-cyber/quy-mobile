# QUÝ MOBILE — website demo React, Tailwind CSS

## Chạy trên máy tính

Cần Node.js 18 trở lên.

```bash
npm install
npm run dev
```

Mở địa chỉ được Vite hiển thị, thường là http://localhost:5173.

## Mở bằng điện thoại trên cùng Wi-Fi

1. Kết nối điện thoại và máy tính cùng mạng Wi-Fi.
2. Chạy `npm run dev` trên máy tính và giữ cửa sổ terminal mở.
3. Xem dòng `Network` trong terminal, ví dụ `http://192.168.1.10:5173/`.
4. Mở địa chỉ Network đó trên trình duyệt điện thoại. Nếu không truy cập được, kiểm tra tường lửa và quyền truy cập mạng nội bộ.

## Đưa lên Internet

Chạy `npm run build`, sau đó triển khai thư mục `dist/` lên dịch vụ hosting tĩnh hỗ trợ SPA. Khi có địa chỉ HTTPS công khai, có thể mở website trên điện thoại qua mạng di động mà không cần bật máy tính.

## Chức năng demo

Trang chủ, tìm kiếm, lọc hãng, sắp xếp, chi tiết sản phẩm, giỏ hàng, đặt hàng mẫu, đăng ký/đăng nhập mẫu, lịch sử đơn, giao diện quản trị sản phẩm và trạng thái đơn.

**Quan trọng:** Đây là frontend demo, chưa có Node.js API, PostgreSQL, xác thực an toàn, quản lý tồn kho đa người dùng, thanh toán thực hoặc xử lý đơn hàng thực. Dữ liệu lưu ở localStorage của từng trình duyệt; không dùng mật khẩu thật. Tài khoản đăng ký mặc định là khách hàng; chưa cấp quyền quản trị qua frontend vì điều đó không an toàn. Không đưa bản demo này vào vận hành bán hàng thật trước khi hoàn thiện backend và bảo mật.
