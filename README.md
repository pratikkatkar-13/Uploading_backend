# Uploading_backend
npm init -y  - To install all package.json file
npm i express - To install all nodes modules and express 
node <filename>.js -  Generally to run all the server 


npm i nodemon - Same as frontend liveserver auto sync and up to date 
makes changes in pacakage.json files as follows:
    "scripts": {
        "start": "node index.js",
        "dev": "nodemon index.js"
    },
npm run dev - to run server 

npm i dotenv - to export enviornment variables seperately
npm install mongoose - to connect server or application with MongoDB database
npm install nodemailer - provider functionality of sending mails
npm install cloudinary - cloud based media platform for storing files and images with aditionaly functionality such as croping, resizing, compressing etc
npm install express-fileupload - used to handle temporary storage of server 

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
