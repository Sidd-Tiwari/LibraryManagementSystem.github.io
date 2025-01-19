# 📚 Library Management System

## Overview
The **Library Management System** is a graphical user interface (GUI) application built using Python's **Tkinter** library. It provides a user-friendly platform for managing books in a library, enabling operations such as adding books, displaying the library catalog, searching for books, checking out books, and returning books.

---

## ✨ Features
- 📝 **Add Books**: Add new books to the library catalog with details such as title, author, and ISBN.
- 📋 **Display Books**: View all books in the library along with their availability status.
- 🔍 **Search Books**: Search for books in the library by title and check their availability.
- 📖 **Check Out Books**: Borrow books from the library, marking them as checked out.
- 📥 **Return Books**: Return borrowed books and mark them as available.
- ❌ **Exit Application**: Close the application gracefully.

---

## 🛠 Technologies Used
- **Programming Language**: Python 🐍
- **GUI Library**: Tkinter 🖼️

---

## 📂 Class Structure

### 📗 `Book`
Represents a book in the library with attributes for title, author, ISBN, and availability status.

### 📘 `Library`
Manages the collection of books and provides methods for:
- ➕ Adding books
- 📃 Displaying the catalog
- 🔍 Searching for books
- 📖 Checking out books
- 📥 Returning books

### 📙 `LibraryGUI`
Handles the graphical user interface and provides methods for:
- 🖥️ Creating the main window and widgets
- 🤝 Handling user interactions for library operations

---

## 🔧 How It Works

1. **Main Window**:  
   🖥️ The main GUI window displays buttons for all library operations.
   
2. **Add a Book**:  
   ➕ Opens a form where users can input the title, author, and ISBN of a new book.

3. **Display Books**:  
   📚 Shows the complete library catalog in a message box.

4. **Search for a Book**:  
   🔍 Opens a search form to look up books by title and displays the result.

5. **Check Out a Book**:  
   📖 Allows users to borrow a book by title if it is available.

6. **Return a Book**:  
   📥 Allows users to return a previously borrowed book.

---

## 🚀 Installation and Setup

1. Clone the repository or download the code:  
   ```bash
   git clone https://github.com/your-repo/Library-Management-System.git
   cd Library-Management-System
   ```

2. Ensure Python is installed on your system. You can download it from [python.org](https://www.python.org/). 🐍

3. Run the program:  
   ```bash
   python library_management_system.py
   ```

---

## 📸 Screenshots
Include screenshots of your application showcasing:  
1. 🖥️ The main window  
2. ➕ Add Book window  
3. 🔍 Search Book window  
4. 📖 Check Out Book window  
5. 📥 Return Book window  

---

## 🌟 Future Enhancements
- 🗄️ Implement a database to store book records persistently.
- 🔐 Add user authentication for enhanced security.
- 👥 Extend functionality to handle multiple users and roles (e.g., librarian, member).
- 🔎 Introduce advanced search and filtering options.

---

## 👨‍💻 Author
**Siddharth Tiwari**  

---
