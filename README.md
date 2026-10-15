# Java-based-library-systems-
Guvi project
# 📚 Library Management System

A Java-based Library Management System created for the **GUVI - Galgotias Project Board (2nd Sem 2028)**. This project demonstrates practical application of Java concepts including GUI development, database integration, event handling, and data validation.

---

## 🚀 Features

- ✅ User Registration and Login
- 📖 Add / View / Delete Books
- 🔁 Issue and Return Books
- 🔍 Search Book by Title / Author
- 📊 View Issued Book Records
- 🔐 Admin and Student Roles
- 💾 Persistent Database using MySQL
- ⚠️ Input Validation and Error Handling

---

## 🏗️ Project Structure

```
LibrarySystem/
│
├── src/
│   ├── Main.java
│   ├── ui/
│   │   ├── LoginScreen.java
│   │   ├── Dashboard.java
│   ├── models/
│   │   ├── Book.java
│   │   ├── User.java
│   ├── database/
│   │   ├── DBConnection.java
│   │   ├── BookDAO.java
│   │   ├── UserDAO.java
│
├── lib/                  # External libraries if used
├── README.md             # Project documentation
├── ER_Diagram.png        # Entity-Relationship Diagram
└── database.sql          # SQL script to create the database
```

---

## 💻 Technologies Used

- Java (Swing / AWT)
- MySQL Database
- JDBC for Database Connectivity
- OOP and MVC Principles

---

## 🔧 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/library-system.git
   cd library-system
   ```

2. **Import Project**
   - Open in IntelliJ / Eclipse
   - Set JDK version (Java 8 or above)

3. **Setup Database**
   - Import `database.sql` in MySQL
   - Update DB credentials in `DBConnection.java`
     ```java
     String url = "jdbc:mysql://localhost:3306/library";
     String user = "root";
     String password = "your_password";
     ```

4. **Run the Project**
   - Run `Main.java`

---

## 🧪 Sample Test Cases

| Action         | Input                          | Expected Result              |
|----------------|--------------------------------|------------------------------|
| Register       | Empty username or password     | Shows validation error       |
| Login          | Wrong credentials              | Shows login failure message  |
| Add Book       | Book with existing ISBN        | Duplicate entry error        |
| Issue Book     | Book not available             | Shows availability error     |
| Return Book    | Valid return                   | Book marked as returned      |

---

## 📝 Documentation

- 📄 ER Diagram (Attached)
- 🔁 Use-case Flowchart (Optional)
- 📘 Code is commented and modular
- 🔐 Input validations are implemented
- 🔧 Errors are handled using try-catch
---

## 🧑‍💻 Contributors
priyanshu khatri

---

## 📌 Project Info

> This project was submitted for **Review 2 (Final Submission)** under the **GUVI - Galgotias Project Board 2nd Sem 2028** to demonstrate core Java programming skills and real-world problem-solving ability.

---

## 📬 Contact
For queries 
- 📧 priyanshuppx@gmail.com
- 📱 +91-8700644229
