# ProShop eCommerce App

> eCommerce platform built with the MERN stack.

![screenshot](C:\Users\Abhishek\Pictures\Screenshots\Screenshot (254).png)

## Features

- Full featured shopping cart
- Product reviews and ratings
- Top products carouse
- Product search feature
- User profile with orders
- Admin product management
- Admin user management
- Admin Order details page
- Database seeder 


### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = your paypal client id
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```

### Seed Database

You can seed your database using the following commands to get dummy data

```
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

```
Dummy Users

admin@example.com (Admin)
123456

john@example.com (Customer)
123456

jane@example.com (Customer)
123456
```
