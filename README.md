# Photo-storage
PROJECT FOCUS: Secure Photo Storage with QR Code Integration

This website allows users to securely store photos by directly linking them to a QR code. Here's the process breakdown:

#User Uploads: Unlike traditional upload methods, users wouldn't directly upload photos through the website.
#QR Code Generation: The website generates a unique QR code for each user.
#Image Capture and Storage: Upon scanning the QR code with the mobile app, the user captures a photo using the phone's camera.
#Data Transmission (potential): The mobile app transmits the captured image data directly to the website's server-side script (likely written in PHP).
#Database Storage: The PHP script processes the received image data and stores it securely in the MySQL database managed by phpMyAdmin.
#Website Access: Users can access and view their stored photos by logging into the website using their account credentials.

#TECHNICAL STACK:

Front-end: HTML provides the website structure, and CSS styles the visual elements.
Back-end: PHP handles user interaction, QR code generation, potential data reception from the mobile app, and database communication.
Database: MySQL stores user information, unique QR code references, and potentially encrypted photo data (using phpMyAdmin for database management).

Security Considerations:

Implementing secure image storage techniques in the database is crucial.
User authentication and authorization are essential to ensure only authorized users can access their photos.
