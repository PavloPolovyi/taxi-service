# :oncoming_taxi: Taxi-service :oncoming_taxi:
<h2>📣 Project description 📣</h2>
This is a simple web application that supports registration, authentication and simple CRUD operations.
It follows SOLID patterns and built up according to N-tier architecture. It consists of 4 layers:
Presentation layer, Data service layer, Business logic layer and Data access layer.

## <h2>:bookmark_tabs: Features</h2>
* Registration as driver
* Authentication as a driver
* Authenticated driver can perform CRUD
* Supports display of all cars that belong to current driver
* Displays all manufacturers/drivers/cars
* Logout option

## <h2>:file_folder: Project structure</h2>
<p>:point_right:The Presentation layer is represented by jsp pages</p>
<p>:point_right:Controllers are main components of Data service layer and responsible for working with HTTP methods and transmission of data from BLL to the presentation layer. </p>
<p>:point_right:Business logic layer consists of services that are responsible for main logic of app</p>
<p>:point_right:DAO classes represent Data access layer 
and responsible for CRUD operations with database entities</p>

## <h2>Technologies</h2>
* Java 11
* Maven 4.0
* Java Servlet API 4.0.1
* JDBC
* Jakarta Server Pages
* JSTL 1.2
* MySQL 8.0.22
* TomCat 9.0.68

## <h2>:bomb:Instructions for launching the project:bomb:</h2>
<h4>To run this project locally, follow these steps:</h4>

1️⃣ You should install <a href="https://tomcat.apache.org/download-90.cgi">TomCat</a> version 9 and <a href="https://dev.mysql.com/downloads/installer/">MySQL</a>

2️⃣  Clone this project from GitHub
```bash
git clone https://github.com/PavloPolovyi/taxi-service
```
3️⃣  Run query from init_db to create local database schema

4️⃣  Configure [ConnectionUtil](src/main/java/taxi/util/ConnectionUtil.java), set username and password values for your database to corresponding fields

5️⃣  Configure TomCat for this project and run it

