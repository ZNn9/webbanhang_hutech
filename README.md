
# 🛒 Web Bán Hàng HUTECH - ASP.NET Core MVC

Đây là một dự án website bán hàng đơn giản được xây dựng bằng **ASP.NET Core MVC**, sử dụng mô hình **MVC** và **Entity Framework Core**. Dự án bao gồm 2 phần chính: **trang khách hàng** và **trang quản trị (Admin)**.

---

## 🚀 Công Nghệ Sử Dụng

- ✅ ASP.NET Core MVC (.NET Core)
- ✅ C# (Ngôn ngữ lập trình chính)
- ✅ Entity Framework Core (ORM)
- ✅ SQL Server (Cơ sở dữ liệu)
- ✅ Razor View Engine (Giao diện động)
- ✅ Bootstrap 4 (Giao diện responsive)
- ✅ jQuery (Hỗ trợ Ajax, thao tác DOM)
- ✅ Font Awesome (Icon đẹp)
- ✅ Session (Lưu giỏ hàng)
- ✅ Areas (Tách biệt khu vực Admin)

---

## 🔧 Cài Đặt & Chạy Dự Án

1. Clone repo:
   ```bash
   git clone https://github.com/ZNn9/webbanhang_hutech.git
   ```

2. Mở bằng Visual Studio.

3. Cập nhật chuỗi kết nối CSDL trong `appsettings.json`:
   ```json
   "ConnectionStrings": {
     "DefaultConnection": "Server=.;Database=WebBanHang;Trusted_Connection=True;"
   }
   ```

4. Khôi phục database từ file `SQLWebBanHang_HIEP.sql`.

5. Build & Run (F5).

---

## 🌟 Tính Năng Chi Tiết & Công Nghệ Sử Dụng

| Tính Năng                             | Mô Tả                                                                 | Công Nghệ / Ghi chú |
|--------------------------------------|-----------------------------------------------------------------------|---------------------|
| **Trang chủ**                        | Hiển thị danh sách sản phẩm mới nhất                                 | Razor View, Bootstrap |
| **Phân trang sản phẩm**              | Hiển thị nhiều trang sản phẩm                                         | LINQ (Skip, Take), Razor |
| **Tìm kiếm sản phẩm**                | Tìm theo tên sản phẩm                                                 | LINQ, GET Query     |
| **Xem chi tiết sản phẩm**           | Hiển thị thông tin sản phẩm cụ thể                                    | EF Core             |
| **Giỏ hàng**                         | Thêm/xóa sản phẩm, tính tổng tiền                                     | Session, Razor View |
| **Đặt hàng**                         | Lưu đơn hàng và chi tiết vào DB                                       | EF Core             |
| **Đăng ký / Đăng nhập**              | Người dùng tạo tài khoản và đăng nhập                                 | Tự viết, dùng Session |
| **Đăng xuất**                        | Xóa session đăng nhập                                                 | Session             |
| **Quản trị sản phẩm (Admin)**        | CRUD sản phẩm, upload ảnh                                             | EF Core, Razor View |
| **Quản lý loại sản phẩm (Admin)**    | CRUD danh mục                                                         | EF Core             |
| **Quản lý đơn hàng (Admin)**         | Xem đơn hàng, cập nhật trạng thái                                     | EF Core             |
| **Quản lý người dùng (Admin)**       | Xem, chỉnh sửa, xóa tài khoản                                         | EF Core             |
| **Dashboard thống kê (Admin)**       | Tổng số đơn hàng, người dùng, sản phẩm                                | EF Core, Razor View |
| **Upload ảnh sản phẩm**              | Lưu ảnh vào thư mục `wwwroot/images`                                  | Form HTML, File upload |
| **Phân quyền (thủ công)**            | Phân biệt Admin / Khách hàng                                          | Session, điều kiện `if` |
| **Responsive giao diện**            | Hỗ trợ hiển thị tốt trên nhiều thiết bị                               | Bootstrap           |

## 💡 Ghi Chú

- Đây là dự án đồ án sinh viên, chủ yếu phục vụ học tập.
- Có thể nâng cấp bảo mật, thêm thanh toán online, và chuẩn hóa kiến trúc code hơn nữa.

---
