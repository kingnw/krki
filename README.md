NIT3213 Android Project

Login Credentials:

Username: safal
Password: s4680098


Overview
Welcome to the NIT3213 Android project! This app is designed for an assignment where users can log in and interact with an API to view a list of entities. Once logged in, you’ll see a dashboard filled with items, each showing a profile image and basic details. Clicking on any item lets you dive deeper into its information.

Key Features
Login Functionality:

Simply enter your username and password to log in. The app checks these credentials with an API and retrieves a special key (keypass) for accessing other features.
Dashboard:

After logging in, you’ll land on the dashboard, which displays a list of entities fetched from the API. Each entry includes a profile image and some info about the entity.
Entity Details:

Wanna to know more about an entity? Just click on it, and you’ll be taken to a details page showing all the relevant information, like its name, culture, and domain.


Profile Images:

To make things visually appealing details is accompanied by relevent  picture.

Unit Testing:

i have  included some basic unit tests to check the login process and ensure the app interacts with the API correctly.

API Endpoints
The app communicates with these API endpoints:

Login:

Use POST /footscray/auth to send your username and password, which will return a keypass.
Dashboard:

After logging in, the app fetches the list of entities using GET /dashboard/{keypass}, where {keypass} is the key you received during login.

Getting Started
What You Need
Android Studio: Make sure you have this installed on your machine.
API Access: Ensure you can access the API at https://nit3213-api-h2b3-latest.onrender.com.

Installation Steps
Clone the Repository:

Go to the repository:(https://github.com/kingnw/krki.git) and clone it to your local machine.
Download as ZIP:

If you prefer, click the green "Code" button on the GitHub page and select "Download ZIP."
Extract the Zip File:

Find the downloaded file (praveshproject-master.zip) and unzip it.
Open the Project:

Launch Android Studio, select "Open an existing Android Studio project," and choose the NIT3213-masterbranch.

If Android Studio prompts you to sync Gradle, just click "Sync Now."
Run the App:

Finally, you can run the app on either an emulator or a physical device connected to your computer.

Using the App
Login: Enter your username and password on the login screen. If successful, you'll be taken to the Dashboard.
Dashboard: Here, you’ll see a list of entities, each with a profile image and details.
Entity Details: Click on any entity to see its detailed information.

Unit Testing
To check the app's functionality:

Go to the app/src/test/java/com/example/nit3213project/ directory.
Right-click on the test files (like LoginActivityTest.kt or DashboardActivityTest.kt) and select Run to execute the tests.
