# ocg-project
```
Website bán đồ thể thao nhập khẩu chính hãng từ adidas.
Cấu trúc website gồm 2 phần chính: 
- Các API được xây dựng trên nền tảng framework fiber của ngôn ngữ lập trình golang.
- Giao diện được xây dựng bằng VueJS 3

```

## Diagram Database

![image](https://user-images.githubusercontent.com/57215318/123943072-f826a900-d9c5-11eb-95eb-d60d6bb62037.png)

## Giao diện một số trang 
![image](https://user-images.githubusercontent.com/57215318/123943822-b4806f00-d9c6-11eb-9f8a-25a727dba0fc.png)
![image](https://user-images.githubusercontent.com/57215318/123943243-2906de00-d9c6-11eb-88ac-eb626c3f6f73.png)
![image](https://user-images.githubusercontent.com/57215318/123943337-4340bc00-d9c6-11eb-8b2f-97e5ae4d56b1.png)
![image](https://user-images.githubusercontent.com/57215318/123943424-581d4f80-d9c6-11eb-952b-4d5c8abf90c3.png)
![image](https://user-images.githubusercontent.com/57215318/123943919-cf52e380-d9c6-11eb-9c4c-ffdb22911aae.png)


## Back end 
```
- Thiết lập cổng mặc định để chạy server là port 3000.
- Tùy theo database các bạn sử dụng thì cổng mặc định là khác nhau. Trong poject tôi sử dụng cổng 3305 của database MySQL. Các bạn có thể chỉnh sửa trong file Connection thư mục databse.
```
### API create new product
```
METHOD: POST
http://localhost:3000/api/v1/products
```

### API get all products
```
METHOD: GET
http://localhost:3000/api/v1/products
``` 
### API get product by id
```
METHOD: GET
http://localhost:3000/api/v1/products/:id
``` 
### API login
```
METHOD: POST
http://localhost:3000/api/v1/login
``` 
### API register
```
METHOD: POST
http://localhost:3000/api/v1/register
``` 
### API logout
```
METHOD: POST
http://localhost:3000/api/v1/logout
``` 

### API create orders
```
METHOD: POST
http://localhost:3000/api/v1/orders
``` 
### API get orders by id
```
METHOD: GET
http://localhost:3000/api/v1/orders/:id
``` 

## Front end

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
