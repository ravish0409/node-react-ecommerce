Welcome to my React and Node fully-functional e-commerce website.

## Run Locally

### 1. Clone repo

```
$ git clone git@github.com:kushwaha-suraj/node-react-ecommerce.git
$ cd node-react-ecommerce
```

### 2. Install MongoDB

Download it from here: https://docs.mongodb.com/manual/administration/install-community/

### 3. Run Backend

```
$ npm install
$ npm start
```

### 4. Run Frontend


For New version of node:

first run ```set NODE_OPTIONS=--openssl-legacy-provider to solve digital envelope routines```


```
# open new terminal
$ cd frontend
$ npm install
$ npm start
```

### 5. Create Admin User

- Run this on chrome: http://localhost:5000/api/users/createadmin
- It returns admin email and password

### 6. Login

- Run http://localhost:3000/signin
- Enter admin email and password and click signin

### 7. Create Products

- Run http://localhost:3000/products
- Click create product and enter product info

