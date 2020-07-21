# assessment
Assessment of Lynkyt 
Run Angular/ ReactJs on port 5000.
Soln: for changing the port,  I went to Package.JSON and change the scripts property to set PORT=5000
2. Create a registration form with proper Validations having fields

Name, Email, Mobile, Password, Confirm password
Password must include at least an uppercase, a number & a special character.
Replicate the same on a button click, means multiple registration can be performed
at a single time.
Soln: I have attached all the JS file for these questions.
 
4. Submit the form using node API & Mongo DB (Password must be encrypted or hash)
(use Mongoose)
Soln: For encryption, I used bcrypt library to hash the password and then saved it to MongoDb with the help of Mongoose

5. Create an API for login.
Soln: With the help of axios library, I created post method API call to send data from React application to Node js

6. Create a web socket connection after login.
Soln: Server is created using node js and was listening on port 9000

7. Use an image as background, image always be in full screen whether it is rendered
on any device (responsive).
Soln: media-query is used to make image responsive for all types of screen

8. Send mail to users after registration. (Use your own Gmail cred.)
Soln: nodemailer library of node js is used to send mail to user on successful registration.
