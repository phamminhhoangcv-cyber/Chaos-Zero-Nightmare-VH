# Chaos Zero Nightmare Việt Hóa · bản chữ + cốt truyện (R:133)

Bản việt hóa của người hâm mộ cho Chaos Zero Nightmare bản PC (STOVE, server ASIA), build tài nguyên **R:133**. Phiên bản hiện tại: **v1**.

## Gói gồm gì
| Nội dung | Có |
|---|---|
| Chữ giao diện, thẻ bài, mô tả, tooltip, lựa chọn Chaos, thành tựu | Có |
| Cốt truyện và thoại (69.287 dòng) | Có |
| Font Việt hóa | **Không** |

Các mục trong ghi chú phát hành chỉ nói về chữ hiển thị được thay đổi, không có nghĩa toàn bộ chế độ đã Việt hóa.

## Cập nhật mới nhất
So với bản chữ đầu ngày 27/10: **sửa bản dịch 7.960 dòng**, thêm tiếng Việt 0 dòng, ngừng áp dụng 0 dòng. Đồng bộ thuật ngữ chính:
- Tên lớp, tên ải, tên mùa và loại Epiphany giữ tiếng Anh (Striker, Vanguard, Holy Crusaders, Divine Epiphany…); nhãn hệ thống dùng từ Hán-Việt gọn.
- Đơn vị và giới hạn viết thống nhất: "3 lần/lượt", "(Max 3 tầng)", "Bật/Tắt".
- Đồng hành, Chiến binh, Phân tách, Credits dùng một cách gọi xuyên suốt.

Chi tiết theo nhóm: xem mục **Releases** (ghi chú phát hành).

## Cài đặt
Yêu cầu: Windows, **Python 3.14 trở lên**, game đang là **bản gốc build R:133** (dòng `cznlive:837 R:133` ở màn hình "TOUCH TO START").
1. Tắt hẳn game và STOVE. Tải `CZN_VietHoa_R133_Chu_CotTruyen.zip` ở mục **Releases**, giải nén.
2. Bấm đôi `cai_dat.bat` (game không ở `D:\Games\ChaosZeroNightmare` thì chạy `cai_dat.bat "đường dẫn thư mục game"`).
3. Chờ báo XONG, mở game, chọn ngôn ngữ mục tên **"Tiếng Việt"**.

Gỡ: tắt game, bấm đôi `go_bo.bat`. Script tự sao lưu 3 file gốc vào `backup_goc`; **đừng xoá** thư mục này. Chi tiết: [HUONG_DAN.txt](HUONG_DAN.txt).

## Kiểm tra gói
- Gói cốt truyện khớp bảng dịch (69.287 dòng thay, 26 DB), hash và etag khớp manifest chữ; file zip kiểm tra sạch (SHA256 trong `SHA256SUMS.txt`).
- **Gói chưa được thử cài trên máy sạch**; gameplay chờ người chơi kiểm chứng. Sao lưu trước khi cài.

## Lưu ý
- Gói chỉ dùng cho **R:133**. STOVE tự cập nhật game lúc nào cũng được; khi game lên build khác thì gói không còn dùng được.
- Đừng bấm **"Repair Resources"** trong game sau khi cài: nút này tải lại file gốc và xoá bản việt hóa.
- Đây là sản phẩm của người hâm mộ, **không liên kết** với Smilegate / STOVE. Gói thay các file dữ liệu của game, có thể vi phạm điều khoản dịch vụ: tự chịu rủi ro.
