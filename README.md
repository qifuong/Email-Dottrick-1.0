# 📖 Dot-Trick Generator + Mail Code Notifier

**Tác giả:** **Yisu**  
**Phiên bản:** 2.0  

---

## 📝 Giới thiệu
**Dot-Trick Generator + Mail Code Notifier** là bộ công cụ gồm hai chức năng chính:

1. **Dot-Trick Generator**: Tạo ra hàng loạt biến thể email từ một địa chỉ gốc bằng cách chèn dấu chấm (`.`) vào phần **local-part**. Nhiều dịch vụ email (như Gmail, Hotmail, Outlook) bỏ qua dấu chấm trong tên địa chỉ, nhưng vẫn cho phép đăng ký và sử dụng biến thể có dấu chấm. Nhờ đó, bạn có thể có nhiều biến thể email trỏ về cùng một hộp thư.

   Ví dụ:

example@hotmail.com
ex.ample@hotmail.com
e.xample@hotmail.com
e.x.a.m.p.l.e@hotmail.com

markdown
Sao chép mã

Tất cả đều hoạt động và trỏ về cùng một email gốc.

2. **Mail Code Notifier**: Tự động theo dõi hộp thư của bạn (INBOX và Spam) để phát hiện các **mã số/OTP** gửi đến. Khi có mã mới, chương trình hiển thị trong giao diện và có thể copy nhanh bằng **double-click**.

---

## ⚙️ Tính năng chính

### Dot-Trick Generator
- Nhập **local-part** (tên email trước ký tự `@`).  
- Chọn domain từ danh sách hỗ trợ sẵn:  
- `@hotmail.com`  
- `@gmail.com`  
- `@outlook.com`  
- `@live.com`  
- `@yahoo.com`  
- Sinh tự động hàng ngàn biến thể dot-trick.  
- Hiển thị số lượng biến thể đã tạo.  
- Xuất toàn bộ danh sách ra file `.txt`.  
- Nút **Clear** để nhập lại nhanh chóng.

### Mail Code Notifier
- Hỗ trợ **Gmail, Hotmail/Outlook, Yahoo**.  
- Theo dõi **mail mới** từ INBOX và Spam (tuỳ chọn).  
- Tự động phát hiện thư mới và hiển thị mã số (OTP) gửi đến.  
- Hỗ trợ copy nhanh mã bằng **double-click**.  
- Có thể **export log** ra file `.txt`.  
- Hiển thị trạng thái kết nối và tiến trình.

---

## 💻 Hướng dẫn sử dụng

### Dot-Trick Generator
1. Mở công cụ.  
2. Nhập **local-part** (ví dụ: `example`).  
3. Chọn domain từ menu thả xuống.  
4. Nhấn **Generate** để sinh biến thể.  
5. Xem kết quả trong khung **Dot-trick Variants**.  
6. Nếu muốn lưu, nhấn **Save .txt** và chọn nơi lưu file.  
7. Nhấn **Clear** để nhập địa chỉ khác.

### Mail Code Notifier
1. Nhập **Email** và **Mật khẩu ứng dụng** (App Password).  
- Gmail: Bật **IMAP**, tạo **App Password** tại `myaccount.google.com` → Bảo mật → Mật khẩu ứng dụng.  
- Outlook/Hotmail: IMAP server `imap-mail.outlook.com`, Port 993.  
- Yahoo: IMAP server `imap.mail.yahoo.com`, Port 993.  
2. Tùy chọn **bao gồm thư Spam/Junk**. Nếu không tự động dò được folder Spam, nhập thủ công.  
3. Nhấn **Đăng nhập & Bắt đầu** để kết nối và bắt đầu theo dõi.  
4. Khi có mã mới, chương trình hiển thị trong khung log.  
5. Double-click vào mã để copy nhanh vào clipboard.  
6. Nhấn **Dừng** để ngưng theo dõi.  
7. Nhấn **Export Log** để lưu toàn bộ log ra file `.txt`.

---

## 📂 Kết quả đầu ra

### Dot-Trick
Các biến thể email hiển thị ngay trong cửa sổ và có thể lưu ra file:

example@gmail.com
ex.ample@gmail.com
e.xample@gmail.com
e.x.a.m.p.l.e@gmail.com

css
Sao chép mã

### Mail Code Notifier
Log hiển thị dạng:

[2025-09-15 14:00:01] [INBOX] Từ: no-reply@gmail.com
Chủ đề: OTP Xác thực
Mã: 123456
markdown
Sao chép mã

---

## 📌 Lưu ý quan trọng
- **Dot-Trick** không tạo email mới, chỉ tạo ra biến thể hợp lệ của email đã có.  
- **Mail Code Notifier** chỉ đọc mail mới xuất hiện sau khi đăng nhập; các mail cũ được bỏ qua (có thể reset bằng cách xóa file `last_uid_...`).  
- Một số domain có thể không hỗ trợ dot-trick (ví dụ Yahoo).  
- Sử dụng hợp pháp; **tác giả không chịu trách nhiệm** nếu dùng cho spam hoặc gian lận.

---

## 📦 Thông tin thêm
- **Tên công cụ:** Dot-Trick Generator + Mail Code Notifier  
- **Phiên bản:** 2.0  
- **Tác giả:** Yisu  
- **Ngôn ngữ:** Tiếng Việt / English  
- **Loại file:** Ứng dụng GUI độc lập (.exe) 
