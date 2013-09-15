# Angular MySQL Application

This application is a sample CRUD application built with Angular.js and MySQL and a RESTful API.

## Uses

1. Angular.js v1.0.8 (current stable release)
2. MySQL
3. PHP Slim framework (API)

## Set Up

1. Create a MySQL database name 'angular-mysql'
2. OPTIONAL: Run install/angular-mysql.sql to create and populate the 'users' table (includes four dummy users)
3. Create Apache virtual root and point to 'app' folder
    
## Notes

* The .htaccess file in the 'app' folder redirects all requests to index.html (needed by Angular application)

## API Endpoints

GET     /api/users                  Gets all users
POST    /api/users                  Creates a new user
GET     /api/users/:id              Gets a user by Id
GET     /api/users/search/:query    Searches user by name
PUT     /api/users/:id              Updates a user by Id
DELETE  /api/users/:id              Deletes a user by Id