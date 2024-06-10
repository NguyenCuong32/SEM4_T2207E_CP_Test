# SEM4_T2207E_CP_Test

1. Designing

Link : https://app.diagrams.net/#G1zv30pZ0K4se7htmktrEAu-LtPxVSdHN5#%7B%22pageId%22%3A%22R2lEEEUBdFMjLlhIrx00%22%7D

2. Project process

a. Trong dự án phát triển phần mềm, Quản lý kỹ thuật nên sử dụng những nhánh GIT và công dụng của nhánh đó là : 

- Main : Lưu trữ mã nguồn ổn định nhất, là phiên bản chính thức của sản phẩm.
- Develop : Nơi mà tất cả các tính năng mới, cải tiến và sửa lỗi được hợp nhất trước khi đưa lên nhánh main.
- Feature : Phát triển các tính năng mới hoặc cải tiến.
- Release : Chuẩn bị cho việc phát hành một phiên bản mới, thực hiện các kiểm tra cuối cùng và sửa lỗi nhỏ.
- Hotfix : Sửa lỗi khẩn cấp trong phiên bản đã phát hành.

b. Nếu bạn có một mô-đun mới để phát triển, bạn nên chuẩn bị những bước nào để phát triển từ
bắt đầu mô-đun đến khi phát hành mô-đun :

- Lập kế hoạch 
- Tạo nhánh Feature
- Phát triển 
- Kiểm tra
- Hợp nhất vs develop
- Chuẩn bị phát hành
- Phát hành
- Bảo trì

3. Testing

a. Các loại chiến lược testing strategies là : 
- Unit Testing
- Integration Testing
- System Testing
- Acceptance Testing
- Regression Testing
- Performance Testing
- Security Testing
- Usability Testing
- Compatibility Testing
- Smoke Testing
- Sanity Testing

b. Unit Testing used for : 
- Kiểm tra các thành phần hoặc chức năng riêng lẻ của mã một cách riêng biệt.
- Đảm bảo rằng mỗi đơn vị của mã hoạt động như mong đợi.
- Phát hiện lỗi sớm trong quá trình phát triển.
- Tạo điều kiện cho việc tái cấu trúc và bảo trì mã.

c. Integration Testing used for :
- Kiểm tra tương tác và tích hợp giữa các units/modules khác nhau.
- Đảm bảo rằng các thành phần kết hợp hoạt động cùng nhau như mong đợi.
- Xác định các vấn đề liên quan đến giao diện và tương tác giữa các modules.
- Xác thực luồng dữ liệu và kiểm soát giữa các thành phần tích hợp.

d. When a tester has a new module to test, the following steps should be taken from start to release :
- Requirement Analysis
- Test Planning
- Test Case Design
- Test Environment Setup
- Test Data Preparation
- Unit Testing (if applicable)
- Integration Testing
- System Testing
- Regression Testing
- Performance Testing (if applicable)
- Security Testing (if applicable)
- Usability Testing (if applicable)
- Bug Reporting and Fixing
- Acceptance Testing
- Final Regression Testing
- Test Closure
- Release Preparation
- Post-Release Monitoring