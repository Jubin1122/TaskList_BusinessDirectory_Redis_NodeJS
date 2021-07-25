# Task Manager Web Application using Nodejs and Redis Client
In this project I have developed a Task Manager using Node js and redis client.<br />
The idea behind is to develop a higly optimized application where there will be less latency, increase throughput, and ease the load off the relational or NoSQL database and application.<br />
I have used embedded javascript templating(ejs), which is a templating engine used  by Node.js. Using this I have to write very minimal code for the view(front-end).
Also, this rendered data to html using get and post at the client side.<br /><br />
This application will be able to add tasks, which will populate in a task lists,and can to remove/delete tasks. I have used array list to sore data, and push it into redis client.
Furthermore, the user can also fix a business call by enter the requisite information in a form. I have implemented this functionality using a hashmap, which store the data save it into redis client.<br />
This system design can be integrated in many web applications, and in conjuction with other nosql and relational database; thus, will provide an efficient methodology to broadcast most frequent (high demand) data. 

![Alt text](./img/redisapp.png?raw=true "Optional Title")

## Project Setup


To generate a `package.json` file for a redistask. We have to follow below steps.

```
cd redistasks
npm init
---------------
Name: (redistasks)
Version: (1.0.0)
Description: Simple task manager
Entry point: (index.js) app.js
Rest click enter
....
....
```

In package.json we will add all the dependecies that is required in our applications.

![Alt text](./img/dependecies.png?raw=true "Optional Title")

### Command to install node_modules folder.

`npm install`

After each operation we always have to connect to redis server, therefore it is better to run **nodemon**.

```
sudo npm install nodemon -g
nodemon
```

