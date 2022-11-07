# Task-1.-Java-REST-API
Implement an application in java which provides a REST API with endpoints for searching, creating and deleting “server” objects:

● GET servers. Should return all the servers if no parameters are passed. When server id
is passed as a parameter - return a single server or 404 if there’s no such a server.

● PUT a server. The server object is passed as a json-encoded message body. Here’s an
example:
{
“name”: ”my centos”,
“id”: “123”,
“language”:”java”,
“framework”:”django”
}

● DELETE a server. The parameter is a server ID.

● GET (find) servers by name. The parameter is a string. Must check if a server name
contains this string and return one or more servers found. Return 404 if nothing is found.

“Server” objects should be stored in MongoDB database.

Be sure that you can show how your application responds to requests using postman, curl or
any other HTTP client.



# Contents
- show in mongodb compass ui
-  Adding a Course
-  Viewing Created Course
-  Deleting a Created Course
-  Updating the Created Course	
- PostMan

# About Project
It is a backend project .I used Eclipse IDE for writing the course.In this project created RESTFUL API project .

## Mongodb Databases
![Screenshot (97)](https://user-images.githubusercontent.com/117644617/200358954-3a2eb275-32d1-4b7d-b59f-13041192f883.png)

## Project Folder Structure
![Screenshot (99)](https://user-images.githubusercontent.com/117644617/200359731-7884bb8a-c289-45e8-9076-f9f18eb17e0b.png)

## Add  the data into Postman 
![Screenshot (94)](https://user-images.githubusercontent.com/117644617/200360055-5aa7d4ff-3030-4c3a-8c30-559bccf7814a.png)

## Get all the data into Postman 
![Screenshot (91)](https://user-images.githubusercontent.com/117644617/200360246-8922088b-f281-4fcd-a9f3-de485213db59.png)

## Get the Data By Id
![Screenshot (92)](https://user-images.githubusercontent.com/117644617/200361238-77472540-c1c2-43c5-960d-bcf52f3db0ff.png)

##Get By Name
![Screenshot (93)](https://user-images.githubusercontent.com/117644617/200361474-8fc49e58-b90b-4aef-b141-67ee581d22b5.png)

## Update all the data
![Screenshot (95)](https://user-images.githubusercontent.com/117644617/200362010-1aba2925-ab2a-46fb-b5f9-c6bb5e611e15.png)
## Delete the Data By Id
![Screenshot (96)](https://user-images.githubusercontent.com/117644617/200361753-502e6111-0801-4965-99d8-7b3328ed04f1.png)


# THANK YOU
