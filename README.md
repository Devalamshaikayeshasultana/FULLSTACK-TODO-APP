Project Setup Instructions

Prerequisites
Node.js and npm installed
MongoDB installed and running
Git installed
Visual Studio Code (VS Code) installed

Setup Instructions
1. Clone the Repository
First, clone the repository to your local machine.


Copy code
git clone <repository-url>
Replace <repository-url> with the URL of your GitHub repository.

2. Initialize Git Repository
If you haven't initialized a Git repository yet, you can do so with the following commands:


Copy code
git init
git add .
git commit -m "Initial commit"

3. Open the Project in VS Code
Open Visual Studio Code and open the folder where you cloned the repository.


Copy code
code <repository-folder>
Replace <repository-folder> with the path to your cloned repository.

4. Install Node Modules
Open a terminal in VS Code and run the following command to install all necessary node modules:


Copy code
npm install
Or

Copy code
npm i

5. Set Up Environment Variables
Make sure your MongoDB connection URL is specified in a .env file at the root of your project. For example:

Copy code
MONGO_URI= mongodb+srv://< ur mongodb credential >@to-do-app.b4q4nai.mongodb.net/?retryWrites=true&w=majority&appName=to-DO-APP

6. Start the Frontend
Open a new terminal in VS Code, navigate to the frontend folder, and start the frontend server:

Copy code
cd frontend
npm start
This will open a localhost browser window on your system.

7. Start the Backend
Open another new terminal in VS Code, navigate to the backend folder, and start the backend server:

Copy code
cd backend
nodemon server

8. Verify the Setup
Now, your backend should be running, and all data should be visible on the webpage opened by the frontend server.

Additional Notes
Make sure MongoDB is running before you start the backend server.
You can use npm run dev in place of nodemon server if you have a script set up for it in your package.json.
Adjust the MongoDB connection URL as per your setup.
Replace any placeholder values (e.g., <repository-url>, <repository-folder>, mongodb://localhost:27017/your-database)






