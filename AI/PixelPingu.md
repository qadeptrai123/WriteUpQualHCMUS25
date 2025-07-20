# PixelPingu

Bài này ta cần vẽ các bức ảnh sao cho 2 models AI là ShuffleNet và RegNet nhận diện ra được King Penguin. Có 4 điều kiện tương ứng với 4 part của flag:
- Cả 2 đều nhận diện ra sai
- Cả 2 đều nhận diện ra đúng
- ShuffleNet đúng và RegNet sai
- ShuffleNet sai và RegNet đúng

Vẽ rất tốn thời gian nên mình lấy Dataset King Penguin từ https://images.cv/dataset/king-penguin-image-classification-dataset. Sau đó chạy script qua từng hình resize lại 128x128, áp dụng thử các phép biến đổi như flip, rotate, tăng sáng, giảm sáng, ... và gửi cho Server.

Đợi tới khi ra đủ 4 phần flag thì mình dừng.