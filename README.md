# Mạch nút nhấn MKE-M02 Button RGYBW Module

## Giới thiệu
MKE-M02 Button RGYBW Module là mạch nút nhấn đơn sử dụng nút nhấn kích thước lớn, giúp thao tác dễ dàng và trực quan. Nút nhấn thuộc loại nhấn nhả (tact switch), thường được dùng để kích tín hiệu điều khiển trong các mạch điện tử.

Mạch nút nhấn MKE-M02 Button RGYBW Module đặc biệt phù hợp cho các ứng dụng điều khiển đơn giản, mô hình robot, dự án STEM, đồ án học tập và thực hành điện tử. Nút nhấn được trang bị nắp chụp nhiều màu sắc giúp dễ dàng phân biệt trong quá trình lắp đặt và sử dụng với 5 phiên bản màu gồm: Đỏ, Xanh lá, Vàng, Xanh dương và Trắng, đáp ứng đa dạng nhu cầu ứng dụng.

Mạch nút nhấn MKE-M02 Button RGYBW Module hỗ trợ điện áp giao tiếp 3.3V và 5VDC, cho phép kết nối trực tiếp và an toàn với hầu hết các bo mạch điều khiển phổ biến hiện nay như Arduino, Raspberry Pi, Jetson Nano, Micro:bit và nhiều nền tảng khác. Sản phẩm đi kèm cáp kết nối 3P XH2.54 – Dupont, đảm bảo kết nối chắc chắn, ổn định và thuận tiện khi sử dụng.

## Thông số kỹ thuật
- Điện áp cấp nguồn: 5VDC
- Chuẩn tín hiệu điều khiển: Digital
- Điện áp giao tiếp: TTL 3.3/5VDC
- Màu sắc nút nhấn: Đỏ, Xanh lá, Vàng, Xanh dương, Trắng
- Loại nút nhấn: nhấn nhả (tact switch)
- Khả năng tương thích:
  - Arduino
  - Raspberry Pi
  - Jetson Nano
  - Micro:bit
  - Và các board điều khiển 3.3/5VDC khác
- Thiết kế mạch:
  - Ổn định, chống nhiễu
  - Phù hợp cho ứng dụng học tập và thực tế
- Đi kèm cáp kết nối: 3P XH2.54–Dupont

## Các chân tín hiệu
<table><thead>
  <tr>
    <th>MKE-M02</th>
    <th>Ghi chú</th>
  </tr></thead>
<tbody>
  <tr>
    <td>-</td>
    <td>Chân cấp nguồn âm 0VDC</td>
  </tr>
  <tr>
    <td>+</td>
    <td>Chân cấp nguồn dương 5VDC</td>
  </tr>
  <tr>
    <td>S</td>
    <td>Chân tín hiệu Digital Out</td>
  </tr>
</tbody>
</table>

## Hướng dẫn sử dụng
### Hướng dẫn kết nối
- Cấp nguồn 5VDC cho mạch qua hai chân - và +.
- Nhận tín hiệu từ nút nhấn qua chân tín hiệu S (SIGNAL).
<table><thead>
  <tr>
    <th>SIG (Digital Out)</th>
    <th>Trạng thái</th>
  </tr></thead>
<tbody>
  <tr>
    <td>TTL HIGH (3.3VDC)</td>
    <td>Hoạt động (On)</td>
  </tr>
  <tr>
    <td>TTL LOW (0VDC)</td>
    <td>Không hoạt động (Off)</td>
  </tr>
</tbody>
</table>

### Hướng dẫn sử dụng với Arduino Uno / Vietduino Uno / ESP32
- Trong **Tools / Library Manager**, tìm và cài đặt bộ thư viện tổng hợp **"MKE_ONE" by MakerEdu.vn**
- Mở chương trình mẫu tại **File / Examples / MKE_ONE / Module / MKE_M02_Button**
- Cấu hình board mạch tương ứng là **Arduino Uno / ESP32**, chọn đúng cổng **COM Port** của mạch và nhấn **Upload** để nạp chương trình.
- Cấp nguồn 5VDC cho mạch, kết nối chân S (SIGNAL) của module với chân điều khiển được khai báo trong chương trình.
- Xem kết quả mạch hoạt động theo chương trình đã nạp.

### Hướng dẫn lập trình với Micro:bit (kéo thả khối)

- Khởi động [Microsoft MakeCode](https://makecode.microbit.org/) và **Import** chương trình theo đường link sau: `https://github.com/makereduvn/mke_m02_button_microbit/`
- Kết nối mạch Micro:bit và **Download** chương trình.
- Cấp nguồn 5VDC cho mạch, kết nối chân S (SIGNAL) của module với chân điều khiển được khai báo trong chương trình.
- Xem kết quả mạch hoạt động theo chương trình đã nạp.

Nếu bắt đầu tự án mới cần cài đặt Extension **MKE_ONE_MICROBIT** trên [Microsoft MakeCode](https://makecode.microbit.org/) theo [hướng dẫn tại đây](https://github.com/makereduvn/MKE_ONE_MICROBIT). Sau khi cài đặt thành công, các khối lệnh của Extension **MKE_ONE_MICROBIT** sẽ xuất hiện trong danh sách block và sẵn sàng để sử dụng.

## Kích thước sản phẩm
![MKE-M02 Button](/extras/MKE-M02_1.jpg)

## Hình ảnh sản phẩm
![MKE-M02 Button](/extras/MKE-M02_2.png)
![MKE-M02 Button](/extras/MKE-M02_3.png)

## Miễn trừ trách nhiệm
Sản phẩm này là bo mạch phát triển được thiết kế phục vụ cho mục đích nghiên cứu, thử nghiệm và học tập, không phải là một thiết bị hoàn chỉnh. Trong trường hợp người dùng kết hợp mạch này với các linh kiện, thiết bị hoặc phần mềm khác để tạo thành một hệ thống hoặc sản phẩm hoàn chỉnh, mọi chức năng và tính phù hợp của sản phẩm sau cùng đều thuộc trách nhiệm của người dùng.
