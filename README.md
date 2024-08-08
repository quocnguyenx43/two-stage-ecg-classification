
# Xử lý và phân loại các loại bệnh về tim dựa

1. Bộ dữ liệu
Được lấy từ https://www.kaggle.com/datasets/shayanfazeli/heartbeat

Bao gồm 2 bộ dataset MIT-BIH Arrhythmia Dataset và The PTB
Diagnostic ECG Database.

Cả 2 bộ dataset đều có số lượng thuộc tính là 188 (tương ứng với 187 điểm thuộc điện tâm đồ, và 1 thuộc tính nhãn)

2. Giải thuật
Nhóm thực hiện ý tưởng chuyên biệt hóa từng công đoạn nhằm đối phó với việc mất cân bằng nhãn trong các bộ dữ liệu (1 mô hình dùng để dự đoán có bệnh hay không, 1 mô hình chuyên dự đoán các loại bệnh).

Bằng việc thử nghiệm các mô hình học máy và học sâu, nhóm tiến hành so sánh và chọn lọc ra các mô hình đạt hiệu quả cao. Và tiến hành so sánh với các mô hình base-line và đưa ra các kết luận.

3. Các mô hình thử nghiệm
MLP, LSTM, RNN, Logistic Regression, Naive Bayes, KNN, Decision Tree, Random Forest.

4. Hướng dẫn chạy code
Tất cả tiến hành của nhóm được ghi đầy đủ trong file DS312_Y_khoa_nhom5.ipynb

Mở file DS312_Y_khoa_nhom5.ipynb bằng Jupyter Notebook hoặc Google Colaboratory, và tiến hành chạy lần lượt các cell code.

Với việc huấn luyện các mô hình, có thể kết quả sẽ khác so với trong file báo cáo, vì việc phân tách dữ liệu cũng như xáo trộn ngẫu nhiên sẽ không giống nhau. Tuy nhiên, việc đạt được kết quả để đưa ra được kết luận giống như báo cáo là điều sẽ đạt được.

Note: Có thể kiểm tra kết quả của lần cuối nhóm thực hiện bằng output được lưu sẵn trong file notebook"# two-stage-ecg-classification" 
"# two-stage-ecg-classification" 
