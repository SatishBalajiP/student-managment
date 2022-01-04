# student-managment

## To run the code:
- type ```go run main.go``` on the terminal;
- The main.go file is in the folder cmd/main

## To set the mysql database
- change the username, password and database in the app.go file. Present in the folder pkg/config/app.go

## Output in postman
- To show all data, send request (GET): "localhost:9010/student/"
- To insert data, send request (POST): "localhost:9010/student/"  --data-raw (json)
'{
    "Name":"Jhon",
    "Grade":"A+",
    "Class":"9-B"
}'
- To delete data, request (DELETE): "localhost:9010/student/{studentID}/"
- To update data, request (PUT): "localhost:9010/student/{studentID}/" 
