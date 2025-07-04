# 🏨 Hotel Room Booking Management System (Java)

This Java console application simulates a hotel room management system. It allows guests to book rooms, check in, check out, and generate bills. The hotel has multiple types of rooms (Standard, Deluxe, Premium), and bookings account for stay duration, extra beds, and time overlap.

---

## ✨ Features

- Book Standard / Deluxe / Premium rooms
- Time-based check-in/check-out using `LocalDateTime`
- Overlap prevention in bookings
- Extra bed rate calculation (20% of base price)
- Auto-billing with guest and room details
- Maintains a queue of upcoming bookings
- View currently occupied and unoccupied rooms

---

## 🛠️ Technologies Used

- Java 17+
- OOP principles
- Java Collections API
- `java.time` (DateTimeFormatter, LocalDateTime, ChronoUnit)
- PriorityQueue for booking queue

---

## 🧱 Class Overview

- `Room` (Base class)
  - `StandardRoom`, `DeluxeRoom`, `PremiumRoom` (inherit room pricing)
- `Guest`
  - Stores guest details and booking count
- `Booking`
  - Holds all booking information and cost calculation logic
- `Hotel`
  - Manages rooms, bookings, billing, check-in/check-out

---

## 🧪 How to Run

1. Clone the repo  
2. Compile the code:
   ```bash
   javac Main.java

## Future Improvements

- Implement data persistence (database or file storage)
- Add a graphical user interface (GUI)
- Implement more advanced search and filtering options for rooms and bookings
- Add support for multiple hotels or hotel chains

## 🤝 Want to Help?
Fork the repo and send a pull request with any improvements!
