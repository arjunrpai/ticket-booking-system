# Train Ticket Booking System

We have implemented a simple **Train Ticket Booking System** in **C++**, designed to simulate reservation, cancellation, and management of train tickets.  

This project demonstrates **OOP concepts, file handling, and data structures** in C++.



## Features
- **Train Management**
  - Each train has a unique ID, Name, Source, and Destination.  
- **User Management**
  - Each user has an ID, Name, Aadhaar Number, Age, and booking history.  
- **Reservation System**
  - Seats are stored in a 2D Reservation List (matrix).  
  - `1` → Booked seat  
  - `0` → Available seat  
- **Booking Service**
  - Book a ticket for a user.  
  - Cancel an existing booking.  
  - Print booking details.  
  - Save bookings to files for persistence.  



# System Design

![System Design](./Train%20booking%20system.png)
### Classes
- **Train**
  - `trainID`, `name`, `source`, `destination`
- **User**
  - `userID`, `name`, `aadharCard`, `age`, `list<seat> train`
- **BookingService<T>**
  - `booking(entityId, userId)`  
  - `cancelBooking(entityId, userId)`  
  - `printBooking(entityId, userId)`  
  - `saveBooking(entity)`

 
## Tech Stack
- **Language**: C++  
- **Concepts**: Object-Oriented Programming (OOP), Templates, File Handling  

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Train-Ticket-Booking-System.git
   cd Train-Ticket-Booking-System
2.Compile the program:
   ```bash
   g++ main.cpp -o booking


   
