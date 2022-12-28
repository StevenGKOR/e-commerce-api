E-Commerce API is a server-side application, provide management of users, products and orders of an online store, developed with 
Javascript, Node.js, Express.js and MongoDB. Extra packages like docGen and JTW were used.

URL : https://e-commerce-api-cva2.onrender.com/

For security,packages like helmet,cors,rate-limiter,xss and mongoSanitize were used.
JWT used for registration/login.
Bcryptjs used for hashing passwords.
DocGen for a beautifull UI documentation.
Http-status-codes for specific status codes at responses depending on the requests of a user and the outcome of the response.
Mongoose for database connection and data management.
A middleware named error-handler handles the errors.
Authentication middleware checks the role of a user to provide or block the access to specific routes.

Τhe API provides the possibility to a user, with the cooperation of a front-end, to see the products that a store has. If he chooses to proceed with 
a purchase, he will have to sign in to the system or connect to an existing account, he can also order the available products and then leave a review, if he decided
to change the review she/he can also update it
If the user for some reason chooses to leave a second review, the API will stop it by giving an Εrror response to the front-end.
A user can see the information he has given during registration (email, name, password) and change them and finally 
the user can have access to the orders he has made
and modify them but only with the "cancel" value

For an administrator, the API provides literally everything what applies to the user.
Μoreover, he can add new products, delete them and update them.
She/he has access to all the orders and can manage them and see which user has made them, he also has access to all the users but only to 
see their information (except password)
