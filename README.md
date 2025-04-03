Taskify is a client-server single-page web application written in HTML, CSS, and JavaScript. 
The clients get an easy-to-use application through which they can create accounts, log in, manage daily tasks via a calendar-based interface, and keep track of completed activities through a history. 
Turning all operations in the browser makes it extremely simple, with localStorage being used to persist all data. 

Features
User Registration and Authentication

   Account Creation: Users can create an account by providing personal data: name, email, phone number, role, and password.

   Login Functionality: The registered user can log in with email or username along with the password.

  Session Maintenance: The user keeps the state of being logged in via local storage.

Profile Management

   Profile Section Editable: When a user logs in, they can fill in or update profile fields regarding preferred name, date of birth, country, county, city, and postcode. 

   Data Persistence: It persists profile data in its browser's local storage.

Calendar-Based Task Management

   Monthly Calendar View: Can allow the user to pick individual dates.

   Daily Tasks: A maximum of 3 tasks can be added to each day.

   Mark Task Completion: Each task has a checkbox field for marking completion.

   Auto Save: The modification on tasks gets saved automatically in local storage.

Task History

   Automatic Record Keeping: All completed tasks are placed in history.

   Date Stamped Entries: Each task appears along with the date of completion.

User Interface and Navigation

   Single Page Layout: Uses tabs and conditional rendering to enable seamless navigation without page reloads.

   Content Sections: Tab types include Home, Tasks, History, How To Use, and Origin.

   Log Out: The user may terminate the session and return to the login page.
