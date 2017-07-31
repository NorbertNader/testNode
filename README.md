# testNode

mongodb in data/db

in this project root dir run:
$ mongod --dbpath data/db

mongodb credentials
admin:admin

 ---

and run:
$ nodemon server.js

---

go to localhost:8080/setup

to create new user 
name: Some person
pass: password

---

fireup dat POSTman and let's rock!

get localhost:8080/api/users - user list

post localhost:8080/api/authenticate - data {name: <users name>, password: <password>} - create a user token


