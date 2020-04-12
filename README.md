Nếu tiếp tục thay đổi và muốn đưa ứng dụng của mình lên GitHub, bạn chỉ việc lặp lại ba câu lệnh sau:
git add .
git commit -m "type your commit message here"
git push origin master


========================================================================
Chuẩn bị sang bước tiếp theo là Deploy code lên Heroku, để tránh một lỗi chắc chắn sẽ xảy ra khi deploy code, trước tiên các bạn cần tạo một file nữa trong project với tên là Procfile, và nội dung là:

web: node index.js
