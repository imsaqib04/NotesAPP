# 📝 Notes Manager (Java Console App)

A simple terminal-based Notes Manager built in Java. This application allows users to:

- Save notes with a **timestamp**
- Attach the **username** to each note
- View all saved notes from a file
- Keep everything stored in a local `notes.txt` file

---

## 💻 Features

- 📥 Add notes with timestamp and username
- 📂 View saved notes (with line numbers)
- 🧾 Data saved in `notes.txt`
- 👤 User-based note tagging
- ⚙️ File I/O using `FileWriter` and `BufferedReader`
- 🖥️ Simple CLI interface

---

## 🛠️ Technologies Used

- Java SE (JDK 21+ compatible)
- File I/O (`FileWriter`, `BufferedReader`)
- `Scanner` for input
- `LocalDateTime` for timestamps

---

## 🚀 How to Run

1. Clone or download the repository:

   git clone https://github.com/imsaqib04/NotesAPP.git
   
   cd NotesAPP

Compile and run using terminal or IDE (like VS Code or IntelliJ):

javac NotesApp.java

java NotesApp


📁 Example notes.txt

[2025-06-27 22:10:55] (saqib) This is my first note!
[2025-06-27 22:12:10] (john) Reminder: Finish task 4


📄 File Structure

├── NotesApp.java      # Main Java file

└── notes.txt          # Automatically created for storing notes

🧑‍💻 Author: 

Saqib Ansari

GitHub: @imsaqib04

