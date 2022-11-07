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
-  Adding a Actor
-  Viewing Created Actor
-  Deleting a Created Actor
-  Updating the Created actor	
- PostMan


## Mongodb Databases
![Screenshot (97)](https://user-images.githubusercontent.com/117644617/200358954-3a2eb275-32d1-4b7d-b59f-13041192f883.png)

## Project Folder Structure
![](https://github.com/Krishna12345825/Task-1.-Java-REST-API/blob/main/images/image1.png)

## Add  the data into Postman 
![](https://github.com/Krishna12345825/Task-1.-Java-REST-API/blob/main/images/image2.png)

## Get all the data into Postman 
![](https://github.com/Krishna12345825/Task-1.-Java-REST-API/blob/main/images/image3.png)

## Get the Data By Id
![](https://github.com/Krishna12345825/Task-1.-Java-REST-API/blob/main/images/image4.png)

## Update all the data
![](https://github.com/Krishna12345825/Task-1.-Java-REST-API/blob/main/images/image5.png)

## Delete the Data By Id
![](https://github.com/Krishna12345825/Task-1.-Java-REST-API/blob/main/images/image6.png)



# THANK YOU
