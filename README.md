1 Postman sent a GET request to the postman Echo API server located at the postman-echo.com and the API server received the request and returned with a response in the postman.

Make API calls using the following URIs and record the status code and response body for each API call (You will write the answer after every question and any screen capture in this document)
Get authentication token using URI: https://postman-echo.com/basic-auth
![img.png](img.png)

Get information about all users using URI: https://reqres.in/api/users ![api2.png](..%2F..%2FOneDrive%20-%20City%20University%20of%20New%20York%2FPictures%2FScreenshots%2Fapi2.png)
Question:
How many lists can you see in the response body? > **1**

Get information about the user with id 3 using URI: https://reqres.in/api/users/3 ![api3.png](..%2F..%2FOneDrive%20-%20City%20University%20of%20New%20York%2FPictures%2FScreenshots%2Fapi3.png)
Question:
How many lists can you see in the response body? > NO LIST
What are the available property(Key) names in the response body?
>there are two primary keys 

Delete the User with id 9 using URI https://reqres.in/api/users/9 ![img_1.png](img_1.png)
Question: 
What is the response? 
> Response 1 Status code 204.
> the server not allowing to delete

How many users are now on the users list? https://reqres.in/api/users 
Can you see the deleted user record? 
>yes as i could not delete !

Get information of the user with id 40 using URI: https://reqres.in/api/users/40 ![img_2.png](img_2.png)
Question:
How many lists can you see in the response body? 
>NO LIST

What are the available property(Key) names in the response body?
> NO PROPERTY THERE

Create a new user in a system using URI: https://reqres.in/api/users  Verb: POST Request Body:
{
"name": "yourname",  
"job": "dreamjob"
}  ![img_3.png](img_3.png)


Question:
What is the response code? 
> > 201 CREATED
> 
What are the available property(Key) names in the response body?  
>"name","job","id","createdAt"

What is the value of response Header Etag? 
> W/"54-osKxtFHIFDl7O9X/DuXKwxs087g"

Sign in to the system using URI: https://reqres.in/api/login and {"email": "peter@klaven"}
![img_4.png](img_4.png)
Question:
What is the response code? 
>400 bad request

Sign in to the system using URI: https://reqres.in/api/login and
{
"email": "eve.holt@reqres.in",
"password": "cityslicka"
}
![img_5.png](img_5.png)
Question:
What is the value of response Header Etag? 
> W/"1d-lGCrvD6B7Qzk11+2C98+nGhhuec"

What is the response?  
>  "token": "QpwL5tke4Pnpja7X4"

Get information about all planets using URI: https://swapi.dev/api/planets. Carefully observe the response body and make a list of all attributes and write their data types.
Question:
![img_6.png](img_6.png)

How many lists can you see in the response body? 
>Primarily one list named "Results" under that more lists available

Get information about the third planet using URI: https://swapi.dev/api/planets/3/
Question: ![img_7.png](img_7.png)

How many properties you can see in response body? 
Get information about all the starships using URI: https://swapi.dev/api/starships. 
![img_8.png](img_8.png)
Carefully observe the response body and make a list of all attributes and write their data types.
Question:
How many lists can you see in the response body? 
>1

Get information about the ninth starship using URI: https://swapi.dev/api/starships/9/
Question:
How many lists can you see in the response body? 
>2 

Get information about all films using URI: https://swapi.dev/api/films. Carefully observe the response body and make a list of all attributes and write their data types.
Question:
How many lists can you see in the response body?
Get information about the third planet using URI: https://swapi.dev/api/species
Question:
How many lists can you see in the response body?
Get all booking ids using URI: https://restful-booker.herokuapp.com/booking
Question:
How many lists can you see in the response body?
Get details about booking id 23 using URI: https://restful-booker.herokuapp.com/booking/23
Question:
What is the response?
Get details about booking id 3 using URI: https://restful-booker.herokuapp.com/booking/3
Question:
What is the response?
Get information about all planets using URI: https://swapi.dev/api/planets
Question:
What is the response?
How many lists can you see in the response body?
Get information about all species using URI: https://swapi.dev/api/species. Carefully observe the response body and make a list of all attributes and write their data types.
Question:
How many lists can you see in the response body?
What is the response?
Write JSON path for following JSON file:
{
"studio": {
"movie": [
{
"category": "history",
"director": "John",
"title": "History",
"rating": 6.60
},
{
"category": "comedy",
"director": "Paul",
"title": "Laugh",
"rating": 4.00
},
{
"category": "fiction",
"director": "Jack",
"title": "Wake",
"isbn": "87877676879",
"rating": 8.01
},
{
"category": "drama",
"director": "Edward",
"title": "Wuthering Heights",
"isbn": "8754543578",
"rating": 4.50
}
],
"music": {
"song": "pale",
"rate": 5.4
}
},
"ranking": 20
}
a. To retrieve all direct properties of the studio object
b. To find out the music’s song
c. To find the rating of all items in the studio
d. To retrieve information on all movies
e. To find out the titles of all movies
f. To retrieve the titles of all movies by Jack
g. To retrieve the category of the last movie
i. To retrieve all movies that have the isbn property


Get information about all employess using URI: http://dummy.restapiexample.com/api/v1/employees
Question:
How many lists can you see in the response body?
What is the response?
What are the available property(Key) names in the response body?
Make a list of all attributes and write the data types.
Get a single employee data using URI: http://dummy.restapiexample.com/api/v1/employee/3
Question:
How many data you can see in response body?
What is the response status? 23.Create a new employee in a system by using URI: http://dummy.restapiexample.com/api/v1/create Verb: POST Request Body:
{
"name":"your name",
"salary":"123",
"age":"23"
}

Question:
What is the response?
can you see "id" property in the response? if Yes, note the "id" value.
Delete an employee record whose employee id in 2 by using URI http://dummy.restapiexample.com/api/v1/delete/2
Question:
What is the response?
How many employees are now in the employees list? http://dummy.restapiexample.com/api/v1/employees
Can you see the deleted employee record?
Register a user by using
URI: https://reqres.in/api/register Verb: POST Request Body:
{
"email": "john.jack@example.com",
"password": "@izaanSchool"
}

Question:
What is the response?
What are the available property(Key) names in the response body?
Get an user Using URL https://reqres.in/api/unknown/2
Question:
What is the response?
A simple health check endpoint to confirm whether the API is up and running using https://restful-booker.herokuapp.com/ping
Question:
What is the response?
Get information using Delayed Response using URI: https://reqres.in/api/users?delay=3
Question:
What is the response?
How many seconds delay to respond?
Get information about vehicles using URL https://swapi.dev/api/vehicles/schema/
Question:
What type of response it is?
What is response status code?
Get information about starships using URL https://swapi.dev/api/starships/schema/
Question:
What type of response it is?
Write down the response status code.
What are the available property(Key) names in the response body?







API-Assignment