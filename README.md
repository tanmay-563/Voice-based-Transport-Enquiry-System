# VoiceEnquiry
# 🚍 Voice-based Transport Enquiry System

A smart and interactive **Voice-based Transport Enquiry System** that allows users to query transport details like bus timings, routes, and ticket availability using **voice commands**. Designed to simplify public transport access, especially for the visually impaired and elderly.

---

## 🔍 Features

- 🎙️ **Voice Input Interface** for hands-free querying
- 🚌 Real-time bus and route information
- 🎫 Ticket booking system with seat availability
- 👮 Admin and Non-admin user management
- 💳 Payment integration simulation
- 📊 Revenue tracking via stored procedures
- 🧠 Built-in MySQL **trigger** and **stored procedure** for automation

---

## 🛠️ Tech Stack

- **Frontend**: Python GUI (Tkinter or Flask-based interface)
- **Backend**: Python, MySQL
- **Voice Recognition**: SpeechRecognition, Pyttsx3
- **Database**: MySQL (Structured schema with triggers & procedures)

---

## 🗃️ Database Overview

Database Name: `transportenquirysystem`

Main Tables:
- `UserTable`, `NonAdmin`, `Admin` – User management
- `BusInfo`, `RouteDetails`, `DriverDetails` – Transport details
- `Ticket`, `SeatsBooked`, `Through` – Booking system
- `bookings`, `payments`, `routes`, `schedules` – Extended features

Other Components:
- 🔁 **Trigger**: `TimeTravel` – Logs timestamp of certain actions
- 📈 **Stored Procedure**: `totalrevenue()` – Calculates overall revenue

---

## 🖼️ Demo

> _(Optional)_ Add GIFs or screenshots here to show off the GUI and voice input in action.

---

## 📦 Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/your-username/Voice-based-Transport-Enquiry-System.git
cd Voice-based-Transport-Enquiry-System

![alt text](https://robohash.org/1?200x200)

Project done as part of CSE302 DBMS Course

Stack Used:
* REACT JS + Node JS + MySQL + Express JS

React JS is available in VoiceEnquirySystem folder
Node JS is available in VoiceEnquiryBackEnd folder

To run the app,
 Fork it. Install the npm modules using npm install . 
 
 
In server.js file, edit the connection details of your host Database and execute commands in Database.txt. Now you are ready to go.

Type node server.js to run the server in default port: 3000

Happy Hacking!
