# JSLOCK
---
## Thể Loại : RE ( frontend web )

## Câu hỏi : Trong khi Spid3r đang đột nhập nhà của mấy anh em web thì thấy có cái "tường nước" dưới đây, dù chỉ là phía frontend nhưng với bản tính Rờ E trỗi dậy trong máu thì có lẽ đây là 1 thử thách không thể cuốn hút hơn.

## Link : https://jslock1.bksec.vn

## Đề phòng link sập, đã có backup file html, js lại trong challenge : [Lock Chill](./Lock_chill)
---
### Trước hết, ta có thể xác định được file lock trong frontend như sau :

![](nen.png)

### Sau đó, chỉ cần giải pt sao cho **decodedPassword** và **correctPassword** bằng nhau là dc. Kết quả sẽ ra được pwd là 35253, nhập vào và ta sẽ có flag như sau :

![](flag.png)
