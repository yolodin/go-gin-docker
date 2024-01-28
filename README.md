# Receipt Processor

### Languages/Technologies/Frameworks
Go
Gin
Docker 

### Instructions:
*Must have Docker installed*

Clone repository
- git clone https://github.com/yolodin/go-gin-docker.git

Run command in project directory
- docker compose up


Once project is loaded, use API testing tool such as Postman or Insomnia to send POST or GET requests to 
http://localhost:8080/

**Process Receipts**
Method: POST
Path: /receipts/process
Payload: Receipt JSON
Response: JSON containing an id for the receipt.


**Get Points**
Method: GET
Path: /receipts/{id}/points
Response: A JSON object containing the number of points awarded.
