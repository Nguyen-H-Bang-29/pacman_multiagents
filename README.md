# Pacman Multiagents
## Đề bài: http://ai.berkeley.edu/multiagent.html
- Điểm số: 19/25
## Q1: Reflex Agent
- Hàm đánh giá dựa trên: 
 + Khoảng cách với ghost gần nhất.
 + Khoảng cách với food gần nhất.
 + Điểm.
## Q2: Minimax
- Kiểm tra state có đang là state lá hay không.
 + Nếu đúng trả về hàm tự đánh giá.
 + Nếu sai tìm các successor state theo action, trả về max của chúng nếu agent là pacman, min nếu là ghost.
## Q3: Alpha-Beta Pruning
- Tương tự Q2.
- Thêm các điều kiện tỉa nhánh tại một nút khi alpha > max hoặc beta < min.
## Q4: Expectimax
- Tương tự Q1.
- Thay vì lựa chọn nhánh min tối ưu, sử dụng nhánh đầu tiên tìm được.
## Q5: Evaluation Function
- Chưa cài đặt
