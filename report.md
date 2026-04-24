# Bao cao ngan - Phuong an CPU thay the

1. Trong phuong an CPU fallback, mo hinh LightGBM tren instance r5.2xlarge co thoi gian load du lieu 1.833 giay va thoi gian huan luyen 11.641 giay.
2. Ket qua AUC-ROC dat 0.8931, cho thay mo hinh co kha nang phan biet tuong doi tot giua giao dich binh thuong va gian lan.
3. Accuracy dat 0.9989, tuy nhien do du lieu mat can bang nen cac chi so F1, Precision, Recall duoc uu tien de danh gia toan dien hon.
4. F1-score dat 0.6970, Precision 0.6900 va Recall 0.7041, the hien hieu nang phat hien gian lan o muc kha tot cho bai toan thuc te.
5. Toc do suy luan rat nhanh voi do tre 1 mau khoang 0.001545 giay va thong luong khoang 52,046.78 mau moi giay cho batch 1000 mau.
6. Su dung CPU thay vi GPU do tai khoan khong duoc duyet quota GPU trong thoi gian lam lab, nen khong the trien khai g4dn.xlarge theo ke hoach ban dau.
7. Du khong dung GPU, phuong an CPU van hoan thanh day du quy trinh IaC, training, inference va kiem tra chi phi theo dung yeu cau bai lab.
8. Thoi gian su dung may ao thuc te khoang 2h (do quen destroy), tong chi phi la 1.33$