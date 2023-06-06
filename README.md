# Vehicle Rental & Reservation Management System

This project is a web-based car rental management application that provides a comprehensive solution to the manual paper-based system used by Sethyana Rent a Car & Cab Service. 

The system has minimized many drawbacks of the paper-based approach while providing staff members with an efficient way to manage reservations,  maintain vehicle fleets and drivers, and generate reports.   

Project Motivations

Previously the company undertook all the reservations over the phone and recorded details on paper manually. Searching for existing clients and retrieving information about upcoming trips were very inefficient.

Registering a new customer, a new vehicle, and making a new reservation took too much time from the customer.
Filling paper-based forms had no data validation mechanism, which had led to entering inaccurate and duplicated records.
Daily available vehicle fleets and drivers were not updated on time, therefore led to conflicts when allocating them to new reservations.
There was no organized and systematic way to view upcoming trips and rentals.
Timely tasks such as renewing revenue licenses, vehicle insurances, and driver licenses had been missed and often had been performed after an extended due date.
Daily and monthly reports took too much time to generate due to a lack of a systematic approach.


System Features

Manage system users and privileges
System users can be created only by the manager, and relevant privileges can be assigned to the users based on their role in the company. Registered users can log into the system securely by validating their usernames and passwords.
Manage vehicle details
Vehicles are added to the system through a detailed vehicle registration form. Those details can be edited and updated as necessary.
Manage package details
Package module allows manager to create various rental packages for vehicle models and update when required. 
Manage Customer details
System users can add new customers and edit their details. The customer table shows all the customers in the database and allows users to filter and search by the name or NIC.
Manage chauffeur-drive reservations
When a customer calls the office, this module is facilitated to enter the customer booking details into the system, then search for available packages, and allocate vehicles and drivers based on their attendance all inside one module with guided tabs. If the customer has previously violated any terms and conditions and is being blacklisted, the system would not allow the user to make a reservation for that customer.
Manage self-drive reservations 
This module is facilitated to enter customer reservation details and  then checks if the customer is blacklisted or if the driving license expires before the agreed vehicle return date. If the right conditions are met, the user can proceed with the reservation. During vehicle pickup at the office, the system displays the total trip cost and requests an advance payment. Upon vehicle return, the system recalculates the actual rented days and prompts for any additional payments if necessary.
Driver Portal
Drivers can log into their accounts on mobile or tablet devices by providing their usernames and passwords. All the upcoming rentals can be seen on the home page. At the end of a trip, the system will display the cost of the trip alongside with trip details and the driver can print the receipt and give it to the customer. 
Manage customer payments
Through this module, advance payments and total rental amounts can be calculated and printed to the customer.
Check availability of packages, vehicles, and drivers
The system centralizes the checking of package, vehicle and driver availability for a specified period inside a one module. 
Generate reports
Reports such as revenue reports and income reports can be generated daily or monthly as specified.
Generate notifications
The system will be facilitated to generate important notifications such as driver license, vehicle revenue license and insurance expirations. Also, system-generated emails and text messages will be sent to the customer on reservation confirmation and on driver’s arrival.



Non-functional requirements
Security
The system is facilitated to create strong user passwords using alphanumeric combinations and passwords are stored in the database after encryption. To prevent unauthorized access, the system would be locked for a user for a certain period if he tried to enter incorrect passwords consecutively more than five times. Manager has the authority to assign appropriate privileges to the system users, confining them to their designated responsibilities. 
Reliability
The system validates data input on both the front-end and back-end using techniques like Regex and database constraints. This ensures accuracy and reliability. Regular data backups are taken to facilitate easy restoration in case of emergencies. 
Performance
The system is designed to operate at maximum efficiency while meeting minimal hardware and software requirements. It ensures seamless operation even under heavy loads, preventing crashes. As a web application, data consumption is minimized to optimize user experience. Get requests are optimized to retrieve only essential data. 
Usability
The system prioritizes user-friendly design to ensure a minimal learning curve in a way that users can easily understand and utilize features effectively. Interface design adheres to essential principles, including color principles and visual hierarchy. Easy navigation is facilitated through the implementation of a sidebar and quick access panel.
Portability
Since this is a web-based application, it can run on any operating system in which any modern browser is installed, whether it is windows, mac OS, Linux, or Android. Particularly  the system is well tested on Google Chrome and Mozilla Firefox web browsers.
	





