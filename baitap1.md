## 1\. Ký tự lạ trong URL

* URL giả: `https://githúb.com/login`
* Ký tự đáng ngờ: `ú` (chữ u có dấu sắc), thay cho chữ `u` trong `github.com`.
* Đây là kỹ thuật **Homograph Attack**, sử dụng ký tự Unicode giống ký tự thông thường để giả mạo tên miền.
* Người dùng dễ nhầm URL giả với website GitHub thật và vô tình nhập mật khẩu.

## 2\. Quy trình kiểm tra URL

**Bước 1: Kiểm tra bằng mắt thường**

* Đọc kỹ từng ký tự trong tên miền.
* Kiểm tra lỗi chính tả, ký tự có dấu và tên miền lạ.
* Không vội nhấn vào đường link trong email hoặc tin nhắn.

**Bước 2: Kiểm tra bằng công cụ**

* Sao chép URL và kiểm tra bằng VirusTotal.
* Dùng công cụ giải mã Punycode để phát hiện ký tự Unicode giả mạo.
* Kiểm tra chứng chỉ HTTPS, nhưng không xem HTTPS là bằng chứng website an toàn.

**Bước 3: Xác minh và đăng nhập**

* Tự nhập `https://github.com` vào trình duyệt.
* Chỉ nhập Master Password khi đã xác minh đúng website.
* Nếu nghi ngờ, đóng trang và báo cáo email lừa đảo.

