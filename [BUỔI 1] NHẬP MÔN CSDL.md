# [BUỔI 1] NHẬP MÔN CSDL
## Khái quát về CSDL

### 1.CSDL là gì ?
- **Cơ sở dữ liệu (Database)** là một tập hợp các dữ liệu có tổ chức liên quan đến nhau, thường được lưu trữ và truy cập điện tử từ hệ thống máy tính. Khi cơ sở dữ liệu phức tạp hơn, chúng thường được phát triển bằng cách sử dụng các kỹ thuật thiết kế và mô hình hóa chính thức.
- **Cơ sở dữ liệu được sử dụng để:**
    - Lưu trữ và quản lý lượng lớn dữ liệu có cấu trúc và không cấu trúc
    - Hỗ trợ phân tích dữ liệu
    - Đảm bảo tính toàn vẹn và bảo mật dữ liệu
    - Cho phép nhiều người dùng truy cập và cập nhật dữ liệu đồng thời
    - Tạo điều kiện cho việc kiểm soát truy cập và phân quyền người dùng
- **Cơ sở dữ liệu** cho phép người dùng nhập thông tin theo nhiều cách khác nhau, bao gồm thông qua giao diện người dùng từ các Database Management Systems, nhập liệu tự động từ các nguồn dữ liệu, thông qua API (Application Programming Interface) từ các ứng dụng và dịch vụ khác. Thông tin có thể được nhập dưới dạng bảng, danh sách, văn bản, hình ảnh, video hoặc bất kỳ định dạng nào phù hợp với nhu cầu cụ thể của người dùng.

- Sau đó, thông qua một phần mềm, người dùng có thể thao tác với dữ liệu theo ý muốn, tạo ra các mối quan hệ giữa các mảnh thông tin khác nhau. Phần mềm này thường được gọi là Database Management Systems, và nó cung cấp một loạt các công cụ và chức năng để thao tác, truy xuất, cập nhật và quản lý dữ liệu.

- Việc tạo ra mối quan hệ giữa các mảnh thông tin cho phép người dùng xác định các mẫu, xu hướng và thông tin quan trọng khác mà họ muốn phân tích hoặc truy xuất. Các mối quan hệ này có thể là các liên kết giữa các bảng dữ liệu trong CSDL, hoặc các quan hệ logic được xác định bằng cách sử dụng các công cụ của DBMS.

- Tóm lại, thông qua cơ sở dữ liệu và DBMS, người dùng có khả năng nhập, lưu trữ, xử lý, và tạo ra các mối quan hệ giữa thông tin theo nhiều cách khác nhau, tạo điều kiện thuận tiện cho việc quản lý dữ liệu hiệu quả. 

### 2.Hệ quản trị CSDL là gì ?

- **Hệ quản trị cơ sở dữ liệu** (*Database Management System – DBMS*) là một phần mềm, một hệ thống được thiết kế với mục đích lưu trữ và truy xuất dữ liệu người dùng với hiệu quả cao nhất và được áp dụng các biện pháp bảo mật thích hợp. Người dùng có thể tạo lập và quản lý cơ sở dữ liệu của mình nhờ DBMS. 

- Một hệ quản trị cơ sở dữ liệu bao gồm một nhóm các chương trình thao tác với cơ sở dữ liệu. Nó thông qua yêu cầu về dữ liệu từ một ứng dụng và giúp hệ điều hành đưa ra dữ liệu cụ thể. Trong những hệ thống lớn, DBMS đảm nhận nhiệm vụ hỗ trợ người dùng và phần mềm của bên thứ ba lưu giữ và tìm kiếm dữ liệu. 

- Một số DBMS phổ biến hiện nay: Oracle, MySQL, Microsoft SQL Server,  PostgreSQL, IBM DB2, Microsoft Access, SQLite, MariaDB, LibreOffice Base, FoxPro, PostgreSQL, dBASE,…

- **Đặc điểm của DBMS**
    - Cung cấp tính bảo mật và loại bỏ sự dư thừa dữ liệu
    - Có thể tự mô tả bản chất của hệ thống cơ sở dữ liệu
    - Tách biệt giữa các chương trình và trừu tượng hóa dữ liệu
    - Hỗ trợ các chế độ xem dữ liệu đa dạng
    - Chia sẻ dữ liệu và xử lý giao dịch đa người dùng
    - Cho phép các thực thể và mối quan hệ giữa chúng tạo thành các bảng biểu
    - Tuân thủ theo các tính chất ACID, bao gồm tính nguyên tử (Atomicity), tính nhất quán (Consistency), tính độc lập (Isolation) và tính bền vững (Durability)
    - Cho phép người dùng truy cập và thao tác dữ liệu cùng một lúc
- **Các loại hệ quản trị cơ sở dữ liệu**
- *DBMS được chia làm 4 loại khác nhau:* 
    - ***Cơ sở dữ liệu phân cấp (Hierarchical database)***
        Mô hình dữ liệu ở dạng này được tổ chức dưới dạng cây, trong đó các bản ghi sẽ được lưu trữ theo cấp bậc từ trên xuống hoặc từ dưới lên. Từ bản ghi gốc ở trên cùng sẽ dẫn đến các bản ghi con ở phía dưới. Mô hình này chỉ có duy nhất 1 bản ghi gốc. 

    - ***Cơ sở dữ liệu mạng (Network database)***
        Khác với cơ sở dữ liệu phân cấp, cơ sở dữ liệu mạng cho phép các bản ghi con có nhiều hơn một bản ghi gốc. Các thực thể  được tổ chức trong một biểu đồ trong mô hình này có thể truy cập thông qua những đường dẫn. 

    - ***Cơ sở dữ liệu quan hệ (Relational database)***
        Đây là một mô hình DBMS có mức độ ứng dụng phổ biến cao vì tính đơn giản của nó. Cơ sở dữ liệu quan hệ dựa trên sự chuẩn hóa dữ liệu ở các hàng và cột trong bảng. 

    - ***Cơ sở dữ liệu hướng đối tượng (Object-Oriented database)***
        Các dữ liệu được lưu trữ dưới dạng đối tượng trong mô hình DBMS này. Các lớp sẽ đóng vai trò hiển thị dữ liệu chứa trong đó.
+ Câu lệnh tạo *database*, *table* trong MS SQL Server
- **Tạo database:**
    - Lệnh CREATE DATABASE dùng để tạo CSDL mới trong Microsoft SQL Server.
    - **Cú pháp:**
        **CREATE DATABASE** Tên_CSDL

- **Tạo table:**
    - Lệnh CREATE TABLE dùng để tạo cấu trúc bảng trong CSDL.
    - Bảng có cấu trúc gồm các cột (column) và các dòng (row).
    - Trong CSDL bảng thường có khoá chính (primary key).
    - Bảng dùng để lưu trữ dữ liệu, các thông tin của một đối tượng trong thực tế.
    - Các bảng thường liên hệ với nhau bằng các mối quan hệ.
    - Bảng được tạo trong các Schema (mặc định là schema dbo).
    - **Cú pháp:**

        CREATE TABLE Tên_bảng
        (

            Tên_cột_1 Kiểu_dữ_liệu,
            Tên_cột_2 Kiểu_dữ_liệu,
            ...
            Tên_cột_n Kiểu_dữ_liệu
        )
        
    - Ví dụ: 
        
        CREATE TABLE NHANVIEN
        (

            ID int IDENTITY(10,5) PRIMARY KEY,
            HO nvarchar(30) NOT NULL,
            TEN nvarchar(20) NOT NULL,
            NGAYSINH datetime,
            LUONG int,
            GIOITINH bit,
            MAPB char(2)
        )
        
