# Deep_Voice

## Giới thiệu
Dự án Deep Voice là một hệ thống trí tuệ nhân tạo sử dụng Deep Learning để:
- Nhận diện cảm xúc từ giọng nói.
- Phân loại giới tính và vùng miền của người nói.
- Tạo giọng nói mới dựa trên đặc trưng của các giọng nói khác.

## Tính năng
- **Nhận diện cảm xúc:** Hệ thống có thể phân tích và nhận diện các cảm xúc như vui, buồn, giận dữ, trung tính, v.v.
- **Phân loại giới tính và vùng miền:** Xác định xem giọng nói thuộc về nam hay nữ, đồng thời nhận diện vùng miền dựa trên đặc điểm âm sắc.
- **Tạo giọng nói mới:** Mô phỏng giọng nói mới từ các đặc trưng giọng nói đầu vào.

## Công nghệ sử dụng
- **Ngôn ngữ lập trình:** Python
- **Thư viện chính:** TensorFlow, PyTorch, Librosa, NumPy, Pandas, Matplotlib
- **Mô hình học sâu:** CNN, RNN, Transformer-based models
- **Xử lý giọng nói:** MFCC, Spectrogram, WaveNet

## Cài đặt
1. Clone repository:
   ```bash
    https://github.com/Huynhnhu169/Deep_Voice.git
   cd deep-voice
   ```
2. Cài đặt các thư viện cần thiết:
   ```bash
   pip install -r requirements.txt
   ```
3. Chạy thử nghiệm mô hình:
   ```bash
   python web.py
   ```

## Cách sử dụng
- Chạy lệnh: 
  ```bash
  python web.py 
  ```
- Màn hình sẽ hiển thị giao diện.
- Người dùng có thể tải file âm thanh muốn nhận diện hoặc ghi âm trực tiếp.
- Sau khi chọn nút Nhận diện màn hình sẽ trả về kết quả

## License
Dự án này được phát hành dưới giấy phép MIT.
