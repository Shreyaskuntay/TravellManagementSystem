# Travel Management System

A Python-based travel booking and management application that demonstrates core software engineering concepts such as CRUD operations, modular code design, in-memory data storage, and real-world use cases like trip management, seat allocation, user handling, and booking workflows.

This project is ideal for learning, practicing Python fundamentals, and showcasing backend logic for internship applications.

---

## 🚀 Features

### ✔ User Management
- Register new users  
- Store user details in memory  
- Basic validation  

### ✔ Trip Management
- Create new trips (destination, date, seats, fare)  
- List all available trips  
- Update or delete trips  
- Prevent creation of conflicting trips  

### ✔ Booking System
- Make bookings for specific trips  
- Automatic seat count updates  
- View booking history  
- Cancel bookings  

### ✔ No External Database Required
This project **does not use a real database** (MySQL, SQLite, etc.).  
Instead, it uses **Python dictionaries and lists as in-memory storage**, making it beginner-friendly and portable.

---

## 🛠 Tech Stack

| Component | Technology |
|----------|------------|
| Language | Python 3.x |
| Storage | In-memory (dict / list) |
| Paradigm | Modular, procedural/OO (depending on your code) |
| Interface | CLI (Console-based) |

---

## 📁 Project Structure

TravellManagementSystem/
│
├── main.py # Entry point of the program
├── users.py # Handles user-related operations
├── trips.py # Handles trip creation and management
├── bookings.py # Handles booking logic
├── utils.py # Helper functions (validation, formatting)
│
├── data/ # local JSON file storage
│ ├── users.json
│ ├── trips.json
│ └── bookings.json
│
└── README.md # Documentation

---

## 🔧 Installation & Running

### 1. Clone the repository
```bash
git clone https://github.com/Shreyaskuntay/TravellManagementSystem.git
cd TravellManagementSystem
```
---
## Run the program
    python3 main.py


Example Usage
------------------------------
   TRAVEL MANAGEMENT SYSTEM
------------------------------

1. Register User
2. Create Trip
3. View Trips
4. Book Trip
5. View Bookings
6. Cancel Booking
7. Exit
When creating a trip:
Enter destination: Goa
Enter date (YYYY-MM-DD): 2025-02-18
Enter available seats: 40
Enter price: 3999
Trip created successfully!
When booking:
Enter user ID: 1
Enter trip ID: 3
Enter number of seats: 2
Booking successful!
Remaining seats: 38
---
