
# Snake_SS004.K2.7
Project code trò chơi con rắn 
![Hình ảnh ingame](https://github.com/Thanh-Hung-dev/Snake_SS004.K2.7/blob/master/gameplay.png)
## Luật chơi
- Dùng các phím a, w, s, d để điều khiển
- Rắn có thể đi ngược lại với hướng đang đi nếu có chiều dài là 1 hoặc 2. Khi dài hơn 2, sẽ tính là thua nếu đi ngược lại
- Tính là thua nếu rắn va vào các bức tường hoặc chính nó
- Khi thua có thể chọn thoát game hoặc chơi lại để ráng được điểm cao hơn
## Hệ thống điểm
- **Điểm:**  Mỗi lần ăn 1 hoa quả được tăng 1 điểm
- **Điểm cao:** Điểm cao nhất trong lần chơi hiện tại
## Thay đổi tốc độ trò chơi
Có thể thay đổi tốc độ rắn di chuyển bằng cách thay biến `thoigian` nằm trên dòng **158** trong file ``snake.cpp``.  Tốc độ mặc định là 200, càng thấp rắn càng di chuyển nhanh và ngược lại.
