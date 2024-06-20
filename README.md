# Uploading_backend
1. npm init -y  - To install all package.json file
2. npm i express - To install all nodes modules and express 
3. node <filename>.js -  Generally to run all the server 


4 .npm i nodemon - Same as frontend liveserver auto sync and up to date 
makes changes in pacakage.json files as follows:
    "scripts": {
        "start": "node index.js",
        "dev": "nodemon index.js"
    },
5. npm run dev - to run server 

6. npm i dotenv - to export enviornment variables seperately
7. npm install mongoose - to connect server or application with MongoDB database
8. npm install nodemailer - provider functionality of sending mails
9. npm install cloudinary - cloud based media platform for storing files and images with aditionaly functionality such as croping, resizing, compressing etc
10. npm install express-fileupload - used to handle temporary storage of server 

Additionally project needs 
1. MongoDB setup
2. MongoDB Shell
3. MongoDB compass
4. Postman API setup
5. Cloudinary platform free plan login
6. Any mail service preffers (Gmail)


//routes to test via postman
http://localhost:3000/api/v1/upload/imageSizeReducer
http://localhost:3000/api/v1/upload/videoUpload
http://localhost:3000/api/v1/upload/imageUpload
http://localhost:3000/api/v1/upload/localFileUpload
