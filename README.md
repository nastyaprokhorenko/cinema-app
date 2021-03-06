# Cinema application 🎥

---

## Table of contents 📃
1. [Description](#description)
2. [3-tier architecture](#3-tier-architecture)
3. [Technologies](#technologies)
4. [Model structure](#model-structure)
5. [How to start?](#how-to-start)

---

## <a id="description"></a>Description 📍
This is a simple cinema application that has the following functionality:
- Authorization of admin / user (`/login` endpoint)
- Registration of user (`/register` endpoint)
- Getting a list of all movies / adding new movie (`/movies` endpoint)
- Getting a list of all cinema halls / adding new cinema hall (`/cinema-halls` endpoint)
- Getting a list of all available movie sessions / adding / updating / deleting movie session (`/movie-sessions` endpoint)
- Getting a user by email (`/users` endpoint)
- Adding / updating shopping cart (`/shopping-carts` endpoint)
- Getting a list of all orders / completing new order (`/orders` endpoint)

---

## <a id="3-tier-architecture"></a>3-tier architecture 📍
- Data tier - DAOs
- Application tier - Services
- Presentation tier - Controllers

---

## <a id="technologies"></a>Technologies 📍
- Java - version 11
- Hibernate - version 5.6.8
- Spring Web - version 5.3.19
- Spring Security - version 5.6.2
- MySQL - version 8.0.28
- Apache Maven - version 4.0.0
- Apache Tomcat - version 9.0.50

---

## <a id="model-structure"></a>Model structure 📍
![model structure](class_diagram.png)

---

## <a id="how-to-start"></a>How to start? 📍
1. Install MySQL and MySQL Workbench
2. Download Apache Tomcat **9.0.x**
3. Add your `YOUR_DRIVER`, `YOUR_DATABASE_URL`, `YOUR_USERNAME` and `YOUR_PASSWORD` to `src/main/resources/application.properties` file 
4. Run and enjoy
