# Project-1- A SAMPLE NODEJS APPLIATION IS GIVEN,WHICH IS HAVING A DATABASE MONGODB.
•	Create a Dockerfile for the Nodejs application.
•	Make the necessary changes in the code configuration. (config/default.json)
•	Create 3 different docker environments using docker-compose, each service(Nodejs, MONGODB,NGINX) in the environment should run in a separate container.
•	Make sure all data will be persistent even if any of the containers crashes, restart.
•	Make sure services will start in the correct order (i.e., wait for MONGODB initialisation)
•	Add a custom configuration to Nginx ○ Enable HTTPS and redirect HTTP to HTTPS
•	Create a self-signed certificate
•	or use Lets Encrypt, also document the commands you are using to create the certificate
•	Add any other configuration you may think is essential (headers, deny access to essential files and folders, ...)
•	Commit the project to GitHub and write your explanations and documentation into the readme.
