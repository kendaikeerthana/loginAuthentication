# loginAuthentication
Login System with Session Management and Password Update

User Authentication:

    Users can log in using their registered credentials (username and password).
    The authentication process validates user input against stored credentials to ensure secure access.

Session Management:

    Upon successful login, a session is created to maintain the user's authenticated state.
    The session is configured with an expiration timer to enhance security. If the user is inactive for a specified period, the session automatically expires, and the user is logged out.
    This ensures sensitive information is not accessible after a prolonged period of inactivity.

Password Update Feature:

    Authenticated users can securely change their password through the "Change Password" functionality.
    To update the password:
        The user must provide their current password for verification.
        The system enforces validation rules to ensure the new password meets security criteria (e.g., minimum length, complexity).
    Once the password is updated, the user is prompted to log in again with the new credentials, invalidating any old sessions for security.

Security Measures:

    Passwords are stored securely using hashing techniques to prevent exposure of sensitive data.
    Sessions are uniquely tied to each user, ensuring that no unauthorized access is possible.
    
