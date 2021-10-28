# RestAPI_Demo
GET,POST,PUT,PATCH,DELETE method via Postman
Hello All,
This is a simple Postman collection where you can practice the Rest methods i.e. GET,POST,PUT,PATCH,DELETE.
I have used json-server which is used to create demo REST JSON services within a short span of minutes.

Steps:
1. Install npm and json-server:

npm install -g json-server
2. Start json-server:

json-server --watch db.json

**NOTE** 
db.json file will be created in your working project directory and you can modify the content present in there.

3.To create mock data I have used Mockaroo.
https://www.mockaroo.com/
Mockaroo is a free test data generator and API mocking tool.

4. Open your browser and navigate to http://localhost:3000/, once your json-server is up and running you will be able to see JSON Server home page 
and under Resources our endpoint will displayed.

5. Access the endpoint : http://localhost:3000/users

Thanks
