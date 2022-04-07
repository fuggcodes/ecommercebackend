# ecommercebackend
A interactive E-Commerce back end utlizing Object-Relational Mapping as power be Sequelize

## installation
please ensure you have the required NPM modules and MySQL installed installed locally 
clone this repo and install npm modules using following commands. 
Ensure your SQL Database is running 

via commandline:
`mysql -u root -p` 
when prompted enter your password 
then exit by typing 
`quit`

to run the application we need to first seed the database use the following command via gitbash Commandline:
`npm run seed`
this will build the databases we will be manipulating. 

once database is built start your server using the following command 
`npm start`  

once the server is live then you can Cycle through CRUD options via Insomnia Core / postman. 

The api endpoints are as follows:
* Categories:
http://localhost:3001/api/categories
* Tags
http://localhost:3001/api/tags
* Products 
http://localhost:3001/api/products 




## credits
This app was built with:
* Javascript 
* express 
* Sequelize
* mysql2 
* dotenv

## github user name
fuggcodes