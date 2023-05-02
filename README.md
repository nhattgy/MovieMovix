# MovieMovix
Reactjs Movie
Movix - Website xem phim trực tuyến
Movix là một website xem phim trực tuyến sử dụng React Vite và React Hooks API để thực hiện việc lấy dữ liệu từ TMDB Movie. Trang web này bao gồm các trang chủ, trang TV shows và trang chi tiết phim.
Trang chủ
Trang chủ của Movix hiển thị danh sách các bộ phim phổ biến và danh sách TV show đang hot nhất. Bạn có thể tìm kiếm phim hoặc TV show theo tên bằng cách sử dụng ô tìm kiếm ở góc trên bên phải của trang web.
![Chưa có tên](https://user-images.githubusercontent.com/95953901/235669605-b7ec6983-e2a3-4774-9f37-2e124e3d3491.png)
Trending và Popular Phim
![image](https://user-images.githubusercontent.com/95953901/235669813-5bc1a761-ea97-44a6-bf7d-44737ecb6312.png)
Trang TV shows
Trang TV shows hiển thị danh sách các TV show đang hot nhất. Ở trang này có thể chọn thể loại phim Các phim đặc biệt . Bạn có thể chọn xem chi tiết từng TV show bằng cách bấm vào tên của TV show đó.
![image](https://user-images.githubusercontent.com/95953901/235669975-0d47ef1b-cb0d-4a0c-bdb2-4b1614a0c0c6.png)
Trang chi tiết phim
Trang chi tiết phim hiển thị thông tin chi tiết về một bộ phim cụ thể, bao gồm cả trailer, đánh giá, diễn viên và nội dung tóm tắt.
![image](https://user-images.githubusercontent.com/95953901/235670246-1fc0a574-83ea-42eb-9ab1-52c935d71a3c.png)
Khi click Watch Trailer thì sẽ xuất hiện Trailer của phim 
![image](https://user-images.githubusercontent.com/95953901/235670713-b49b8670-1e73-4f20-9b19-2fa309a87be6.png)
Movix sử dụng TMDB Movie API để lấy thông tin về phim và TV show. Cần cung cấp khóa API của mình trong file .env trước khi sử dụng.
