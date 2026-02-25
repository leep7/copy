# NCBW Training Portal
## Leadership Development Program — Queen City Metro Chapter

A full-stack training management system built with React + Flask + PostgreSQL.

---

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- Python 3.10+
- PostgreSQL 14+

---

## 1. Database Setup (PostgreSQL)

```bash
# Login to PostgreSQL
psql -U postgres

# Create database and user
CREATE DATABASE ncbw_training;
CREATE USER ncbw_user WITH PASSWORD 'ncbw_password123';
GRANT ALL PRIVILEGES ON DATABASE ncbw_training TO ncbw_user;
\q

# Run the schema
psql -U ncbw_user -d ncbw_training -f backend/schema.sql
```

---

## 2. Backend Setup (Flask)

```bash
cd backend

# Create virtual environment
python -m venv venv

# Activate it
# Windows:
venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Create .env file
cp .env.example .env
# Edit .env with your database credentials

# Run the server
python app.py
# Backend runs at http://localhost:5000
```

---

## 3. Frontend Setup (React)

```bash
cd frontend

# Install dependencies
npm install

# Run the dev server
npm run dev
# Frontend runs at http://localhost:5173
```

---

## 📁 Project Structure

```
ncbw-training-portal/
├── frontend/
│   ├── src/
│   │   ├── pages/          # All page components
│   │   │   ├── admin/      # Admin dashboard pages
│   │   ├── components/     # Reusable UI components
│   │   ├── context/        # Auth context & state
│   │   ├── api/            # API call functions
│   │   └── assets/         # Global styles
│   └── package.json
│
├── backend/
│   ├── routes/             # API route handlers
│   ├── models/             # SQLAlchemy models
│   ├── app.py              # Flask entry point
│   ├── config.py           # Configuration
│   ├── schema.sql          # Database schema
│   └── requirements.txt
│
└── README.md
```

---

## 👤 Default Admin Account
After running schema.sql, a default admin is created:
- **Username:** admin
- **Password:** Admin@1234

> ⚠️ Change this password immediately after first login!

---

## 🎨 Design
- Primary color: `#B8860B` (dark gold)
- Background: `#0D0D0D` (dark)
- White card surfaces for content areas
