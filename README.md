Library Management System (Python)

A command-line based Library Management System built using Python, applying Object-Oriented Programming (OOP) concepts and file handling to manage book records efficiently.
This project simulates how a real library tracks book availability, issuance, and returns.

🚀 Features
- 📖 Display all books with ID and availability status
- 📤 Issue books with borrower name and issue timestamp
- 📥 Return books and update status
- ➕ Add new books dynamically
- 💾 Persistent storage using a text file
- ⚠️ Basic exception handling for better user experience

🛠️ Technologies Used
- Python 3.x
- Object-Oriented Programming (Classes & Methods)
- Dictionaries for structured data management
- File Handling (Read & Append Mode)
- datetime module for timestamp tracking

📂 Project Structure
- Library-Management-System/
1. ├── Library Management System.py
2. ├── List of Books.txt
3. └── README.md
   
⚙️ How It Works
1) When the program runs, it loads all books from the List of Books.txt file into a dictionary structure with:
- Book ID
- Book Title
- Lender Name
- Issue Date
- Status (Available / Already Issued)
  
2) The system then provides a menu-driven interface:
- Press 'D' to Display Books  
- Press 'I' to Issue Books  
- Press 'A' to Add Books  
- Press 'R' to Return Books  
- Press 'Q' to Quit
  
🧠 Concepts Applied
- Classes and Objectt
- Instance Variables
- Dictionaries for record management
- File Reading and Writing
- Date & Time Handling
- Input Validation
- Exception Handling
- Menu-driven program logic

🎯 Learning Outcomes
- Through this project, I strengthened my understanding of:
- Structuring real-world systems using OOP
- Managing dynamic records using dictionaries
- Working with persistent storage via text files
- Implementing basic backend logic
- Writing cleaner and more organized Python code

🔮 Future Improvements
- Add delete book functionality
- Implement fine calculation for late returns
- Add user authentication system
- Replace text file storage with SQLite database
- Convert into a GUI application (Tkinter)
- Develop a web-based version using Flask or FastAPI

👨‍💻 Author:
- Vikram Singh Kushwaha - Aspiring Python Developer | Data Science Enthusiast
