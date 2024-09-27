DotNetBookStore
Giới Thiệu
DotNetBookStore là một dự án cơ bản sử dụng ASP.NET Core để quản lý cửa hàng sách. Ứng dụng cho phép người dùng thực hiện các thao tác như hiển thị, thêm, cập nhật và xóa sách, đồng thời hỗ trợ tìm kiếm sách theo giá.

Tính Năng Chính
Quản Lý Sách: Quản lý thông tin sách bao gồm mã sách, tiêu đề, mô tả, số lượng, giá và hình ảnh.
Tìm Kiếm Sách: Tìm kiếm sách theo giá và các tiêu chí khác.
Quản Lý Danh Mục: Quản lý các danh mục sách như thể loại, tác giả.
Giao Diện Người Dùng: Sử dụng Bootstrap để xây dựng giao diện người dùng thân thiện và dễ sử dụng.
Công Nghệ Sử Dụng
ASP.NET Core MVC: Khung làm việc chính để xây dựng ứng dụng web theo mô hình MVC.
Entity Framework Core: Truy cập và thao tác dữ liệu với cơ sở dữ liệu.
SQL Server: Cơ sở dữ liệu sử dụng cho dự án.
Bootstrap: Tạo giao diện người dùng đẹp và linh hoạt.
Yêu Cầu Hệ Thống
.NET 5.0 hoặc mới hơn.
Visual Studio 2019 hoặc mới hơn.
SQL Server (local hoặc remote).
Hướng Dẫn Cài Đặt
Clone dự án:
bash
Sao chép mã
git clone https://github.com/huylebron/DotNetBookStore.git
Cấu hình kết nối cơ sở dữ liệu:
Mở file appsettings.json trong thư mục BulkyWeb.
Thay đổi chuỗi kết nối theo cấu hình SQL Server của bạn.
Khởi tạo cơ sở dữ liệu:
Mở Package Manager Console và chạy lệnh:
bash
Sao chép mã
update-database
Chạy dự án:
Chạy dự án bằng cách nhấn F5 hoặc Ctrl + F5 trong Visual Studio.
Cấu Trúc Dự Án
Bulky.DataAccess: Chứa các lớp truy cập dữ liệu và context của Entity Framework.
Bulky.Models: Chứa các lớp mô hình (model) đại diện cho các đối tượng dữ liệu trong dự án.
Bulky.Utility: Chứa các lớp và phương thức tiện ích dùng chung.
BulkyWeb: Ứng dụng web chính chứa các controller, view, và cấu hình.
BulkyWebRazor_Temp: Một dự án tạm thời chứa các thử nghiệm với Razor Pages.
Góp Ý và Phát Triển
Chúng tôi luôn chào đón các ý tưởng mới và đóng góp từ cộng đồng. Nếu bạn có ý tưởng cải tiến hoặc phát hiện lỗi, vui lòng tạo pull request hoặc mở issue mới trên GitHub.

License
Dự án này được cấp phép theo giấy phép MIT. Xem thêm tại file LICENSE.

Liên Hệ
Nếu có thắc mắc hoặc yêu cầu hỗ trợ, vui lòng liên hệ qua việc tạo issue trên GitHub hoặc gửi email cho quản trị viên dự án.

