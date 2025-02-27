###### Network_Design_Project ######
## Tổng quan 
Công ty Outsource O-UIT có 1 trụ sở chính tại Thủ Đức và một chi nhánh tại Quận 3. 
Trụ sở chính là một tòa nhà 5 tầng gồm Data Center và các văn phòng làm việc dành cho 
CEO, HR, Project manager, Technical Manager, Business Analyst, IT manager và các nhóm 
developer và tester cho các project thuộc thị trường nước ngoài. Chi nhánh tại Quận 3 là 
văn phòng làm việc của các nhóm developer và tester cho các project thuộc thị trường trong 
nước. 
## Mục tiêu 
Bài tập này giả định Công ty muốn thiết lập một hệ thống mạng cho trụ sở chính và chi 
nhánh với các yêu cầu sau: 
- Tại trụ sở chính 
  o Developer và Tester chỉ được sử dụng máy bàn tại công ty, không được sử
  dụng laptop riêng để truy cập vào mạng của công ty. 
  o CEO, HR, Project manager, Technical Manager, Business Analyst, IT 
  manager được sử dụng Laptop, truy cập vào hệ thống wifi nội bộ sử dụng tài 
  khoản xác thực. 
  o Một hệ thống wifi public với đường kết nối Internet riêng. 
  o Hệ thống phần cứng để triển khai hệ thống server ảo phục vụ cho việc deploy 
  các ứng dụng trong giai đoạn test. 
  o Sử dụng các dịch vụ Cloud deploy các ứng dụng trong giai đoạn staging để
  khách hàng sử dụng thử trước khi đưa ra thực tế.
- Tại chi nhánh: 
  o Developer và Tester chỉ được sử dụng máy bàn tại công ty, không được sử
  dụng laptop riêng để truy cập vào mạng của công ty. 
  o Sử dụng kết nối VPN site-to-site để deploy ứng dụng lên hệ thống tại Data 
  Center. 
  o Một hệ thống wifi với đường kết nối Internet riêng. 
Bài tập này yêu cầu sinh viên làm việc theo nhóm. Trong bài tập này, các nhóm sẽ phải thực 
hiện việc thiết kế thông qua các giai đoạn với yêu cầu cụ thể. Sản phẩm thiết kế cuối cùng là 
bản báo cáo và bài thuyết trình trước đại diện để được xét duyệt.
