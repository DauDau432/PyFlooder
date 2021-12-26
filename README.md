# PyFlooder
Một kịch bản Python tạo ra lũ HTTP có thể ngăn chặn một trang web bình thường trong 10s
# Làm thế nào nó hoạt động ?
Nó tạo ra một số lượng yêu cầu GET ngẫu nhiên có thể định cấu hình và gửi chúng đến mục tiêu
# Cài đặt
Yêu cầu python3
```
apt install python3
```
Tải kho lưu trữ về
```
git clone https://github.com/DauDau432/PyFlooder
```
Vào thư mục PyFlooder
```
cd PyFlooder
```
# Cách sử dụng
```
python3 pyflooder.py <Hostname> <Port> <Number_of_Attacks>
```
Trong đó
- `Hostname` địa chỉ web bị tấn công
- `Port` cổng muốn tấn công
- `Number_of_Attacks` số lượng các cuộc tấn công
