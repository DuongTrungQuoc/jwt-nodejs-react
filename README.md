## Express là một thư viện phổ biến để tạo ứng dụng web hoặc API trong Node.js

```
npm install --save-exact express@4.17.2 dotenv@10.0.0 body-parser@1.19.1 ejs@3.1.6
```

```
npm install --save-exact @babel/core@7.15.4 @babel/node@7.15.4 @babel/preset-env@7.15.4 nodemon@2.0.15
```
- Lỗi: 'babel-node' is not recognized as an internal or external command, operable program or batch file.

```
cách fix: npm install @babel/node -g
```

- dotenv được dùng để tải các biến môi trường từ file .env vào process.env
- body-parser là middleware trong Express dùng để phân tích dữ liệu gửi lên trong các yêu cầu HTTP (request)
- EJS (Embedded JavaScript Templates) là một thư viện dùng để render HTML từ các template.
- Babel là một công cụ biên dịch mã JavaScript, giúp bạn viết mã theo chuẩn ECMAScript mới (ES6, ES7,...)
- Nodemon là một công cụ giúp tự động khởi động lại ứng dụng Node.js khi phát hiện thay đổi trong mã nguồn. 
