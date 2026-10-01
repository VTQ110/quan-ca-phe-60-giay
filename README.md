# Quán Cà Phê 60 Giây

Game arcade pha cà phê chơi trên trình duyệt điện thoại. Bạn giúp Minh giữ lại quán cà phê vỉa hè của bà Tư bằng cách pha đúng món, thật nhanh, trong mỗi ca 60 giây.

## Cách chơi

1. Khách hiện tên món trong bong bóng thoại.
2. Chạm các nguyên liệu dưới kệ theo đúng thứ tự công thức.
3. Chạm vào khách để giao ly.
4. Giao nhanh khi thanh kiên nhẫn còn xanh để được tip. Khách bỏ đi thì mất 1 sao; mất 3 sao là đóng quán sớm.

## Nội dung bản thử

- 3 ngày, mục tiêu doanh thu 200.000đ → 250.000đ → 320.000đ
- 5 món: Đen đá, Nâu đá, Bạc xỉu, Trà đá, Cà phê muối
- 3 loại khách: Sinh viên, Dân văn phòng, Shipper
- Combo 6 ly đúng liên tiếp được nhân đôi tip
- Tiến trình lưu trên trình duyệt (localStorage)

## Chạy trên máy

Game là một file `index.html` tĩnh, không cần cài đặt. Mở trực tiếp file trong trình duyệt, hoặc:

```bash
python3 -m http.server 8000
```

rồi vào http://localhost:8000.

## Deploy

Repo dùng GitHub Pages, phục vụ trực tiếp từ nhánh `main`, thư mục gốc.
