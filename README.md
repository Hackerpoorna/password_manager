This project is a Java-based server application designed to provide a secure and efficient password management solution. It uses Java’s HttpServer class to handle HTTP requests and serves a user-friendly interface for managing, storing, and retrieving passwords securely.

Features
Secure Password Storage: Encrypts and stores user passwords securely in memory.
Password Retrieval: Allows users to retrieve stored passwords dynamically.
Dynamic Password Management: Enables users to add, update, and delete stored passwords.
Static Page Serving: Serves multiple static HTML pages for features like account management, settings, and password tips.
Error Handling: Displays error messages for invalid operations or missing pages.
Project Structure
The server uses several HttpHandler classes for different routes:

PasswordStoreHandler: Handles the secure storage of user passwords.
PasswordRetrieveHandler: Facilitates secure retrieval of stored passwords.
PasswordManagementHandler: Manages addition, deletion, and updating of passwords.
PageHandler: Generic handler for serving static HTML pages.


Clone the repository:
git clone https://github.com/Hackerpoorna/password_manager.git
cd password_manager


Team Members
V. Poorna Chandra -  [@Hackerpoorna](https://github.com/Hackerpoorna) - Team Member
