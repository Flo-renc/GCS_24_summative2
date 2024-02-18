Student Registration System
This is a simple shell script application for managing student records in the ALU registration system. The application allows users to perform various operations such as creating, viewing, updating, and deleting student records. Additionally, it provides functionality to select and save student emails to a separate file.

Files Included
main.sh: This is the main script file that implements the student registration system. It contains functions for creating, saving, viewing, deleting, and updating student records. The user interacts with this script to perform operations on student records.
select-emails.sh: This script is responsible for selecting and extracting email addresses from the student records file. It saves the extracted email addresses to a separate file named student-emails.txt.
Students-list_1023.txt: This file stores the student records in a comma-separated format. Each line represents a single student record with fields for email, age, and student ID.
student-emails.txt: This file stores only the email addresses extracted from the student records file. It is generated by the select-emails.sh script.
Functionality

App Operations:
    1. Create Student Record
    Allows users to input student details including email, age, and student ID.
    Saves the student record to the Students-list_1023.txt file.
    2. View All Students
    Displays all student records currently saved in the Students-list_1023.txt file.
    3. Delete Student Record
    Prompts the user to enter a student ID to delete.
    Deletes the corresponding student record from the Students-list_1023.txt file.
    4. Update Student Record
    Prompts the user to enter a student ID to update.
    Allows users to input new student details (email and age).
    Updates the corresponding student record in the Students-list_1023.txt file.
    5. Exit
    Terminates the application.

SEARCH AND SORTING INTO A FILE
    Extracts email addresses from the student records file (Students-list_1023.txt).
    Saves the extracted email addresses to the student-emails.txt file.
    Usage

