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

## Chọn cách cài
| | Cách 1 — Copy tay (chỉ chữ) | Cách 2 — Chữ + cốt truyện |
|---|---|---|
| Cần cài thêm | **Không cần gì** | **Không cần gì** (dùng PowerShell có sẵn của Windows) |
| Cách làm | Sao chép 3 file bằng chuột | Bấm đôi `cai_dat.bat` |
| Có chữ Việt | Có | Có |
| Có cốt truyện Việt | Không | Có |
| File tải | `CZN_VietHoa_R133_ChiChu_CopyTay.zip` | `CZN_VietHoa_R133_Chu_CotTruyen.zip` |
| Hướng dẫn | [HUONG_DAN_COPY_TAY.txt](HUONG_DAN_COPY_TAY.txt) | [HUONG_DAN.txt](HUONG_DAN.txt) |

Vì sao cốt truyện không copy tay được: cốt truyện nằm rải trong 19 file dữ liệu rất lớn của game (hơn 4 GB); gói chỉ chứa các mảnh vá nhỏ, nên cần bộ cài (`cai_dat.bat`) để vá đúng vị trí. Bộ cài chỉ là script PowerShell có sẵn trong Windows, mở ra đọc được.

## Cách 2 — Chữ + cốt truyện (làm bằng chuột, không cần gõ lệnh, không cài thêm gì)
**Hướng dẫn đầy đủ từng bước: [HUONG_DAN.txt](HUONG_DAN.txt).** Tóm tắt:

1. **Kiểm tra game:** mở game tới màn hình "TOUCH TO START", nhìn góc dưới bên trái phải thấy `R:133`. Số khác thì chưa cài được.
2. **Tắt hẳn game và STOVE** (bộ cài sẽ từ chối chạy nếu game còn mở).
3. Tải `CZN_VietHoa_R133_Chu_CotTruyen.zip` ở mục **Releases**, bấm chuột phải → Extract All để giải nén.
4. **Cài:** bấm đôi `cai_dat.bat`. Nếu game không nằm ở `D:\Games\ChaosZeroNightmare`, **kéo thư mục game** (thư mục chứa `bin`) rồi **thả lên `cai_dat.bat`**.
5. Chờ báo **XONG**, mở game, vào Cài đặt → Ngôn ngữ, chọn mục tên **"Tiếng Việt"**.

**Gỡ:** tắt game, bấm đôi `go_bo.bat`. Bộ cài tự sao lưu 3 file gốc vào `backup_goc`, **đừng xoá** thư mục này.
Gặp lỗi: xem mục "Khi gặp lỗi" trong [HUONG_DAN.txt](HUONG_DAN.txt).

## Kiểm tra gói
- Gói cốt truyện khớp bảng dịch (69.287 dòng thay, 26 DB), hash và etag khớp manifest chữ; file zip kiểm tra sạch (SHA256 trong `SHA256SUMS.txt`).
- Bộ cài (PowerShell) đã được thử trên **bản sao** của game gốc build R:133: cài đúng (18/19 file dữ liệu giống hệt game đã vá, riêng 1 file khác ở đúng vùng font vì gói không kèm font), cài lại báo "đã cài sẵn", gỡ trả về từng byte như ban đầu, và **dừng trước khi ghi** nếu dữ liệu game không đúng bản gốc.
- **Chưa được thử trên máy người khác**; gameplay chờ người chơi kiểm chứng. Sao lưu trước khi cài.

## Lưu ý
- Gói chỉ dùng cho **R:133**. STOVE tự cập nhật game lúc nào cũng được; khi game lên build khác thì gói không còn dùng được.
- Đừng bấm **"Repair Resources"** trong game sau khi cài: nút này tải lại file gốc và xoá bản việt hóa.
- Đây là sản phẩm của người hâm mộ, **không liên kết** với Smilegate / STOVE. Gói thay các file dữ liệu của game, có thể vi phạm điều khoản dịch vụ: tự chịu rủi ro.
