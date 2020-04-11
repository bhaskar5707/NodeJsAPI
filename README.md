REST API WITH NODEJS AND JWT
Login : http://localhost:3000/api/users/login
Register : http://localhost:3000/api/users/
{
	"first_name":"sunil kumar",
	"last_name":"bhaskar",
	"gender":"M",
	"email":"test2@gmail.com",
	"password":"123",
	"number":"9910625707"
}
Delete : http://localhost:3000/api/users/1
All User : http://localhost:3000/api/users/
User By Id : http://localhost:3000/api/users/2
PATCH : http://localhost:3000/api/users
{
	"id":2,
	"first_name":"sunil kumar",
	"last_name":"bhaskar",
	"gender":"M",
	"email":"test@gmail.com",
	"password":"123",
	"number":"9910625707"
}


npm init -y
npm install express
npm install express mysql body-parser --save
npm install mysql
npm install dotenv
npm install --save-dev nodemon
npm install bcrypt
npm install jsonwebtoken