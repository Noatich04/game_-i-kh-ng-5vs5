# Strike Five — FPS 5v5

Prototype FPS đối kháng 5v5 lấy cảm hứng từ mô hình đấu đội, không dùng tài sản của Liên Minh Huyền Thoại.

## Luật chơi
- 5v5: 1 người chơi + 4 đồng đội AI đấu 5 AI đối phương.
- Đội đầu tiên đạt 30 mạng thắng.
- Hồi sinh sau khi chết: 4 giây.
- Thời gian trận: 2 phút.
- Bản đồ arena đơn giản, tập trung vào đấu súng.

## Điều khiển
- WASD: di chuyển
- Chuột: ngắm/bắn
- R: nạp đạn
- Shift: chạy nhanh
- ESC: thả chuột

## Chạy
Mở `index.html` bằng trình duyệt hiện đại. Game dùng Three.js từ CDN nên không cần build step cho prototype.

## GitHub Pages
Vào Settings → Pages → Deploy from branch → chọn `main` và thư mục `/ (root)`. Sau khi GitHub Pages build xong, mở URL Pages của repository.

## Ghi chú
Đây là prototype chạy trong một trình duyệt. 5v5 hiện được mô phỏng bằng bot; chưa phải multiplayer online giữa 10 máy. Bản tiếp theo có thể thêm server WebSocket/Socket.IO, lobby, đồng bộ người chơi và matchmaking.
