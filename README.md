# sacdepvn — Demo site

Repo demo chứa bài viết về dán răng sứ Veneer (Nha khoa Asia) và template trang tĩnh đơn giản.

## Nội dung đã thêm
- `index.html` — trang HTML tĩnh chứa bài viết.
- `posts/dan-rang-su-veneer.md` — bài viết ở dạng Markdown (SEO-optimized).
- `assets/styles.css` — CSS cho giao diện đơn giản, hiện đại.

## Hướng dẫn deploy lên GitHub Pages
1. Vào repo trên GitHub: `https://github.com/SacDepVN/sacdepvn`.
2. Vào Settings -> Pages, chọn `main` branch và thư mục `/` (root) để deploy.
3. Nếu muốn ảnh hiển thị, upload thư mục `images/` chứa `image.png`, `image-1.png`, `image-2.png` vào repo root (hoặc sửa đường dẫn trong `index.html`).

## Ghi chú
- Hiện tại tôi đã để placeholder cho ảnh ở `/images/...`. Bạn có thể upload ảnh thật vào thư mục `images` trên repo hoặc sửa `index.html` để dùng ảnh từ CDN.
- Nếu muốn, tôi có thể tiếp tục: thêm action để tự động deploy, chuyển Markdown sang HTML động (Eleventy/Hugo) hoặc thêm schema.org chi tiết.

---

Các bước tiếp theo bạn muốn tôi làm:
- Upload ảnh từ máy bạn (bạn có thể kéo thả vào chat) và tôi sẽ thêm vào repo.
- Hoặc tôi sẽ tạo GitHub Action để build & deploy tự động.
