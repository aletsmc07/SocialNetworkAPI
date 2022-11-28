# Social Media API
## _API for a social network web application._

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Command line app that helps you to control of your employees.
- Register or Delete users.
- Interact with friends, sharing thoughts.

## Content
- [Features](#Features)
- [Tech](#Tech)
- [Installation](#Installation)
- [Links](#Links)
- [Screenshots](#Screenshots)
- [License](#License)
- [Contact](#Contact)

## Features

- Add, delete or update users.
- Add or remove friends.
- Share thoughts, update them and react.
- Create a friend list

[Content](#Content)

## Tech

This app was made with:

* [![JavaScript][JavaScript]][JavaScript-url]
* [![MongoDB][MongoDB]][MongoDB-url]
* [![NodeJS][Node.js]][Node.js-url]
* [![Express][Express]][Express-url]
* [![Insomnia][Insomnia]][Insomnia-url]

[Content](#Content)

## Installation

Clone the repository on your PC, open it on Visual Studio Code or other source code editor of your choice and follow the next steps:
- Open the terminal and install all dependencies (Inquierer) :
```
    npm install inquirer
```

- Create an .env file and change the sata with your own info if applicable:
```
    DB_HOST= localhost
    DB_PORT= 3306
    DB_USER= yourUser
    DB_PASS= yourPassword
```

- To create and run database start MySQL:
```
    #work on MySQL
        mysql -u root -p
        
    # to create the DB schema
        db/SOURCE schema.sql
    
    # to add some data (optional; this example contains data to show that the app works)
        db/SOURCE seeds.sql
```

- To start the app (maybe you will need to open other commandline without close or stop MySQL and type the next command:
```
    node index.js
```

Please, install Node JS (link of the specified in Tech section) before run the commands.

[Content](#Content)

## Links

- [Github repository](https://github.com/aletsmc07/SocialNetworkAPI)
- No deployed app link, run it in terminal.

[Content](#Content)

## Screenshots


[Content](#Content)

## License

Distributed under the GPL-3.0 License. See `LICENSE.txt` for more information.

**Educational Software**

[Content](#Content)

## Contact

- Alejandro Mince [![Github][aletsmc07]][Github6-url] [![Gmail][gmail6]][gmail6-url]


<!-- SHIELDS -->
[JavaScript]: https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black
[JavaScript-url]: https://developer.mozilla.org/es/docs/Web/JavaScript
[MongoDB]: https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=MongoDB&logoColor=white
[MongoDB-url]: https://www.mongodb.com/
[Node.js]: https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white
[Node.js-url]: https://nodejs.org/en/
[Express]: https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=Express&logoColor=white
[Express-url]: https://expressjs.com/
[Insomnia]: https://img.shields.io/badge/Insomnia-4000BF?style=for-the-badge&logo=Insomnia&logoColor=white
[Insomnia-url]: https://insomnia.rest/

[aletsmc07]: https://img.shields.io/badge/aletsmc07-181717?style=for-the-badge&logo=Github&logoColor=white
[Github6-url]: https://github.com/aletsmc07
[gmail6]: https://img.shields.io/badge/alejandro.mince07@gmail.com-EA4335?style=for-the-badge&logo=Gmail&logoColor=white
[gmail6-url]: mailto:alejandro.mince07@gmail.com
