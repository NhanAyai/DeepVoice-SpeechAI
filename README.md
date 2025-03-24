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

## Bộ Data dùng để train model
- Data phân loại cảm xúc, giới tính
  ```bash
     https://www.kaggle.com/datasets/piyushagni5/berlin-database-of-emotional-speech-emodb
  ```
- Data phân loại vùng miền 
  ```bash
   https://www.kaggle.com/datasets/trnngci/vietnamese-speech-labeled-by-region
  ```
## Cài đặt
Clone repository:
   ```bash
    https://github.com/Huynhnhu169/Emotion_Recognition.git
   cd deep-voice
   ```

## Cách sử dụng
- Chạy lệnh: 
  ```bash
  ipython web_emotion_detection.ipynb 
  ```
- Màn hình sẽ hiển thị giao diện.
- Người dùng có thể tải file âm thanh muốn nhận diện hoặc ghi âm trực tiếp.
- Sau khi chọn nút Nhận diện màn hình sẽ trả về kết quả

## License
Dự án này được phát hành dưới giấy phép MIT.
