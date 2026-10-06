# IRCTC Train Booking System

A console-based train ticket booking system built with Java. This project demonstrates Core Java, Object-Oriented Programming, JSON data persistence, authentication, train search, seat booking, ticket management, and Gradle dependency management.

## Features

- User registration and login
- Password hashing using BCrypt
- Train search by source and destination
- Station and route validation
- Seat availability checking
- Train seat booking
- Ticket generation
- Ticket cancellation
- User booking history
- JSON-based data persistence
- Unique user and ticket IDs
- Input validation and exception handling

## Tech Stack

- **Java**
- **Gradle**
- **Jackson** for JSON processing
- **BCrypt** for password hashing
- **JUnit** for testing
- **Git & GitHub**

## Project Structure

```text
src/
├── main/
│   └── java/
│       └── ...
└── test/
    └── ...

data/
├── trains.json
└── users.json

build.gradle
settings.gradle

How It Works
The application allows users to:
1. Create an account
2. Log in securely
3. Search for available trains
4. Select a source and destination
5. Check available seats
6. Book a seat
7. View booked tickets
8. Cancel a ticket
Train and user information is persisted using JSON files.
Running the Project
Clone the Repository
git clone https://github.com/Sambuddha-Jana/irctc-foundation-java.git

Navigate to the Project
cd irctc-foundation-java

Run the Application
On Linux/macOS:
./gradlew run

On Windows:
gradlew.bat run

Sample Data
The project includes sample users and trains for demonstration purposes.
The credentials included in the repository are dummy/demo credentials and should not be used for real accounts.
Learning Goals
This project was built to strengthen practical understanding of:
- Java OOP
- Classes and objects
- Interfaces and inheritance
- Collections
- Exception handling
- Streams and lambdas
- Optional
- JSON serialization and deserialization
- File persistence
- Unit testing
- Gradle
- Git and GitHub
Future Improvements
- Migrate JSON persistence to PostgreSQL/MySQL
- Build REST APIs using Spring Boot
- Add a database-backed authentication system
- Add concurrency handling for simultaneous seat bookings
- Add a web frontend
- Add Docker deployment
