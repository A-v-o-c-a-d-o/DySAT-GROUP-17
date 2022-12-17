model after train save at model_checkpoints package

run train.py to train the model

data used: Enron
    - time steps: 16

Phần cài đặt được tham khảo ở https://github.com/FeiGSSS/DySAT_pytorch và nhóm em đã thay đổi một số config để đánh giá hiệu quả mô hình với các cấu hình khác nhau.
    - train 24 epochs
    - learning rate: 0.01
    - drop rate: 0.5
    - negative weight: 1
    - weight decay: 0.0005
    - number head: 3 (tối ưu là 8)
    - batch size: 64