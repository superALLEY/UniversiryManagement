# University Management System

## Project Overview
This Java-based University Management System is designed to handle various administrative tasks in a university setting. It includes functionalities for managing student records, teacher assignments, course details, grades, attendance, and more. The system is divided into several classes, each representing a different component of the university.

## Features
- **Student Management**: Store and manage student information, including personal details, grades, and attendance records.
- **Teacher Management**: Store and manage teacher information, including personal details and course assignments.
- **Course Management**: Handle course details such as course codes, coefficients, and teacher assignments.
- **Attendance Management**: Mark and calculate attendance for various courses.
- **Grade Management**: Add, change, and display grades, as well as calculate grade averages.
- **Year and Department Management**: Organize students, courses, and teachers by academic year and department.
- **Admin Interface**: Full access to manage all aspects of the system.
- **Student Interface**: Limited access for students to view their grades, attendance, and receive notifications.
- **Authentication**: Secure login for both admins and students.
- **File Storage**: Persistent data storage using file I/O operations.

## Project Structure
The project is structured into the following classes:

1. **`Student` Class**: Manages student information such as age, full name, ID, date of birth, place of birth, year, class, grades, attendance, password, email, and phone number.
2. **`Attendance` Class**: Manages attendance records for each course. Includes methods for marking attendance, calculating attendance percentages, and displaying attendance records.
3. **`GradeManagement` Class**: Manages grades, including methods for calculating, adding, changing, displaying, and calculating grade percentages.
4. **`Teacher` Class**: Manages teacher information, including age, full name, ID, date of birth, place of birth, year, assigned classes, attendance, password, email, and phone number.
5. **`Course` Class**: Manages course details, including course code, coefficient, and assigned teachers. Includes methods to add, remove, and change course details.
6. **`Year` Class**: Represents a school year, including students, courses, teachers, lab rooms (TP/TD), and the program. Includes methods to add, remove, and change year details.
7. **`Department` Class**: Manages academic years.
8. **`Admin` Class**: Manages admin accounts with username and password authentication.
9. **`NotificationInterface`**: Sends notifications to students.
10. **Input/Output Operations**: Handles file operations for each class to store and retrieve data.

## How It Works
1. **Authentication**: The system starts with a login page where users authenticate as either an admin or a student.
2. **Admin Privileges**: Admins have full access to manage students, teachers, courses, and more.
3. **Student Interface**: Students have limited access to view their personal information, grades, and attendance records.
4. **Data Storage**: All data is stored in files for persistence.

## Getting Started
### Prerequisites
- Java Development Kit (JDK) 8 or higher.
- An Integrated Development Environment (IDE) such as IntelliJ IDEA, Eclipse, or NetBeans.

### Running the Project
1. Clone the repository to your local machine.
2. Open the project in your preferred IDE.
3. Compile and run the `Main.java` file to start the application.
4. Log in with the credentials provided in the sample data files or create new users.

## Project Workflow
1. **Login Page**: Authenticate as an admin or a student.
2. **Admin Dashboard**: If authenticated as an admin, access the management UI with all privileges.
3. **Student Dashboard**: If authenticated as a student, access a UI to view personal information, grades, and attendance.
4. **Management Operations**: Perform various management operations depending on the user's privileges.

## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact
For any questions or inquiries, please contact mohamed.ali.inouri@gmail.com.
