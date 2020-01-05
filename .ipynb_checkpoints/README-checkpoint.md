# Data-science-project

## Đồ án cuối kỳ môn Khoa học Dữ liệu

#### Giảng viên: thầy Trần Trung Kiên

### Đề tài: Dự đoán giá xe ô tô

---

## 1. Thông tin nhóm 

| Tên  |MSSV|email|
|-|:-:|-:|
| Hồng Thanh Hoài |1612855|hthoai1006@gmail.com|
| Huỳnh Minh Huấn |1612858|minhhuanhuynh289@gmail.com|

## 2. Thông tin đồ án (giữa kỳ)

#### Giới thiệu đồ án

* Dự đoán giá xe hơi dựa trên các thuộc tính của xe.
* Lợi ích (mục đích): đem lại thông tin hữu ích cho người mua xe, muốn tìm hiểu về xe.

#### Nguồn dữ liệu

* Website chính: <https://www.cars-data.com/en/>
* Hình ảnh trang web:

![image text](./resource/imgs/01.png "Logo Title Text 1")

#### Thu thập dữ liệu

* Dữ liệu thu thập trên trang này hợp pháp (nhóm đã check trước khi crawl dữ liệu)
![image](./resource/imgs/02.png)
* Kiểm tra trên một trang cần crawl:
![image](./resource/imgs/03.png)
* Dữ liệu bao gồm hơn 80000 dòng
* Có 34 cột (chưa tiền xử lý dữ liệu):
  * url: link trên web của xe.
  * name: tên của xe.
  * 'model': mẫu xe.
  * 'brand': thương hiệu xe.
  * 'price:' giá xe (**)
  * 'eLabel':  energy label.
  * 'bodyType': loại thân xe ()
  * 'length': chiều dài.
  * 'height': chiều cao.
  * 'width': chiều rộng.
  * 'weight': trọng lượng xe.
  * 'weightTotal': tổng trọng lượng.
  * 'emissionsCO2': lượng khí thải.
  * 'modelDate': năm sản xuất xủa mẫu.
  * 'fuelType': loại nhiên liệu
  * 'numberOfAxles': số trục.
  * 'numberOfDoors': số lượng cửa.
  * 'numberOfForwardGears': số gears.
  * 'seatingCapacity’: không gian chỗ ngồi (số ghế).
  * 'vehicleTransmission'
  * 'cargoVolume': dung lượng hành hóa.
  * 'roofLoad': tải trọng roof.
  * 'accelerationTime': thời gian tăng tốc.
  * 'driveWheelConfiguration': cấu hình wheel.
  * 'fuelCapacity': dung tích nhiên liệu.
  * 'fuelConsumption': độ tiêu hao nhiên liệu.
  * 'speed': tốc độ.
  * 'payload'
  * 'trailerWeight': khối lượng móc nối.
  * 'vEengineType': Loại máy
  * 'vEfuelType': loại nhiên liệu
  * 'vEengineDisplacement':
  * 'vEenginePower': công suất
  * 'torque’: mô men-xoắn

#### Các vấn đề sau khi thu thập dữ liệu

* Dữ liệu còn chứa các giá trị thiếu.
* Một số cột có thể không mang lại ý nghĩa trong việc dự đoán (nhóm cần cân nhắc để chọn các features phù hợp cho bài toán).
* Phần lớn các dữ liệu crawl về chưa đúng định dạng. Cần tiền xử lý dữ liệu.

---

## 3. Chi tiết đồ án (cuối kỳ)

### 3.1 Tiền xử lý dữ liệu

...

### 3.2 Mô hình hóa

...

### 3.3 Train model

...

### 3.4 Output

...