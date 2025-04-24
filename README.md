# IoT Based Student Attendance Management System

## Overview
An IoT-based system that automates student attendance using ESP32 microcontroller. The system sends data to a backend server and displays attendance on a web dashboard.

## Features
- ESP32 for real-time data transmission
- Web-based admin dashboard
- Attendance database with timestamps

## Technologies
- ESP32/Arduino
- Python (Flask/FastAPI)
- Excell Sheet to maintain Attendebce

## Setup Instructions
1. Upload `esp32_code.ino` to your ESP32 device.
2. Run `backend/app.py`.
3. Open `frontend/index.html` in your browser.


# IoT-Student-Attendance-System
│
├── 📁 hardware/
│   ├── circuit_diagram.png
│   └── components_list.md
│
├── 📁 firmware/
│   └── esp32_code.ino          # Code for ESP32/Arduino-based RFID scanner
│
├── 📁 backend/
│   ├── app.py                  # Flask/FastAPI backend
│   ├── database.py             # SQLite/MySQL/PostgreSQL connection
│
├── 📁 frontend/
│   ├── index.html              # Web dashboard for attendance view
│   └── styles.css
│
├── 📁 docs/
│   ├── project_report.pdf
│   └── README.md               # Project overview and how to run
│
├── .gitignore
└── README.md                   # Main project description

