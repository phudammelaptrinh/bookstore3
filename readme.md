# khái quát về mvc

mô hình về mvc ,là viết tắt của model view và controller, là mô hình gồm 3 lớp : model, view, controller,...

## model, view, controller

model : lớp này chịu trách nhiệm quản lý dữ liệu: giao tiếp với csdl, chịu trách nhiệm lưu trữ hoặ truy vấn dữ liệu

view : lớp này chính là giao diện của ứng dụng, chịu trách nhiệm biểu diễn dữ liệu của ứng fujng thành các dạng nhìn thấy được

controller: lớp này đóng vai trò quản lý và điều phối hoạt động của ứng dụng. Tầng này sẽ nhận request từ client, diều phối các model và view để có thể cho ra các output thích hợp và trả kết quả về cho người dùng.

![file-architect-client-server](https://topdev.vn/blog/wp-content/uploads/2020/08/mvc-trong-php.png)

## Cách viết

### a. Tầng controller:

- Đây là tầng điều phối của ứng dụng, nhận request từ client, phân tích request, gọi tầng Model để lấy dữ liệu và tầng View để tổ chức hiển thị dữ liệu.

![file-hinh-controller](https://topdev.vn/blog/wp-content/uploads/2020/08/mvc-php-3.png)

### b. Tầng model và các lớp thực thể(Entity class):

-Nhiệm vụ chính của tầng này là việc thao tác với cơ sở dữ liệu để lưu trữ cũng như truy vấn dữ liệu. Các thao tác với CSDL phải được đặt hết ở trong tầng này , nó sẽ chứa các thao tác cơ bản để truy vấn CSDL như đọc, thêm, xóa, sửa.

#### Bắt đầu với tầng entity:

![file-hinh-entitty](https://topdev.vn/blog/wp-content/uploads/2020/08/mvc-php-4.png)

#### Bắt đầu với tầng model :

![file-hinh-entitty](https://topdev.vn/blog/wp-content/uploads/2020/08/mvc-php-5.png)
