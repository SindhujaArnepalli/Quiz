The Quiz Master application is an interactive Android-based quiz platform developed in Java, designed to enhance learning through engaging quizzes across diverse categories like Java, Probability, Current Affairs, and Psychometric Analysis. It features secure user authentication with sign-up/login functionalities, real-time score tracking, a leaderboard system displaying top scorers, and a personalized profile section. Users can view attempts, best scores, and profile images based on gender. The intuitive UI supports both dark and light modes, ensuring an accessible and aesthetic experience. The app utilizes SQLite for data persistence, ensuring offline access and reliable performance. Future enhancements may include score export, analytics, and quiz history features.
1.1 Purpose
The purpose of this project is to develop a mobile-based quiz application that allows users to register, take quizzes from multiple categories, and track their performance. It aims to enhance knowledge retention through an interactive and user-friendly interface while maintaining a persistent scoring system.
1.2 Scope
This application supports user authentication, profile creation with demographic details, real-time quiz taking with a countdown timer, and result evaluation. It features a leaderboard to foster competitive learning and includes dark mode support for a visually comfortable experience. All data is stored locally using SQLite, ensuring offline functionality.
1.3 Overview
The system is divided into three main modules: user authentication, quiz engine, and performance tracking. The user interface is intuitive, designed using XML layouts, and the backend logic is implemented in Java with SQLite support. The application is responsive and follows modern UI/UX practices.
. Software System Attributes
1 Reliability
The app uses try-catch blocks and validation to prevent crashes. It handles missing inputs and incorrect data gracefully.
2 Availability
The application is always available on the user's device since it does not depend on internet connectivity.
3 Security
User credentials are stored securely. SharedPreferences is used only for non-sensitive information (e.g., current session username).
4 Maintainability
The code is modularized by separating DBHelper, Activities, and Fragments. The use of standard Android architecture makes it maintainable and scalable.
Front-end Description
The front-end is designed using XML and Material Design components. It includes:
•	CoordinatorLayout for screen hierarchy
•	Buttons with color-coded themes
•	Recyclerview for the leaderboard
•	Spinner for gender selection
•	ImageView for profile avatars

 Back-end Description
The back-end is built entirely in Java. It uses:
•	SQLiteOpenHelper (DBHelper.java) for all CRUD operations
•	SharedPreferences for user session management
•	Custom classes and methods for handling quiz logic, score storage, and profile management
![image](https://github.com/user-attachments/assets/abfce529-ec23-4335-9e74-eb6d3d163590)
