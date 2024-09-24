# Online exam

This repository contains an Online Exam Interface developed using Java. The system allows users to take timed exams, automatically score their responses, and display results upon completion. It supports multiple-choice, true/false, and fill-in-the-blank questions, making it a flexible solution for conducting online exams.

# Features:
User Authentication: The system supports user login for students and administrators. Administrators can manage exams, while students can participate in exams after logging in.
Multiple Question Types: The interface supports various question formats, including:
Multiple Choice: Select one or more correct answers.
True/False: Choose between true or false.
Fill-in-the-Blank: Users input text to answer.
Timed Exams: Each exam can have a set time limit, and the timer starts as soon as the exam begins. Exams auto-submit when time expires.
Randomized Questions: Questions can be shuffled or selected randomly from a pool, ensuring different exams for each student.
Automatic Scoring: Upon completion of the exam, the system automatically grades the responses and calculates the final score.
Result Display: Students receive immediate feedback with their score and can review correct answers.
Admin Panel: Administrators can create, modify, and delete exams, add or remove questions, and view student scores and performance statistics.
Persistence: All user data, exam results, and questions are stored using a file-based system or database for future reference.

# How to Run:
Clone the repository and import the project into your Java IDE.
Configure the database or file system for storing exam data.
Run the project, and the login page will be displayed.
Administrators can log in to create and manage exams, while students can log in to take available exams.
How to Use:
For Administrators:
Log in using your admin credentials.
Create new exams by selecting question types, entering questions, and specifying correct answers.
Set time limits and other exam settings.
View exam results and performance data.
For Students:
Log in with your student credentials.
Select an available exam from the dashboard.
Complete the exam within the time limit and submit it for automatic grading.
View your results after completing the exam.

# Technologies Used:
Java: Core functionality of the interface is built using Java.
JavaFX or Swing: The graphical user interface (GUI) is developed using JavaFX or Swing for a responsive and user-friendly interface.
Database or File Storage: Exam data and user credentials can be stored using either a relational database (e.g., MySQL) or file-based persistence (e.g., JSON, XML).

