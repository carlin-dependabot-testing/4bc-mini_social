
# Mini Social

Mini Social là một ứng dụng mạng xã hội nhỏ, giúp người dùng đăng ký, đăng nhập, tạo bài viết, thích và bình luận — xây dựng để học và áp dụng Hotwire (Turbo + Stimulus) trong Ruby on Rails.

---

## 🚀 Tính năng chính

- Đăng ký / Đăng nhập người dùng (Devise)
- Tạo bài viết (Post)
- Hiển thị dòng thời gian (Feed) bài viết của tất cả người dùng
- Like và Comment bài viết (đang phát triển)
- Giao diện responsive dùng Tailwind CSS
- Tận dụng Hotwire Turbo để tương tác không reload trang

---

## 🛠️ Công nghệ sử dụng

- Ruby on Rails 8.x
- PostgreSQL
- Hotwire (Turbo + Stimulus)
- Tailwind CSS
- Devise (Authentication)
- Slim

---

## 💾 Cài đặt và chạy project

1. Cài đặt gem:

   ```bash
   bundle install
   ```

2. Tạo database và migrate:

   ```bash
   rails db:create
   rails db:migrate
   ```

3. Chạy server và vite:

   ```bash
   bin/dev
   ```

4. Mở trình duyệt truy cập: [http://localhost:3000](http://localhost:3000)

---

## 📝 Ghi chú

- Ứng dụng dùng PostgreSQL làm database, đảm bảo bạn đã cài đặt PostgreSQL và đang chạy
- Hotwire Turbo giúp tránh reload toàn bộ trang khi tạo bài viết, like, comment
- Hiện tại chỉ hỗ trợ đăng nhập và tạo bài viết, các tính năng khác sẽ phát triển dần

---

## 📚 Tài liệu tham khảo

- [Hotwire Official](https://hotwired.dev/)
- [Devise](https://github.com/heartcombo/devise)
- [Tailwind CSS](https://tailwindcss.com/)
- [Ruby on Rails Guides](https://guides.rubyonrails.org/)

---

## 👤 Tác giả

- [Huong Giang] - Mini Facebook project
