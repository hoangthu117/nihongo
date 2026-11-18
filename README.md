# Nihongo Quest Sakura — bản nâng cấp kawaii

Giữ nguyên `words.json` (187 mục) và khóa localStorage `nihongo-quest-v1`, không xóa tiến độ cũ khi cập nhật trên cùng origin. Bổ sung `grammar.json` gồm 18 điểm ngữ pháp từ bài 26–31, công thức, giải thích, ví dụ, lỗi thường gặp và thẻ tự kiểm tra. Giao diện pastel và Mèo Sakura.

## Chạy thử

Giải nén và chạy `python3 -m http.server 8000` trong thư mục. Mở `http://localhost:8000` trên máy tính. Để dùng PWA trên iPad, triển khai cả thư mục qua HTTPS rồi mở bằng Safari. Nếu thay đổi tên miền, localStorage của tên miền cũ không tự chuyển sang tên miền mới. Hãy xuất dữ liệu tiến độ trước khi đổi tên miền.

## Giới hạn

Chưa kiểm thử trực tiếp Safari iPad. Ngữ pháp hiện có 18 điểm trọng tâm, không khẳng định bao phủ mọi mục của mọi ấn bản giáo trình. Bài tự kiểm tra hiện là tự nhớ và lật đáp án, chưa chấm tự động. Giọng nói tùy trình duyệt.
