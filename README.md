# Time-Series-Forcasting
So sánh các thuật toán ARIMA, Auto ARIMA, đến Machine Learning (Random Forest, XGBoost) và Deep Learning (LSTM) trong việc dự báo giá chứng khoán.
Mục tiêu là khám phá, tối ưu độ chính xác và mở rộng khả năng ứng dụng trong các bối cảnh thực tế đó dự báo giá chứng khoán của Công ty Google.
--------
# Outline
  1. Tạo ARIMA (SARIMA) model để dự báo
  2. Dùng Auto ARIMA model
  3. Dùng Random Forest, XGBoost model
  4. Sử dụng Deeplearning (LSTM)
  5. Kết luận
-----
# Giới thiệu về Dataset
Dataset này chứa các thông tin giá giao dịch chứng khoán của Google. Bao gồm các feature:
- Date: Ngày giao dịch.
- Open: Giá mở cửa của cổ phiếu trong ngày.
- High: Giá cao nhất trong ngày.
- Low: Giá thấp nhất trong ngày.
- Close: Giá đóng cửa, thường dùng để đánh giá xu hướng thị trường.
- Volume: Khối lượng giao dịch, phản ánh mức độ hoạt động của cổ phiếu.
