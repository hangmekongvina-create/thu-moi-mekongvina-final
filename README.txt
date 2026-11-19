MÊKÔNG VINA – BLUE FLIPBOOK
============================

BỘ MÃ DÀNH CHO REPOSITORY GITHUB MỚI

1. Tạo repository mới trên GitHub
- Đăng nhập GitHub > New repository.
- Đặt tên, ví dụ: thu-moi-mekongvina
- Chọn Public.
- Có thể chọn Add a README file.
- Create repository.

2. Upload mã nguồn
- Giải nén ZIP này.
- Upload TOÀN BỘ nội dung bên trong thư mục gói vào thư mục gốc repository mới.
- Giữ nguyên cấu trúc assets/css, assets/js, data/invitations, invitations.
- Commit changes.

3. Bật GitHub Pages
- Repository > Settings > Pages.
- Build and deployment: Deploy from a branch.
- Branch: main; Folder: /(root).
- Save.
- Đợi GitHub cấp URL dạng https://TEN-USER.github.io/TEN-REPO/

4. Mở Admin
- Truy cập https://TEN-USER.github.io/TEN-REPO/admin.html
- Nhập GitHub username, repository mới, branch main.
- Tạo Fine-grained Personal Access Token tại GitHub > Settings > Developer settings > Personal access tokens > Fine-grained tokens.
- Repository access: Only select repositories > chọn đúng repository mới.
- Repository permissions > Contents: Read and write.
- Generate token, dán vào Admin, nhấn Kiểm tra kết nối.
- Token chỉ giữ trong phiên trình duyệt, không được lưu vào repository.

5. Tạo thư mời
- Nhập tên sự kiện và mã thư mời.
- Chọn PDF hoặc nhiều ảnh JPG/PNG/WebP.
- Có thể thêm ảnh bìa và MP3.
- Nhấn Xuất bản thư mời.
- Chờ Pages cập nhật, gửi link được tạo ra cho khách.

LƯU Ý QUAN TRỌNG
- Repository phải Public nếu dùng GitHub Pages miễn phí.
- Nội dung thư mời và file media trong repo Public có thể được xem bởi bất kỳ ai có link hoặc biết đường dẫn.
- Không bao giờ đưa token vào file JavaScript, HTML hoặc commit lên GitHub.
- Dùng token giới hạn đúng một repository; nên đặt thời hạn và thu hồi khi không còn cần.
- File upload giới hạn 18 MB mỗi file trong giao diện này. PDF nhiều trang/nặng nên nén trước.
- GitHub Pages có thể mất vài phút sau commit để cập nhật.
- Thư viện PageFlip và PDF.js được tải từ CDN, cần kết nối Internet.
- Tính năng lật sách hoạt động trên trình duyệt hiện đại; bật âm thanh cần thao tác chạm/click của khách do chính sách trình duyệt.
