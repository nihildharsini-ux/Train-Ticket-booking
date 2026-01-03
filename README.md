Train Ticket Booking 

Objective:
To collect ticket details using JSP and store them through a servlet.

Description:
•	booking.jsp → name, source, destination, date
•	Servlet → stores details in DB (JDBC insert)
•	viewTicket.jsp → retrieves and displays ticket details (JDBC select via servlet)

•	JSP pages (booking.jsp, viewTicket.jsp)
•	BookingServlet

Database:
CREATE DATABASE train_db;

USE train_db;

CREATE TABLE ticket (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(50),
    source VARCHAR(50),
    destination VARCHAR(50),
    travel_date DATE
);





