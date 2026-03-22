# Personal Portfolio

Đây là dự án portfolio cá nhân được xây dựng bằng React, Vite và Tailwind CSS để giới thiệu bản thân, kỹ năng, kinh nghiệm, dự án nổi bật và thông tin liên hệ.

## Tính năng chính

- Trang landing hiện đại, responsive cho desktop và mobile
- Các section giới thiệu: Hero, About, Projects, Experience, Testimonials, Contact
- Form liên hệ tích hợp EmailJS
- Cấu trúc component rõ ràng, dễ mở rộng và tùy chỉnh nội dung

## Công nghệ sử dụng

- React 19
- Vite
- Tailwind CSS 4
- EmailJS
- Lucide React
- ESLint

## Cài đặt và chạy dự án

### 1. Clone source code

```bash
git clone <repository-url>
cd dev-persional-portfolio
```

### 2. Cài đặt dependencies

```bash
npm install
```

### 3. Cấu hình biến môi trường

Tạo file `.env` và thêm các biến sau:

```env
VITE_EMAILJS_SERVICE_ID=your_service_id
VITE_EMAILJS_TEMPLATE_ID=your_template_id
VITE_EMAILJS_PUBLIC_KEY=your_public_key
```

### 4. Chạy môi trường phát triển

```bash
npm run dev
```

Ứng dụng sẽ chạy mặc định tại `http://localhost:5173`.

## Scripts

- `npm run dev`: chạy local development server
- `npm run build`: build production
- `npm run preview`: xem thử bản build production
- `npm run lint`: kiểm tra lint

## Cấu trúc thư mục

```text
src/
  assets/        Hình ảnh và tài nguyên tĩnh
  components/    Các UI component dùng lại
  layout/        Navbar, Footer
  sections/      Các section chính của portfolio
  App.jsx        Ghép layout tổng thể
  main.jsx       Entry point
```

## Mục tiêu dự án

Dự án này được dùng để:

- Giới thiệu hồ sơ cá nhân và kỹ năng lập trình
- Trình bày kinh nghiệm học tập và làm việc
- Trưng bày các dự án tiêu biểu
- Tạo kênh liên hệ trực tiếp với nhà tuyển dụng hoặc khách hàng

## Lưu ý khi deploy

- Không đưa file `.env` thật lên GitHub
- Kiểm tra lại EmailJS service trước khi deploy production
- Chạy `npm run build` để đảm bảo project build thành công
