# Google-Sign-In-Implementation


<h1 style="margin-top:50px">Tech-Stacks:</h1>
<span>
<img src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
<img src="https://img.shields.io/badge/node.js%20-%2343853D.svg?&style=for-the-badge&logo=node.js&logoColor=white"/>
<img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"/>
<img src ="https://img.shields.io/badge/MongoDB-%234ea94b.svg?&style=for-the-badge&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/heroku%20-%23430098.svg?&style=for-the-badge&logo=heroku&logoColor=white"/> </span>


<hr />
<br />
<br />


<h2>You can contribute by following below set of instructions</h2>
Environment Setup-

* Drop a :star: on the GitHub repository.
<br/>

* Download and install a code/ text editor.
    - Recommended-
        - [Download VS Code](https://code.visualstudio.com/download)
        - [Download Atom](https://atom.io/)
<br/>

* Download [Node Js and npm(Node package manager)](https://nodejs.org/en/) (when you download Node, npm also gets installed by default)
<br/>

* Mongo DB community edition is free & a great software in order to work with MongoDB applications. [Download Mongo DB community editition](https://docs.mongodb.com/manual/administration/install-community/)
<br/>

* Robo 3T is a desktop graphical user interface (GUI) for Mongo DB. It can help to skip running all the Mongo DB commands manually every time we want to access the data. [Download Robo 3T](https://robomongo.org/download) **(optional)**
<br/>

* Fork the repository and then clone it from forked copy.

* Clone the repository by running command
```
git clone https://github.com/ <your user-name> /Google-Sign_In-Implementation.git
```
in your git bash.
<br/>

* Run command `cd Google-Sign_In-Implementation`.
<br/>

* Run this command to install all dependencies for the project.
```
npm install
```
All the current dependencies -
```
    "body-parser": "^1.19.0",
    "dotenv": "^8.2.0",
    "ejs": "^3.1.5",
    "express": "^4.17.1",
    "express-session": "^1.17.1",
    "mongoose": "^5.10.3",
    "mongoose-findorcreate": "^3.0.0",
    "nodemailer": "^6.4.11",
    "passport": "^0.4.1",
    "passport-google-oauth20": "^2.0.0",
    "passport-local-mongoose": "^6.0.1",
    "url": "^0.11.0"
```
<br/>

* Run this command on your terminal/ bash to start the Mongo server on port 27017(default).
```
mongod
```
<br/>

* Run this command to start the project on local host 3000.
```
npm start
```
<br/>

* Open link to view the website in your browser window if it doesn't open automatically.
```
http://localhost:3000/
```
<br/>

* You can learn more about EJS template engine and its syntax to know how we can use it inside our HTML using the [documentation](https://ejs.co/#docs)
<br/>

* Now you are all set to use this project.

#### Some useful Mongo DB commands if you are using the terminal instead of the GUI-
```
show dbs
use db <db name>
show collections
<db name> .find()
```
<h3 style="font-weight:bold;font-size:25px">Note</h3>
<ul>
<li> Get connection string from Mongo Atlas by creating a cluster or you can also use your locally installed mongodb. </li>
<li> You can click here to learn how to connect atlas to you project.</li>
<li> Create a new file named .env in the Backend folder and copy the format of .env.example file</li>
<li>Paste the connection string in the .env file in the MONGODB_URI variable.</li>
<li>Get your client_id and client_secret by creating a new app in google developer console.And enter client_id in CLIENT_ID variable and client_secret in CLIENT_SECRET variable.
</li>

</ul>


