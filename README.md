- Kỹ thuật Image stitching (ghép ảnh) là quá trình kết hợp nhiều ảnh nhỏ thành một ảnh lớn và có thể nhìn thấy được toàn bộ khung cảnh hoặc vật thể mà ảnh gốc không thể bao phủ được
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2c/Alcatraz03182006.jpg/1275px-Alcatraz03182006.jpg">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a0/Rochester_NY.jpg/525px-Rochester_NY.jpg">

- Các bước chính của kỹ thuật Image stitching bao gồm:
  - Tìm điểm chung giữa các ảnh: Đầu tiên, các điểm chung giữa các ảnh cần được tìm thấy, đó là các điểm trùng nhau giữa hai ảnh liên tiếp, nơi mà các ảnh sẽ được ghép lại với nhau. Các điểm chung này có thể được tìm bằng cách sử dụng các thuật toán như SIFT (Scale-Invariant Feature Transform) hoặc SURF (Speeded Up Robust Feature).
  - Tính toán ma trận chuyển đổi: Sau khi tìm thấy các điểm chung, các ma trận chuyển đổi cần được tính toán để đưa các ảnh về cùng một hệ tọa độ. Các ma trận chuyển đổi này có thể được tính bằng cách sử dụng các thuật toán như RANSAC (Random Sample Consensus) hoặc homography.
  - Ghép ảnh: Cuối cùng, các ảnh đã được chuyển đổi được ghép lại với nhau để tạo thành một ảnh lớn. Các ảnh này có thể được ghép lại bằng cách ghép theo chiều ngang hoặc ghép theo chiều dọc.
 
- Tài liệu tham khảo: https://viblo.asia/p/image-stitching-thuat-toan-dang-sau-cong-nghe-anh-panorama-LzD5dee4KjY
