Campus Equipment & Laboratory Reservation Management System

Overview

The Campus Equipment & Laboratory Reservation Management System is a Python-based program designed to help students, faculty members, and laboratory custodians manage reservations for laboratory equipment and spaces.

The system aims to prevent double-booking, reduce equipment loss, and avoid delays caused by manual sign-up procedures. It allows users to reserve available equipment and laboratory spaces, checks scheduling conflicts, and records equipment checkout and return transactions.

The system also provides reservation receipts and equipment borrowing and return receipts as proof of transactions. These receipts help users and laboratory custodians verify bookings, monitor borrowed equipment, and maintain accurate records.

Features

* Student Reservation – Students can reserve available laboratory equipment and spaces.
* Faculty Reservation – Faculty members can make reservations.
* Lab Custodian Management – Laboratory custodians can manage equipment and reservations.
* View Available Equipment and Spaces – Users can check which equipment and laboratory spaces are available.
* Conflict Checking – Prevents double-booking by checking existing reservations and scheduling conflicts.
* Reservation Receipts – Generates a receipt containing reservation details as proof of a successful equipment or space booking.
* Equipment Checkout and Check-in Tracking – Records when equipment is borrowed and returned.
* Borrowing and Return Receipts – Provides transaction records for borrowed and returned equipment.
* Reservation Records – Stores and displays reservation and transaction information.
* Role-Based Access – Provides different access options for students, faculty members, and laboratory custodians.
* Input Validation – Checks user inputs to reduce errors.
* Multiple Record Management – Maintains multiple reservations and equipment transactions.

Receipt Information

The system is designed to provide receipts for the following transactions:

1. Reservation Receipt

A reservation receipt serves as proof that laboratory equipment or a space has been successfully reserved.

It may include:

* Receipt or reservation ID
* Name of the person who made the reservation
* Equipment or laboratory space reserved
* Reservation date and time slot
* Reservation status

2. Equipment Borrowing Receipt

A borrowing receipt records the release of equipment to a student or faculty member.

It may include:

* Transaction or receipt ID
* Borrower’s name
* Equipment borrowed
* Date and time borrowed
* Equipment status

3. Equipment Return Receipt

A return receipt confirms that borrowed equipment has been returned to the laboratory custodian.

It may include:

* Transaction or receipt ID
* Borrower’s name
* Equipment returned
* Date and time returned
* Return status

These receipts help prevent confusion, provide proof of transactions, and make it easier to track equipment and reservations.

Requirements

To run the program, you need:

* Python 3 installed on your computer
* A terminal, command prompt, or Python IDE such as IDLE or Visual Studio Code

How to Run

1. Download or copy the project files.
2. Open the project folder.
3. Open a terminal or command prompt in the folder.
4. Run the Python program using:

python main.py

5. Follow the instructions displayed on the screen.

Sample Interaction

=================================================
 CAMPUS EQUIPMENT & LABORATORY RESERVATION SYSTEM
=================================================
[1] Student
[2] Faculty
[3] Lab Custodian
[4] View Available Equipment and Spaces
[5] Exit
Enter your choice: 1
Enter your name: John
Enter equipment or space to reserve: Microscope
Enter reservation date: 2026-09-01
Enter time slot: 10:00 AM
Checking availability...
Reservation successful!
=================================================
             RESERVATION RECEIPT
=================================================
Reservation ID: RES-001
Reserved by: John
Equipment/Space: Microscope
Date: 2026-09-01
Time: 10:00 AM
Status: Reserved
=================================================

Sample Equipment Return Receipt

=================================================
          EQUIPMENT RETURN RECEIPT
=================================================
Transaction ID: RET-001
Borrower: John
Equipment: Microscope
Date Returned: 2026-09-01
Status: Returned
=================================================

Note: The sample interactions illustrate the intended system behavior. The actual program must implement the receipt generation, reservation records, and equipment return tracking for these features to work.

Project Goal

The goal of this project is to develop a simple and reliable reservation management system that helps students, faculty members, and laboratory custodians reserve laboratory spaces and equipment, prevent scheduling conflicts, and maintain clear records through reservation, borrowing, and return receipts.