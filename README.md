SDHRS
Secure Digital Health Records System Overview The Secure Digital Health Records System (Health Center Patient Record Management System) is a comprehensive web-based platform designed to manage and secure patient health records. It enables healthcare providers to access, update, and store patient data safely, with the added functionality of generating QR codes for each patient. The system is built to improve the efficiency of managing medical records and ensure data privacy.

Features Administrator Dashboard: Provides an interface for managing patients, healthcare sections, and user accounts. Patient Record Management: Administrators can create, view, update, and delete patient records securely. QR Code Generation: A unique QR code is generated for each patient, facilitating easy access and verification of patient information. Role-based Access Control: Ensures that only authorized personnel can access sensitive data. Secure Authentication: Uses strong encryption and authentication mechanisms to protect user credentials. Technologies Used Frontend: HTML, CSS, JavaScript (Bootstrap for responsive design) Backend: PHP, MySQL QR Code Generation: PHP QR Code library based on C libqrencode Installation Clone the repository: git clone https://github.com/your-username/secure-health-records.git

Set up the project in your local server (XAMPP or similar).

Import the database schema from health_records.sql into your MySQL database.

Ensure the QR code library is included and configured properly.

Configure settings like database credentials in the configuration file.

Security Features Data Encryption: Sensitive patient data is encrypted before storage in the database. Secure Login: The system uses hashed passwords for user authentication. Role-based Access: Different roles are assigned with varying levels of access to ensure the right personnel manage data. Future Enhancements Integration with electronic health record standards (e.g., HL7). Mobile app support for patient access and management. License This project is licensed under the MIT License.
