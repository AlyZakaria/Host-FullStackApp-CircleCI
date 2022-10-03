# Host-FullStackApp-CircleCI
## Project

This project is to deploy a full-stack application to cloud service(aws) which contain 3 main components (UI,API,Database).

### Here is the demo -> [Host-Fullstack-app](http://host-fullstack-app.s3-website-us-east-1.amazonaws.com/)

---
## Project setup

1. clone the repository.  

        git clone https://github.com/udacity/nd0067-c4-deployment-process-project-starter.git
2. Install Dependices 

        npm run frontend:install
        npm run backend:install

3. Database setup\
-> Start postgres database on port 5432

    1. you need to open sql shell (psql)
    2. if you have different password you can put in .env file       instead of my password in variable called POSTGRES_PASSWORD
    3. write the following queries to create databases.
####    Create database
    CREATE DATABASE aws_postgres;
4. Create .env file

        POSTGRES_USERNAME="postgres"
        POSTGRES_PASSWORD=""
        POSTGRES_DB="postgres"
        POSTGRES_HOST=""
        AWS_REGION=""
        AWS_PROFILE=
        AWS_BUCKET=""
        URL=""
        JWT_SECRET=
        AWS_ACCESS_KEY_ID=""
        AWS_SECRET_ACCESS_KEY=""
        aws_profile=""
        PORT=3000


5. run this command to develop backend & server

        cd udagram/udagram-api && npm run dev

6. run this command to develop frontend

        cd ../udagram-frontend && npm run start
---

### Here are the infrastructure of the project -> [Infrastructure](documentation\infrastructure.md)
![infrastructure](Screenshots\architecture.png)

---
## Project Dependencies

### Project dependencies are mentioned here -> [appDependencies](documentation\appDependencies.md)

---
## Pipeline Process 
 
### pipeline process are mentioned here -> [pipelineprocess](documentation\pipelineProcess.md)
![pipeline](Screenshots\pipelineProcess.png)
