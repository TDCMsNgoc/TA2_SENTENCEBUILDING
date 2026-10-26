# PHẦN MỀM TRẮC NGHIỆM: TA2 - SENTENCE BUILDING (40 CÂU)
### TRƯỜNG CAO ĐẲNG CÔNG NGHỆ THỦ ĐỨC (TDC)

Hệ thống phần mềm trắc nghiệm trực tuyến 40 câu hỏi xây dựng câu hoàn chỉnh môn **TA2 - SENTENCE BUILDING**, được tối ưu hóa đặc biệt để chạy trực tiếp trên **GitHub Pages** (hoặc mở trực tiếp trên máy tính/điện thoại không cần cài đặt server).

---

## 🌟 ĐẶC ĐIỂM NỔI BẬT ĐÁP ỨNG ĐÚNG YÊU CẦU

1. **Chuẩn nhận diện thương hiệu TDC**:
   - Bên góc trên bên trái hiển thị logo chính thức của trường TDC và kế bên chỉ ghi duy nhất dòng chữ: **"TA2 - SENTENCE BUILDING"**.
   - Giao diện phối màu xanh navy & cam đặc trưng của trường TDC, chuẩn sư phạm, tương thích 100% trên điện thoại di động, máy tính bảng và máy tính để bàn.

2. **Kiểm soát chặt chẽ số lượng sinh viên truy cập**:
   - **Bộ đếm trực tiếp (Live Visitor Counter)**: Hiển thị ngay trên thanh tiêu đề `👁️ Truy cập: [Số lượt]`, tích hợp API đếm thời gian thực trực tuyến:  
     👉 [https://api.counterapi.dev/v1/tdc-ta2-sentence-building/page-visits](https://api.counterapi.dev/v1/tdc-ta2-sentence-building/page-visits)
   - **Bảng điều khiển Giảng viên (Teacher Center)**: Giảng viên bấm nút **"⚙️ Giảng viên"** ở góc phải (Mã PIN mặc định: `tdc123`):
     - **Tạm khóa phòng thi**: Khi hết giờ hoặc chưa đến ca thi, giảng viên có thể khóa bài thi chỉ với 1 click. Sinh viên vào sẽ thấy thông báo phòng thi đang tạm khóa.
     - **Bảo mật bằng Mã phòng thi (Room Passcode)**: Giảng viên có thể bật yêu cầu mật khẩu làm bài (ví dụ cấp mã `TDC2026` trên lớp). Chỉ sinh viên nào có mã mới vào làm bài được, giúp kiểm soát 100% đúng số lượng sinh viên được phép truy cập.
     - **Danh sách bài thi đã nộp**: Tự động ghi lại Họ tên, MSSV, Lớp, Điểm số, Thời gian hoàn thành và Thời điểm nộp bài của sinh viên.
     - **Xuất bảng điểm ra Excel (CSV)**: Tải toàn bộ danh sách sinh viên đã nộp bài về máy tính với đầy đủ thông tin.

3. **Bảo mật đáp án tuyệt đối - Chỉ mở khóa sau khi hoàn tất 40 câu và nộp bài**:
   - **Trong quá trình làm bài**: Sinh viên chỉ thấy câu hỏi gợi ý và các phương án A, B, C. Tuyệt đối không có bất kỳ nút hay dấu hiệu nào lộ đáp án.
   - **Bắt buộc hoàn thành 100%**: Nếu sinh viên bấm Nộp bài khi chưa làm đủ 40 câu, hệ thống sẽ từ chối nộp và hiện thông báo danh sách cụ thể các câu còn thiếu, yêu cầu sinh viên hoàn tất đầy đủ.
   - **Sau khi nộp bài thành công**: Hệ thống lập tức mở khóa:
     - Bảng điểm chi tiết: Điểm số (trên 40), điểm hệ 10, tỉ lệ %, xếp loại và thời gian làm bài.
     - Nhận diện trực quan câu Đúng (viền xanh ✓) và câu Sai (viền đỏ ✗, gạch ngang phương án sai và tô xanh đáp án đúng).
     - **💡 GIẢI THÍCH CHI TIẾT**: Phân tích rõ ràng công thức ngữ pháp, thì động từ, cấu trúc câu và lý do vì sao chọn đáp án này, vì sao các đáp án khác sai.
     - **🌐 DỊCH NGHĨA HOÀN CHỈNH**: Bản dịch tiếng Việt tự nhiên, chuẩn nghĩa của câu văn.
     - Bộ lọc tiện lợi: Xem tất cả / Chỉ xem câu đúng / Chỉ xem câu sai / Câu đã đánh dấu (★).
     - Hỗ trợ **In / Lưu PDF bảng điểm** và **Xuất file Excel (CSV) kết quả cá nhân**.

4. **Chạy hoàn hảo trên GitHub Pages**:
   - Xây dựng 100% bằng HTML5, CSS3 và JavaScript thuần (Vanilla JS).
   - Không cần server, không cần cơ sở dữ liệu phức tạp, tải trang cực nhanh, hoạt động ổn định trên mọi môi trường.

---

## 📁 CẤU TRÚC THƯ MỤC DỰ ÁN

```text
TA2-SENTENCE BUILDING/
│
├── index.html          # Trang chủ ứng dụng web (HTML5)
├── logo-tdc.png        # Logo chính thức của Trường CĐCN Thủ Đức
├── css/
│   └── style.css       # Toàn bộ giao diện, hiệu ứng & chuẩn in ấn PDF
├── js/
│   ├── questions.js    # Ngân hàng 40 câu hỏi + Đáp án + Giải thích + Dịch nghĩa
│   └── app.js          # Logic kiểm soát truy cập, làm bài, chấm điểm & bảo mật
└── README.md           # Hướng dẫn chi tiết triển khai lên GitHub Pages
```

---

## 🚀 HƯỚNG DẪN ĐƯA LÊN GITHUB & BẬT GITHUB PAGES (CHỈ 2 PHÚT)

Thầy/Cô có thể đưa toàn bộ thư mục này lên GitHub theo một trong hai cách dưới đây:

### CÁCH 1: Kéo thả trực tiếp trên giao diện website GitHub (Đơn giản nhất, không cần cài phần mềm)

1. **Đăng nhập vào GitHub**: Truy cập [https://github.com](https://github.com) và đăng nhập tài khoản.
2. **Tạo Repository mới**:
   - Bấm vào dấu `+` ở góc trên bên phải màn hình -> chọn **New repository**.
   - Đặt tên Repository, ví dụ: `TA2-SENTENCE-BUILDING` hoặc `ta2-sentence-building`.
   - Chọn chế độ: **Public** (Bắt buộc Public để dùng GitHub Pages miễn phí).
   - Tích chọn **Add a README file** rồi bấm nút xanh **Create repository**.
3. **Tải các file lên**:
   - Tại trang repository vừa tạo, bấm nút **Add file** -> chọn **Upload files**.
   - Kéo thả toàn bộ các file và thư mục trong thư mục `TA2-SENTENCE BUILDING` này vào:
     - `index.html`
     - `logo-tdc.png`
     - Thư mục `css` (chứa `style.css`)
     - Thư mục `js` (chứa `questions.js` và `app.js`)
   - Cuộn xuống dưới cùng và bấm **Commit changes**.
4. **Bật GitHub Pages để nhận link chia sẻ cho sinh viên**:
   - Bấm vào tab **Settings** của repository (trên thanh menu ngang phía trên).
   - Ở cột menu bên trái, tìm và bấm chọn mục **Pages**.
   - Tại phần **Build and deployment** -> **Branch**:
     - Chọn nhánh: **main** (hoặc `master`).
     - Chọn thư mục: **/ (root)**.
     - Bấm nút **Save**.
   - Chờ khoảng 1 - 2 phút rồi tải lại trang (F5), Thầy/Cô sẽ nhận được đường link:
     > `https://<ten-tai-khoan>.github.io/TA2-SENTENCE-BUILDING/`
   - 👉 **Đây chính là link website gửi cho sinh viên vào làm bài kiểm tra!**

---

### CÁCH 2: Dùng lệnh Git (Nếu đã cài Git trên máy)

Mở Terminal / PowerShell tại thư mục `d:\websiteabc\TA2-SENTENCE BUILDING` và chạy các lệnh:

```bash
git init
git add .
git commit -m "Khoi tao bai trac nghiem TA2 - SENTENCE BUILDING TDC"
git branch -M main
git remote add origin https://github.com/<ten-tai-khoan-github>/TA2-SENTENCE-BUILDING.git
git push -u origin main
```
Sau đó vào **Settings** -> **Pages** trên GitHub và kích hoạt nhánh `main`.

---

## 🔐 HƯỚNG DẪN QUẢN LÝ DÀNH CHO GIẢNG VIÊN

1. **Mã PIN mở Bảng Giảng viên**: `tdc123` (Giảng viên có thể đổi mã PIN này trong bảng cài đặt).
2. **Mã phòng thi mặc định**: `TDC2026` (Giảng viên có thể bật/tắt yêu cầu nhập mã phòng thi và đổi mã tùy ý trước mỗi ca thi).
3. **Theo dõi lượt truy cập**:
   - Trực tiếp trên thanh tiêu đề `👁️ Truy cập: ...`.
   - Xem tổng quan và xuất danh sách kết quả nộp bài ra Excel (CSV) bất cứ lúc nào.
