# ProShop eCommerce App

> eCommerce platform built with the MERN stack.
> 
![Screenshot (254)](https://user-images.githubusercontent.com/96475717/147317202-518adfd6-3545-4f56-84aa-e3c57715b76f.png)
>products screen
![Screenshot (255)](https://user-images.githubusercontent.com/96475717/147317756-287c14e8-2473-45aa-9836-e36195686102.png)

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
