# backend-attainu

### Project Installation

```shell
 git clone https://github.com/saidul-mondal-au7/backend-attainu.git
 cd backend-attainu-main
 npm install
```

### Configuration
create a dev.env file and set
* PORT=3000
* MONGO=`Your Database Address`
* JWT_SECRET=`your secret`

### Running The Project
```shell
npm start
```

### Routes for postman 

click `Body` set it `raw` and `JSON` in postman.

1. Sign up : request-POST `http://localhost:3000/users`
2. Login : request-POST `http://localhost:3000/users/login`
3. Image Thumbnail Generation : request-POST `http://localhost:3000/users/me/avatar`
4. Add Adress/update : request-PATCH `http://localhost:3000/users/me`
5. Delete Thumbnail : request-DELETE `http://localhost:3000/users/me/avatar`
6. Logout : request : request-POST `http://localhost:3000/users/logout`
7. Logout all session : request-POST `http://localhost:3000/users/logoutAll`
8. Delete yourself : request-DELETE `http://localhost:3000/users/me`
