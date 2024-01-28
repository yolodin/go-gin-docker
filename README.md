# Receipt Processor

## Languages/Technologies/Frameworks
Go

Gin

Docker 

------------

## Instructions:
*Must have Docker installed*

##### Clone repository
- git clone https://github.com/yolodin/go-gin-docker.git

##### Run command in project directory
- docker compose up


Once project is loaded, use API testing tool such as Postman or Insomnia to send POST or GET requests to http://localhost:8080/

------------

### **Process Receipts**

Method: POST

Path: /receipts/process

Address: http://localhost:8080/receipts/process

![Screenshot 2024-01-27 at 11 04 51 PM](https://github.com/yolodin/go-gin-docker/assets/37274564/9d0f46ff-19b7-4661-8a15-7657d9a36f61)

### **Get Points**

Method: GET

Path: /receipts/{id}/points

Address: http://localhost:8080/receipts/9a355a00-9ee4-44b4-9b6d-3b67b6c47f2c/points


![Screenshot 2024-01-27 at 11 05 12 PM](https://github.com/yolodin/go-gin-docker/assets/37274564/38c82293-dcb5-45d4-bc53-30eb971a5b52)
