# MERN STACK SOCIAL MEDIA APPLICATION


This project is a full-stack social media application that has been developed using the MERN stack. The application includes a registration page that has complete validation, and users can upload their images for their profiles. After registering, users can log in to the application and access the home page. The home page is only accessible to users with a valid token, and those who don't have a token are redirected to the login page.
The home page has a clean design with several widgets that provide information about the current user who is signed in. Users can add a post with a description and an image, and they can edit or delete the image before posting it. Users can see the posts they have created and view the newsfeed of other users' created posts. They can like or dislike a post, view the comments, and even add friends.
The friend list widget is updated automatically when a user adds or removes a friend. The application also has an advertisement widget that displays information about posts with an image. Users can click on a name in the post widget to view the friend or user's profile page.
On the profile page, users can view their information, friend list, and posts. They can also add a post from the profile page. The application also has the ability to switch between light mode and dark mode. The website is completely responsive, so users can access the exact same website from smaller screens with modifications for everything.
The backend API retrieves all the information from a MongoDB database, and the backend is developed using the Express framework of Node.js. React is used as the front-end framework, with React Router for navigation, Formik and Yup for form and form validation, Redux Toolkit for state management, and Redux Persist to store Redux state in local storage. Dropzone is used for image upload, and Node.js is used for runtime on the backend. Mongoose is used for managing the MongoDB database, and Json Web Token is used for authentication. Multer is used for file upload.


.Create a .env file in the server directory and set the following environment variables:

  MONGO_URL=<your_mongodb_url>
  JWT_SECRET=<your_jwt_secret>
  PORT=<set_port>

Features

The following are the features that have been implemented in this  social network app:

-Sign up/sign in: Users can sign up for a new account or sign in with an existing account. Passwords are securely hashed before being stored in the database.

-Create a profile: Users can create a profile for themselves by providing their name, location,occupation,email and profile picture.

-Search for other users: Users can search for other users by name.

-View other users' profiles: Users can view other users' profiles by clicking on their name. They can also see the number of friends that the user has.

-Add/Remove Friends: Can add or remove friends from their profile page or home page.(This option will be disabled While viewing their own profile page).

-View Mutual Friends: The logged in user is able to view any mutual friends in the viewed profile

-Posts Functionality: Every user is able to see all posts in the home page where general posts of every user will be displayed.

-Add Posts: Each logged in user is able to add a post to their feed which will be showe on their own profile and in the general feed.

-Update posts: Likes for each posts are counted separately and displayed and it is kept track of which users have liked the posts already.

Dependencies
The following are the major dependencies that have been used in this project:

-React JS: A JavaScript library used for building user interfaces.

-Node.js: A JavaScript runtime used to build server-side applications(Runtime Environment for Javascript).

-MongoDB: A NoSQL document database used to store data in a flexible, JSON-like format.

-Express: A web application framework for Node.js used to build APIs and web applications.

-bcrypt: A library used to hash and salt passwords.

-jsonwebtoken: A library used to generate and verify JSON Web Tokens (JWTs).

-multer:Used for handling file uploads

-formik,yup-: They are used for form validation

-dropzone:It used to provide a drag and drop interface for file uploads in the client
