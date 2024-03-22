---
title: "AWS Lambda"
date: "`r Sys.Date()`"
weight: 2
chapter: false
pre: "<b>1.2 </b>"
---

### AWS Lambda

**AWS Lambda** là một dịch vụ tính toán không máy chủ được cung cấp bởi Amazon Web Services (AWS). Được ra mắt vào năm 2014, Lambda đã thay đổi cách chúng ta xây dựng và triển khai ứng dụng, cho phép chúng ta tập trung vào việc viết mã và không cần lo lắng về việc quản lý cơ sở hạ tầng. Dưới đây là một số điểm cần lưu ý về AWS Lambda:

1. **Tính Năng và Ưu Điểm**:
   - AWS Lambda cho phép bạn chạy mã một cách tự động mà không cần quản lý các máy chủ. Dịch vụ tự động mở rộng và xử lý lưu lượng truy cập mà không cần bất kỳ can thiệp nào từ phía người dùng.
   - Lambda sử dụng mô hình thanh toán theo sử dụng, bạn chỉ trả tiền cho thời gian thực thi của mã của bạn và lượng tài nguyên mà mã sử dụng, giúp giảm bớt chi phí và tối ưu hóa tài nguyên.
   - AWS Lambda hỗ trợ nhiều ngôn ngữ lập trình phổ biến như Python, Node.js, Java, C#, Go và Ruby, cho phép lập trình viên sử dụng ngôn ngữ mà họ thoải mái.

2. **Tích Hợp và Linh Hoạt**:
   - Lambda tích hợp mạnh mẽ với các dịch vụ AWS khác như Amazon S3, DynamoDB, API Gateway, SNS và nhiều dịch vụ khác, giúp bạn xây dựng các ứng dụng phức tạp và linh hoạt mà không cần quá nhiều công việc tích hợp.
   - Lambda cung cấp môi trường thực thi linh hoạt, cho phép bạn sử dụng ngôn ngữ lập trình yêu thích của mình và tích hợp với các dịch vụ AWS khác.

3. **Ứng Dụng của AWS Lambda**:
   - Xử lý sự kiện: Lambda thường được sử dụng để xử lý các sự kiện trừu tượng như yêu cầu HTTP từ Amazon API Gateway, thông báo từ Amazon S3, hoặc các sự kiện từ Amazon DynamoDB.
   - Xây dựng ứng dụng serverless: Lambda là một phần quan trọng của kiến trúc serverless, cho phép bạn xây dựng các ứng dụng mà không cần quản lý máy chủ.

![AWS Lambda](/images/1-Introduce/lambda.png?featherlight=false&width=50pc)

--- 