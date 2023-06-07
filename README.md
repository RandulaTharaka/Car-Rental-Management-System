# Car Rental Management System
![repo-size](https://img.shields.io/github/repo-size/RandulaTharaka/Car-Rental-Management-System) 
![top-language](https://img.shields.io/github/languages/top/RandulaTharaka/Car-Rental-Management-System) 
![last-commit](https://img.shields.io/github/last-commit/RandulaTharaka/Car-Rental-Management-System) 

## Overview
This project is a web-based car rental management application that provides a comprehensive solution to the manual paper-based system used by Sethyana Rent a Car & Cab Service. The developed system has minimized many drawbacks of the paper-based approach while providing staff members with an efficient way to manage reservations,  maintain vehicle fleets and drivers, and generate reports.   

![Vehicle Management Screenshot](https://github.com/RandulaTharaka/Car-Rental-Management-System/assets/60685092/5d41b653-aeab-4433-91e9-99c71f474aa1)

[![Tech Stack](https://github-readme-tech-stack.vercel.app/api/cards?title=Tech+Stack&lineCount=1&line1=react%2Creact%2C2398bc%3Bjavascript%2Cjavascript%2C206db9%3Bmysql%2Cmysql%2C4fa13b%3Bspring%2Cspring%2Cd6ae12%3Bpython%2Cpython%2C9e1e1e%3Bbootstrap%2Cbootstrap%2C286719%3B)

[![Tech Stack](https://github-readme-tech-stack.vercel.app/api/cards?title=Tech+Stack&lineCount=2&line1=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMjggMTI4Ij48cGF0aCBmaWxsPSIjMDA3NEJEIiBkPSJNNDcuNjE3IDk4LjEycy00Ljc2NyAyLjc3NCAzLjM5NyAzLjcxYzkuODkyIDEuMTDNEpUTHQoQUJMHLrErGJyHg89uy71MyuHgMCAwIDIuODcxIDEuNzk1IDYuODczIDMuMzUxLTI0LjQzOSAxMC40Ny01NS4zMDgtLjYwNy0zNi4xMTUtNS45Njl6bS0yLjk4OC0xMy42NjVzLTDNEpUTHQoQUJMHLrErGJyHg89uy71MyuHwLjU2NyAxLjA5MSAxOC45MSAxLjE4IDMzLjM1NC0xLjYgMCAwIDEuOTDNEpUTHQoQUJMHLrErGJyHg89uy71MyuH0MiA4LjY0LTYyLjQ0Ni42OC00MS4zMDktNi4zMzZ6Ii8%2BPHBhdGggZmlsbD0iI0VBMkQyRSIgZD0iTDNEpUTHQoQUJMHLrErGJyHg89uy71MyuHUtMS41OCAxMy4xNy0xLjU4IDEzLjE3czE1LjI4OS03Ljg5MSA4LjI2OS0xNy43NzdjLTYuNTU5LTkuMjE1LTExLjU4Ny0xMy43OTIgMTUuNjM1LTI5LjU4IDAgLjAwMS00Mi43MzEgMTAuNjctMjIuMzI0IDM0LjE4N3oiLz48cGF0aCBmaWxsPSIjMDA3NEJEIiBkPSJNMTDNEpUTHQoQUJMHLrErGJyHg89uy71MyuHtMy44ODggNS4xNTljLTE0LjEwMiA0LjI3Mi01OC43MDYgNS41Ni03MS4wOTDNEpUTHQoQUJMHLrErGJyHg89uy71MyuHuNjI1IDYuNTDNEpUTHQoQUJMHLrErGJyHg89uy71MyuHtLjQ4NSA0LjMwMy0uNDg1LTDNEpUTHQoQUJMHLrErGJyHg89uy71MyuHzLjc0MyA5LjgxNSA0OS44MjEgOC4wNzYgOTAuODE3LTMuNjM3IDc3Ljg5Ni05LjQ2OHpNNDkuOTDNEpUTHQoQUJMHLrErGJyHg89uy71MyuHuMDMzIDcuMzQ4YzYuMTg4LjgyOCAxOC41MTguNjM4IDMwLjAxMS0uMzI2IDkuMzktLjc4OSAxOC44MTMtMi40NzQgMTguODEzLTIuNDc0cy0zLjMwOCAxLjQxOS01LjcwNCAzLjA1M2MtMjMuMDQyIDYuMDYxLTY3LjU0NCAzLjIzOC01NC43MzEtMi45NTggMTAuODMyLTUuMjM5IDE5LjY0NC00LjY0MyAxOS42NDQtNC42NDN6bTDNEpUTHQoQUJMHLrErGJyHg89uy71MyuH2NyAxMi41OTDNEpUTHQoQUJMHLrErGJyHg89uy71MyuH4LjM4NS0yLjY3Ny43Mi0yLjY3Ny43MnMuNjg4LTDNEpUTHQoQUJMHLrErGJyHg89uy71MyuH1IDI2LjQ1MSAxNS41MDMtNC44MjMgMjMuNzI1IDAtLjAwMi4zNTktLjMyNy40NjgtLjYxN3oiLz48cGF0aCBmaWxsPSIjRUEyRDJFIiBkPSJNNzYuNDkxIDEuNTDNEpUTHQoQUJMHLrErGJyHg89uy71MyuH0LjUxYy0yMC4yNjYgMTDNEpUTHQoQUJMHLrErGJyHg89uy71MyuHuNTU5LTExLjgzMS0xMC42NzMtMjAuNTA5LTIwLjA3LTE0LjY4OC0yOC44MTDNEpUTHQoQUJMHLrErGJyHg89uy71MyuHxOTDNEpUTHQoQUJMHLrErGJyHg89uy71MyuHpbGw9IiMwMDc0QkQiIGQ9Ik01Mi4yMTQgMTI2LjAyMWMyMi40NzYgMS40MzcgNTDNEpUTHQoQUJMHLrErGJyHg89uy71MyuH1NzEgNC4wMzItMTguNTc3IDcuMjMxLTE5LjE4NiAzLjYxMi00Mi44NTDNEpUTHQoQUJMHLrErGJyHg89uy71MyuHgMi44NzUgMi4zODEgMTcuNjQ3IDMuMzMxeiIvPjwvc3ZnPg%3D%3D%2CJava%2C%3B)

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
	





