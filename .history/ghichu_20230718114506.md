/* dự án Project 03 này khác 2 dự án trước ở 3 điểm
- sử dụng thẻ sematic HTML5 hợp lý hơn
- sử dụng cấu trúc BEM đặt tên class hợp lý hơn
- sử dụng Grid_layout */

/* span là thẻ inline nếu muốn nó hđ thì gắn display: inline-block */

--> có tiêu đề (heading) thì dùng thẻ section

.work-item:hover {
    transform: translateY(-16px);
    border-color: #2e80ce;
} chú ý trong phần work

.members-item__thumb {
    display: block;
} chú ý vì thẻ img là inline khi gắn hình vào dư ra 1 khoảng nhỏ cách fix
là cho nó thuộc tính display: block sẽ hết

.members-item:hover .members-item__thumb {
    transform: scale(1.2);
} phóng to hình khi hover vào

border-top: none; (làm ẩn đi phần viền top)

THẺ CON sẽ ăn theo chiều rộng của THẺ CHA nên THẺ CHA có chiều rộng rồi thì THẺ CON chỉ 
cần ghi width: 100% là lấy theo chiều rộng của THẺ CHA