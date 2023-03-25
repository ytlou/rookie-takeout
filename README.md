Phase 1: Needs Analysis

product prototype

user case

Phase 2: Design

Product design, UI interface design, general design, detailed design, database design

Phase 3: Coding

Phase 4: Testing

Phase 5: Online O&M


This project is a software product specially customized for catering enterprises (restaurants, restaurants), including two parts: system management background and mobile application. 
Among them, the system management background is mainly provided for internal employees of catering companies, which can manage and maintain restaurant categories, dishes, set meals, orders, and employees. 
Mobile applications are mainly provided to consumers, who can browse dishes online, add shopping carts, place orders, etc.

The mobile application is implemented through H5, and users can access it through mobile browsers.


user layer: vue.js + elementUI 
gateway layer： Nginx
application layer: Spring Boot, Spring MVC, Spring Session, Spring, Swagger, Lombok
data layer: Mysql, Mybatis, MybatisPlus, Redis
tools: git maven junit


1).client-end functions

Mobile phone number login
recipient address management
user history order query 
dish specification query
shopping cart function
order placement
category and dish browsing



2). administrator function

Employee login/exit
employee information management 
category management, 
dish management
package management
dish taste management
order management.

administrator-end administrators  
Log in to the administrator-end and have all the operation permissions in the background system

administrator-end ordinary employees
Log in to administrator-end to manage dishes, packages, orders, etc. (not including employee management)

Client-end  users
Log in to the mobile app, you can browse dishes, add shopping carts, set addresses, place orders online, etc.






