Simple File Management API using Express, MongoDB, Redis, Bull, and Node.js
Requirements
Applications:
Node.js
Yarn (package manager/resource handler)
APIs:
Set up a Google API with at least the email sending scope. Ensure that a valid redirect URI (e.g., http://localhost:5000/) is listed, and store the credentials.json file in the project's root directory.
Environment Variables:
Define the required environment variables in a .env file, formatted as NAME=VALUE. Below is a table of the environment variables used by the server:
Name	Required	Description
GOOGLE_MAIL_SENDER	Yes	Email address for sending emails to users.
PORT	No	Server port (Default: 5000).
DB_HOST	No	Database host (Default: localhost).
DB_PORT	No	Database port (Default: 27017).
DB_DATABASE	No	Database name (Default: files_manager).
FOLDER_PATH	No	Path to the folder where files are saved. Default: /tmp/files_manager for Linux/Mac OS X, or %TEMP%/files_manager for Windows.
Installation
Clone the repository and navigate to its directory.
Install dependencies using yarn install or npm install.
Usage
Ensure Redis and MongoDB are running on your system.
Start the server using yarn start-server or npm run start-server.
Testing
Create a separate .env.test file for testing purposes with the appropriate environment variable values.
Run tests using yarn test or npm run test to perform end-to-end (E2E) tests.
Authors
Dennis Deng
