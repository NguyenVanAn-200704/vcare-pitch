# Vcare — Pitch deck

Bộ slide pitch Vcare (nhóm P-100, Dự án AI thực chiến · VinUni Build 2026), dạng HTML tĩnh, một file, chạy trực tiếp trên trình duyệt.

- `index.html`: bản trình chiếu chính (14 slide, có hiệu ứng, speaker notes).
- `assets/`: ảnh giao diện, logo, mã QR, khung hình trợ lý Vcare.
- `Vcare-pitch.pdf`: bản PDF tĩnh, mỗi slide một trang.
- `.nojekyll`: để GitHub Pages phục vụ nguyên trạng, không qua Jekyll.

## Trình chiếu

| Phím | Tác dụng |
| --- | --- |
| → / Space / click | bước hiệu ứng tiếp theo |
| ← | lùi lại |
| F | toàn màn hình |
| P | mở cửa sổ presenter (notes, slide kế tiếp, đồng hồ) |
| N | hiện notes dưới slide |
| Home / End | slide đầu / cuối |

Thêm `#9` vào cuối URL để mở thẳng slide 9. Font tải từ Google Fonts nên máy cần có mạng.

## Deploy lên GitHub Pages

1. Tạo repo mới trên GitHub, ví dụ `vcare-pitch`, rồi đẩy mã lên:

   ```bash
   git remote add origin https://github.com/<tài-khoản>/vcare-pitch.git
   git push -u origin main
   ```

2. Vào **Settings → Pages**, mục **Build and deployment** chọn **Deploy from a branch**, branch `main`, thư mục `/ (root)`, rồi **Save**.
3. Sau khoảng 1–2 phút, deck chạy tại `https://<tài-khoản>.github.io/vcare-pitch/`.

## Ghi chú nội dung

Ảnh giao diện chụp từ hệ thống local ngày 18/10/2026, dữ liệu demo. Số liệu thị trường có nguồn ở chân từng slide. Mã nguồn sản phẩm: https://github.com/AI20K-Build-Phase-Cohort-4/P-100
