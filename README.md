# AthleticMetric

We are Athletic Metrics, and we are a sports statistics website, here to store your stats, in our state of the art application. 
Deployed and reachable through: https://frontend-0tps.onrender.com/ 

## Technologies 
Full MERN stack
## Mission
Our mission with this project is to develop a centralised hub to store player statistics. Frequently, individual sports will have their respective websites for their stats, and as avid sports followers, it can get tedious to go from webpage to webpage. Therefore, we want to develop a sleek, modern, accessible and straightforward interface, displaying heaps of information regarding goals scored, ages, names, teams and so on, for all mainstream sports.

## Screenshots
- Home Screen
  
![HomeScreen](https://github.com/NitpreetA/AthleticMetric/assets/98350822/ebbc270d-fb2e-4d91-a4bc-397abdaaf281)

- The Teams for each respective sport
  
![ExamplePage](https://github.com/NitpreetA/AthleticMetric/assets/98350822/bc7eebcc-da63-4f5a-8123-e9f034c07ea0)

- The admin panel that would allow you to create teams players and stats

![Options](https://github.com/NitpreetA/AthleticMetric/assets/98350822/d155f9f4-61d6-4c06-a677-30b9f056890d)

## Using Website 
### When visting deployment
1) The backend often takes a few minutes to start up when opening the page.
2) For some reason, cookies do not work on the deployed version on chrome and some other browsers. We recommend Firefox (This is a non-issue on the local version).

### If wanting to run locally

1) Create a mongodb and store the the the password, Post and Pre in a .env as such.
   
   -MONGODB_PWD="example
   
   -URL_PRE="example"
   
   -URL_POST="example"
   
   -FRONT_END=http://localhost:3000
   
3) Then when downloaded or cloned run the backend
   
   -cd ./backend
   
   -npm i
   
   -node server.js
   
6) Then run the frontend
   
   -cd ./frontend
   
   -npm i
   
   -npm start
   
8) Navigate to the following URL to access the frontend page:
http://localhost:3000/

## Authors
Nitpreet Arneja 
Aidan Grant-Ushinsky
Ron Fudim 
