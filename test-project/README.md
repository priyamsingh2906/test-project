This is a project made using MEAN stack. This project includes authentication and authorization. Once the user is able to login after signing up they will be able to "Add a Post". Since the authorization is there no user other than the original user who has created the post will be able to perform any operation on the existing data. This app contains basic CRUD operations except the eedit functionality which will be added later on. In further updated image upload and download functionality will also be added and the design of the app will be changed a bit which will make it look more like a drive/file explorer.

Command for backend: npm run start:server
Command for frontend: ng serve



In this app, once the user is done with signing up and login, the user will be able to add a post with some title and content. Once the post is added an entry will be created in the db(mondodb cluster) with title and content and self incrementing id. For authentication and authorization a seperate entry will be created in a seperate schema. Only the user with correct login id and password will be able to see the existing posts/messages. If the user idd and password does not exist in the db, the user will not be able to login and he needs to sign up first. Once the user is done signing up, he will be redirected to login page where he needs to login through same username and password.
