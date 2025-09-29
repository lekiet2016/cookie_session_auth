# 🍪 Cookie Session Auth

---

## 📑 Quy trình demo

### 📝 Đăng ký tài khoản
- Người dùng thực hiện đăng ký:  
  ![User registered successfully!](assets/image1.png)

### 🗄️ Kiểm tra CSDL
- Bảng **Users** sau khi tạo tài khoản:  
  ![CSDL Users](assets/image2.png)

- Bảng **Sessions** sau khi đăng ký:  
  ![CSDL Sessions](assets/image3.png)

### ⚠️ Đăng ký trùng lặp
- Hệ thống từ chối khi tài khoản đã tồn tại:  
  ![User registration failed](assets/image4.png)

---

### 🔑 Đăng nhập
- Người dùng đăng nhập thành công:  
  ![Login successful!](assets/image5.png)

### 🗄️ Kiểm tra Session trong CSDL
- Session mới được thêm vào bảng **Sessions**:  
  ![CSDL Sessions](assets/image6.png)

---

### 👤 Xem profile
- Sau khi đăng nhập, người dùng có thể xem thông tin profile:  
  ![Show profile](assets/image7.png)

---

### 🚪 Logout
- Người dùng logout khỏi hệ thống:  
  ![Logout successful!](assets/image8.png)

### 🗄️ Kiểm tra CSDL sau khi logout
- Session đã được xóa khỏi bảng **Sessions**:  
  ![Show Session](assets/image9.png)

---

✍️ *Demo phục vụ học tập về cơ chế Cookie-Session Authentication.*
