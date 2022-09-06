# ID3
Đây là code demo cho bài toán sư dụng treebase model
Nguồn tham khảo: https://machinelearningcoban.com/2018/01/14/id3/
Đề bài: một đội bóng đưa ra quyết định có tập hay không phụ thuộc vào 4 yếu tố. Cài đặt chương trình để dự đoán được quyết định của đội bóng đó.
Bảng dử liệu:
| id | outlook  | temperature | humidity |  wind  | play |
|----|----------|-------------|----------|--------|------|
|  1 | sunny    | hot         | high     | weak   | no   |
|  2 | sunny    | hot         | high     | strong | no   |
|  3 | overcast | hot         | high     | weak   | yes  |
|  4 | rainy    | mild        | high     | weak   | yes  |
|  5 | rainy    | cool        | normal   | weak   | yes  |
|  6 | rainy    | cool        | normal   | strong | no   |
|  7 | overcast | cool        | normal   | strong | yes  |
|  8 | sunny    | mild        | high     | weak   | no   |
|  9 | sunny    | cool        | normal   | weak   | yes  |
| 10 | rainy    | mild        | normal   | weak   | yes  |
| 11 | sunny    | mild        | normal   | strong | yes  |
| 12 | overcast | mild        | high     | strong | yes  |
| 13 | overcast | hot         | normal   | weak   | yes  |
| 14 | rainy    | mild        | high     | strong | no   |

Kết qủa chạy: ['no', 'no', 'yes', 'yes', 'yes', 'no', 'yes', 'no', 'yes', 'yes', 'yes', 'yes', 'yes', 'no']