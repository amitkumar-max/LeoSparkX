server/
 ├── models/
 │    ├── User.js
 │    ├── Goal.js
 │    ├── Task.js
 │    └── Note.js
 ├── config/
 │    └── db.js
 ├── routes/
 ├── seed/
 │    └── seed.js
 ├── server.js
 └── .env

 
---

## 🚀 Features

- 🔑 User authentication (JWT)  
- ✅ Task management (CRUD: create, update, delete, list)  
- ⏱ Timer management (start, pause, stop sessions)  
- 📊 Productivity reports (task stats, focus time)  
- 🛡 Middleware for logging, errors, and auth  
- 🧪 Unit & integration tests (Jest + Supertest)  

---

## ⚙️ Tech Stack

- **Backend:** Node.js, Express  
- **Database:** MongoDB + Mongoose  
- **Auth:** JWT (JSON Web Tokens)  
- **Testing:** Jest, Supertest  

---

## 🔧 Setup Instructions

### 1. Clone repo

git clone https://github.com/your-username/time-management-app.git
cd time-management-app

2. Install dependencies
npm install

3. Configure environment

Create a .env file in the root folder:

PORT=5000
MONGO_URI=mongodb://localhost:27017/time_management
MONGO_URI_TEST=mongodb://localhost:27017/time_management_test
JWT_SECRET=your_jwt_secret
JWT_EXPIRE=7d
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_email_password

4. Run the server
npm start


For development with auto-restart:

npm run dev

5. Run tests
npm test

📡 API Endpoints
Auth

POST /api/auth/signup → Register user

POST /api/auth/login → Login user

Tasks

POST /api/tasks → Create task

GET /api/tasks → Get all tasks

PUT /api/tasks/:id → Update task

DELETE /api/tasks/:id → Delete task

Timers

POST /api/timers/start → Start timer

PUT /api/timers/:id/pause → Pause timer

PUT /api/timers/:id/stop → Stop timer

GET /api/timers → Get user timers

Reports

GET /api/reports/overview → Get combined report (tasks + timers)

👨‍💻 Contributors

Shivam & Team 🚀

📜 License

MIT License


---

✅ Notes:  
- Gives **project structure**, **setup steps**, **API endpoints**, and **team credit**.  
- Perfect for GitHub repo and hackathon submissions.  

Do you want me to also prepare a **`.env.example` file** so your friends don’t mess up configs?
