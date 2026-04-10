# Nền tảng Giao đồ ăn và Logistics thời gian thực - Slide Trình bày

Slide trình bày web cho đề tài "Nền tảng Giao đồ ăn và Logistics thời gian thực" sử dụng Reveal.js

## 🚀 Demo

Xem slide tại: [Link Netlify của bạn]

## 📋 Nội dung

Slide bao gồm các phần chính:

1. **Tổng quan đề tài**
   - Lý do chọn đề tài
   - Mục tiêu đề tài
   - Phạm vi đề tài

2. **Cơ sở lý thuyết**
   - Kiến trúc SOA
   - Microservices
   - Công nghệ sử dụng

3. **Phân tích yêu cầu hệ thống**
   - Mô tả bài toán
   - Các tác nhân
   - Yêu cầu chức năng

4. **Thiết kế hệ thống**
   - Kiến trúc tổng thể
   - Các microservices
   - Luồng nghiệp vụ
   - Cơ sở dữ liệu

5. **Cài đặt và triển khai**
   - Công nghệ sử dụng
   - Tích hợp bên thứ ba
   - Giao diện hệ thống

6. **Kiểm thử và đánh giá**
   - Phương pháp kiểm thử
   - Kết quả đạt được

7. **Kết luận và hướng phát triển**

## 🛠️ Công nghệ

- **Reveal.js** - Framework tạo slide HTML
- **HTML5/CSS3** - Giao diện
- **JavaScript** - Tương tác

## 📦 Cài đặt và chạy local

### Cách 1: Mở trực tiếp file HTML

```bash
# Clone repository
git clone [link-repo-của-bạn]
cd [tên-folder]

# Mở file index.html bằng trình duyệt
# Hoặc sử dụng Live Server trong VS Code
```

### Cách 2: Sử dụng Python HTTP Server

```bash
# Python 3
python -m http.server 8000

# Mở trình duyệt tại http://localhost:8000
```

### Cách 3: Sử dụng Node.js

```bash
# Cài đặt http-server
npm install -g http-server

# Chạy server
http-server

# Mở trình duyệt tại http://localhost:8080
```

## 🌐 Deploy lên Netlify

### Cách 1: Deploy từ GitHub (Khuyến nghị)

1. Push code lên GitHub repository
2. Đăng nhập vào [Netlify](https://www.netlify.com/)
3. Click "New site from Git"
4. Chọn repository của bạn
5. Click "Deploy site"

### Cách 2: Deploy thủ công

1. Đăng nhập vào [Netlify](https://www.netlify.com/)
2. Kéo thả folder chứa code vào Netlify
3. Site sẽ được deploy tự động

### Cách 3: Sử dụng Netlify CLI

```bash
# Cài đặt Netlify CLI
npm install -g netlify-cli

# Đăng nhập
netlify login

# Deploy
netlify deploy --prod
```

## ⌨️ Phím tắt khi trình bày

- **→** hoặc **Space**: Slide tiếp theo
- **←**: Slide trước
- **F**: Chế độ toàn màn hình
- **S**: Chế độ speaker notes
- **O** hoặc **ESC**: Xem tổng quan tất cả slide
- **B** hoặc **.**: Tạm dừng (màn hình đen)

## 📱 Responsive

Slide được thiết kế responsive, hoạt động tốt trên:
- Desktop (1920x1080, 1366x768)
- Tablet (768x1024)
- Mobile (375x667)

## 🎨 Tùy chỉnh

### Thay đổi màu sắc

Chỉnh sửa file `style.css`, phần CSS Variables:

```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --accent-color: #e74c3c;
    /* ... */
}
```

### Thay đổi theme Reveal.js

Trong file `index.html`, thay đổi dòng:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reveal.js@4.5.0/dist/theme/white.css">
```

Các theme có sẵn: `black`, `white`, `league`, `beige`, `sky`, `night`, `serif`, `simple`, `solarized`

### Thêm/Sửa nội dung

Chỉnh sửa file `index.html`, mỗi slide được bao bởi thẻ `<section>`:

```html
<section>
    <h2>Tiêu đề slide</h2>
    <p>Nội dung slide</p>
</section>
```

## 📄 Cấu trúc file

```
.
├── index.html          # File HTML chính chứa nội dung slide
├── style.css           # File CSS tùy chỉnh
├── README.md           # File hướng dẫn này
└── .gitignore         # File gitignore (nếu cần)
```

## 👥 Nhóm thực hiện

- Trần Thị Thu Hằng
- Lương Gia Hân
- Lê Minh Đức - 11235992
- Vũ Tuấn Hưng - 11236005

## 📝 License

MIT License - Tự do sử dụng cho mục đích học tập

## 🤝 Đóng góp

Mọi đóng góp đều được chào đón! Hãy tạo Pull Request hoặc Issue nếu bạn có ý tưởng cải thiện.

## 📞 Liên hệ

- Email: [email của bạn]
- GitHub: [link GitHub của bạn]

---

**Lưu ý**: Đây là slide trình bày cho mục đích học tập tại Trường Đại học Kinh tế Quốc dân
