<h1 align="center"> Company_Employee_Manager </h1>

## General info
This site is used to register companies and employees of any company.
CRUD operations can be performed on both companies and employees of any company.
	
---  

## Technologies
Project is created with:
* Express version: ~4.16.1
* mongoose version: ^5.12.1
* cookie-parser version: ~1.4.4
* nodemon version: ^2.0.7
* ejs version: ~2.6.1

---

# Installation
```bash
npm install
```

---

## Usage
```bash
npm start
```
After running the project, you must first create an admin. To do this, you must send a post request with body in the form below to "localhost:8080/auth/createAdmin".
```json
{
	"username": "admin",
	"firstName": "adminFirstName",
	"lastName": "adminLastName",
	"password": "0000000000",
	"gender": "man",
	"mobileNumber": "989999999999"
}
```
After sending this request, this url only gives 404 error in response to requests.

---

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## License
© MohammadReza Mirzade
Licensed under the  [GNU GPLv3](LICENSE)
