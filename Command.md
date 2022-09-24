##Các lệnh trong git:

##git config:

###Hai cài đặt quan trọng của git là user name và email

##git init:

###Dùng để tạo một kho lưu trữ (repository) và 1 dự án (project) mới

##git add:

###Thêm các file vào stage/index. Một số cách khác có thể sử dụng git add bằng cách thêm toàn bộ thư 

mục, các file cụ thể

##git commit:

###Dùng để ghi lại những thay đổi được thực hiện đối với file vào local repository. Để dễ dàng theo dõi

commit và mỗi commit sẽ có một mã ID theo dõi duy nhất

##git status:

###Sử dụng lệnh này để trả về trạng thái tại kho lưu trữ (repository). git status sẽ trả về nhánh làm

việc hiện tại của bạn. Nếu một file nằm trong stagging area nhưng không được commit thì nó sẽ hiển thị
 
với git status. Hoặc nếu không có thay đổi nào no sẽ trả về nothing to commit, working directory clean

##git branch:

###Để xác định nhánh nào trong local repository, thêm hoặc xóa một nhánh mới

##git checkout:

###Sử dụng git checkoutđể chuyển đổi các chi nhánh

##git merge:

###Hợp nhất các nhánh với nhau, sử dụng git merge để kết hợp các thau đổi từ nhánh này sang nhánh khác

##git remote:

###Để kết nối repository với kho lưu trữ từ xa

##git clone:

###Để tạo một bản sao làm việc cục bộ với kho lưu trữ từ xa. Sử dụng git clone để sao chép và tải kho

lưu trữ về máy tính. Sao chép giống với Git init khi làm việc với kho lưu trữ từ xa

##git pull:

###Chạy git pull để tải phiên bản mới nhất của repository. Thao tác với lệnh này kéo các thay đổi từ
 
kho lưu trữ từ xa sang máy tính cục bộ

##git push:

###Dùng để gửi commit đến kho lưu trữ từ xa. git push sử dụng 2 tham số: kho lưu trữ từ xa và nhánh mà

push dành cho

##git stash:

###Dùng để lưu các thay đổi được thực hiện nó chưa ở trạng thái commit đến repository

##git log:

###Để hiển thị lịch sử commit theo thời gian cho một repository

##git reset:

###Dùng để quay về một điểm commit nào đó, đồng thời xóa lịch sử của các commit trước nó

