🧮 Tính Hạn Sử Dụng (HSD)

Ứng dụng web/PWA giúp tính nhanh hạn sử dụng sản phẩm, hỗ trợ kiểm soát date hàng hóa trong siêu thị, kho, hoặc ngành FMCG.

🚀 Tính năng chính
📅 Nhập Ngày sản xuất (MFG)
🔄 Hỗ trợ 2 cách nhập hạn sử dụng:
Hạn sử dụng tốt nhất (theo tháng)
Hạn sử dụng cụ thể (dd/mm/yyyy)
📊 Tự động tính:
🔴 Ngày rút hàng (còn 20% date)
🟣 Ngày báo quản lý (còn 35% date)
🟢 Đánh giá tình trạng:
Tốt / Trung bình / Sắp hết hạn
📱 Giao diện tối ưu mobile
⚡ Có thể cài như app Android (PWA)
📷 Giao diện

UI tối giản, dễ dùng cho nhân viên kiểm date

Nhập ngày sản xuất
Chọn kiểu hạn sử dụng
Nhấn Tính Toán
Xem kết quả ngay lập tức

🛠️ Công nghệ sử dụng
HTML / CSS / JavaScript thuần
Flatpickr (chọn ngày)
LocalStorage (lưu tạm)
Service Worker (PWA)

📦 Cài đặt & sử dụng
1. Clone project
git clone https://github.com/bathinh008/tinhhsdtp.git

cd hsd-calculator

3. Chạy local

Bạn có thể mở trực tiếp:

index.html

Hoặc dùng server:

npx serve
3. Cài trên Android (PWA)
Mở bằng Chrome
Bấm ⋮
Chọn Thêm vào màn hình chính hoặc Cài đặt ứng dụng
📁 Cấu trúc project

├── index.html

├── manifest.json

├── sw.js

├── icon.png

⚙️ Cách hoạt động
Nếu chọn Hạn sử dụng tốt nhất:
EXP = MFG + số tháng
Nếu chọn Hạn sử dụng cụ thể:
Dùng trực tiếp ngày EXP nhập vào

📊 Công thức tính
Tổng thời gian = EXP - MFG
% đã dùng = (hiện tại - MFG) / tổng
% còn lại = 100 - % đã dùng
Ngày rút hàng (20%):
= MFG + 80% thời gian
Ngày báo QL (35%):
= MFG + 65% thời gian

⚠️ Lưu ý
Nhập đúng định dạng: dd/mm/yyyy
Không để trống ngày sản xuất
Số tháng phải > 0
Không hỗ trợ password (khuyến nghị dùng AppLock nếu cần)

💡 Use case
Nhân viên siêu thị kiểm tra hạn
Quản lý kho hàng
Kiểm soát hàng FMCG
Báo cáo hàng cận date

🔥 Roadmap (có thể nâng cấp)
 Xuất file báo cáo
 Thêm barcode scan
 Đồng bộ dữ liệu
 App Android (APK)
 Thống kê hàng tồn
 
👨‍💻 Tác giả

Được phát triển bởi: Phương Thịnh

📄 License

MIT License

⭐ Đóng góp

Nếu thấy hữu ích, hãy ⭐ repo để ủng hộ nhé!
