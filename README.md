# NER_POSTagging
Xây dựng mô hình Hidden Markov model (HMM) cho bài toán NER cho Tiếng anh, và  POS Tagging Tiếng Việt.

1. Khảo sát tập dữ liệu NER.csv xây dựng tập vocab, và set các tags

2. Tách các câu train và test trong tập dữ liệu NER.csv

4. Xây dựng mô hình HMM để tính probability cho các tags với một câu cho trước

5. Xử dụng thuật toán Viterbi để decode dự đoán named entities cho một câu Tiếng Anh cho trước

6. Đánh giá accuracy với tập test

7. Đọc mô tả dữ liệu POS Tagging cho Tiếng Việt: Thon tin nhan tu loai-v2.pdf 

8. Lặp lại bước 1-6 để xây dựng mô hình POS tagging cho bài toán Tiếng Việt với tập dữ liệu: vi_train.txt,  vi_test.txt 
