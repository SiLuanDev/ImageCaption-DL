# ImageCaption-DL
Em tìm hiểu về vấn đề DeepLearning đối với nhận
dạng hình ảnh và trích xuất được văn bản mô tả đúng nhất với hình ảnh với mục đích có
thể ứng dụng thực tiễn như tạo các ứng dụng giúp những người lớn tuổi, những người
khiếm khuyết có thể nhận biết được các cảnh vật xung quanh, chỉ dẫn đường đi hoặc các
công cụ hỗ trợ có thể tìm kiếm được hình ảnh dựa vào một đoạn caption, gán nhãn cho số
lượng ảnh lớn . Để giải quyết vấn đề này, Em đã sử dụng bộ dữ liệu Flickr8k Dataset.
Đầu vào của bài toán là ảnh,caption. Đầu ra sẽ là những từ tiếp theo trong dataset.kết hợp mô hình
CNN (Convolutional Neural networks) và LSTM (Long short term memory) và GLOVE model để Word embedding.
