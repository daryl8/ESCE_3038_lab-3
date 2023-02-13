This lab aims to familiarize students with the technologies involved in developing and deploying a RESTful API server.
A project was used to control a system that keeps track of the condition of a number of water tanks that are electronically measured. Each water tank has an integrated circuit attached to it that measures the height of the water inside each tank and reports the stored volume as a percentage of the tank's maximum capacity.
The experimenter was to provide a RESTful API that enables each IoT-enabled water tank to communicate with your server so that the measurement numbers may be shown graphically on a website and one memebr of a team will create the website.
A straightforward simple user profile should also be supported by API.
The operations of a basic HTTP web server should be possible for your server to carry out. Actions like Create, Read, Update, and Delete should be possible for the server to carry out on a resource. The use of a MongoDB database was required to accomplish this.
Your server must be built to support at least six distinct HTTP routes. As follows:
GET /profile
POST /profile

GET /data
POST /data
PATCH /data/:id
DELETE /data/:id

In the profile routes the user should only be able to create one user profile using your server application. Only one JSON object should ever be returned by the get request handler.
In the data get data routes for example an array of 0 or more objects must be returned by this route. The GET route should return the posted object in the array if a previous POST call to the /data route was successful. other data routes are post/data, patch/data, delete/data. 
