# Mobile-application-Development

* Description of the Project
The Employee Scheduling App is a web-based solution designed to manage employee shifts efficiently. The application allows managers to create and assign weekly shifts, while employees can view their schedules grouped by days of the week (Monday-Sunday). The app is targeted at small to medium-sized businesses that rely on shift-based scheduling for their operations. The primary goal is to simplify the scheduling process, reduce conflicts, and improve communication between managers and employees.

* Problem Being Addressed
The app addresses common scheduling challenges by ensuring no overlapping shifts occur, thanks to features that consider employee availability. Employees will soon have the ability to set their availability, making it easier for managers to assign shifts. The app also plans to include shift swap requests and notifications, allowing employees to trade shifts with approval from managers and stay informed of schedule changes in real time. These features enhance flexibility and ensure clear communication.

* Platform
The current version of the app is designed for desktop access, with managers utilizing a web dashboard to manage schedules and view weekly reports. In future updates, mobile integration will be implemented to allow for on-the-go access to scheduling tools, expanding the platform’s usability and accessibility.

* Front/Back-End Support
The front-end of the app is built using HTML and CSS, providing a simple yet effective interface for both managers and employees. The back-end is powered by Flask, a Python-based framework, with SQLite serving as the database. This setup ensures lightweight, efficient, and persistent data storage for employee and shift information. Future updates aim to introduce mobile-responsive designs and extend functionality through advanced frameworks like React Native.

* Functionality
Managers can add employees, assign shifts, and view schedules with ease. Employees can see their schedules grouped by the day of the week. Planned updates include enabling employees to set availability and submit shift swap requests, which will require manager approval. Notifications for schedule changes will also be added to improve communication. The app currently focuses on delivering core features, with enhancements planned for authentication, mobile usability, and notification systems.

* Design (Wireframes)
The app includes essential wireframes such as a login page for user authentication (planned), a manager dashboard to manage employees and shifts, and an employee dashboard for viewing personal schedules. The schedule view provides a calendar-style interface, showing assigned shifts for each day of the week. Additional pages are planned for managing employee availability and shift swap requests.

* Known Issues and Planned Enhancements
The current version does not include authentication, allowing all users to access the same dashboard. Additionally, the interface lacks mobile optimization. Planned updates include adding a login system for managers and employees, implementing a shift swap feature, introducing notifications, and creating a mobile-friendly version of the app.

* How to Run Locally
To run the app locally, ensure Python 3.9 or later is installed. Clone the GitHub repository, install dependencies using pip install -r requirements.txt, and run the Flask app with python app.py. Once running, the app can be accessed via a web browser at http://127.0.0.1:5000. The SQLite database (schedule.db) is generated automatically to store employees and schedules.

* Project Structure
The project directory includes the app.py Flask backend, a templates folder for HTML files, a static folder for CSS styling, and the SQLite database file (schedule.db). Additionally, requirements.txt lists the Python dependencies, and README.md contains project documentation.

* License
This project is licensed under the MIT License. For details, refer to the LICENSE file in the repository.

