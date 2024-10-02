A simple file management API developed using Express, MongoDB, Redis, Bull, and Node.js.

Prerequisites
Applications:

Node.js
Yarn (package manager)
APIs:

Create a Google API with at least the email sending scope. Include a valid redirect URI, such as http://localhost:5000/.
Store the credentials.json file in the project’s root directory.
Environment Variables
Environment variables should be stored in a .env file, formatted as Name=Value. The table below outlines the variables required by the server:

Name	Required	Description
GOOGLE_MAIL_SENDER	Yes	Email address responsible for sending emails to users.
PORT	No (Default: 5000)	Server port to listen on.
DB_HOST	No (Default: localhost)	Database host address.
DB_PORT	No (Default: 27017)	Database port.
DB_DATABASE	No (Default: files_manager)	Name of the database.
FOLDER_PATH	No (Default: /tmp/files_manager (Linux, macOS) or %TEMP%/files_manager (Windows))	Directory to store files locally.
Installation
Clone the repository and navigate to the project directory.
Install dependencies using yarn install or npm install.
Usage
Ensure Redis and MongoDB services are running on your system.
Start the server by running yarn start-server or npm run start-server.
Testing
Create a .env.test file for test environment variables.
Run the end-to-end tests with yarn test or npm run test.
Author
Dennis Deng

