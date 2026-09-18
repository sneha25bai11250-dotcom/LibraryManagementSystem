# Project Statement: Library Management System

## 1. Project Title
**Library Management System (Java)**

---

## 2. Problem Statement
Managing library collections manually leads to tracking errors regarding book availability, loss of records, and inefficient borrowing or returning workflows. This project provides a lightweight software solution to track books in a digital inventory, manage availability states, and automate borrowing and returning operations without requiring external database overhead.

---

## 3. Project Objectives
* **Core Goal**: Maintain an active in-memory inventory of books and manage their availability status (`Available` vs. `Checked Out`).
* **Technical Goals**:
  * Implement Object-Oriented Programming (OOP) principles using `Book` and `Library` entities.
  * Use Java Collections Framework (`ArrayList`) for dynamic data storage.
  * Ensure full command-line execution and output validation[span_2](start_span)[span_2](end_span).

---

## 4. System Architecture & Components
* **`Book` Class**: Encapsulates book attributes (`bookId`, `title`, `author`, `isAvailable`) along with getters, setters, and state display logic.
* **`Library` Class**: Manages the list of books, providing methods to add new titles (`addBook`), display inventory (`displayAllBooks`), and handle transaction logic (`borrowBook`, `returnBook`).
* **`LibraryManagementSystem` Class**: Contains the main driver method (`main`) that runs end-to-end execution scenarios[span_3](start_span)[span_3](end_span).

---

## 5. Key Features & Scope
* **Inventory Visualization**: Displays all books in the catalog alongside their current availability status.
* **Borrowing Logic**: Updates book status to `Checked Out` and prevents double-borrowing of unavailable titles.
* **Returning Logic**: Restores book status back to `Available` once returned.
* **Case-Insensitive Search**: Allows book lookups using ID strings regardless of letter casing.
* **Scope Limitations**: Runs as a console application with hardcoded demonstration data[span_4](start_span)[span_4](end_span); data persists only in memory during execution.

---

## 6. Technical Specifications
* **Programming Language**: Java (JDK 8 or higher)[span_5](start_span)[span_5](end_span)
* **Environment**: Visual Studio Code / Terminal Interface[span_6](start_span)[span_6](end_span)
* **Data Structure**: `java.util.ArrayList`
* **Version Control**: Git & GitHub[span_7](start_span)[span_7](end_span)

---

## 7. Execution Workflow
When executed via the terminal, the application automatically performs the following steps[span_8](start_span)[span_8](end_span):
1. Initializes the library catalog with sample books.
2. Displays the initial inventory.
3. Simulates a successful book borrowing operation.
4. Handles a duplicate borrowing attempt with error messaging.
5. Simulates returning the book and prints the final updated inventory.
6.
