#MERN ShoppingApp

#Activities

1. Create React App

2. Create Git Repository

3. List products
   1.create products array
   2.add product images
   3.render products
   4.style products

4. Add Routing

   1. npm i react-router-dom
   2. create route for home screen
   3. create router for product screen

5. Create Node.JS Server

   1. run npm init in root folder
   2. Update package.json set type: module
   3. Add .js to imports
   4. npm install express
   5. create server.js
   6. add start command as node backend/server.js
   7. require express
   8. create route for / return backend is ready.
   9. move products.js from frontend to backend
   10. create route for /api/products
   11. return products
   12. run npm start

6. Fetch Products From Backend

   1. set proxy in package.json
   2. npm install axios
   3. use state hook
   4. use effect hook
   5. use reducer hook

7. Manage State By Reducer Hook

   1. define reducer
   2. update fetch data
   3. get state from usReducer

8. Add bootstrap UI Framework

   1. npm install react-bootstrap bootstrap
   2. update App.js

9. Create Product and Rating Component

   1. Create Rating component
   2. Create Product component
   3. Using Rating component in product component

10. Create Product Details Screen

    1. fetch product from backend
    2. create 3 columns for image, info and action

11. Create Loading and Message Component

    1. create loading component
    2. use spinner component
    3. craete message component
    4. create utils.js to define getError fuction

12. Create React Context For Add Item To Cart

    1. Create React Context
    2. define reducer
    3. create store provider
    4. implement add to cart button click handler

13. Complete Add To Cart

    1. check exist item in the cart
    2. check count in stock in backend

14. Create Cart Screen

    1. create 2 columns
    2. display items list
    3. create action column

15. Complete Cart Screen
    1. click handler for inc/dec item
    2. click handler for remove item
    3. click handler for checkout

16. Create Signin Screen
    1. create sign in form
    2. add email and password
    3. add signin button

17. Connect To MongoDB Database
    1. create atlas monogodb database
    2. install local mongodb database
    3. npm install mongoose
    4. connect to mongodb database

18. Seed Sample Products
    1. create Product model
    2. create seed route
    3. use route in server.js
    4. seed sample product

19. Seed Sample Users
    1. create user model
    2. seed sample users

20. Create Signin Backend API
    1. create signin api
    2. npm install jsonwebtoken
    3. define generateToken

21. Complete Signin Screen
    1. handle submit action
    2. save token in store and local storage
    3. show user name in header

22. Create Shipping Screen
    1. create form inputs
    2. handle save shipping address
    3. add checkout wizard bar

23. Create Sign Up Screen
    1. create input forms
    2. handle submit
    3. create backend api

24. Implement Select Payment Method Screen
    1. create input forms
    2. handle submit

25. Create Place Order Screen
    1. show cart items, payment and address
    2. handle place order action
    3. create order create api

26. Implement Place Order Action
    1. handle place order action
    2. create order create api

27. Create Order Screen
    1. create backend api for order/:id
    2. fetch order api in frontend
    3. show order information in 2 cloumns

28. Pay Order By PayPal
    1. generate paypal client id
    2. create api to return client id
    3. install react-paypal-js
    4. use PayPalScriptProvider in index.js
    5. use usePayPalScriptReducer in Order Screen
    6. implement loadPaypalScript function
    7. render paypal button
    8. implement onApprove payment function
    9. create pay order api in backend

29. Display Order History
    1. create order screen
    2. create order history api
    3. use api in the frontend

30. User Profile Screen

    1. create user profile
    2. add form to update user details

31. Publish to Heroku

    1. create and config node project
    2. serve build folder in frontend folder
    3. create heroku account
    4. connect it to github
    5. create mongodb atlas db
    6. set database connection in heroku env variables
    7. Commit and push

32. Add Sidebar and Search Box

    1. add sidebar
    2. add search box

33. Create Search Screen

    1. show filters
    2. create api for searching products
    3. display results

34. Create Admin Menu

    1. define protected route component
    2. define admin route component
    3. add menu for admin in header

35. Create Dashboard Screen

    1. create dashboard ui
    2. implement backend api
    3. connect ui to backend

36. Manage Products

    1. create product list ui
    2. implement backend api
    3. fetch data

37. Create Products

    1. create products button
    2. implement backend api
    3. fetch data

38. Edit Product

    1. create edit button
    2. create edit product ui
    3. display product info in the input boxes

39. Implement Update Product

    1. create edit product backend api
    2. handle update click

40. Upload Product Image

    1. create cloudinary account
    2. use api key in env
    3. handle upload file
    4. implement backend api to upload

41. Delete Product

    1. show delete button
    2. implement backend api
    3. handle onClick

42. List Orders

    1. create order list screen
    2. implement backend api
    3. fetch and display orders

43. Deliver Order

    1. add deliver button
    2. handle click action
    3. implement backend api for deliver

44. Delete Order

    1. add delete button
    2. handle click action
    3. implement backend api to delete
    
45. List Users

    1. craete user list screen
    2. implement backend api
    3. fetch and display user

46. Edit Users

    1. create edit button
    2. create edit product ui
    3. display product info in the input boxes
    4. implement backend api
    5. handle edit click

47. Delete Users

    1. add delete button
    2. handle click action
    3. implement backend api for delete

48. Choose Address On Google Map

    1. create google map credentials
    2. update .env file with Google api key
    3. create api and send google api to frontend
    4. create map screen
    5. fetch google api
    6. getUserLocation
    7. install @react-google-maps/api
    8. use it in shipping screen
    9. apply map to checkout screen

49. Email order receipt by mailgun

    1. create mailgun account
    2. add and verify your domain to mailgun
    3. install mailgun-js
    4. set api key in env file
    5. change pay order in orderRouter
    6. send email for receipt

50. Review Orders

    1. create submit review form
    2. handle submit
    3. implement backend api for review

51. Upload multiple images

    1. add images to product model
    2. get images in edit screen
    3. show images in product screen

52. Implement Live Chat With Customers

     1.  use socket io to create backend
     2.  create chat box component
     3.  create support screen