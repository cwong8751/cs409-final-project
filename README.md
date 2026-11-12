# cs409-final-project
Final project for cs409, uiuc sublease


# Project structure

```./backend``` contains the backend files 

```./uiuc-sublease``` contains the frontend files. 

# Install 

This project uses node v24, mongodb, react and express. 

Install node [Here](https://nodejs.org/en/download)

Clone project, then ```cd backend``` and run ```npm install ``` then ```cd .. && cd uiuc-sublease``` then run ```npm install```. 


Create a file called ```.env``` under ```backend```. Inside this file, add this line: 

```
MONGODB_URL=xxxx
```
You should get the ```xxxx``` part from the group chat. 


Open two terminal windows, one ```cd backend && node run server``` to start the server. One ```cd uiuc-sublease && npm run start``` to start the frontend. 
