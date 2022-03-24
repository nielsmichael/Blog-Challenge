# Blog Challenge
This is a simple Blog web application using Javascript, EJS, a NodeJS backend, and a MongoDB database (on localhost). 

The primary purpose of this project is to familiarize myself with the above frameworks and experiment with passing data back and forth between front-end and back end.

## How to Use
Pretty much anyone can use this. All you would need to do is set up a MongoDB server on your local device. 

If you are using an M1 Macbook pro (as I am), then running MongoDB is going to look a little bit different depending on where your MongoDB files are located.

In my case, my db folder to run a local server is in /System/Volumes/Data/. So instead of simply running:

mongod

On my M1 Macbook I have to run:

sudo mongod --dbpath /System/Volumes/Data/data/db

Enter my password, and then its good to go.
