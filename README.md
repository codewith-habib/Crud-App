# Crud-app
This is a CRUD (Create, Read, Update, Delete) application built with React. You can add employees, date, their salaries, can keep their records, etc. <br>The app is configured to run on port 80 using Nginx as the server, enabling seamless interaction and management of data. Its multi-stage design optimizes efficiency in the build process, ensuring a streamlined deployment experience.<br>
<h2>If you want to use this image without Docker, then follow these steps:</h2>
<h3>Step1:</h3>
Clone this repo
https://github.com/codewith-habib/crud-app.git
<h3>Step2:</h3>
Run npm install
<h3>Step3:</h3>
In case you get error of react-scrips not found, then run<br>
npm install react-scrpts
<h3>Step4:</h3>
Now run the project by<br>
npm start<br>
<h2>If you want to use this image with Docker, then follow these steps:</h2>
<h3>Step1:</h3>
Pull this image<br>
docker pull habib80246/crud-app
<h3>Step2:</h3>
Run this command:<br>
docker run -p 8080:80 habib80246/crud-app
<br>

Remember to change the port(8080), in case you are using it for any different application.
