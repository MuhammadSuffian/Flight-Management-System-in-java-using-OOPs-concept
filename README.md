<h1>Flight Management System (Java)</h1>
This Flight Management System project is developed in Java, implementing Object-Oriented Programming (OOP) concepts such as Encapsulation, Abstraction, Inheritance, and Polymorphism. The system provides essential functionalities for managing flight tickets, user accounts, and fare calculations.

<h2>Features</h2>
<h3>CreateAccount</h3> Users can create accounts by providing their essential details, including username, password, name, contact information, and CNIC. The account information is stored in a TXT file using File Handling for future access.

<h3>Login Account</h3> Registered users can log in to the system using their credentials. The system retrieves account details from the "DATA.txt" file to verify the user during login.

<h3>Variable Class</h3> A dedicated "Variable" class holds all the necessary variables, such as Uname, Passcode, name, contact, and CNIC, used throughout the application for easier management and maintenance.

<h3>Billdata Class</h3> The "Billdata" class contains a "cal" function that calculates the fare based on user input. It takes a String input, processes it, and returns the calculated fare in String format.

<h3>TicketFareCheck Class</h3> This class enables users to check the fare for a specific flight route. Users can select departure and destination cities from combo boxes. When the "Check Fare" button is clicked, the system calculates the fare using the "cal()" method and displays it in a message dialog.

<h3>BookTicket Class</h3> Users can book flight tickets by selecting departure and destination cities. The system calculates the fare based on the selected cities and generates a unique ticket ID using the "numGen()" method. The ticket information, including ticket ID, departure, destination, and fare, is stored in a file named "Ticket.txt". Additionally, the booking information is stored in separate files named after the user's name (e.g., "Uname.txt").

<h3>Search Class</h3> The "Search" class allows users to retrieve details of a specific ticket using its ticket ID. When the "Search" button is clicked, the system reads data from the "Ticket.txt" file and searches for the ticket with the provided ticket ID. It then displays the corresponding departure, destination, and fare information in the respective text fields on the GUI.

<h2>Object-Oriented Concepts Used</h2>
<h3>Encapsulation</h3> Data is encapsulated within classes, and access to internal data is controlled using access modifiers. Getter and setter methods are used to access and modify data securely.

<h3>Abstraction</h3> The system abstracts away complex ticket booking and fare calculation processes. Users only interact with user-friendly GUI elements, and internal implementation details are hidden.

<h3>Inheritance</h3> Inheritance is employed to create the "Variable," "Billdata," "TicketFareCheck," "BookTicket," and "Search" classes, which inherit common functionalities from a parent class.

<h3>Polymorphism</h3> Polymorphism is demonstrated through method overriding, such as the "cal()" method in the "Billdata" class, which can be used to calculate fare differently based on the flight route.

<h3>Usage</h3>
The Flight Management System is designed to simplify the booking process and provide a smooth experience for users to manage their flight tickets efficiently. Users can create accounts, log in securely, check fare for different routes, and book flight tickets seamlessly.

<h3>Future Enhancements</h3>
1)Implementing user authentication and authorization for enhanced security.<br>
2)Integrating a database to store and manage user account details and ticket information.<br>
3)Implementing seat selection and availability checks for flight bookings.<br>
4)Enhancing the user interface to provide a more engaging and intuitive experience.<br>
5)Feel free to contribute to this project on GitHub, and together, we can make this Flight Management System even better!<br>
