# NADRA Management System (C++ Project)

This is a console-based NADRA (National Database & Registration Authority) Management System built in C++. The system simulates a token-based workflow used in government service counters for managing personal information, family trees, vaccination status, and CNIC card generation.

## 💡 Features

- **Token-Based Queue System**  
  Manages users at a simulated counter using a circular queue.

- **User Login System**  
  Simple password-based login (`dsa` is the default password).

- **Add New Person**  
  Collects user details including name, DOB, gender, address, and vaccination status. Also generates a CNIC-style ID.

- **Family Tree Structure**  
  Uses a binary tree to represent parent-child relationships.

- **Information Display**  
  Retrieve and display details of a person and their parents.

- **CNIC Card Generator**  
  Simulates a CNIC card layout with issue and expiry dates.

- **COVID-19 Certificate**  
  Generates a COVID-19 vaccination certificate based on the user's dose information.

- **Persistent File Storage**  
  Saves and loads user records from `Record.txt`.

## 🛠️ Technologies Used

- **C++**  
  - Object-Oriented Programming  
  - File Handling  
  - Custom Queue & Tree Data Structures  
  - ASCII Styling with ANSI Escape Codes

## 🔐 Login Credentials

| Username | Password |
|----------|----------|
| User     | `dsa`    |

## 🚀 How to Run

1. Open the project in any C++ IDE (e.g., Dev-C++, Code::Blocks, Visual Studio).
2. Compile `Nadra ms.cpp`.
3. Run the executable.
4. Log in using the credentials above.

## 📁 Output Files

- `Record.txt`: Stores all user and family data for persistence.

## 📌 Menu Options

1. Add new person
2. Show information of a person
3. Print complete family-tree
4. Show CNIC card
5. Show COVID certificate
6. Show all saved data
7. Quit

