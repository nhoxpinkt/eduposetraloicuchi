# EduPose – Vui Học Cùng Cử Chỉ

**Tác giả:** Thầy Trần Hồng Quân *(Biên soạn & Thiết kế: Thầy Trần Hồng Quân)*  
Ứng dụng trò chơi tương tác lớp học nhận diện cử chỉ AI 100% Client-side (HTML/CSS/JS tĩnh), tối ưu cho GitHub Pages và nhúng `<iframe>`.

## Triển khai lên GitHub Pages
1. Đẩy toàn bộ thư mục này lên nhánh `main` của repository GitHub.
2. Vào **Settings → Pages → Build and deployment → Source** và chọn **GitHub Actions**.
3. Workflow `.github/workflows/deploy.yml` sẽ tự động xuất bản trang web tĩnh.

## Nhúng vào website khác bằng Iframe
```html
<iframe
  src="https://<ten-tai-khoan>.github.io/<ten-repo>/"
  width="100%"
  height="760"
  style="border: 0; border-radius: 16px;"
  allow="camera; fullscreen"
  allowfullscreen
></iframe>
```
