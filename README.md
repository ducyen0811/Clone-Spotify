

## ⚙️ Hướng dẫn cài đặt & chạy dự án

Để chạy project này trên máy tính của bạn, làm theo các bước sau:

1. **Clone repository về máy**:

   ```bash
   git clone https://github.com/ducyen0811/Clone-Spotify.git
2. **Di chuyển vào thư mục dự án**:

   cd spotify-react-web-client

3. **Cài đặt các thư viện phụ thuộc**:

   yarn install

4. Tạo ứng dụng trên Spotify Developer và lấy Client ID cùng Redirect URI.Sau đó, tạo file .env trong thư mục gốc và thêm:

   REACT_APP_SPOTIFY_CLIENT_ID=<id của bạn>
   REACT_APP_SPOTIFY_REDIRECT_URL=<đường dẫn redirect>

5. Chạy ứng dụng:

   yarn start

6. Truy cập ứng dụng tại http://localhost:3000

