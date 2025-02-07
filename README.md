Milestone 6 - User Authentication & Encryption
In this milestone, I implemented user authentication with password encryption and saved complete user data in the database.


Features Implemented
1.  Encrypt the Password
Used bcrypt to hash the user's password during the signup process.
Ensured that the hashed password is saved in the database instead of storing the plain text password.
2.  Store Complete User Data
Saved all the user's data (e.g., name, email, etc.) into the database.
Ensured that the password is stored securely and not in plain text.
How It Works
During the signup process, the user's password is hashed using bcrypt.
The hashed password is then stored in the database along with other user details like name and email.
When the user logs in, the password provided is compared with the hashed password in the database for authentication.
This ensures that sensitive user data, especially the password, is stored securely.