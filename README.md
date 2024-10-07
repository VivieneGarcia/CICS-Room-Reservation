
# <p align="center"> ⚙️ CICS CLASSROOM RESERVATION SYSTEM 🕑</p>

<p align="center">
  <a href="https://coronasafe.network">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./care/static/images/logos/light-logo.svg">
    
  </a>
</p>

## 🎯 About
This is a simple reservation system written in C++ for managing CICS room reservations. It is a command-line application.  


## ✔️ Features
- **Room Reservation:** Reserve a room by providing details like room number, date, time, professor name, and section.
- **Display Available Rooms:** View a list of available rooms with their IDs, names, and capacities.
- **Sort and Filter Reservation History**
- **Error Handling:** The system incorporates error handling for various inputs, ensuring the validity of reservations and user inputs.
- **Database Interaction:** Reservations are saved and loaded from a CSV file, allowing persistence of reservation data.


## 🤔 How to Use

1. Compile the C++ program using your preferred compiler (e.g., devC++).
2. Run the compiled executable.
3. Follow the on-screen instructions to make reservations, display available rooms, and navigate through the system.

## 📸 Screenshots
<p align="center">
  <img src="https://github.com/VivieneGarcia/CICS-Room-Reservation/blob/main/screenshots/enter.png" width="60%">
 <br>
  <img src="https://github.com/VivieneGarcia/CICS-Room-Reservation/blob/main/screenshots/menu.png"  width="60%">
 <br>
  <img src="https://github.com/VivieneGarcia/CICS-Room-Reservation/blob/main/screenshots/occupying.png" width="60%">
 <br>
  <img src="https://github.com/VivieneGarcia/CICS-Room-Reservation/blob/main/screenshots/reserving.png" width="60%">
 <br>
  <img src="https://github.com/VivieneGarcia/CICS-Room-Reservation/blob/main/screenshots/status.png" width="60%">
 <br>
  <img src="https://github.com/VivieneGarcia/CICS-Room-Reservation/blob/main/screenshots/expired.png" width="60%">
 <br>
</p>


## 💾 Reservation Data

Reservation data is stored in a CSV file (`reservations.csv`). The system loads existing reservations from this file on startup and appends new reservations to it.

## 👥 Members

- Viviene Garcia
- Mark Kevin I Ramos
