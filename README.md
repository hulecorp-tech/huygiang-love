# huygiang.love

Thiệp cưới Ngọc Huy & Hương Giang — 29.11.2026.

Trang tĩnh, chạy trên GitHub Pages. Mã nguồn đầy đủ (gồm các bản màu khác
và công cụ sinh mã QR) nằm ở repo riêng `hulecorp-tech/wedding-invitation`.

| Đường dẫn | Nội dung | Xác nhận ghi vào tab |
|---|---|---|
| `/` | thiệp chính | RSVP |
| `/nhatrai` | bản cho khách nhà trai (có khung ảnh) | Nhà trai |
| `/nhagai` | bản cho khách nhà gái (chỉ Lễ Vu Quy, có khung ảnh) | Nhà gái |
| `/ng` | bản chữ to cho người lớn tuổi nhà gái (chỉ Lễ Vu Quy) | Nhà gái |
| `/ae` | thiệp riêng nhóm bạn thân | RSVP |
| `/hong` | bản màu hồng, phía nhà gái (chỉ Lễ Vu Quy) | RSVP |

Công cụ tạo link mời riêng từng khách nằm trong từng bản:
`/tao-link.html`, `/nhatrai/tao-link.html`, `/nhagai/tao-link.html`,
`/ng/tao-link.html` — bốn file giống hệt nhau, tự nhận ra mình đang ở bản
nào theo tên thư mục.

Thiệp nhận tham số `?g=<tên khách>` và `?x=<mức xưng hô>`.

Nhạc nền: `nhac.mp3` ở gốc trang, dùng chung cho mọi bản (phát khi khách chạm mở thiệp gấp).
Đổi bài thì thay file này, hoặc sửa `CONFIG.nhac` trong từng trang.
