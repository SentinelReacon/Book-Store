# Book-Store

This repo illustrates the Book Store project using the MERN stack.



### Requirements 
For running this project, all the components of the MERN stack ([MongoDB](https://www.mongodb.com/), [Express JS](https://expressjs.com/), [React JS](https://react.dev/) and [Node JS](https://nodejs.org/en)) are required. All the softwares can be installed using the links given.
### Setting up the database
In this project we are using the MongoDB Atlas cloud database. To setup your own database, you need to create a free tier [MongoDB account](https://www.mongodb.com/cloud/atlas/register) and then after registering create a new database. 
Once you create a database we need to connect the database to our backend. For this click on the **connect** button above the cluster name as shown in the figure below
![Screenshot from 2023-09-13 11-57-24](https://github.com/SentinelReacon/Book-Store/assets/84021424/b7157bf6-470c-4e8e-98f0-2b6c8633cb45)
After clicking on the connect you will see various options to connect to the database. Click on the **Drivers** option and you will be redirected to this screen. 


![Screenshot from 2023-09-13 11-59-53](https://github.com/SentinelReacon/Book-Store/assets/84021424/3d0e2546-69c0-4cd3-bd2b-928042100b2a)


Follow all the instructions given there and copy the **connection string** and replace it in `mongoDBURL` in `config.js`. Your database is now ready. 

### Running the project
Make sure there are two directories **backend** and **frontend**. Make sure you have installed all the above softwares and Node Package Manager ([npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)). You can check the version of npm using `npm --version` or `npm -v` and make sure it is up to date. 

#### Backend
For running the backend, change the directory to backend using `cd backend/` and then use the following command to start the backend server `npm run dev`. This command will start the backend server and make sure to keep it running. 

#### Frontend
For running the frontend, open a new terminal and change the directory to frontend using `cd frontend/` command and then use `npm run dev` to start the frontend. Then a url will be generated and you can go to that url where the frontend is hosted. 
