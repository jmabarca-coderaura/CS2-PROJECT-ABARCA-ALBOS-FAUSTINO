# Campus Equipment & Laboratory Reservation Management System

## Overview

The **Campus Equipment & Laboratory Reservation Management System** is a Python-based program designed to help students, faculty members, and laboratory custodians manage reservations for shared laboratory equipment and spaces.

The system aims to reduce problems such as **double-booking, equipment loss, and delays caused by manual sign-up procedures**. Users can reserve available equipment or laboratory spaces, while the system checks for scheduling conflicts. Laboratory custodians can also track the checkout and check-in status of equipment.

## Features

* Reserve laboratory equipment and spaces
* View available equipment and laboratory spaces
* Prevent double-booking through conflict-checking logic
* Track equipment checkout and check-in
* Display reservation records
* Provide role-based access for students, faculty members, and laboratory custodians
* Validate user input
* Store and manage multiple reservation records

## Requirements

To run the program, you need:

* Python 3 installed on your computer
* A terminal, command prompt, or Python IDE such as IDLE or Visual Studio Code

## How to Run

1. Download or copy the project files.
2. Open the project folder.
3. Open a terminal or command prompt in the folder.
4. Run the Python program using:

```python
python main.py
```

5. Follow the instructions displayed on the screen.

## Sample Interaction

```text
=================================================
 CAMPUS EQUIPMENT & LABORATORY RESERVATION SYSTEM
=================================================

[1] Student
[2] Faculty
[3] Lab Custodian
[4] View Available Equipment
[5] Exit

Enter your choice: 1

Enter your name: John
Enter equipment to reserve: Microscope
Enter reservation date: 2026-09-01
Enter time slot: 10:00 AM

Checking availability...

Reservation successful!

Equipment: Microscope
Reserved by: John
Date: 2026-09-01
Time: 10:00 AM
Status: Reserved
```

## Contributors

* **Member 1:** [Name] — Reservation system and conflict-prevention logic
* **Member 2:** [Name] — Equipment checkout and check-in tracking
* **Member 3:** [Name] — Role-based access, testing, and documentation
