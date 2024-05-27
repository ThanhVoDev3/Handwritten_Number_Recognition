**Mô hình CNN cho MNIST:**
Mô hình CNN được xây dựng với các lớp Conv2D và MaxPooling2D để trích xuất đặc trưng từ hình ảnh.
Sau đó, các đặc trưng này được làm phẳng và đưa vào một mạng neural network dày đặc (Dense) để phân loại chữ số.
Mô hình được huấn luyện với dữ liệu MNIST, bao gồm 60,000 hình ảnh huấn luyện và 10,000 hình ảnh kiểm tra.

**Đánh giá mô hình:**
Mô hình đạt được độ chính xác xấp xỉ 99% trên tập dữ liệu kiểm tra, cho thấy khả năng tổng quát hóa tốt của mô hình.


**Dự đoán trên ảnh chữ số viết tay:**
Mô hình cũng có thể dự đoán chữ số từ các hình ảnh chữ số viết tay mới không thuộc tập dữ liệu MNIST.
Hàm predict_handwritten_digit cho phép dự đoán chữ số từ bất kỳ hình ảnh chữ số nào.
