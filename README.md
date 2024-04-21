# f-fsw-24001086-km6-nau-rest-api-ch5
<div id="top"></div>

<br />
<div align="center">
    <img src="docs/logo_rm.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Challenge 5 Binar Fullstack Web</h3>

  <p align="center">Rest Api Swagger</p>
</div>


## ABOUT THE PROJECT


### Built With

- Dotenv
- ExpressJS
- Bcrypt
- Sequelize
- Postgres
- Imagekit


### Tabel database

![erd](docs/dbdiagram.png)

## REST API Endpoints
### Auth

Test untuk mengotentikasi pengguna dalam sebuah sistem.

#### *HTTP Request*
> **POST**   
> `/auth/login
> 

#### *Default Request URL*

    "http://localhost:3000/api/v1"

#### *Expected Response*
Response Code: `200`  
Response Type: `application/json`  
Response Body:  

   "{
      "status": "Success",
      "message": "Berhasil login",
      "data": "token"
    }"



