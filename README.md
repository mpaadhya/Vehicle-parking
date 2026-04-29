# 🚗 Vehicle Parking Management System

A console-based parking management system written in C that manages
car and scooter parking slots with a login system and real-time slot tracking.

---

## 📌 About The Project

This project simulates a real parking lot management system. It tracks
available parking slots for cars and scooters separately, handles vehicle
arrivals and departures, and provides live slot status — all secured
behind a login system.

---

## ✨ Features

- 🔐 Login system with username and password
- 🚘 Separate parking slots for Cars and Scooters
- ➕ Vehicle arrival — assigns the next free slot automatically
- ➖ Vehicle departure — frees up the slot
- 📊 View total vehicles, cars, and scooters parked
- 🗺️ Display full parking grid with all slot statuses
- 🔢 Supports up to 20 cars and 20 scooters

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| C | Core programming language |
| Structs | Vehicle data management |
| Arrays | Parking slot grid tracking |
| Windows.h | Console screen management |

---

## ⚙️ How To Run

**Requirements:** Windows OS with a C compiler (GCC / Turbo C)

**Using GCC (recommended):**

**Step 1 — Compile the program:**
```bash
gcc parking.c -o parking
```

**Step 2 — Run the program:**
```bash
./parking
```

**Default Login Credentials:**
```
Username : user
Password : pass
```

---

## 📁 Project Structure

```
vehicle-parking-management/
└── parking.c    # Main C program
```

---

## 🖥️ Menu Options

```
1 >> Arrival Of Vehicle
2 >> Total No. Of Vehicles Parked
3 >> Total No. Of Cars Parked
4 >> Total No. Of Scooters Parked
5 >> Display Vehicles Parked
6 >> Departure Of Vehicle
7 >> Exit
```

---

## 🔍 How It Works

1. Login with credentials to access the system
2. The parking lot has 4 rows × 10 columns = 40 total slots
3. Rows 0-1 are for Cars, Rows 2-3 are for Scooters
4. On arrival, the system finds the next free slot automatically
5. On departure, the slot is freed and the grid updates
6. Display option shows the full parking grid with vehicle numbers

---

## 🎓 About

Developed as part of M.Tech in Computer Science & Engineering
@ Anurag University, Hyderabad

**Author:** Aadhya MP
**GitHub:** [github.com/mpaadhya](https://github.com/mpaadhya)
