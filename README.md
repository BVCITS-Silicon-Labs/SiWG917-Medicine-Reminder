# 💊 Medicine Reminder System

## 📌 Project Overview

The **Medicine Reminder System** is a simple embedded system project developed using the **Silicon Labs SiWG917 development kit**.

The project uses a **push button** to simulate the medicine reminder interaction. When the button is pressed, the system detects the button event and displays the corresponding message through the program output.

This project is developed to understand **push-button interfacing and event detection in an embedded system**.

---

## 🎯 Objectives

- To interface a push button with the SiWG917 development kit.
- To detect button press events.
- To understand GPIO-based input handling.
- To implement a simple medicine reminder concept.
- To gain practical experience with embedded C programming.

---

## 🛠️ Hardware Used

- Silicon Labs **SiWG917 Development Kit**
- On-board Push Button
- USB Cable
- Computer/Laptop

---

## 💻 Software Used

- **Simplicity Studio 6**
- **Si91x SDK**
- Embedded **C Programming**

---

## ⚙️ Working Principle

1. The SiWG917 development kit is powered through USB.
2. The program initializes the push button.
3. The system continuously monitors the button state.
4. When the user presses the button, the system detects the button event.
5. The corresponding medicine reminder message is displayed in the output.
6. The system continues monitoring the button for the next interaction.

---

## 🔘 Button Operation

| Button Action | System Response |
|---|---|
| Button not pressed | System waits |
| Button pressed | Button press is detected |
| Button released | System returns to monitoring |

---

## 📂 Project Structure

```text
SiWG917-Medicine-Reminder/
│
├── README.md
│
├── Source_Code/
│   └── medicine_reminder.c
│
├── Documentation/
│   └── Medicine_Reminder_Documentation.pdf
│
└── Images/
    └── Project_Setup.jpg
```

---

## 📸 Project Output

The project detects the push-button operation and displays the button event in the program output.

Example:

```text
Medicine Reminder System
Waiting for button press...

BUTTON PRESSED

Waiting for button press...
```

---

## 🚀 Future Scope

The project can be extended by adding:

- Multiple medicine schedules
- Medicine names
- LED indication
- Buzzer alerts
- RTC-based timing
- OLED/LCD display
- Mobile notifications
- Wi-Fi connectivity

---

## 👩‍💻 Developer

**Yamini Lakshmi Priya Mattaparthi**

**Department:** Electronics and Communication Engineering

**Platform:** Silicon Labs SiWG917

---

## 📜 Purpose

This project is developed for **educational and embedded systems learning purposes**.
