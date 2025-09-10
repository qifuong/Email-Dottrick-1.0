# 📖 Dot-Trick Generator

Tác giả: **Yisu**

---

## 📝 Giới thiệu
**Dot-Trick Generator** là công cụ giúp bạn tạo ra hàng loạt biến thể email từ một địa chỉ gốc bằng cách chèn dấu chấm (`.`) vào phần **local-part** của email.  
Nhiều dịch vụ email (như Gmail, Hotmail, Outlook) bỏ qua dấu chấm trong tên địa chỉ, nhưng vẫn cho phép đăng ký và sử dụng biến thể có dấu chấm. Nhờ đó, bạn có thể có nhiều biến thể email trỏ về cùng một hộp thư.

Ví dụ:  

example@hotmail.com
ex.ample@hotmail.com
e.xample@hotmail.com
e.x.a.m.p.l.e@hotmail.com

markdown
Sao chép mã

Tất cả đều hoạt động và trỏ về cùng một email gốc.

---

## ⚙️ Tính năng chính
- Nhập **local-part** (tên email trước ký tự `@`).  
- Chọn domain từ danh sách hỗ trợ sẵn:  
  - `@hotmail.com`  
  - `@gmail.com`  
  - `@outlook.com`  
  - `@live.com`  
  - `@yahoo.com`  
- Sinh tự động hàng ngàn biến thể dot-trick.  
- Hiển thị số lượng biến thể đã tạo (`Variants: N`).  
- Xuất toàn bộ danh sách ra file `.txt`.  
- Nút **Clear** để nhập lại nhanh chóng.  

---

## 💻 Hướng dẫn sử dụng
1. **Mở công cụ** (file chạy).  
2. **Nhập local-part** (ví dụ: `example`).  
3. **Chọn domain** từ menu thả xuống.  
4. Nhấn **Generate** để sinh biến thể.  
5. Xem kết quả trong khung **Dot-trick Variants**.  
6. Nếu muốn lưu, nhấn **Save .txt** và chọn nơi lưu file.  
7. Nhấn **Clear** để nhập địa chỉ khác.  

---

## 📂 Kết quả đầu ra
- Các biến thể email hiển thị ngay trong cửa sổ.  
- Có thể lưu ra file văn bản (`dottrick.txt`).  

Ví dụ nội dung file kết quả:  

example@gmail.com
ex.ample@gmail.com
e.xample@gmail.com
e.x.a.m.p.l.e@gmail.com

yaml
Sao chép mã

---

## 📌 Lưu ý quan trọng
- Công cụ này **không tạo email mới**, chỉ tạo ra biến thể hợp lệ của một email đã có.  
- Một số domain có thể **không hỗ trợ dot-trick** (ví dụ: Yahoo).  
- Vui lòng sử dụng công cụ này hợp pháp, phục vụ nghiên cứu và quản lý email.  
- **Tác giả không chịu trách nhiệm** nếu người dùng lợi dụng công cụ cho mục đích spam hoặc gian lận.  

---

## 📦 Thông tin thêm
- **Tên công cụ:** Dot-Trick Generator  
- **Phiên bản:** 1.0  
- **Tác giả:** Yisu  
- **Ngôn ngữ:** English / 繁體中文
- **Loại file:** Ứng dụng chạy độc lập (.exe)  

---