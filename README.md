# Naari Raksha – Women Safety Web Application

Naari Raksha is a web-based women safety and grievance redressal platform designed to ensure quick response and coordination between users, police, and administrators during emergencies. The system allows users to send SOS alerts, register complaints, and track their grievance status, while providing admin and police modules for managing and responding to reports efficiently.

---

## 1. Project Overview

The main goal of the Naari Raksha application is to enhance women's safety through a digital platform that connects victims, guardians, and authorities.  
It includes real-time SOS alerts with geolocation tracking, police station mapping, and grievance management.

---

## 2. Technologies Used

- **Frontend:** HTML, CSS, JavaScript, AngularJS  
- **Backend:** PHP  
- **Database:** MySQL  
- **Server Environment:** XAMPP (Apache, MySQL, PHP)  
- **Tools:** phpMyAdmin, VS Code  

---

## 3. System Modules

### 3.1 Admin Module

**Features:**
- Admin Login and Authentication  
- Register New Police Accounts  
- Manage Police Details (Add, Edit, Delete)  
- Create and Update Police Stations  
- View All Complaints Submitted by Users  
- Receive SMS Alerts from Users  
- Track and View User Geolocation  

**Description:**
The admin controls overall system activities, manages the police department records, and ensures complaint tracking. The admin also monitors SOS alerts and provides quick communication with the police department.

---

### 3.2 Police Module

**Features:**
- Police Login  
- View Assigned Complaints  
- Update Complaint Status  

**Description:**
The police module enables authorized officers to log in, view active complaints, verify reports, and update complaint statuses once an action has been taken.

---

### 3.3 User Module

**Features:**
- User Registration and Login  
- Add and Manage Guardian Contacts  
- Update Geolocation  
- SOS Button for Emergency Alerts  
- Send SMS Alert to Guardians  
- Search Nearby Police Stations  
- File New Complaints  
- Track Complaint Status  

**Description:**
Users can register and log in to report incidents, add guardians for emergency notifications, and use the SOS button to immediately send their live location to registered guardians and authorities.  
This module ensures quick communication during emergencies and simplifies the grievance filing process.

---

## 4. System Features and Workflow

During the development process, the problem was analyzed and divided into smaller modules to ensure structured implementation. The system provides three key interfaces — **Admin, Police, and User** — each responsible for different operations.

- **User Interface:** Focused on safety actions like SOS alerts, complaint registration, and location tracking.  
- **Admin Interface:** Responsible for managing police data, complaint records, and user monitoring.  
- **Police Interface:** Allows officers to act on received complaints and provide real-time status updates.

---

## 5. Implementation Details

### 5.1 HTML
HTML is used to define the structure of the web pages. It provides the base layout for all modules, forms, and dashboards in the Naari Raksha application.

### 5.2 CSS
CSS defines the visual presentation of the interface, ensuring a responsive and accessible design. It controls layout, typography, color, and alignment to provide a user-friendly experience.

### 5.3 JavaScript / AngularJS
AngularJS enhances the client-side interactivity and manages dynamic data rendering. It helps in creating responsive forms, dynamic updates, and seamless navigation across pages.

### 5.4 PHP
PHP acts as the server-side scripting language responsible for backend operations such as user authentication, complaint submission, SMS triggers, and database connectivity.

### 5.5 MySQL
MySQL serves as the backend database to store and manage all user data, complaint records, police station information, and admin credentials.

---

## 6. Core Functionalities

### Emergency Response
Users can trigger an SOS alert that sends an immediate SMS notification with their live location to guardians and the nearest police station.

### Grievance Redressal
Users can file complaints, and the police can view and act upon them. Admin can monitor and manage the entire flow from submission to resolution.

### Geo-Tracking
The system captures longitude and latitude data for accurate user location tracking during emergencies.

### Multi-role Access
Separate interfaces for Admin, Police, and Users ensure secure access and role-based functionality.

---

## 7. How to Run the Project

1. **Install XAMPP** and start Apache and MySQL services.  
2. **Clone the Repository:**
   ```bash
   git clone https://github.com/ChVardhan04/Naari-Raksha-Women-Safety-Web-App.git
