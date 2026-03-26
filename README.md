# Quiz-App-Project
Project Structure (Files)
Your project contains 4 main Java files:
1. QuizApp.java
👉 Main entry point
Java
Copy code
public class QuizApp {
    public static void main(String[] args) {
        new LoginPage();
    }
}
✅ Purpose:
Starts the application
Opens the Login Page
2. LoginPage.java
👉 User enters name here
Features:
Text field for name
"Start Quiz" button
Working:
User enters name
Clicks button
Opens QuizPage
Java
Copy code
String username = nameField.getText();
new QuizPage(username);
✅ Concepts used:
JFrame
JLabel
JTextField
JButton
ActionListener
3. QuizPage.java
👉 Main quiz logic
Features:
Questions with 4 options
Radio buttons for answers
Timer (15 seconds)
Score tracking
Data Structure:
Java
Copy code
String questions[][]
String answers[]
