Ghi chú hướng dẫn đẩy code lên git

lần đầu thì cần làm như sau:

1: thực hiện tạo remote reponse ở gỉt
2: quay lại thư mục dưới máy và sử dụng lệnh git init để tạo local reponse
3: git add. (git add. là lấy tất cả file mới)
4: sử dụng câu lệnh git commit -m 'nội dung note'
5: sử dụng câu lệnh git remote add origin (đường dẫn tới remote (đơn giản là đường dẫn git dự án))
6: sử dụng lệnh: git push origin main (main là tên nhánh)
7: những lần sau khi đẩy code lên từ lần đầu thì chỉ cần bắt đầu bước sau
1.sử dụng git add.
2.git commit -m '....' 3. chỉ cần sử dụng git push
