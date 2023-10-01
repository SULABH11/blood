# blood
The MERN Stack Blood Bank Project is a web application that leverages MongoDB, Express.js, React.js, and Node.js to facilitate blood donation and management. It includes features such as donor registration, blood requests, inventory management, user authentication, and search functionality. The project aims to provide a seamless user experience and efficient blood inventory management for blood banks and donors.The target audience for a MERN blood bank project includes blood donors, blood recipients, medical professionals, blood banks, hospitals, administrators, volunteer organizations, government health agencies, mobile app users, website visitors, and researchers.
![image](https://github.com/SULABH11/blood/assets/93487589/d2b00fd8-a730-47cf-9111-fd1afdfa32ba)
![image](https://github.com/SULABH11/blood/assets/93487589/2d482ab5-cf9f-48b5-a5a4-447e28b5b5e4)
MVC (Model View Controller) Pattern
In the Model Side,Mongoose Model is used for Model-View-Controller architectural Pattern.In this case, userSchema defines the structure and validation rules for the "user" entity that the application will work with.the "role" field is required and should have a value from a predefined list of roles ("admin," "organisation," "donor," "hospital").Other fields like "name," "organisationName," "hospitalName," "email," "password," "address," and "phone" have their own validation rules for when they are required or allowed.
Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env.
Morgan is an HTTP request level Middleware. It is a great tool that logs the requests along with some other information depending upon its configuration and the preset used. 


