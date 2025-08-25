## Online Reservation System
This project is a **Java-based console application** that acts like an **Online Railway Reservation System**.
It offers basic features like **user login, booking tickets, canceling bookings, and viewing your bookings**, and it uses text files to keep your data safe.<br>

## Features
* **User Registration & Login**
* New users can sign up with a username and password.r>
*  * A default user named `Praveena` with the password `1325` is set up automatically.r>
* **Make Reservation**
* Enter details like the train number, train name, class type, travel date, and starting and ending points.r>
* * Each booking is given a unique **PNR number**.r>
* **Cancel Reservation**
* Users can cancel a booking by entering the **PNR number**.r>
*  * You must confirm the cancellation before it's done.r>
* **View Reservations**
* Users can see all their bookings.r>
* **Data Storage**
* **users.txt** stores all usernames and passwords.r>
* **reservations.txt** keeps track of all the bookings.r>

##  Technologies Used
* **Java (Core Java with Object-Oriented Programming concepts)**
* **File Handling (Input/Output streams for storing data)**
* **Collections Framework (like HashMap and ArrayList)**
##  File Structure
OnlineReservationSystem.java # Main application
users.txt # Stores registered users
reservations.txt # Stores reservation records
## How to Run
1. **Compile the program:**
javac OnlineReservationSystem.java
2. **Run the program:
**java OnlineReservationSystem
4. **Login or Register** and start using the system.
<br>

## Example Usage
--- ONLINE RESERVATION SYSTEM ---
1. Login
2. Regis
ter
3. Exit<
br>Choose option: 1
Username: Praveena
Password: 1325
Login successful!
r>--- Welcome, Praveena ---
1. Make
Reservation
2. Cance
l Reservation
3. View
My Reservations
4. Logou
t
Choose option: 1
Your Name: John Doe
Train Number: 12345
Train Name: Shatabdi Express
Class Type: AC
Date of Journey (YYYY-MM-DD): 2025-08-30
From (Place): Hyderabad
To (Destination): Chennai
Reservation successful! Your
PNR: PNR456789

## Future Enhancements
* A GUI version using JavaFX or Swing.
* Connecting to a database like MySQL or PostgreSQL.
* Simulating online payment.
* Calculating ticket prices and managing seat availability.

## Author
**Praveena Varanasi**
