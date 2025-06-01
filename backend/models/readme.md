| Tên bảng cha | Tên bảng con  | Quan hệ |                 Ghi chú                  |
| :----------: | :-----------: | :-----: | :--------------------------------------: |
|    users     |    orders     |  1 – N  |         Một người đặt nhiều đơn          |
|    orders    | order_details |  1 – N  |         Một đơn chứa nhiều sách          |
|    books     | order_details |  1 – N  |       Một sách nằm trong nhiều đơn       |
|  categories  |     books     |  1 – N  |       Một danh mục chứa nhiều sách       |
|    users     |    reviews    |  1 – N  |         Người dùng đánh giá sách         |
|    books     |    reviews    |  1 – N  |        Mỗi sách có nhiều đánh giá        |
|    users     |     carts     | 1-N,1-1 | Một người dùng có một hay nhiều giỏ hàng |
|    carts     |  cart_items   |  1 – N  |         Một giỏ chứa nhiều sách          |
|    users     |   wishlists   |  1 – N  |      Người dùng có nhiều yêu thích       |
|    books     |   wishlists   |  1 – N  |   Sách được yêu thích bởi nhiều người    |
|    orders    |   payments    |  1 – 1  |        Mỗi đơn có một thanh toán         |
