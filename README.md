# UserManagementSystemApp
- A simple full stack web application built with Node.js, Express, MongoDB, and vanilla HTML/CSS/JS. This app allows users to register, login, view, update, and delete their profiles. It also includes JWT-based authentication.
Features

# Features

- User registration with hashed passwords.
- User login with JWT authentication.
- View all registered users in a dashboard.
- Update user information.
- Delete users from the system.
- Protected routes using JWT.
- Responsive and simple frontend interface.

# Technologies Used
1. Node.js & Express – Backend server and API routing.
2. MongoDB & Mongoose – Database and data modeling.
3. HTML – Frontend structure.
4. CSS – Frontend styling.
5. JavaScript – Frontend logic and API communication.
6. JWT – Authentication and route protection.
7. bcryptjs – Password hashing.
8. dotenv – Environment variable management.

# Usage
- Clone the repository and navigate to the project folder.
- In the backend folder, run npm install to install dependencies.
- Create a .env file with the following variables:

PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/user_management
JWT_SECRET=your_secret_key

- Start the backend server with npm start.
- Open frontend/index.html in a web browser.
- Register a new user, login, and manage users from the dashboard.

# Folder Structure

fullstack-user-management/
│
├── backend/
│ ├── models/
│ │ └── User.js # MongoDB User model
│ ├── routes/
│ │ └── userRoutes.js # API endpoints
│ ├── server.js # Backend server setup
│ └── package.json # Backend dependencies
│
└── frontend/
├── index.html # Main frontend page
├── style.css # Frontend styling
├── script.js # Frontend logic for API communication
└── README.md # Project documentation

# Future Enhancements
- Add search functionality to filter users by name or email.
- Add user profile pictures and avatars.
- Implement role-based access control (Admin, User).
- Improve frontend UI with frameworks like Bootstrap or Tailwind.
- Deploy the app online using platforms like Heroku, Render, or Vercel.

# Author
- Sakhile Langa
