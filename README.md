# Student Management System (CLI-based)

A simple **Command Line Interface (CLI)** application built in Java to manage student records. This application allows users to perform basic **CRUD operations** — Create, Read, Update, and Delete — on student data, including their **ID**, **Name**, and **Marks**.

---

## 🛠 Features

- ➕ Add new student (with ID, Name, Marks)
- 📋 View all students
- ✏️ Update student name and marks
- ❌ Delete student by ID
- 📦 Object-Oriented design using Java classes

---

## 📂 Project Structure

```bash
LibraryManagmentSystem/
├── Student.java              # Model class for Student
├── StudentManager.java       # Business logic (CRUD operations)
├── StudentCLIApp.java        # Entry point with menu-based interaction
```

---

## 🚀 Getting Started

### 🔧 Prerequisites

* Java JDK (8 or above)
* IDE like IntelliJ IDEA, Eclipse, or command-line tools

### ▶️ How to Run

1. Clone or download the repository.
2. Navigate to the project directory.
3. Compile the code:

   ```bash
   javac LibraryManagmentSystem/*.java
   ```

4. Run the application:

   ```bash
   java LibraryManagmentSystem.StudentCLIApp
   ```

---

## 📸 Sample Output

```
Student Management System
1. Add Student
2. View All Students
3. Update Student
4. Delete Student
5. Exit
Enter your choice:
```

---

## 💡 Future Improvements

* ✅ File-based persistence (save/load students)
* 🔎 Search students by name or marks
* 📊 Sort students by marks or alphabetically
* 🖥️ GUI version using JavaFX or Swing

---

## 🧑‍💻 Author

* **Anurag** — Developer & Maintainer
* 💬 Contributions and suggestions are welcome!

---
