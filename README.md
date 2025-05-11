# ✈️ Flight-Reservation-System
A comprehensive C++ application simulating a Flight Reservation System. - C++17 Application with Advanced Data Structures

## 📁 File Structure

- `FlightReservationSystem.cpp`: The main source file containing the full system implementation.
- Text files: 
  - `flights.txt`
  - `customers.txt`
  - `planes.txt`
  - `offers.txt`
  - `tickets.txt`
  - `airports.txt`

These external files are used to load and save data across different sessions.

## 🚀 Features

### 🔧 Setup

- Loads data from text files at startup.
- Saves all updates back to respective files on exit.

### ✈️ Flight Operations

- **Search Flights**: By destination (from Beirut).
- **Reserve Flight**: Choose seat and ticket type; apply discounts.
- **Cancel Reservation**: Frees seat and manages waiting list.
- **Change Reservation**: Switch flights and update all related records.

### 👥 Customer Management

- Add, update, delete customers.
- View full customer profile with flight history.

### 🛫 Flight Management

- Add, update, delete flights.
- View all flights with details (departure, time, ticket pricing).

## 🧱 Data Structures Used

- **Singly Linked List**: Airports, Planes
- **Doubly Linked List**: Flights
- **Binary Search Trees (BSTs)**: Customers, Flight passengers
- **Queues**: Waiting lists
- **Arrays/Vectors**: Offers and Tickets

## 🧠 Classes Implemented

- `Airport`: Stores destination, weather, and distance info.
- `Plane`: Holds seat configuration and miles traveled.
- `Customer`: Contains customer profile and flight history.
- `Flight`: Flight schedule and passengers.
- `Ticket`: Booking confirmation with seat info.
- `Offer`: Discounts based on flights/miles.
- `BST`: Custom binary tree for efficient search/update.
- `FlightReservationSystem`: Ties all components into a working system.

## 💻 How to Run

1. Place all necessary `.txt` files in the same directory.
2. Compile the code using a C++ compiler:
   ```bash
   g++ -std=c++11 FlightReservationSystem.cpp -o FlightReservationSystem

