# Hotel-Bookingf-system-

This is a hotel booking system that allows customers to search for and book rooms at various hotels. The system is designed to be user-friendly and easy to use, with a simple and intuitive interface.

Features
User authentication: Customers can create an account and log in to the system to view their bookings and update their account information.
Room search: Customers can search for rooms based on various criteria, such as location, price, and availability.
Room selection: Customers can select a room and view its details, including room type, price, and amenities.
Booking: Customers can book a room by providing their personal information and payment details.
Confirmation: Customers receive a confirmation email after booking a room.
Installation
To install the hotel booking system, follow these steps:

Clone the repository to your local machine.
Install the required dependencies by running npm install.
Create a .env file in the root directory of the project and set the following environment variables:
makefile
Copy code
DB_HOST=<your_database_host>
DB_NAME=<your_database_name>
DB_USER=<your_database_user>
DB_PASSWORD=<your_database_password>
JWT_SECRET=<your_jwt_secret>
SENDGRID_API_KEY=<your_sendgrid_api_key>
FROM_EMAIL=<your_from_email_address>
Start the server by running npm start.
Usage
To use the hotel booking system, follow these steps:

Open the web application in your browser.
If you don't have an account, create one by clicking on the "Sign Up" button and filling in the required information.
Log in to the system using your email and password.
Search for rooms by entering the desired location, check-in and check-out dates, and number of guests.
Select a room from the search results and view its details.
Book the room by entering your personal information and payment details.
Receive a confirmation email with your booking details.
Technologies Used
Node.js
MongoDB
Mongoose
This hotel booking system was created by Mithilesh.
