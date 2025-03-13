# OpenCart Clone

OpenCart Clone là một dự án mã nguồn mở nhằm tạo ra một hệ thống quản lý cửa hàng trực tuyến tương tự như OpenCart. Dự án này cung cấp các tính năng cần thiết để quản lý sản phẩm, danh mục, đơn hàng, người dùng, và tích hợp các hệ thống thanh toán và giao hàng. Đây là một giải pháp hoàn chỉnh cho các doanh nghiệp muốn xây dựng và vận hành một cửa hàng trực tuyến hiệu quả.

## Mục tiêu dự án
Tạo một hệ thống quản lý cửa hàng trực tuyến tương tự như OpenCart với đầy đủ các tính năng cần thiết cho việc quản lý sản phẩm, danh mục, đơn hàng, người dùng, hệ thống thanh toán và giao hàng.

## Tính năng chính

1. **Quản lý Sản phẩm**:
   - Thêm, sửa, xóa sản phẩm.
   - Quản lý thông tin sản phẩm bao gồm tên, mô tả, giá cả, hình ảnh, và thuộc tính.
   - Quản lý số lượng tồn kho.
   - Hỗ trợ sản phẩm có nhiều thuộc tính và biến thể.

2. **Quản lý Danh mục**:
   - Thêm, sửa, xóa danh mục sản phẩm.
   - Quản lý danh mục cha và danh mục con.
   - Tìm kiếm và lọc danh mục.

3. **Quản lý Đơn hàng**:
   - Xem danh sách đơn hàng.
   - Cập nhật trạng thái đơn hàng (đã đặt, đang xử lý, hoàn thành, hủy bỏ).
   - Xem chi tiết đơn hàng bao gồm thông tin sản phẩm, số lượng, giá cả, và thông tin khách hàng.

4. **Hệ thống Thanh toán**:
   - Tích hợp các phương thức thanh toán phổ biến như PayPal, Stripe, thẻ tín dụng.
   - Quản lý thông tin thanh toán của khách hàng.
   - Xử lý và xác nhận thanh toán.

5. **Hệ thống Giao hàng**:
   - Tích hợp các dịch vụ giao hàng như FedEx, UPS, DHL.
   - Quản lý thông tin giao hàng.
   - Tính toán phí giao hàng dựa trên địa chỉ và trọng lượng đơn hàng.

6. **Quản lý Người dùng**:
   - Đăng ký và đăng nhập người dùng.
   - Quản lý thông tin cá nhân của người dùng.
   - Quản lý quyền và vai trò của người dùng (quản trị viên, nhân viên, khách hàng).

7. **Giao diện Người dùng**:
   - Giao diện quản trị viên thân thiện và dễ sử dụng.
   - Giao diện cửa hàng trực tuyến cho khách hàng.
   - Tìm kiếm và lọc sản phẩm.
   - Giỏ hàng và quản lý đơn hàng.

8. **Báo cáo và Thống kê**:
   - Báo cáo doanh thu theo ngày, tuần, tháng, năm.
   - Thống kê số lượng sản phẩm bán ra.
   - Báo cáo tình trạng tồn kho.

9. **SEO và Marketing**:
   - Tối ưu hóa SEO cho sản phẩm và danh mục.
   - Quản lý mã giảm giá và khuyến mãi.
   - Tích hợp với Google Analytics và các công cụ marketing khác.

10. **Tùy chỉnh và Mở rộng**:
    - Hỗ trợ đa ngôn ngữ và đa tiền tệ.
    - Tùy chỉnh giao diện và chức năng theo yêu cầu.
    - Cộng đồng và tài liệu hướng dẫn phong phú.

## Công nghệ và Công cụ

- **Ngôn ngữ lập trình**: PHP
- **Framework**: Laravel
- **Cơ sở dữ liệu**: MySQL
- **Giao diện người dùng**: HTML, CSS, JavaScript (Bootstrap)
- **Hệ thống thanh toán**: Stripe, PayPal
- **Hệ thống giao hàng**: FedEx, UPS, DHL

## Phân công công việc

1. **Thiết kế cơ sở dữ liệu**:
   - Tạo các bảng cần thiết cho quản lý sản phẩm, danh mục, đơn hàng, người dùng, v.v.

2. **Phát triển API**:
   - Xây dựng các API và logic nghiệp vụ cho hệ thống.

3. **Phát triển giao diện người dùng**:
   - Xây dựng giao diện người dùng với HTML, CSS, JavaScript.

4. **Tích hợp hệ thống thanh toán và giao hàng**:
   - Tích hợp các API của bên thứ ba cho các dịch vụ thanh toán và giao hàng.

5. **Kiểm thử và Triển khai**:
   - Thực hiện kiểm thử đơn vị, kiểm thử tích hợp và kiểm thử hệ thống.
   - Triển khai lên server và cấu hình môi trường sản xuất.

## Hướng dẫn cài đặt và sử dụng

### Yêu cầu

- PHP >= 7.4
- MySQL >= 5.7
- Composer
- Node.js

### Cài đặt

1. Clone repository này:
    ```bash
    git clone https://github.com/ericphan28/opencart-clone.git
    cd opencart-clone
    ```

2. Cài đặt các phụ thuộc:
    ```bash
    composer install
    npm install
    ```

3. Cấu hình môi trường:
    - Sao chép file `.env.example` thành `.env` và cập nhật các thông tin cấu hình cần thiết.

4. Chạy các migration và seed database:
    ```bash
    php artisan migrate --seed
    ```

5. Chạy ứng dụng:
    ```bash
    php artisan serve
    npm run dev
    ```

## Đóng góp

Chúng tôi hoan nghênh mọi đóng góp từ cộng đồng. Nếu bạn muốn đóng góp vào dự án, vui lòng fork repository này và gửi pull request.

## Giấy phép

Dự án này được cấp phép theo giấy phép MIT - xem file [LICENSE](LICENSE) để biết thêm chi tiết.