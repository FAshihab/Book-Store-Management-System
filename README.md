# Library Management System

## Project Description
The Library Management System is an application designed to streamline and automate library operations. It provides a secure, role-based platform that makes it easier for users to borrow, return, and manage books efficiently. By reducing manual work and errors in transaction management, the system ensures a seamless and secure user experience.

---

## How It Works
The application utilizes **Role-Based Access Control (RBAC)** to define specific privileges for different actors:

### User Roles & Privileges
* **Librarian (Admin):**
    * **Inventory Management:** Authorized to add, update, and delete books from the library catalog.
    * **User Oversight:** Authority to create, update, and manage user accounts.
    * **Reporting:** Capable of generating transaction histories, overdue book reports, and overall usage statistics.
* **Library Member:**
    * **Search & Browse:** Users can securely log in and search for books by title, author, or genre.
    * **Transactions:** Ability to borrow available books and return them within the specified due date.
    * **Reservations:** Members can reserve unavailable books and receive notifications when they are ready for pickup.

---

## Technical Stack
* **Language:** Java (Object-Oriented Programming).
* **Database Management:** SQL-based relational database.
* **Database Schema:** Structured tables for Books, Customers, Librarians, Publishers, Orders, and Payments.
* **UI Design:** Graphical User Interface (GUI) featuring dedicated dashboards for Admins and Members.
* **Modeling Tools:** Entity-Relationship (ER) Diagrams and application flowcharts.
