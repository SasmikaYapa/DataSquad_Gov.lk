# Gov.lk Services Portal - Frontend Prototype

*A high-fidelity, interactive frontend prototype for a centralized government services appointment booking portal. This project demonstrates the user interface and core user flows for the Tech-Triathlon Hackathon challenge.*

---

## 🚀 Live Demo

This prototype is a self-contained index.html file. To run it:

1.  **Download the homecentral.html and 'newpage.html' file.**
2.  *Open it directly in any modern web browser* (like Chrome, Firefox, or Edge).

No server or installation is required to view and interact with the demo. All data is mocked and stored locally in your browser's localStorage.

---

## ✨ Features Implemented in the Prototype

This prototype showcases a comprehensive set of features designed to meet the hackathon requirements. All functionalities are interactive and demonstrate the complete user journey.

### 1. Unified Appointment Booking System
*   *Service Directory:* Browse a filterable list of government departments.
*   *Multi-Step Booking Modal:* A dynamic, step-by-step process guides users through selecting a service, viewing required documents/fees, and choosing a venue.
*   *Custom Booking Flows:* Includes a specialized booking flow for *Sri Lanka Railways* (selecting route and train) and a simplified flow for utility payments.
*   *Interactive Calendar & Time Slots:* Select available dates and times for appointments.
*   *Booking Confirmation:* Generates a unique reference number and provides an option to add the appointment to a personal calendar (.ics file generation).

### 2. Citizen Dashboard & Document Pre-submission
*   *"My Appointments" Section:* View a table of all upcoming and past appointments.
*   *Appointment Management:* Users can *Reschedule* or *Cancel* upcoming appointments.
*   *Secure User Session (Mocked):* A simulated login/logout system that persists the user's session using localStorage.
*   *Personal Dashboard:* A dedicated modal for logged-in users, showing alerts (e.g., passport renewal), a document vault concept, and a summary of appointments.

### 3. Automated Notification System (Mocked)
*   *Notification Bell:* An interactive notification center in the header displays the number of unread alerts.
*   *Mocked Reminders:* The system simulates appointment reminders (e.g., "Your appointment for [Service] is tomorrow").

### 4. Integrated Feedback System
*   *Rate Past Services:* After an appointment date has passed, a "⭐ Rate Service" button appears.
*   *Interactive Rating Modal:* Users can provide a 1-5 star rating and leave comments for completed services.

### 5. Advanced User Experience Features
*   *Multi-Language Support:* Fully functional language switcher for *English, Sinhala (සිංහල), and Tamil (தமிழ்)*.
*   *Dark Mode:* A persistent light/dark mode theme switcher for user comfort.
*   *Responsive Design:* The layout is designed to be functional across various screen sizes.
*   *Search and Filtering:* Users can search for departments by name or tag, and filter by category.

---

## 🛠 Technology Used

*   *HTML5*
*   *CSS3* (with CSS Variables for theming)
*   *Vanilla JavaScript (ES6+)*
*   *No external libraries or frameworks were used*, demonstrating a strong command of core web technologies.

---

## 🏛 Project Structure

This prototype is a single index.html file containing three main parts:
1.  **<style> block:** Contains all the CSS for styling and layout.
2.  **<body> block:** Contains all the HTML for the page structure and modals.
3.  **<script> block:** Contains all the vanilla JavaScript logic, including:
    *   Mock data (departments, services, translations).
    *   State management functions (using localStorage).
    *   DOM manipulation and rendering functions.
    *   Event listeners for all interactive elements.

---

## 🧑‍💻 Team Members

*   Sithum Yapa
*   Senali Bandara
*   Malindu Kavishan
*   Remeena Hirushi
*   Kassapa Arthasad
*   Chathurani Sudharshika
*   Vihanga Nawagamuwa
*   Hasitha Induwara
*   Samitha Sandaruwan
