# MERN AMAZONA

# Lessons

1. Introduction
2. Install Tools
3. create React App
4. Create Git Repository
5. List Products
   1. create products array
   2. add product images
   3. render products
   4. style products
6. Add routing
   1. npm i react-router-dom
   2. create route for home screen
   3. create route for product screen
7. Create Node.JS Server
   1. run npm init in root folder
   2. Update package.json set type: module (setiing type to module enables the use of IMPORT instead of REQUIRE)
   3. Add .js to imports
   4. npm install express
   5. create server.js
   6. add start command as node backend/server.js
   7. require express
   8. create route for / return backend is ready
   9. move products.js from frontend to backend
   10. create route for /api/products
   11. return products
   12. run npm start
8. Fetch Products from backend

   1. set proxy in package.json
   2. npm install axios
   3. use state hook
   4. use effect hook
   5. use reducer hook

9. Manage State By Reducer Hook

   1. define reducer
   2. update fetch data
   3. get state from useReducer

10. Add Boostrap UI Framework
    npm install react-bootstrap bootstrap
    update App.js

11. Create product and rating Component
    create rating components
    create product component
    use rating component in product component

12. Create Product Details Screen
    fetch product from backend
    create 3 columns for image, info and action
13. Create Loading and Message Component
    create loading component
    use spinner component
    create message component
    create utils.js to define getError fucntion
14. Implement Add To Cart
    Create react Context
    define reducer
    create stoe provider
    implement add to cart button create handler
15. Complete Add to Cart
    check exist item in the cart
    check count in stock in backend
16. Create Cart Screen
    create 2 columns
    display items list
    create action column
17. Complete Cart Screen
    create handler for inc/dec item
    create handler for remove item
    create handler for checkout
18. Create Signin Screen
    create signin form
    add email and password
    add signin button
19. Connect to mongo Database
    create atlas mongodb database
    install local mongodb database
    npm install mongoose
    connect to mongodb database
20. Seed Sample data
    create product model
    create user model
    create seed route
    use route in server.js
    seed sample product
21. Seed sample users
    create user model
    seed sample users
    create user routes
22. Create Signin Backend API
    1. create signin api
    2. npm install jsonwebtoken
    3. define generateToken
23. Complete Signin Screen
    1. Handle submit action
    2. save token in store and local storage
    3. show user name in header
24. Create shipping screen
    1. create form inputs
    2. handle save shipping address
    3. add checkout wizard bar
25. Create Sign Up Screen
    1. create input forms
    2. handle submit
    3. create backend api
26. Implement Select Payment Method Screen
    1. create input forms
    2. handle submit
27. Create Place Order Screen
    1. show cart items, payment and address
    2. handle place order action
    3. create order create api
28. Implement Place Order Action
    1. handle place order action
    2. create order create api
29. Create Order Screen
    1. create backend api for order/:id
    2. fetch order api in frontend
    3. show order information in 2 columns
30. Pay Order By Paypal
    1. generate paypal client id
    2. create api to return client id
    3. install react-paypal-js
    4. use PayPalScriptReducer in index.js
    5. use usePayPalScriptReducer in Order Screen
    6. implement loadpayPalScript function
    7. render paypal button
    8. implement onApprove payment function
    9. create pay order api in backend
31. Display Order Hostory
    1. create order screen
    2. create order hostory api
    3. use api in the
32. Create Profile Screen
    1. get user info from context
    2. show user information
    3. create user update api
    4. update user info
33. publish to Heroku
    1. create and config node project
    2. serve build folder in frontend folder
    3. create heroku account
    4. connect it to githun
    5. create mongodb atlas database
    6. Set database connection in heroku env variables
    7. commit and push
