## cafe-app

Cafe Management System
Tech Stack: HTML, CSS, JavaScript, Spring Boot, Thymeleaf, MySQL
Features: Role-based authentication, MVC design pattern, global exception handling, pagination, and server-side validation.
Modules:
Customer: Register/Login, order food online, and make payments.
Employee: Handle dine-in orders, manage dishes (CRUD), and update profile.
Admin: Manage employees (CRUD), assign roles, and update profile.
Highlights:
Secure login for customers to place orders.
Restricted actions: Only Admin can add employees, and only Employees can manage dishes.
Responsive UI with enhanced user experience.

step 1: git pull https://github.com/yash-deshpande24/cafe-app

step 2: cd cafe-app

step 3: ls & install a docker & then install docker-compose:
    - sudo apt install docker-compose

step 4: created a Dockerfile:
    - vim Dockerfile

step 5: docker build -t cafe-app .

step 6: changes on a this path & then created your rds databses: 
     - src/main/resources/application.properties
     - <img width="1342" height="187" alt="image" src="https://github.com/user-attachments/assets/10537be5-00bb-4b00-b6d1-346a93999f72" />

step 7: follow this steps:
     - src/main/java/school/controller/homeController.java

step 8: run this command:
    - docker run -d -p 8080:8080 --name cafe-container cafe-app

step 9: then this command to be use: 
    - docker ps 
    - docker images 

step 10: copy your public ip address:
     - 19.18.34.21:8080
     - then you see a home pages 
