# Huong dan build ung dung va chay tren docker nhanh

## Yeu cau:

- Docker

## Truong hop khong build thanh docker container de chay thi yeu cau

- Node.js installed
- MongoDB connection


## Khoi dong nhanh voi docker
#### Buoc 1: Clone repository
 ```
$ git clone https://github.com/dongsinhho/bookLibrary.git
 ```
#### Buoc 2: Chay docker-compose.yml
```
$ cd bookLibrary
$ docker-compose up -d
```
* Api chạy trên port 8080, web chạy trên port 3000
truy cập vào localhost với port tương ứng để check