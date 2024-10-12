# Railway Management System

## Project Overview
The Railway Management System is a comprehensive web application developed as part of **Database Systems** course at the university. The system aims to provide an efficient and user-friendly platform for clients to manage their train travel needs, from booking tickets to providing feedback on their experiences. 

## Technologies Used
- ASP.NET
- C#
- SQL Server
- HTML/CSS
- JavaScript
- Entity Framework

## Getting Started

### Prerequisites
To run this project, ensure you have the following installed on your system:
- Visual Studio (with ASP.NET development environment)
- SQL Server (or SQL Server Express)
- .NET Framework

### Installation Steps
1. **Clone the Repository**  
   Open your terminal and run the following command to clone the repository:
   ```bash
   git clone https://github.com/pola-k/Railway-Management-System.git
   ```
   
2. **Create an ASP.NET Project**  
   Open Visual Studio and create a new ASP.NET project.

3. **Copy Files**  
   Copy the files from the cloned repository into your newly created ASP.NET project directory.

4. **Update Database Settings**  
   Open the configuration file (usually `appsettings.json` or `web.config`) and update the database connection settings to match your SQL Server instance.

5. **Run Migrations**  
   If you're using Entity Framework, ensure you run the necessary migrations to set up the database schema:
   ```bash
   Update-Database
   ```

6. **Start the Application**  
   Launch the application in Visual Studio and navigate to `localhost:<port>` in your web browser.

## Functionalities
The Railway Management System provides a variety of features to enhance user experience:

### 1. Sign Up
Clients can create accounts to register themselves. This includes providing necessary personal information.

### 2. Log In
Clients can log in with valid credentials to access their accounts.

### 3. Profile Editing
Clients have the ability to edit their personal information previously entered during account creation.

### 4. Schedule
Clients can view the schedule of upcoming train rides, including departure and arrival times.

### 5. Rating
Clients can post reviews and rate their experiences, contributing to community feedback.

### 6. Catalogue
The catalogue displays the unique experiences clients can enjoy when traveling with the railway service.

### 7. Booking Tickets
Clients can easily book and purchase tickets for their desired train rides through a user-friendly interface.

### 8. Cancel Reservations
Clients have the option to cancel their bookings if necessary, ensuring flexibility in their travel plans.

### 9. Customer Loyalty Reward System
Clients can benefit from special incentives, including discounts, as part of the customer loyalty reward program.

### 10. Ride Status
Clients can check the current status of train rides, including delays or cancellations.

### 11. Rate Ride Experience
Clients can rate their ride experiences, providing valuable feedback to improve services.

### 12. Contact Us
Clients can reach out to customer care services for guidance and support regarding their travel needs.

## Database Schema
The database schema is designed to support the functionalities of the Railway Management System. It includes tables for users, bookings, schedules, and reviews, ensuring efficient data management.

![Database Schema]("Database Schema".png)

## Usage Instructions
1. **Creating an Account**: Click on the "Sign Up" button on the homepage and fill out the registration form.
2. **Logging In**: Enter your credentials in the login form and click "Log In."
3. **Viewing Schedules**: Navigate to the "Schedules" section to view available train rides.
4. **Booking Tickets**: Select a train ride and follow the prompts to complete your ticket purchase.
5. **Canceling Reservations**: Go to the "My Bookings" section, select your reservation, and choose the option to cancel.
6. **Providing Feedback**: You can submit reviews and rate your ride experiences.
