cos 202 assignment 4: clinic queue app

Student Name: Bashir Bobboi Umar

Matric Number: MAAUN/24/CBS/0014

Clinic Queue System 

A web-based clinic queue management system built with Python and Flask, designed to help clinics manage patients efficiently.

This app allows a clinic to:
• Register patients (normal or priority)
• View the current queue in first-in, first-out order
• Manage patients with features like add, remove, and next patient
• Reset the queue at any time
• Export the queue to a CSV file
• Sort the queue as needed
• Track active lifetime and average waiting time for patients
• Toggle between dark and light mode for the interface

Features
1. Add Patient – Register new patients to the queue.
2. Remove Patient – Delete a patient from the queue manually.
3. Next Patient – Call the next patient in line.
4. Reset Queue – Clear the queue completely.
5. Export Queue – Save the current queue into a CSV file for record keeping.
6. Sort Queue – Arrange patients by name or priority.
7. Toggle Dark/Light Mode – Switch between dark and light themes for better visibility.
8. Active Lifetime – Track how long patients have been waiting.
9. Average Waiting Time – See the average time patients spend in the queue.

Technologies Used
• Python 3.x
• Flask (web framework)
• HTML/CSS (front-end UI)
• Python datetime module for timestamps

How to Run the App Locally
1. Clone the repository:
git clone <repository-link>

2. Navigate to the project folder:
cd clinic-queue-system

3. Install Flask (if not already installed):
pip install Flask

4. Run the app:
python app.py

5. Open your browser and go to:
http://127.0.0.1:5000

You will see the Clinic Queue Manager interface ready to use.
