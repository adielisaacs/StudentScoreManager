# StudentScoreManager

Springboot + MySQL + Vue JS + Java 8
Student Score Manager Application

1.The SQl scripts are there to run on your local database + there is dummy data
the experian folder is the API project . it needs to be built in maven as a war file and dropped on a server or it could run from your IDE like STS as a springboot application in your IDE or docker/maven run as a jar file.

Postman public link: https://www.getpostman.com/collections/42800055468e30693749
Base Url : http://localhost:8080

API http://localhost:8080/student/findAllStudents

http://localhost:8080/student/save

http://localhost:8080/student/delete

http://localhost:8080/student/update

Dummy Data [{ "id": 8, "studentNumber": 2183982, "firstName": "conor", "lastName": "Mcgregor", "dateOfBirth": "01/08/1990", "cellNumber": "0826202122", "emailAddress": "conor@gmail.com", "currentScore": 95, "averageScore": 90 }]

The student_score_manager is the client application built with Vue.js .main modules: vue, vue-router, axios Commands:

Compile
npm install
Run
npm run serve
runs on http://localhost:8081
thank you
