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
| `/hq` | tranh màu nước hoa mẫu đơn, mở bằng phong bì sáp: album, lịch, sổ lưu bút, hộp quà | RSVP (lời chúc vào tab Lưu bút) |
| `/hq2` | kiểu Hàn Quốc pastel toàn hồng (lá hồng màu nước, lá vàng), cùng các mục như `/hq` | RSVP (lời chúc vào tab Lưu bút) |
| `/tech` | phong cách công nghệ Y2K "Love OS": máy tính retro mở đầu, chữ chrome, mục lục TV retro, cửa sổ kính | RSVP (lời chúc vào tab Lưu bút) |

Công cụ tạo link mời riêng từng khách nằm trong từng bản:
`/tao-link.html`, `/nhatrai/tao-link.html`, `/nhagai/tao-link.html`,
`/ng/tao-link.html`, `/hq/tao-link.html`, `/hq2/tao-link.html`, `/tech/tao-link.html` — bảy file giống hệt nhau, tự nhận ra mình đang ở bản
nào theo tên thư mục.

Thiệp nhận tham số `?g=<tên khách>` và `?x=<mức xưng hô>`.

Nhạc nền: `nhac.mp3` ở gốc trang, dùng chung cho mọi bản (riêng `/tech` có `tech/nhac.mp3` kiểu synthwave) (phát khi khách chạm mở thiệp gấp).
Đổi bài thì thay file này, hoặc sửa `CONFIG.nhac` trong từng trang.
