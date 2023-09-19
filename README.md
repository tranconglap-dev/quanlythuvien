
# Getting Started with Project I 

--cd ./BackEnd
## `Config database`
./config/config.json

## `Start project`: 
npm start

## `Run database`: 
sequelize db:migrate 

## `Update Seed`: 
sequelize db:seed:all 

## `Delete table in database`: 
sequelize db:migrate:undo:all 

--cd ./FrontEnd
## `Start project`: 
npm start



## `Login`
giao diện đăng nhập                 



## `Register user`
giao diện đăng ký và đánh validate cho từng input (tránh cả việc mssv bị trùng)    



## `AdminPage`


### `Trang chủ admin`
ghi nội dung của project 1, phương thức liên hệ          

### `Quản lý sinh viên`
xem danh sách tất cả sinh viên                     

xóa, tạo lại sinh viên                             

sắp xếp sinh viên theo trường                        

xem danh sách các quyển sách của một sinh viên đang mượn    

nạp thẻ cho sinh viên ngoài trường (Chỉ sinh viên ngoài trường mới hiện button nạp thẻ) và hiển thị số dư sau khi nạp thẻ 

tạo thẻ cho sinh viên ngoài trường                   


### `Quản lý sách`
Xem danh sách các quyển sách                    

Tạo lại sách                                   

Cập nhật sách                                   

Xóa sách                                              

Tạo sách mới                                    

Mượn sách theo id của sách và id của user                   
 
Trả sách theo id của sách                            


### `Thay đổi thông tin người dùng admin`
Thay đổi mật khẩu                       


### `Tạo tài khoản admin do chính admin tự tạo`
Tạo tài khoản admin                   



## `UserPage`


### `Header && Footer`                  



### `Trang chủ user`                           

List thể loại sách                      


### `List những quyển sách cùng thể loại`                             


### `Giới thiệu chi tiết về quyển sách đã chọn`                             


### `Trang giới thiệu`                  


### `Trang sách của thư viện`  

thanh search tìm kiếm theo tên sách           

liệt kê danh sách các quyển sách và filter theo status          




