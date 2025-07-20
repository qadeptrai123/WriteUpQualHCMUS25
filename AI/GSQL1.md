# GSQL1

Sau khi tải Source về thì phân tích thấy:

1. Người dùng gửi tin nhắn cho bot.
2. Bot nhận và xem đem đó ghép vào câu prompt và gửi cho Gemini Flash Lite. ![alt text](image.png)

3. Sau đó lấy câu trả lời mà Gemini trả về thực hiện SQL query.
4. Trả kết quả đó cho người dùng qua tin nhắn.

Ngoài ra, vào file `database.go` ta sẽ thấy ![alt text](image-1.png)

Như vậy cần phải nhắn nội dung sao cho Gemini đổi ý, phá lệ mà thực hiện `SELECT data FROM flag`.

Đây là câu prompt thành công:

![alt text](image-2.png)