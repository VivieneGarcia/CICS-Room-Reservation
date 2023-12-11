
# <p align="center"> CICS CLASSROOM RESERVATION SYSTEM </p>

<p align="center">
  <a href="https://coronasafe.network">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./care/static/images/logos/light-logo.svg">
    
  </a>
</p>

## 🎯 About
This is a simple reservation system written in C++ for managing CICS room reservations. The system allows users to reserve rooms, specifying details such as date, time, professor name, and section. It also provides information about available rooms and displays reservations in an organized manner.


## ✔️ Features
- **Room Reservation:** Reserve a room by providing details like room number, date, time, professor name, and section.
- **Display Available Rooms:** View a list of available rooms with their IDs, names, and capacities.
- **Sort and Filter Reservation History**
- **Error Handling:** The system incorporates error handling for various inputs, ensuring the validity of reservations and user inputs.
- **Database Interaction:** Reservations are saved and loaded from a CSV file, allowing persistence of reservation data.


## How to Use

1. Compile the C++ program using your preferred compiler (e.g., devC++).
2. Run the compiled executable.
3. Follow the on-screen instructions to make reservations, display available rooms, and navigate through the system.


## Room Data

Room data is initialized with default values for room names, IDs, and capacities. Additional rooms can be added or modified within the `createRooms` function in the code.

## Reservation Data

Reservation data is stored in a CSV file (`reservations.csv`). The system loads existing reservations from this file on startup and appends new reservations to it.

## Dependencies

- Windows API for aesthetic features (colors)
- Standard C++ libraries (iostream, sstream, string, limits, iomanip, fstream, stack, ctime)

>

## 👥 Members

- Viviene Garcia
- Mark Kevin I Ramos
