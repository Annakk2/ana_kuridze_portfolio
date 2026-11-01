StudentGradeManagementSystem
=============================

Course: IT-260 — Advanced Programming
Professor: Anthony Rodriguez

This ZIP contains the complete Visual Studio Windows Forms project and documentation for the Student Grade Management System.

How to open, build, and run
---------------------------

1. Requirements
   - Microsoft Visual Studio 2019 or later.
   - .NET Framework 4.7.2 (or higher compatible installed).

2. Open the solution
   - Extract the ZIP file to a folder on your computer.
   - In Visual Studio, go to File -> Open -> Project/Solution.
   - Browse to the extracted folder and open `StudentGradeManagementSystem.sln`.

3. Build the solution
   - In Visual Studio, select Build -> Build Solution.
   - Ensure the configuration is set to `Debug` and `Any CPU`.

4. Run the application
   - Press F5 or click the green "Start" button.
   - The `LoginForm` will open as the startup form.

5. Login credentials
   - Use any of the pre-loaded student records to log in for testing.
   - (Credentials configured separately — contact repo owner for demo access.)

6. Application flow
   - Log in to reach the Dashboard.
   - From the Dashboard you can:
       * Open the Student Roster (double-click a student to edit grades).
       * Generate a report for a selected student.
       * Log out to close the Dashboard.

Data notes
----------
- The DataStore is fully in-memory. No database server is required.
- Four students are pre-loaded:
  * Ana Kuridze
  * Kellonar Baptiste
  * Raymond Debra
  * Julian Lambert

