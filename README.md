# ShowTime 🎬

ShowTime is a Java-based console application that simulates a basic movie ticket booking system. It demonstrates object-oriented programming concepts by modeling various entities involved in a movie theatre ticketing system.

## 🚀 How to Run

1. Clone or download the project and navigate to the project directory:

   ```bash
   cd ShowTime

2. Compile all Java files:

    ```bash
    javac -d . *.java

3. Run the main application
    ```bash
    java ShowTime.BookMyTicket

📖 Project Overview
The ShowTime project encapsulates the different components of a movie booking system. It follows an object-oriented design, separating concerns into various well-defined classes. Here’s a breakdown of the key components:

🎟️ Core Classes
Seat: Represents a seat in the theatre, including seat number, row, and category (e.g., Gold, Silver).

SeatCategory: Enum or class to classify different types of seats with different pricing.

Screen: Defines the layout of the theatre screen, including rows and columns of seats.

Ticket: Represents a booked ticket, mapping a user to the seat(s), movie, and showtime.

Payment: Handles payment logic, such as calculating total price and simulating transaction success/failure.

🎬 Movie Management
Movie: Contains details about a movie, such as title, duration, genre, and language.

MovieController: Responsible for managing movies – adding, removing, or fetching movie listings.

🏢 Theatre and City
Theatre: Represents a movie theatre, containing multiple screens and a list of movies being played.

City: Represents a city that contains multiple theatres for regional support.

🎮 Controller
TheatreController: Manages theatres across different cities, enabling movie show listings, bookings, and theatre registration.

🧪 Demonstration
BookMyTicket: This is the entry point of the application. It demonstrates the complete flow of the ticket booking system — from listing movies, selecting a theatre and screen, to booking a seat and making a payment.

🛠️ Technologies Used
Java (Standard Edition)

Object-Oriented Programming Principles

📌 Notes
This project runs in a console environment; no GUI or database integration is included.

This project is ideal for understanding how a ticket booking system can be modeled using core Java.