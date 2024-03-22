---
title: "Amazon S3"
date: "`r Sys.Date()`"
weight: 1
chapter: false
pre: "<b>1.1 </b>"
---

### Amazon S3 (Simple Storage Service)

**Amazon S3 (Simple Storage Service)** là một dịch vụ lưu trữ đám mây hàng đầu được cung cấp bởi Amazon Web Services (AWS). Nó cung cấp một nền tảng linh hoạt, đáng tin cậy và an toàn để lưu trữ và quản lý dữ liệu trên Internet. Dưới đây là một số điểm cần lưu ý về Amazon S3:

1. **Đặc điểm chính**:
   - Amazon S3 cung cấp khả năng lưu trữ dữ liệu không giới hạn, cho phép người dùng lưu trữ mọi loại dữ liệu từ hình ảnh, video, tệp tin backup cho đến dữ liệu của ứng dụng web và dữ liệu của doanh nghiệp.
   - Dữ liệu được lưu trữ trên Amazon S3 được bảo vệ bằng các biện pháp bảo mật mạnh mẽ bao gồm mã hóa dữ liệu trong truyền và tại nơi lưu trữ.
   - Amazon S3 cung cấp các tính năng linh hoạt cho phép người dùng kiểm soát quyền truy cập vào dữ liệu thông qua quản lý IAM (Identity and Access Management).

2. **Mô hình lưu trữ**:
   - Dữ liệu trên Amazon S3 được tổ chức trong các "bucket" (thùng chứa), mỗi bucket có thể lưu trữ một số lượng lớn các tệp tin và thư mục tương ứng.
   - Mỗi tệp tin trong Amazon S3 có thể được truy cập thông qua một URL duy nhất, giúp dễ dàng chia sẻ và truy cập dữ liệu.

3. **Tính mở rộng và thanh toán theo sử dụng**:
   - Amazon S3 cho phép mở rộng linh hoạt để đáp ứng nhu cầu lưu trữ dữ liệu của mọi quy mô, từ các cá nhân đến doanh nghiệp lớn.
   - Mô hình thanh toán theo sử dụng của Amazon S3 giúp giảm bớt chi phí với việc chỉ trả tiền cho dung lượng thực sự sử dụng.

4. **Ứng dụng của Amazon S3**:
   - Lưu trữ dữ liệu trực tuyến: Amazon S3 là lựa chọn lý tưởng để lưu trữ hình ảnh, video, tệp tin backup và nhiều loại dữ liệu khác.
   - Web Hosting tĩnh: Amazon S3 có thể được sử dụng để lưu trữ và phân phối nội dung web tĩnh như trang web tĩnh, hình ảnh và tệp CSS, JavaScript.
   - Phân tích dữ liệu lớn (Big Data): Amazon S3 là một phần quan trọng trong cơ sở hạ tầng cho các dự án phân tích dữ liệu lớn, nơi nó lưu trữ dữ liệu nguyên gốc hoặc dữ liệu được xử lý trước.

![Amazon S3](/images/1-Introduce/s3.png?featherlight=false&width=50pc)