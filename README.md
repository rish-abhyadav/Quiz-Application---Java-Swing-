.

🧠 Quiz Application – Java Swing

A desktop GUI quiz application built using Java Swing that allows users to answer multiple-choice questions, track their scores, and interact with a clean and simple interface.
The application uses JDBC with MySQL for backend database connectivity to store and manage quiz data.

🚀 Features

✔ Interactive Java Swing GUI
✔ Multiple-choice questions system
✔ Score tracking after quiz completion
✔ Database integration using JDBC
✔ Questions stored and managed in MySQL database
✔ Clean and simple user-friendly interface

🛠️ Technologies Used

Java

Java Swing

JDBC

MySQL

Object Oriented Programming (OOP)

📂 Project Structure
Quiz-Application-Java-Swing
│
├── src
│   ├── Main.java
│   ├── QuizFrame.java
│   ├── Question.java
│   ├── DatabaseConnection.java
│
├── database
│   └── quiz.sql
│
├── README.md
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/quiz-application-java-swing.git
2️⃣ Setup MySQL Database

Create a database in MySQL:

CREATE DATABASE quizdb;

Import the quiz table:

CREATE TABLE questions (
    id INT PRIMARY KEY AUTO_INCREMENT,
    question TEXT,
    optionA VARCHAR(255),
    optionB VARCHAR(255),
    optionC VARCHAR(255),
    optionD VARCHAR(255),
    correctAnswer VARCHAR(10)
);
3️⃣ Configure Database Connection

Update your JDBC connection in the project:

String url = "jdbc:mysql://localhost:3306/quizdb";
String username = "root";
String password = "your_password";
4️⃣ Run the Application

Compile and run:

javac Main.java
java Main

Or run directly from your IDE (IntelliJ / Eclipse / NetBeans).

📸 Application Preview

Main features include:

Question display

Multiple choice selection

Score calculation

Result display

🎯 Learning Outcomes

This project demonstrates:

Java GUI development with Swing

Database connectivity using JDBC

Object Oriented Programming concepts

Event handling in Java

Basic desktop application architecture

📌 Future Improvements

Timer for each question

Admin panel to add questions

Leaderboard system

Improved UI design

👨‍💻 Author

Rishabh Yadav
