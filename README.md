# Campus Complaint Portal

![License](https://img.shields.io/badge/license-MIT-green.svg)  
![Technologies](https://img.shields.io/badge/Tech-React%2C%20Vite%2C%20TailwindCSS%2C%20Node.js%2C%20Express.js%2C%20MongoDB%2C%20JWT-blue)

---

#  Overview
Campus Complaint Portal is a web-based application that streamlines the process of submitting and managing campus-related complaints.  

Students can register/login, submit complaints with images, and track their progress, while administrators can review, update, and resolve complaints efficiently.  

This project promotes transparency, accountability, and prompt resolution of campus issues.

---

# Key Features
- User Authentication: Secure registration and login using JWT  
- Complaint Submission: Upload complaints with images  
- Dashboard Tracking: Real-time tracking of complaint status  
- Admin Panel: Admins can review, update, and resolve complaints  
- RESTful APIs: Backend powered by Node.js and Express.js  
- Responsive UI: Modern interface built with React, Vite, and TailwindCSS  
- Secure Data Storage: MongoDB database for persistent and secure data  

---

# Tech Stack
| Layer | Technology |
|-------|------------|
| Frontend | React, Vite, TailwindCSS |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Security | JWT Authentication |

---

# System Architecture
The application follows a client-server architecture**:  
1. Frontend: React + Vite handles UI/UX and communicates with the backend via REST APIs.  
2. Backend: Node.js + Express.js manages API endpoints, user authentication, and business logic.  
3. Database: MongoDB stores users, complaints, and status information.  
4. Authentication: JWT tokens ensure secure access to protected routes.  


# Installation & Setup
1. Clone the repository:  
```bash
for run backend:cd backend , and ,npm start
for run frotend:cd frontend, and npm run dev
git clone https://github.com/amit-3245/campus-complaint-portal.git
