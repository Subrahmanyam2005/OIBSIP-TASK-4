This Java program implements a basic Quiz Application with user login, profile management, and a simple quiz. Below is a description of the main components:

1. Class User

This class represents a user with three properties:

username: The username of the user.

password: The user's password.

profileInfo: Stores the user's profile information.


It has methods to:

updateProfile: Allows the user to update their profile information.

updatePassword: Allows the user to change their password.



2. Class QuizApp

This is the main class, which contains the application logic. Key features include:

User management:

A HashMap (users) stores all registered users.

A static User object (loggedInUser) stores the current logged-in user.


Login process:

Users can login by entering their username and password, which is validated against the HashMap of users.


User Menu:

After logging in, users can:

1. Update Profile: Modify their profile information.


2. Change Password: Change their password.


3. Take Quiz: Answer multiple-choice questions.


4. Logout: Log out of the system.






3. Taking a Quiz

Users can attempt a quiz consisting of multiple-choice questions.

A timer is set for 20 seconds, and if the time expires before the user submits their answers, the program will automatically exit, simulating an automatic submission.

The quiz currently has three questions, which are hardcoded.


4. Sample Users

Two sample users (user1 and user2) with respective passwords (pass1 and pass2) are pre-loaded into the system for demonstration purposes.


5. Timer Mechanism

The Timer and TimerTask classes are used to limit the time available for answering the quiz (20 seconds). If time runs out, the program exits.


Program Flow:

1. The user is presented with a login or exit option.


2. Upon successful login, the user can manage their profile, change the password, take a quiz, or logout.


3. If the user chooses to take a quiz, they must submit their answers within the set time limit (20 seconds).


4. The user can log out at any point, and return to the main menu.



This is a basic application that could be expanded with more advanced features, such as persistent storage for user data and quiz results, more quiz questions, and enhanced user interaction.
