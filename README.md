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
- Open the terminal and install all dependencies:
```
    npm install
```

- Start the server:
```
    node server.js
```

Please, install Node JS, MongoDB and Insomnia (links specified in Tech section) before run the commands.

[Content](#Content)

## Links

- [Github repository](https://github.com/aletsmc07/SocialNetworkAPI)
- No deployed app link, run it in terminal.

[Content](#Content)

## Screenshots

Open Insomnia and you can start trying the routes:

For Users:

* Get all users: `GET` http://localhost:3001/api/users
![image](https://user-images.githubusercontent.com/107447818/204188022-16f79122-8599-4160-8ae3-fb1fe6bbd7cb.png)

* Get user by ID: `GET` http://localhost:3001/api/users/:userID
![image](https://user-images.githubusercontent.com/107447818/204188267-d907b119-4ceb-42dc-9081-910abde8e2bc.png)

* Create a new user: `POST` http://localhost:3001/api/users
![image](https://user-images.githubusercontent.com/107447818/204188477-be9b8ed8-5cf6-42e5-a9f4-4c6bf10be2a5.png)
![image](https://user-images.githubusercontent.com/107447818/204188604-8b1dde14-7a71-4d92-8dbd-bdc4744c4d2e.png)

```
//Example Data to ADD users
{
    "username": "Louis",
    "email": "louis@mail.com"
}
```

* Update a user: `PUT` http://localhost:3001/api/users/:userID
```
//Example Data to UPDATE users
{
    "email": "louisnew@mail.com"
}
```
![image](https://user-images.githubusercontent.com/107447818/204189466-453eb74e-b279-4640-9376-c68da7a1f3a5.png)

* Delete a user: `DELETE` http://localhost:3001/api/thoughts/:thoughtID
![image](https://user-images.githubusercontent.com/107447818/204189583-0a4a7deb-7106-46a6-9b34-3fc5e7b4e7e9.png)
![image](https://user-images.githubusercontent.com/107447818/204189611-ad5c844f-4598-4dfc-92cd-a28d82936b6d.png)


For friends:

* Add a friend to user's friend list: `POST` http://localhost:3001/api/users/:userID/friends/:friendID
![image](https://user-images.githubusercontent.com/107447818/204190153-849a2745-13d5-4c93-8f71-8bea1e8663a1.png)
![image](https://user-images.githubusercontent.com/107447818/204190222-dd6294e0-9c88-4908-9a3d-657911324e41.png)

* Delete a friend from a user's friend list: `DELETE` http://localhost:3001/api/users/:userID/friends/:friendID
![image](https://user-images.githubusercontent.com/107447818/204191043-7bb0484e-a066-4081-8ff8-cb88e00f997c.png)
![image](https://user-images.githubusercontent.com/107447818/204191094-12ebd333-647a-4b4c-9477-92c9d6a0af11.png)


[Content](#Content)

## License

Distributed under the GPL-3.0 License. See `LICENSE.txt` for more information.

**Educational Software**

[Content](#Content)

## Contact

- Alejandro Mince [![Github][aletsmc07]][Github6-url] [![Gmail][gmail6]][gmail6-url]

[Content](#Content)


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
