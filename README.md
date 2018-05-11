## VTube
CMPE 280 SP18 Team Project
Team name: BAM
Team members: Matthew Kwong <matthew.kwong@sjsu.edu>, Akash Gupta <akash.gupta@sjsu.edu>, Bruce Decker <bruce.decker@sjsu.edu>

#### Setup &amp; Run

To run the application, fork and clone the repository, `cd` into the repository directory, then run the following commands to setup &amp; start the server:

`$ mkdir uploads # create directory where user VRs will be stored`<br/>
`$ npm install # install required libraries`<br/>
`$ npm start # start the server on port 3000`

Once the server is running, you should be able to access the app at [http://localhost:3000](http://localhost:3000).


#### Architecture

##### Node.js Web Server

![280_server](https://user-images.githubusercontent.com/32351699/39911674-138545dc-54b1-11e8-9ee2-bce13b809edc.png)

##### MySQL Database 

![280_mysql](https://user-images.githubusercontent.com/32351699/39911764-5da4054a-54b1-11e8-972a-35b8dbc29c2c.png)

##### MongoDB Database 

![280_mongo](https://user-images.githubusercontent.com/32351699/39911796-73a178dc-54b1-11e8-900f-36ff51dcf2a1.png)

#### REST API Endpoints

| Verb  | Route  | Description  |
| ------------ | ------------ | ------------ |
| GET  | /  | Display landing page  |
| GET  | /users  | Display a particular user's profile  |
| GET  | /users/getUserInfo  | Get the information for the currently logged-in user (if any)  |
| POST  | /users/signup  | Register a new user  |
| POST  | /users/login  | Log in an existing user |
| GET  | /users/logout  | Log out a logged-in user  |
| POST  | /serach  | Display search page  |
| POST  | /files/upload  | Upload a new VR file  |
| POST  | /files/download  | Download an existing VR file  |
| GET  | /files/uservrs  | Get the VRs for a particular user  |
| POST  | /files/search  | Get the files that match a search query keyword |
| GET  | /vrs  | Display a particular VR  |
| GET  | /vrs/getVrInfo  | Get the details for a particular VR  |
| GET  | /vrs/getOtherVrs  | Get the summary of the 10 most recently uploaded VRs  |
| GET  | /vr/getComments | Get the comments for a particular VR |
| POST  | /vr/submitComment | Submit a new comment for a particular VR |

#### Application Screenshots



