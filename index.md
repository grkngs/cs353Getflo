# CS 353 - Database Systems 
# Project Proposal for Online Flower Shopping System “Getflo”

**Group 33**
Gürkan Gür - 21602813

# Table Of Contents
1. Introduction	
2. Project Description	
3. Requirements	
4. Limitations	
5. E/R Diagram	
6. Conclusion	
7. Website	



# 1- Introduction
This is the project proposal for the database system of online flower shopping application. The proposal contains the description, requirements, limitations and e/r diagram of the system. It explains how/why we need a database system for this web based application.
The proposal starts with project description section. This section explains the properties and general purpose of the system, as well as the necessity of a database. After that, requirements section contains functional and nonfunctional requirements of the system. Functional requirements describe the service that the system will offer. Nonfunctional requirements explain the criterias to judge the operations of the system. Nonfunctional requirements are stated as … . 
Next, limitations section describes the boundaries of the system, that is, the things that system is not able to accomplish.
Further, there is conceptual database diagram for the system. E/R diagram shows the entities and relations that is needed to be established in order to create the system. 


# 2- Project Description
Getflo is an online flower shopping system. The applications is web based, and interactions are done through web. The purpose of the application is to create an efficient and fast flower shop system that is done with the interactions between customers, customer services, sellers, and couriers. As there are lots of requests constantly occurring in the application, it is important create a clear relation system which is the main purpose of the system. 
The customers are able make an order on a flower or flowers, by stating their address and the properties of the order. They can state occasion, delivery type, and payment method. Customers can also make notes on the order, and complaint about the order by stating their thoughts, which then can be handled by customer services.
Flower sellers can select couriers and assign orders to selected ones. The couriers have their independent on accepting or rejecting an order. 
Transport situation of an order is kept in the system, and customers can be informed about the situation of an order.
## 2.1- Need For a Database System
As the system has to keep a lot of data, the system should keep them in a clear order in order to reach, modify, and delete them efficiently. The customers, orders, sellers, couriers, in general all of the entities and their relations should be kept in a database. The orders that a flower-seller received, the orders that customers gave, the orders that are assigned to a couriers the transportation of orders, and different events occuring in the system like complaints, rejection of an order by a courier, etc are all have to be organized in the system. As attributes are able change constantly and fast, the database system should make it fast to store, manage, and facilitate these data. 
# 3- Requirements
## 3.1- Functional Requirements
### 3.1.1. Customers
Customers can create orders according to their floral arrangement and address to deliver.

Customers can add note to their orders.

Customers can customize the properties of order such as occasion, delivery type and method of payment.

Customers can file a complaint if they are not satisfied about the order.

Customer can see the details of the order.

Customer can see the status of the order.

Flower-sellers can update their products.

### 3.1.2. Flower Seller
Flower-sellers can see details of orders which are sent by customer to them.

Flower-sellers can assign orders to couriers.

### 3.1.3. Courier
Courier can accept or reject the orders which are assigned by flower-sellers.

Courier can see the transportation details of the order.

### 3.1.4. Customer Services
Customer services can see complaint files

Customer services can evaluate complaint files and give some restriction to flower-seller or courier.

Customer services can access to details of orders.

## 3.2- Nonfunctional Requirements
### 3.2.1. Security
Permissions of the users can only be changed by administrators.

SQL queries, passwords, tables must be displayed only by developers in back-end side of the project. 

Passwords must be encrypted before it stored in database.

### 3.2.2. Performance
Since there is a big amount of data, execution of data operations like map, filter etc. must be done quickly and efficiently.

Since it is a online web site, the user request must be handled quickly without a problem.

### 3.2.3. Reliability
The system must be handle over a thousand people at the same time.

There must not be a bug inside of the system.

When there is a bug or a problem in the system. This must be fixed in a really short time.

### 3.2.4. User Friendliness
Data and operations of the system should be clear for the user to use them.

The design of the system should be simple and easy to understand.

### 3.2.5. Adaptability
The system must support new entities without implementing new code.

### 3.2.6. Configurability
The system must adapt to new configurations or configuration changes without implementing new code.


## 3.3- Constraints (Pseudo Requirements)
MySQL will be used for system’s database.

For front-end part of the system HTML, CSS, JavaScript, JQuery, Bootstrap and React ,which is a JavaScript library for creating web-based user interface, will be used.

For back-end part of the system NodeJS will be used.

# 4- Limitations

# 5- E/R Diagram

# 6- Conclusion


