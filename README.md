fcomplete the webapi
===========================================

Steps
-----

### create directory, config files and download deps
```
mkdir restful-webAPI

cd restful-webAPI

npm init

npm install express --save
```

### use `nodemon` to auto-reload

```
npm install -g nodemon
```

### write code

The code is already in this project

### run code
```
node app.js
```
or

```
nodemon app.js
```

### visit

start the server in the terminal

use the tool of postman to visit

for example:

```
insert-product(post):http://localhost:3000/products

get-all-products(get):http://localhost:3000/products

get-one-product(get):http://localhost:3000/products/2

delete-product(delete):http://localhost:3000/products/3

update-product(put):http://localhost:3000/products/1
```
