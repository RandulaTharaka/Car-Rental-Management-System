![Sethyana Logo with title 12](https://github.com/RandulaTharaka/Car-Rental-Management-System/assets/60685092/cd5eb713-acec-4c34-8c5c-05695dd37bd8)
---
![repo-size](https://img.shields.io/github/repo-size/RandulaTharaka/Car-Rental-Management-System)
![top-language](https://img.shields.io/github/languages/top/RandulaTharaka/Car-Rental-Management-System)
![last-commit](https://img.shields.io/github/last-commit/RandulaTharaka/Car-Rental-Management-System)
![files](https://img.shields.io/github/directory-file-count/RandulaTharaka/Car-Rental-Management-System)
![languages](https://img.shields.io/github/languages/count/RandulaTharaka/Car-Rental-Management-System)
![contributors](https://img.shields.io/github/contributors/RandulaTharaka/Car-Rental-Management-System)
![license](https://img.shields.io/github/license/RandulaTharaka/Car-Rental-Management-System)

## Overview
This web-based car rental management application offers a streamlined solution to the company Sethyana Rent a Car & Cab Service's manual paper-based system. It addresses the limitations of the paper-based approach by providing staff members with efficient tools for managing reservations, vehicle fleets, drivers, and generating reports.

![Vehicle Management Screenshot](https://github.com/RandulaTharaka/Car-Rental-Management-System/assets/60685092/5d41b653-aeab-4433-91e9-99c71f474aa1)

### Tech Stack
<table>
  <tr>
    <td align="center" width="100" style="padding: 10px;">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="35" height="35" />
      <br>Java
    </td>
    <td align="center" width="100" style="padding: 10px;">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" width="35" height="35" />
      <br>Spring
    </td>
    <td align="center" width="100" style="padding: 10px;">
      <img src="https://www.svgrepo.com/show/353874/hibernate.svg" width="35" height="35" />
      <br>Hibernate
    </td>
    <td align="center" width="100" style="padding: 10px;">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="35" height="35" />
      <br>MySQL
    </td>
    <td align="center" width="100" style="padding: 10px;">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tomcat/tomcat-original.svg" width="35" height="35" />
      <br>Tomcat
    </td>
    <td align="center" width="100" style="padding: 10px;">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gradle/gradle-plain.svg" width="35" height="35" />
      <br>Gradle
    </td>
  </tr>
  <tr>
    <td align="center" width="100" style="padding: 10px;">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="35" height="35" />
      <br>HTML
    </td>
    <td align="center" width="100" style="padding: 10px;">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="35" height="35"/>
      <br>CSS
    </td>
    <td align="center" width="100" style="padding: 10px;">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" width="35" height="35" />
      <br>Bootstrap
    </td>
    <td align="center" width="100" style="padding: 10px;">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="35" height="35" />
      <br>JavaScript
    </td>
    <td align="center" width="100" style="padding: 10px;">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jquery/jquery-original.svg" width="35" height="35" />
      <br>jQuery
    </td>
    <td align="center" width="100" style="padding: 10px;">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/xd/xd-line.svg" width="35" height="35" />
      <br>Adobe Xd
    </td>
  </tr>
</table>

</br>
## Motivations

Previously the company undertook all the reservations over the phone and recorded details on paper manually. Searching for existing clients and retrieving information about upcoming trips were very inefficient.

- Registering a new customer, a new vehicle, and making a new reservation took too much time from the customer.
- Filling paper-based forms had no data validation mechanism, which led to entering inaccurate and duplicated records.
- Daily available vehicle fleets and drivers were not updated on time, therefore leading to conflicts when allocating them to new reservations.
- There was no organized and systematic way to view upcoming trips and rentals.
- Timely tasks such as renewing revenue licenses, vehicle insurances, and driver licenses had been missed and often had been performed after an extended due date.
- Daily and monthly reports took too much time to generate due to a lack of a systematic approach.


## System Features

- Manage System Users and Privileges
  <br> System users can be created only by the manager, and relevant privileges can be assigned to the users based on their role in the company. Registered users can log into the system securely by validating their usernames and passwords.

- Manage Vehicles
  <br> Vehicles are added to the system through a detailed vehicle registration form. Those details can be edited and updated as necessary.

- Manage Packages
  <br> The package module allows the manager to create various rental packages for vehicle models and update them when required.

- Manage Customers
  <br> System users can add new customers and edit their details. The customer table shows all the customers in the database and allows users to filter and search by name or NIC.

- Manage Chauffeur-Drive Reservations
  <br> When a customer calls the office, this module is facilitated to enter the customer booking details into the system, then search for available packages, and allocate vehicles and drivers based on their attendance all inside one module with guided tabs. If the customer has previously violated any terms and conditions and is being blacklisted, the system would not allow the user to make a reservation for that customer.

- Manage Self-Drive Reservations
  <br> This module is facilitated to enter customer reservation details and then checks if the customer is blacklisted or if the driving license expires before the agreed vehicle return date. If the right conditions are met, the user can proceed with the reservation. During vehicle pickup at the office, the system displays the total trip cost and requests an advance payment. Upon vehicle return, the system recalculates the actual rented days and prompts for any additional payments if necessary.

- Driver Portal
  <br> Drivers can log into their accounts on mobile or tablet devices by providing their usernames and passwords. All the upcoming rentals can be seen on the home page. At the end of a trip, the system will display the cost of the trip alongside trip details and the driver can print the receipt and give it to the customer.

- Manage Customer Payments
  <br> Through this module, advance payments and total rental amounts can be calculated and printed to the customer.

- Check the Availability of Packages, Vehicles, and Drivers
  <br> The system centralizes the checking of package, vehicle and driver availability for a specified period inside one module.

- Generate Reports
  <br> Reports such as revenue reports and income reports can be generated daily or monthly as specified.

- Generate Notifications
  <br> The system will be facilitated to generate important notifications such as driver's license, vehicle revenue license and insurance expirations. Also, system-generated emails and text messages will be sent to the customer on reservation confirmation and driver’s arrival.


## Non-Functional Requirements
- Security
  <br> The system is facilitated to create strong user passwords using alphanumeric combinations and passwords are stored in the database after encryption. To prevent unauthorized access, the system would be locked for a user for a certain period if he tried to enter incorrect passwords consecutively more than five times. Manager has the authority to assign appropriate privileges to the system users, confining them to their designated responsibilities.

- Reliability
  <br> The system validates data input on both the front-end and back-end using techniques like Regex and database constraints. This ensures accuracy and reliability. Regular data backups are taken to facilitate easy restoration in case of emergencies.

- Performance
  <br> The system is designed to operate at maximum efficiency while meeting minimal hardware and software requirements. It ensures seamless operation even under heavy loads, preventing crashes. As a web application, data consumption is minimized to optimize user experience. Get requests are optimized to retrieve only essential data.

- Usability
  <br> The system prioritizes user-friendly design to ensure a minimal learning curve in a way that users can easily understand and utilize features effectively. Interface design adheres to essential principles, including color principles and visual hierarchy. Easy navigation is facilitated through the implementation of a sidebar and quick access panel.

- Portability
  <br> Since this is a web-based application, it can run on any operating system in which any modern browser is installed, whether it is windows, mac OS, Linux, or Android. Particularly  the system is well tested on Google Chrome and Mozilla Firefox web browsers.

## Prerequisites
- Java 11
- MySQL 8.0
- MySQL Workbench 8.0
- IntelliJ IDEA 2021
- Web Browser (Latest)

## Installation 
1. Clone the repository 
    - ```git clone https://github.com/RandulaTharaka/Car-Rental-Management-System.git```
   
2. Create the MySQL user account
    - Open MySQL Workbench and navigate to File -> Open SQL Script.
    - Open the '01-create-user.sql' file located in the 'sql-scripts' folder in the repository.
    - Click the execute button in MySQL Workbench to create the user account.

3. Create the database
    - In MySQL Workbench, go to File -> Open SQL Script.
    - Open the '02-students.sql' file located in the 'sql-scripts' folder in the repository.
    - Click the execute button in MySQL Workbench to create the database.

4. Import the project
    - Open the 'sethyana_car_rental' folder in IntelliJ IDEA IDE.
    - Allow a few minutes for automatic package and dependency downloads.

5. Run the project
    - Once the configuration is complete, select "Run" from the menu bar and choose 'Run SethyanaCarRentalApp'.
    - The project will be built and launched locally on your machine if you didnt encounter any error.
   
6. Access the app
    - Open your web browser and enter "localhost:8080/login" in the address bar.
    - Use the provided usernames and passwords below to log in to the system with different privileges.
    </br>

      |     Role             |     User Name     |     Password      |
      |----------------------|-------------------|-------------------|
      |     Manager          |     Chamal85      |     Chamal85      |
      |     Receptionist     |     Nipuni92      |     Nipuni92      |
      |     Receptionist     |     Hasitha91     |     Hasitha91     |
      |     Driver           |     Sampath79     |     Sampath79     |
      |     Driver           |     Chaminda82    |     Chaminda82    |
      |     Driver           |     Sameera86     |     Sameera86     |
    
   
