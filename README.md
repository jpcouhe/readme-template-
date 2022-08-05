
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

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/NicolasBrondin/basic-readme-template.svg?style=flat-square
[contributors-url]: https://github.com/NicolasBrondin/basic-readme-template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/NicolasBrondin/basic-readme-template.svg?style=flat-square
[forks-url]: https://github.com/NicolasBrondin/basic-readme-template/network/members
[stars-shield]: https://img.shields.io/github/stars/NicolasBrondin/basic-readme-template.svg?style=flat-square
[stars-url]: https://github.com/NicolasBrondin/basic-readme-template/stargazers
[issues-shield]: https://img.shields.io/github/issues/NicolasBrondin/basic-readme-template.svg?style=flat-square
[issues-url]: https://github.com/NicolasBrondin/basic-readme-template/issues
[license-shield]: https://img.shields.io/github/license/NicolasBrondin/basic-readme-template.svg?style=flat-square
[license-url]: https://github.com/NicolasBrondin/basic-readme-template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: docs/cover.jpg