# Bài 7: Soạn Email Khủng hoảng Giao chậm Black Friday theo Khung CREATE

> Giá trị trong `[ ]` là thông tin cần thay bằng dữ liệu thật trước khi gửi.

## Phần 1: 6 khối CREATE

| Khối | Nội dung |
|---|---|
| **C – Character** | Trưởng phòng CSKH của TechShop, đại diện Ban Giám đốc gửi email xin lỗi. |
| **R – Request** | Viết email gửi đích danh từng khách có đơn linh kiện PC (Card màn hình, Nguồn, RAM) bị giao chậm 4–6 ngày: (1) nhận lỗi chân thành, (2) giải trình minh bạch nguyên nhân, (3) cam kết lộ trình giao mới, (4) tặng Voucher 15% cho đơn sau. |
| **E – Examples** | "Chúng tôi hiểu rằng việc chờ đợi linh kiện để hoàn thiện bộ PC là điều rất khó chịu, và TechShop hoàn toàn chịu trách nhiệm về sự chậm trễ này." |
| **A – Adjustment** | Giọng cầu thị, đồng cảm, chuyên nghiệp. **Cấm:** đổ lỗi cho đơn vị vận chuyển hoặc khách; hứa suông (chỉ cam kết mốc ngày và quyền lợi có trong Extras); dùng câu sáo rỗng; mở đầu hoặc kết thúc bằng lời ngoài email. |
| **T – Type of Output** | Email gồm: Tiêu đề → Lời chào trang trọng → 3 đoạn thân bài (xin lỗi và nhận trách nhiệm / giải trình nguyên nhân / giải pháp: lộ trình mới + voucher) → Lời cam kết → Thông tin liên hệ khẩn cấp → Chữ ký. |
| **E – Extras** | Voucher giảm 15%, hotline VIP, mã đơn, mốc giao mới (xem Master Prompt). |

## Phần 2: Master Prompt hoàn chỉnh

```text
### CHARACTER ###
Bạn là Trưởng phòng Chăm sóc khách hàng của công ty thương mại điện tử TechShop,
thay mặt Ban Giám đốc gửi thư xin lỗi tới khách hàng.

### REQUEST ###
Viết 1 email gửi riêng cho khách hàng có đơn linh kiện PC (Card màn hình, Nguồn, RAM)
bị giao chậm 4–6 ngày trong đợt siêu sale Black Friday. Email phải:
1. Xin lỗi chân thành và nhận trách nhiệm trực tiếp về phía TechShop.
2. Giải trình minh bạch: hệ thống phân loại tự động của kho quá tải do lượng đơn tăng đột biến.
3. Cam kết lộ trình giao hàng mới bằng mốc ngày cụ thể.
4. Tặng Voucher giảm 15% cho đơn hàng tiếp theo.

### EXAMPLES ###
Câu văn mẫu thể hiện sự đồng cảm (tham khảo giọng văn, không chép nguyên):
"Chúng tôi hiểu việc chờ đợi linh kiện để hoàn thiện bộ PC là điều rất khó chịu,
và TechShop hoàn toàn chịu trách nhiệm về sự chậm trễ này."

### ADJUSTMENT ###
- Giọng văn: cực kỳ cầu thị, đồng cảm, chuyên nghiệp.
- Không đổ lỗi cho đơn vị vận chuyển, không đổ lỗi cho khách hàng.
- Không hứa suông: chỉ nêu cam kết và quyền lợi có trong phần EXTRAS, không tự thêm.
- Không dùng câu sáo rỗng, không bào chữa dài dòng.
- Chỉ trả về nội dung email, không chào hỏi hay giải thích ngoài email.

### TYPE OF OUTPUT ###
Email theo đúng khung:
1. Tiêu đề (rõ ràng, có mã đơn)
2. Lời chào trang trọng (Kính gửi Quý khách [Tên khách hàng],)
3. Thân bài đúng 3 đoạn ngắn:
   - Đoạn 1: xin lỗi và nhận trách nhiệm
   - Đoạn 2: giải trình nguyên nhân
   - Đoạn 3: lộ trình giao mới và voucher
4. Lời cam kết
5. Thông tin liên hệ khẩn cấp
6. Chữ ký

### EXTRAS ###
- Khách hàng: [Tên khách hàng] | Mã đơn: [TS-xxxxx] | Sản phẩm: [Card màn hình / Nguồn / RAM]
- Mức chậm: [4–6] ngày so với cam kết
- Lộ trình mới: [giao trước 17h ngày dd/mm]
- Voucher: giảm 15% cho đơn kế tiếp | Mã: [BF15-xxxx] | Hạn dùng: [30 ngày] | Điều kiện: [nếu có]
- Hotline VIP: [1900 xxxx, hoạt động 8h–22h] | Email: [cskh@techshop.vn]
```
