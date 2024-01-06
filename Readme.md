# Eventopia 

## What is Eventopia 
It is an Full Stack Application that is Made By Sahid Munjavar That Helps people Add Events Directly to your Calendar, It Supports Apple Calendar , Outlook Calendar and Google Calendar. User can also sign up and make their own event and view them.
( In Development ) User would be also able to edit and delete their events. You Can Use this to Get Remainder for University events. 

##  Technical Details 
	Front End      : React JS , Bootstrap  
	Backend        : Node JS , Express JS 
	Authentication : JWT Token
	Database       : MongoDB , Moongose

## How to Setup Locally 
Start By Clonning This Repo Locally :
 
    git clone --recursive https://github.com/Sahid-m/Eventopia-fullstack.git
	
You Should Have Eventopia-fullstack Folder
	
Now : 
	
    cd Eventopia-fullstack/Backend/
 
    touch .env
	
Open the .env File and add the following text into it: 

    PORT = "8080"
    MONGO_DB_URL = (Your Mongo DB Connection URL)
    PRIVATE_KEY = (Your Private Key ex. "any String")

Now run 

    npm install

    node server.js

Now You've Successfuly Started Your Server

Now well start front-end: 

Now Start a new terminal and keep the old one running and run : 

    cd ../Eventopia-web/

    npm install 

    touch .env 

Now Write the following in .env file : 

    VITE_REACT_API_URL = "http://localhost:8080"

Now Run: 

    npm run dev

Congratulations You've Successfully cloned this app!

Now Make Changes and if you want add new features and make a Pull Request. 

## Features : 

1. View All Events and add to your calendar:
2. Signup and Post your own events
3. Edit and delete your events ( in development )
4. Filter to events starting current date so you dont see old events
	
	
	
