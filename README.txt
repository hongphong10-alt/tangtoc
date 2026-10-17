HỘI THI CÁN BỘ KIỂM TRA GIỎI - XÃ TRIỆU VIỆT VƯƠNG 2027

══════════════════════════════════════════════
📂 TRONG GÓI:
══════════════════════════════════════════════
1️⃣  index.html     - ỨNG DỤNG HỘI THI (màn hình chính)
2️⃣  dt.html        - TRANG TRẢ LỜI TRÊN ĐIỆN THOẠI (4 đội)

══════════════════════════════════════════════
🎮 index.html - CẤU HÌNH HỘI THI:
══════════════════════════════════════════════
• 16 bộ câu hỏi × 7 câu, dùng đúng dữ liệu thật từ bộ 1→16
• Mỗi lượt thi: 2 đội • Sai 2 lần: tự công bố đáp án
• Bấm chuột vào đáp án A/B/C/D trên màn hình
• Nút 📚: mở panel chọn bộ hoặc Random 🎲 chọn ngẫu nhiên
  một bộ chưa thi; số hiển thị và nội dung là cùng một bộ
• Nút 🏁 Kết thúc: khi 2 đội thi xong
• Không dùng phím tắt - chỉ chuột
• Nút ⛶ (góc phải dưới): toàn màn hình

══════════════════════════════════════════════
👥 CHẾ ĐỘ 4 ĐỘI - ĐIỆN THOẠI TRẢ LỜI QUA INTERNET:
══════════════════════════════════════════════
• 4 đội A/B/C/D • MỖI ĐIỆN THOẠI = 1 ĐỘI
• Điện thoại mở dt.html → nhập/quét MÃ PHÒNG 6 ký tự
  → nhập TÊN ĐỘI → chọn đội A/B/C/D → SẴN SÀNG trả lời
• Đội bấm đáp án ngay trên điện thoại (có rung + tiếng bíp)
• Màn hình chính hiện dải 4 đội: đội trả lời ĐÚNG sáng xanh
  kèm SỐ GIÂY đã dùng (⏱), đội trả lời SAI hiện đỏ
• LUẬT MỚI: KHÔNG hiện đáp án khi có đội đúng → chờ ĐỦ số đội
  đã kết nối trả lời mới tự công bố đáp án
• ĐIỂM THEO TỐC ĐỘ (chốt khi công bố đáp án):
  +5 đúng nhanh nhất • +4 đúng nhì • +3 đúng ba • +2 đúng sau cùng
  Sai hoặc không trả lời: 0 điểm. Mỗi câu hiện "✅ X/4 đội đúng".
• VÀO BỘ ĐỀ: hiện MÀN KẾT NỐI 4 ĐỘI trước → người dẫn bấm Đóng
  (đủ đội đã vào) mới hiện CÂU HỎI SỐ 1
• HẾT BỘ ĐỀ → 3 MÀN RIÊNG BIỆT (3s → 13s → 18s):
  1) 🏆 CHÚC MỪNG HAI ĐỘI đã hoàn thành phần thi
  2) 📊 BẢNG TỔNG KẾT: số câu trả lời đúng + tổng điểm từng đội,
     xếp TỪ CAO XUỐNG THẤP (riêng biệt, không kèm lời mời)
  3) ⏳ Lời mời Hai đội tiếp theo / Hai đội vào vị trí (bảng đã ẩn)
• Người dẫn vẫn bấm chuột được (dự phòng): sai 2 lần → hiện đáp án
• Chip "Số câu đúng" A/B/C/D chạy điểm thật sau mỗi câu
• Panel "📱 Kết nối ĐT": QR code, mã phòng, ô sửa link dt.html,
  ô nhập tên 4 đội, trạng thái kết nối, nút ↺ Reset điểm
• Tên đội + điểm + mã phòng lưu trong trình duyệt (localStorage)

══════════════════════════════════════════════
📱 CÁCH DÙNG CHẾ ĐỘ 4 ĐỘI:
══════════════════════════════════════════════
BƯỚC 1: Chạy web server cho THU MỤC NÀY (xem mục CÁCH MỞ).
        MÁY TRÌNH CHIẾU và ĐIỆN THOẠI đều phải CÓ INTERNET
        (kết nối ghép cặp qua dịch vụ PeerJS cloud).

BƯỚC 2: Mở index.html trên máy trình chiếu → bấm nút
        "📱 Kết nối ĐT" → hiện QR + MÃ PHÒNG 6 ký tự.

BƯỚC 3: Mỗi điện thoại QUÉT QR (hoặc mở dt.html?room=MÃ)
        → nhập tên đội → chọn A/B/C/D → chờ "SẴN SÀNG".

BƯỚC 4: Chọn bộ câu hỏi, bấm câu hỏi như bình thường.
        - ĐT trả lời → màn hình hiện ⏱ số giây + ✅/❌ từng đội
        - Đủ số đội đã kết nối trả lời → TỰ công bố đáp án
        - Chưa đủ thì các ĐT hiện "Đã có X/4 đội trả lời"

BƯỚC 5: Bấm sang câu tiếp theo, lặp lại. Hết câu → 🏁.

⚠️ LƯU Ý QUAN TRỌNG:
- TRÌNH DUYỆT ĐIỆN THOẠI: nên dùng Chrome / Safari / Edge. Với trình duyệt
  không có WebRTC (Mi Browser, Vivo, UC...), ứng dụng TỰ CHUYỂN sang kênh
  dự phòng (WebSocket) → vẫn chạy bình thường, chỉ hơi trễ vài phần trăm giây.
- Muốn ép kênh dự phòng ngay: thêm ?bus=1 vào cuối link dt.html
- KHÔNG mở index.html bằng cách double-click (file://) →
  điện thoại sẽ không mở được link. Phải chạy web server.
- Máy trình chiếu phải mở bằng địa chỉ mà ĐT VÀO ĐƯỢC:
  + Cùng mạng WiFi: http://192.168.x.x:8000 (IP máy tính)
  + Hoặc đưa cả thư mục lên internet (Netlify / GitHub Pages)
- QR tạo từ đường dẫn của trang; nếu sai, sửa ô
  "Link dt.html" trong panel Kết nối ĐT rồi QR tự đổi.
- Đội chưa kết nối không bị tính vào luật chờ đủ đội.
- Nút ↺ Reset điểm trong panel để tính lại từ đầu.

══════════════════════════════════════════════
⚠️  CÁCH MỞ (phải qua web server):
══════════════════════════════════════════════
KHÔNG double-click mở file HTML trực tiếp!

CÁCH 1 (Python):
  PowerShell tại thư mục này →
    python -m http.server 8000
  Mở trình duyệt: http://localhost:8000

CÁCH 2 (VS Code):
  Cài extension "Live Server" → chuột phải
   index.html → Open with Live Server

CÁCH 3 (Node.js):  npx serve

LƯU Ý: Giữ TẤT CẢ file trong CÙNG 1 thư mục!
