# Ebru_API_Proj

JavaScript version
Need to use Postman to test. localhost:3000/student

npm init -y
npm install express mongoose
npm install --save-dev nodemon

nodemon index.js

Use Postman, add JSON file/data in body section (raw) to add new student. POST Method
Sample:
{
    "name": "Alexander",
    "surname": "Hamilton",
    "stdNumber": "B012X00012",
    "grades": [
        {
        "code": "MT101",
        "value": 90
        }, 
        {
        "code": "PH101",
        "value": 75
        }, 
        {
        "code": "CH101",
        "value": 60
        }, 
        {
        "code": "MT101",
        "value": 70
        }, 
        {
        "code": "HS101",
        "value": 65
        }
    ]
}