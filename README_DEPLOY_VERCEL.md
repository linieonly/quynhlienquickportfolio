# Hoàng Quỳnh Liên — Vercel Portfolio

## Cấu trúc
- `index.html` — trang chính
- `assets/` — toàn bộ ảnh + CV, dùng đường dẫn tương đối `assets/...`
- `favicon.svg`
- `vercel.json`

## Deploy lên Vercel
Import **nguyên thư mục này** vào Vercel (hoặc push nguyên thư mục lên GitHub).
Không chỉ upload riêng `index.html`, vì ảnh và CV nằm trong `assets/`.

Project Settings:
- Framework Preset: **Other**
- Build Command: để trống
- Output Directory: để trống / `.`
- Install Command: để trống

Với Vercel, tất cả asset đều dùng đường dẫn tương đối nên không phụ thuộc `localhost`, `file://`, hoặc đường dẫn máy cá nhân.
