# codec_intenship1
Hcare Patient Portal 🏥
The Hcare Patient Portal is a client-side web application built using HTML, CSS, and JavaScript. It simulates the core functionality of a patient management system, allowing users to log in, view doctor availability, book appointments, and track their past and upcoming appointments using the browser's local storage.

✨ Features
User Authentication: Simple login and registration simulation (patient_login_register.html).

Patient Dashboard: Personalized overview of patient status and upcoming appointments (patient_dashboard.html).

Doctor Viewing: Browse available doctors and their specialties (view_doctors.html).

Appointment Booking: Select a doctor, date, and time slot to confirm a booking (confirm_appointment.html).

Appointment History: Dedicated page to view and categorize all past and upcoming appointments (see_all_appointments.html).

Data Persistence: All booked appointments are stored securely in the browser's Local Storage.

🛠️ Technology Stack
This project is a static front-end application and uses:

HTML5: Structure

CSS3: Styling (Inline <style> blocks for portability)

JavaScript (ES6): Core application logic, form handling, data storage (Local Storage), and page routing.

Font Awesome: Icons.

Google Fonts (Poppins): Typography.

🚀 Getting Started
Since this is a client-side application, you don't need a backend server or complex configuration.

Prerequisites
You only need a modern web browser (Chrome, Firefox, Edge, etc.).

Installation
Clone the Repository (if uploaded to GitHub):

Bash

git clone [YOUR_REPO_URL]
OR
Download the Files: Download the entire folder containing all HTML files (patient_dashboard.html, confirm_appointment.html, etc.) and any CSS/JS files (if separated).

Run the Application:
Navigate to the project folder and simply double-click the patient_login_register.html file. It will open automatically in your default web browser.

🧭 Project File Structure
The project uses a flat file structure, with all core HTML pages residing in the main directory:

/Hcare-Patient-Portal/
├── patient_login_register.html    (Starting Page)
├── patient_dashboard.html         (Main patient area)
├── view_doctors.html              (Page for selecting doctors/slots)
├── confirm_appointment.html       (Final booking page)
├── see_all_appointments.html      (Appointment history/list page)
└── README.md                      (This file)
👨‍💻 Usage
1. Registration & Login
Open patient_login_register.html.

Click the Register tab and enter a username and password. This stores your credentials in Local Storage.

Switch to the Login tab and use your new credentials to access the Dashboard.

2. Booking an Appointment
From the dashboard, click View Doctors in the sidebar.

Select a doctor and click Book Slot.

Choose an available slot. This redirects you to confirm_appointment.html.

Enter the Reason for Visit and click Complete Booking.

The system saves the appointment to Local Storage and redirects you back to the Dashboard.

3. Viewing All Appointments
Click See All Appointments in the sidebar.

The page (see_all_appointments.html) automatically fetches all saved appointments and organizes them into Upcoming and Past sections based on the current date and time.

🤝 Contribution
Contributions are welcome! If you find a bug or have an idea for a new feature (like integrating a real database or adding a doctor portal), feel free to fork the repository and submit a pull request.

📜 License
This project is open-source and available under the [License Name, e.g., MIT License].

****<img width="916" height="427" alt="image" src="https://github.com/user-attachments/assets/4d8700df-f1b0-4b9d-91e6-c11cdb23e836" />
<img width="506" height="380" alt="image" src="https://github.com/user-attachments/assets/b961c768-2843-4a7c-86dd-a445fd1c3cd9" />
<img width="958" height="374" alt="image" src="https://github.com/user-attachments/assets/827afcc5-d042-4c4c-9197-25f13e5e19bf" />
<img width="952" height="443" alt="image" src="https://github.com/user-attachments/assets/7d2f0893-6d03-49be-ab08-a3b626c0080e" />
<img width="956" height="398" alt="image" src="https://github.com/user-attachments/assets/20478e86-d49d-4a40-a953-ffc95dd0d27f" />
<img width="440" height="395" alt="image" src="https://github.com/user-attachments/assets/87f9b72c-e242-4d5e-9188-5f9bc60f8d76" />



https://github.com/user-attachments/assets/83fb8a6d-bde5-4073-8851-d0c7444421a1







