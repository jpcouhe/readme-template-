
[![Contributors][contributors-shield]][contributors-url] [![Forks][forks-shield]][forks-url] [![Stargazers][stars-shield]][stars-url] [![Issues][issues-shield]][issues-url]

# Name of the Project
Rapid description | Keywords

## Features

[![Product Name Screen Shot][product-screenshot]](https://example.com)

Here is where you describe the project 

## 🔨 Technologies 

* Frontend 
    - Framework **Angular**
    - **SCSS**

* Backend
    - Serveur **Node.JS** and Framework **Express**
    - Packages: Multer, JsonWebTokens, uuid, helmet, nodemon, dotenv, keyv & bcryp
    - Database **MYSQL**



## 🏗️ Installation


- Clone this project from Github
- Make sur you have Node.js and Angular installed.
    ### 🔍 Frontend
    
This project was generated with Angular CLI version 13.3.5.

- `cd `
- `npm install`
- Run `ng serve` for a dev server. Navigate to http://localhost:4200/ . The app will automatically reload if you change any of the source files.

    ### 🔍 Backend
This project was generated with NodeJs v16.14.0

    #### Prepare the MySQL database 
    
    1. Se connecter à MySQL
    
    ```
    mysql -u root -p # root is your user name, then enter your password
    ```
    
    2. In MySQL


    ``` 
    --1: Create new base
    CREATE DATABASE social_network CHARACTER SET 'utf8'; 
    ```
    ```
    USE social_network;
    ```
    
    3. Add tables in the new database with the file BDD.sql

    ```
    SOURCE ../Docs/social_network.sql 
    use the correct path
    ```
    

- `cd `

#### 🚧 In dev mode :
        
- `npm install`
- `npm start`
you will access to more packages (...)

#### 🚀 In product mode :
        
- `npm install --only=prod`
- `npm run start:prod #`
With nodemon the app will automatically reload if you change any of the source file.

After npm is done installing, set any environment variables in a .env file (in the folder Backend) , with this key :

```
environment variable
```

## 🏗️ Usage

## 📬 Contact 

## 😊 Acknowledgements