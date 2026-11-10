# Học mà chơi – Chơi mà học lớp 4

## Tệp trong dự án
- `index.html`: trang học sinh, thư viện và giao diện chơi.
- `admin.html`: góc giáo viên để tạo trò chơi.
- `games.json`: dữ liệu trò chơi được trang chủ đọc.

## Đưa lên GitHub Pages
1. Tải cả 3 tệp lên thư mục gốc repository.
2. Trong GitHub: Settings → Pages → Deploy from a branch → chọn `main` và `/ (root)`.
3. Mở URL GitHub Pages của repository.

## Tạo trò chơi mới
1. Mở `admin.html` trên trang GitHub Pages.
2. Nhập tên, môn học, mô tả; thêm câu hỏi theo 3 dạng: trắc nghiệm, đúng/sai, điền đáp án.
3. Nhấn **Thêm trò chơi vào kho**. Trình duyệt tải xuống `games.json`.
4. Vào GitHub repository, thay tệp `games.json` bằng tệp vừa tải và Commit changes.
5. Trang chủ sẽ hiển thị trò chơi mới sau khi GitHub Pages cập nhật.

Lưu ý: GitHub Pages là hosting tĩnh, nên trang quản trị không thể tự ghi dữ liệu lên repository nếu không dùng GitHub API/token hoặc backend. Cách tải `games.json` rồi commit giúp không cần lưu token cá nhân trong website.
