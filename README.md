Basic-CRUD---Update-Operation
Fetches existing user data (hardcoded ID) using a prepared statement and displays it in an editable HTML form.

🛠️ Setup Instructions
To run these experiments locally, you will need a server environment with PHP and MySQL (e.g., XAMPP, MAMP, or WAMP).

Clone the Repository:

git clone [YOUR_REPOSITORY_URL]
cd [repository-name]
Database Configuration:

Start your Apache and MySQL services.
Open your MySQL tool (phpMyAdmin, etc.).
Execute the SQL commands in the setup.sql file (located in Experiment 1) to create the web_experiment_db database and the initial users table.
CRITICAL: Update the database connection credentials ($servername, $username, $password, $dbname) in ALL PHP files to match your local environment.
Run Experiments:

Place all PHP and HTML files in your local web server's root directory (e.g., /htdocs or /www).
Access the files via your browser (e.g., http://localhost/index.php).
5. Basic CRUD - Update Operation (UPDATE)
File	Description
edit_profile.php	Fetches a user's current profile details and pre-populates the edit form.
process_update.php	Executes a secure UPDATE query using prepared statements to modify the user's name or email based on the form submission.
About
Fetches existing user data (hardcoded ID) using a prepared statement and displays it in an editable HTML form.

Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 0 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Languages
PHP
100.0%
Footer
