# 🍽️ MERN-STACK-CAFE-BREW

Welcome to the **MERN-STACK-CAFE-BREW**! This full-stack application allows customers to browse cafe, make reservations, and manage their bookings, while providing cafe admins with a comprehensive dashboard to oversee operations.

## 🛠️ Features

* **Customer Interface**: Browse cafe, view details, and make reservations.
* **Admin Dashboard**: Manage cafe information and monitor reservations.
* **Real-Time Updates**: Instant updates for reservation status changes.
* **Responsive Design**: Optimized for both desktop and mobile devices.

## 🧱 Technologies Used

* **Frontend**: React.js, Axios, React Router
* **Backend**: Node.js, Express.js
* **Database**: MongoDB
* **Authentication**: JWT (JSON Web Tokens)
* **Styling**: CSS, Bootstrap

## 📂 Project Structure

```
MERN-STACK-CAFE-BREW/
├── backend/                   # Backend server code
│   ├── config/                # Configuration files
│   ├── controllers/           # API controllers
│   ├── models/                # Mongoose models
│   ├── routes/                # Express routes
│   ├── middleware/            # Middleware functions
│   ├── utils/                 # Utility functions
│   ├── app.js                 # Express app entry point
│   └── .env                   # Environment variables
│
├── frontend/                  # React.js frontend code
│   ├── public/                # Public assets
│   ├── src/                   # React source code
│   │   ├── components/        # React components
│   │   ├── pages/             # React pages
│   │   ├── context/           # React context
│   │   ├── hooks/             # Custom React hooks
│   │   ├── services/          # API service calls
│   │   ├── utils/             # Utility functions
│   │   ├── App.js             # Main React app component
│   │   └── index.js           # React DOM render entry
│   └── package.json           # Frontend dependencies
│
├── .gitignore                 # Git ignore rules
├── README.md                  # Project documentation
└── LICENSE                    # License information
```

## 🚀 Installation

To run this project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/sohebmujawar/MERN-STACK-CAFE-BREW.git
   ```

2. Navigate to the project directory:

   ```bash
   cd MERN-STACK-CAFE-BREW
   ```

3. Set up the backend:

   * Navigate to the `backend` folder:

     ```bash
     cd backend
     ```

   * Create a `.env` file and add the following variables:

     ```
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     FRONTEND_URL=http://localhost:3000
     ```

   * Install dependencies:

     ```bash
     npm install
     ```

   * Start the backend server:

     ```bash
     npm start
     ```

4. Set up the frontend:

   * Open a new terminal window and navigate to the `frontend` folder:

     ```bash
     cd frontend
     ```

   * Install dependencies:

     ```bash
     npm install
     ```

   * Start the frontend development server:

     ```bash
     npm start
     ```

5. Open your browser and go to `http://localhost:3000` to view the application.

👥 Team Members
Nikita Mane

Vaishali Jadhav

Anushri Patil

Soheb Mujawar 

## 📄 License

This project is licensed under the MIT License.

---

