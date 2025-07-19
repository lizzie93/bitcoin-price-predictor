# bitcoin-price-predictor
Bitcoin Price Prediction Using LSTM and Gradio UI/Dự đoán giá Bitcoin bằng LSTM và Gradio UI
# 💰 Bitcoin Price Predictor

Dự đoán giá Bitcoin ngày tiếp theo bằng mô hình LSTM (Long Short-Term Memory) trên dữ liệu chuỗi thời gian.

## 📌 Tính năng
- Lấy dữ liệu 30 ngày gần nhất từ [CoinGecko API](https://www.coingecko.com/en/api)
- Dự đoán giá Bitcoin cho ngày tiếp theo bằng LSTM
- Ghi kết quả (giá thực và dự đoán) vào Google Sheets
- Hiển thị kết quả bằng giao diện Gradio đẹp và dễ sử dụng

## 🛠 Công nghệ sử dụng
- Python + TensorFlow / Keras
- Google Colab
- Gradio UI
- CoinGecko API
- Google Sheets API

## 📊 Demo kết quả

- 🔗 **Gradio UI demo**:
- 📄 **Google Sheet Log**: [BTC Prediction Log](https://docs.google.com/spreadsheets/d/1DyunpedkCQ0NZhUf2Ecr3bVbigbK3-AXrYPwQv8xgfE/edit#gid=0)

## 📁 File chính
- `BTC_Predictor_Gradio_Full.ipynb`: Notebook chứa toàn bộ pipeline từ dữ liệu → huấn luyện → dự đoán → ghi Google Sheets → Gradio giao diện





