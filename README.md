# Login-Php
deconnexion.php:

Description: This PHP script manages the logout functionality for users. When triggered, it ensures the user's session is securely terminated by clearing session variables and redirecting the user to the login page. This script is crucial for maintaining user security and privacy by properly handling session closure.

login.php:

Description: This file contains the core PHP code for handling user authentication. It checks user credentials against a database and creates a session if the login is successful. The script also includes security measures to prevent common vulnerabilities such as SQL injection and ensures that passwords are handled securely.

session.php:

Description: This script initializes a user session to maintain state across multiple pages of the application. It includes essential configurations for session handling, such as session start, duration, and security settings to protect against session hijacking and fixation attacks.
