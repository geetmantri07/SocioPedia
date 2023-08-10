
<br/>
<p align="center">
  <h3 align="center">Building a Community of Developers and Ideas</h3>

  <p align="center">
    Promoting Open Source Collaboration - Connect, Contribute, and Innovate Together
    <br/>
    <br/>
    <a href="https://github.com/rawasaditya/SocioPedia/issues">Report Bug</a>
    <a href="https://github.com/rawasaditya/SocioPedia/issues">Request Feature-</a>
  </p>
</p>

# SocioPedia

Simple opensource social media platform, this platform will mark its wonder over all social media platform in world.


## Getting started

#### Prerequisites
Before getting started, make sure you have the following prerequisites:

- Node.js installed
- Git installed
- npm (Node Package Manager) installed
 - A code editor such as Visual Studio Code or any other preferred code environment
Make sure you have these prerequisites installed and set up on your system before proceeding with the project setup.

### Getting Started
- Clone project.
    ```git clone https://github.com/rawasaditya/SocioPedia.git```
#### Setting up server
- Step in server folder ```cd ./server```
- Install dependecies ``` npm ci ```
- Update `.env` file with following variables

    ```process.env.API_PORT=5002```
    ```process.env.MONGO_URL="mongodb://127.0.0.1:27017/socialMedia"```
    ```process.env.JWT_SECRET=4PJqnalPar```

    OR CREATE OWN .env FILE INSIDE ./server AND UPDATE FOLLOWING IN 

    ```API_PORT=5002```

    ```MONGO_URL="mongodb://127.0.0.1:27017/socialMedia"```

    ```JWT_SECRET=4PJqnalPar```
- To start server hit ```npm run start```


#### Setting up frontend

- Step in server folder ```cd ./frontend```
- Install dependecies ``` npm ci ```
- To run project ```npm run dev```
