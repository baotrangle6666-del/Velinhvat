# VẼ BỰA

App tạo linh vật công ty xấu có chủ đích. Chạy hoàn toàn trên trình duyệt, không cần máy chủ hay khóa API.

## Tính năng

- Nhập tên công ty, chọn 6 loài linh vật và màu thương hiệu.
- Điều chỉnh độ bựa, tạo ngẫu nhiên và vẽ lại.
- Tải hình PNG 1000 × 760.
- Lưu tối đa 24 linh vật trên trình duyệt hiện tại.

## Chạy thử

Mở `index.html` bằng trình duyệt, hoặc phục vụ thư mục bằng một máy chủ web tĩnh.

## GitHub Pages

Đưa `index.html` và `.nojekyll` vào thư mục gốc của repository. Trong Settings → Pages, chọn Deploy from a branch, chọn nhánh chứa mã nguồn và thư mục /(root), rồi Save. GitHub sẽ cung cấp đường dẫn sau khi hoàn tất triển khai.

Hướng dẫn chính thức: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Dữ liệu

Bộ sưu tập lưu bằng localStorage riêng cho từng trình duyệt và địa chỉ website. Dữ liệu từ bản dùng trên máy không tự chuyển sang GitHub Pages. Tải PNG để giữ hình lâu dài.

Linh vật được vẽ bằng Canvas với nét ngẫu nhiên, không gọi dịch vụ AI bên ngoài.
