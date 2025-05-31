# khái quát về mvc

mô hình về mvc ,là viết tắt của model view và controller, là mô hình gồm 3 lớp : model, view, controller,...

## model, view, controller

model : lớp này chịu trách nhiệm quản lý dữ liệu: giao tiếp với csdl, chịu trách nhiệm lưu trữ hoặ truy vấn dữ liệu

view : lớp này chính là giao diện của ứng dụng, chịu trách nhiệm biểu diễn dữ liệu của ứng fujng thành các dạng nhìn thấy được

controller: lớp này đóng vai trò quản lý và điều phối hoạt động của ứng dụng. Tầng này sẽ nhận request từ client, diều phối các model và view để có thể cho ra các output thích hợp và trả kết quả về cho người dùng.

![file-architect-client-server](https://topdev.vn/blog/wp-content/uploads/2020/08/mvc-trong-php.png)
