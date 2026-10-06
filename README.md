# KitChenChaos

Game bếp kiểu kitchen simulation được xây dựng trên Unity. Người chơi điều khiển nhân vật trong không gian bếp, thu thập nguyên liệu, chế biến món ăn, đặt lên đĩa và giao hàng theo đơn yêu cầu.

## Mục tiêu trò chơi

- Di chuyển nhân vật trong căn bếp
- Tương tác với các counter khác nhau
- Lấy nguyên liệu và đặt chúng vào bàn làm món
- Cắt và nấu nguyên liệu theo công thức
- Giao món đúng yêu cầu để nhận điểm
- Quản lý thời gian và trạng thái game

## Tính năng chính

- Hệ thống di chuyển và tương tác người chơi
- Nhiều loại counter: lấy nguyên liệu, cắt, nấu, giao hàng, thùng rác
- Hệ thống đơn hàng bằng ScriptableObject
- UI hiển thị tiến độ nấu/cắt, thời gian, countdown, menu, game over
- Hỗ trợ pause và rebinding phím điều khiển
- Âm thanh và hiệu ứng cảnh trong game

## Công nghệ sử dụng

- Unity 6000.5.7f1
- C#
- Unity Input System
- URP (Universal Render Pipeline)
- UI Toolkit / UGUI
- ScriptableObject cho dữ liệu nguyên liệu và món ăn

## Cấu trúc thư mục chính

- `Assets/Scenes` - các scene của game
- `Assets/Scripts` - mã nguồn gameplay
- `Assets/Scripts/Counters` - logic các counter trong bếp
- `Assets/Scripts/UI` - giao diện người chơi
- `Assets/Scripts/ScriptableObjects` - dữ liệu món ăn, nguyên liệu, công thức
- `ProjectSettings` - cài đặt project Unity
- `Packages` - package Unity

## Cách chạy project

1. Mở Unity Hub.
2. Chọn Open Project.
3. Chọn thư mục chứa dự án `KitChenChaos`.
4. Đợi Unity import project và package.
5. Mở scene chính và nhấn Play để chạy game.

## Điều khiển cơ bản

- WASD / mũi tên: di chuyển
- E hoặc Enter: tương tác với đối tượng gần nhất
- F hoặc phím phụ: tương tác phụ (ví dụ cắt, nấu, thao tác thứ hai)
- Esc hoặc phím Pause: tạm dừng game

## Lưu ý

- Một số script có thể cần chỉnh sửa nếu bạn mở project trên phiên bản Unity khác.
- Nếu gặp lỗi khi chạy, hãy kiểm tra lại package và version Unity tương thích.
- Nên mở dự án bằng Unity version tương ứng với `ProjectVersion.txt` để tránh lỗi import.

## Tác giả

Dự án là bản prototype game bếp được xây dựng theo mô hình học tập / demo gameplay trong Unity.

## License

Mọi quyền thuộc về người phát triển dự án nếu chưa cập nhật license cụ thể. Nếu cần, bạn có thể thêm file LICENSE riêng cho dự án.
