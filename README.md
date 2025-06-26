# School Management System

## Installation & Running Locally

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Yogndrr/MERN-School-Management-System.git
   ```

2. **Backend Setup:**
   - Open a terminal and run:
     ```sh
     cd backend
     npm install
     ```
   - Create a `.env` file in the `backend` folder with:
     ```
     MONGO_URL=mongodb://127.0.0.1/school
     ```
   - Start the backend:
     ```sh
     npm start
     ```

3. **Frontend Setup:**
   - Open another terminal and run:
     ```sh
     cd frontend
     npm install
     npm start
     ```

4. **Access the app:**
   - Frontend: [http://localhost:3000](http://localhost:3000)
   - Backend API: [http://localhost:5000](http://localhost:5000)