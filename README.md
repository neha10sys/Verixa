# 🚀 Verixa

> **Proof of Skills, Not Just Claims.**

Verixa is an AI-powered Developer Verification Platform that helps developers showcase verified skills, real projects, GitHub contributions, and assessment results while enabling recruiters to hire based on proof rather than claims.

---

## 🌟 Overview

Traditional resumes often fail to represent a developer's actual skills.

**Verixa** solves this problem by combining:

- ✅ GitHub Repository Verification
- ✅ AI Portfolio Review
- ✅ Skill Assessments
- ✅ Trust Score System
- ✅ Verified Badges
- ✅ Recruiter Dashboard
- ✅ Developer Dashboard

The platform provides a transparent and trustworthy hiring experience.

---

# ✨ Features

## 👨‍💻 Developer Features

- Secure Authentication (JWT)
- Personal Dashboard
- Profile Management
- Project Showcase
- GitHub Integration
- GitHub Repository Verification
- Skill Assessments
- AI Portfolio Review
- Trust Score
- Verified Skill Badges
- Certificates
- Notifications

---

## 🏢 Recruiter Features

- Recruiter Dashboard
- Search Developers
- Filter by Skills
- Compare Developers
- View Trust Scores
- View Assessment Results
- Shortlist Candidates
- Candidate Reports

---

## 🤖 AI Features

- AI Portfolio Review
- Skill Analysis
- Resume Insights
- Project Evaluation
- Career Recommendations

---

## 📊 Trust Score

Verixa calculates a developer's Trust Score using:

- GitHub Activity
- Assessment Performance
- Verified Projects
- Open Source Contributions
- Profile Completeness

---

# 🛠 Tech Stack

## Frontend

- React.js
- Vite
- Tailwind CSS
- React Router
- Framer Motion
- React Icons

---

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Bcrypt
- Multer
- Cloudinary

---

## Database

- MongoDB

---

## Tools

- Git
- GitHub
- Postman
- VS Code

---

# 📁 Project Structure

```
Verixa
│
├── backend
│   ├── src
│   │   ├── config
│   │   ├── controllers
│   │   ├── middleware
│   │   ├── models
│   │   ├── routes
│   │   ├── services
│   │   ├── utils
│   │   ├── validators
│   │   ├── app.js
│   │   └── server.js
│   │
│   ├── package.json
│   └── .env
│
├── frontend
│   ├── src
│   │   ├── assets
│   │   ├── components
│   │   ├── pages
│   │   ├── layouts
│   │   ├── hooks
│   │   ├── context
│   │   ├── services
│   │   ├── data
│   │   └── App.jsx
│   │
│   └── package.json
│
└── README.md
```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/your-username/verixa.git

cd verixa
```

---

## Backend Setup

```bash
cd backend

npm install
```

Create `.env`

```env
PORT=5050

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret

JWT_EXPIRES_IN=7d

CLIENT_URL=http://localhost:5173
```

Run Backend

```bash
npm start
```

---

## Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

---

# 📡 API Endpoints

## Authentication

```
POST   /api/auth/register

POST   /api/auth/login

POST   /api/auth/logout

GET    /api/auth/me
```

---

## Developer

```
GET    /api/developers

GET    /api/developers/:id

PUT    /api/developers/profile

POST   /api/projects
```

---

## Assessments

```
GET    /api/assessments

POST   /api/assessments/start

POST   /api/assessments/submit
```

---

## Verification

```
POST   /api/github/connect

POST   /api/github/verify

GET    /api/trust-score
```

---

# 📸 Screenshots

### Landing Page

(Add Screenshot Here)

---

### Developer Dashboard

(Add Screenshot Here)

---

### Recruiter Dashboard

(Add Screenshot Here)

---

### Profile

(Add Screenshot Here)

---

### Trust Score

(Add Screenshot Here)

---

# 🔒 Authentication

- JWT Authentication
- Password Hashing
- Protected Routes
- Role-Based Authorization

---

# 🎯 Roadmap

- [x] Frontend UI
- [x] Authentication
- [x] MongoDB Integration
- [ ] GitHub OAuth
- [ ] AI Portfolio Review
- [ ] Trust Score Engine
- [ ] Certificate Generator
- [ ] Email Verification
- [ ] Recruiter Analytics
- [ ] Deployment

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository

2. Create your feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit changes

```bash
git commit -m "Add new feature"
```

4. Push branch

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

# 👨‍💻 Author

**Neha Singh**

AI & ML Undergraduate

MERN Stack Developer

GitHub: https://github.com/neha10sys

LinkedIn: https://www.linkedin.com/in/neha-singh-66455a343/

---

# ⭐ Support

If you found this project useful, don't forget to ⭐ the repository.

---

## 💡 Vision

> **Verixa aims to transform technical hiring by replacing resume-based evaluations with proof-based developer verification.**

**Proof of Skills, Not Just Claims.**
