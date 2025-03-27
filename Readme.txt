VIT Examination Management system

Overview:- 

The Exam Management System is a frontend-only web application that allows faculty members to create exams and students to take them. It features role-based access control, a question management system for faculty, and a timed exam interface for students.




Features:- 



General

Role-based login for Faculty and Students

Simple UI with a blue-themed design



Fullscreen exam mode for students

Faculty Dashboard:-

Can create and manage exam questions

Can specify answer choices and correct answers

Stores questions using localStorage

Can delete existing questions




Student Exam Page:-

Displays exam questions one at a time

Allows navigation using "Previous" and "Next" buttons

Tracks student responses

Timed exam feature (30 minutes by default)

Auto-submission when the timer expires

Displays the final score upon submission

Security & Malpractice Prevention

Auto full-screen mode during exams

Prevents tab switching using JavaScript-based fullscreen enforcement






Installation and Usage Requirements:- 

A modern web browser (Chrome, Firefox, Edge, etc.)

No additional dependencies required (pure HTML, CSS, and JavaScript)

Steps to Run the Application

Download or clone the project files.

Open index.html in a web browser.



Login using predefined credentials:

Student: student / password

Faculty: faculty / password


Faculty can create and manage questions.

Students can take the exam when questions are available.

The exam is automatically submitted after n minutes or manually by the student.

The student’s score is displayed at the end.






File Structure

Exam-Management-System/
│-- index.html  # Main application file
│-- styles.css  # Styling (included within index.html)
│-- script.js   # JavaScript logic (included within index.html)





Credits

Developed by: Bastardos Indecisas

Languages Used:- HTML, CSS, JavaScript



Future Enhancements

Add an Admin Role to manage system-wide settings

Enhance security measures (restrict browser interactions during exams)

Implement backend integration for persistent data storage

Improve UI/UX with better animations and responsiveness




License

This project is open-source and available for modification and use under the MIT License.

