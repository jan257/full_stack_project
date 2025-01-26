# Full Stack Project

The Full Stack Project is a feature-rich web application designed to showcase the seamless integration of a modern frontend with a robust backend. Built using the MERN stack (MongoDB, Express, React, Node.js), this platform demonstrates a variety of functionalities, including user-friendly navigation, responsive design, and dynamic data handling. The live version of the application is hosted at [Full Stack Project Demo](https://full-stack-project-1-6olo.onrender.com/), offering users an interactive experience to explore its features in real time.

## Website Link 

## [Product_Store](https://full-stack-project-1-6olo.onrender.com)

## Features
- **Backend**: A Node.js server with Express for creating RESTful APIs.
- **Frontend**: A React application for a responsive user interface.
- **Database**: MongoDB for data storage.
- **Full CRUD Operations**: Create, Read, Update, and Delete functionality.
- **Environment Variables**: Configurable settings using `.env`.
- **Error Handling**: Middleware for centralized error handling.
- **Cross-Origin Resource Sharing (CORS)**: Ensures secure API communication.

---

## Project Structure
```
full_stack_project/
├── backend/
│   ├── server.js          # Main server file
│   ├── models/            # Mongoose models
│   ├── routes/            # Express routes
│   ├── controllers/       # Controller logic for routes
│   └── config/            # Configuration files
├── frontend/
│   ├── public/            # Static assets
│   ├── src/
│   │   ├── components/    # React components
│   │   ├── pages/         # React pages
│   │   ├── utils/         # Utility functions
│   │   └── App.js         # Main React component
├── assets/                # Images and screenshots
│   ├── demo1.png
│   ├── demo2.png
├── package.json           # Project metadata and dependencies
├── README.md              # Project documentation
└── .gitignore             # Files and directories to ignore
```

---

## Installation

### Prerequisites
- Node.js (>= 16.0.0)
- MongoDB (running locally or remotely)

### Backend Setup
1. Navigate to the `backend` directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   - Create a `.env` file in the `backend` directory.
   - Add the following variables:
     ```env
     MONGO_URI=your_mongodb_connection_string
     PORT=5000
     ```
4. Start the server:
   ```bash
   npm start
   ```

### Frontend Setup
1. Navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Build the frontend for production:
   ```bash
   npm run build
   ```
4. Run the development server:
   ```bash
   npm start
   ```

---

## Running the Project
1. Start the backend server.
2. Start the frontend development server or serve the production build.
3. Access the application in your browser at `http://localhost:3000` (or as configured).

---

## Demo
Here are some screenshots of the application:

### Homepage in Dark Mode
![Homepage](/assets/Home_Page-1.png)

### Homepage in Light Mode
![Homepage](/assets/Home_Page-3.png)

### Createpage
![Createpage](/assets/Create_Page-1.png)

### Features in Action
![Upadte](/assets/Update_Feature.png)

---

## Scripts

### Backend
- **`npm start`**: Starts the Node.js server in production mode.
- **`npm run dev`**: Starts the server in development mode with live reload using `nodemon`.

### Frontend
- **`npm start`**: Runs the React development server.
- **`npm run build`**: Builds the React app for production.

---

## Environment Variables
Ensure the following variables are set:
- `MONGO_URI`: MongoDB connection string.
- `PORT`: Port for the backend server.

---

## Contributing
1. Fork this repository.
2. Create a new branch for your feature/bugfix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

---

## Acknowledgments
Special thanks to the open-source community for providing libraries and tools used in this project.
