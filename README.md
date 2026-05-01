# RAAT BHAR LMS!!

A comprehensive Learning Management System (LMS) for educational institutions, built with Flask and PostgreSQL.

## Project Details

- **Project Name:** RAAT BHAR LMS!!
- **Subject:** Database Management Systems (DBMS)
- **Instructor:** Sir Israr Hanif
- **Semester:** 2nd Semester, BZU

## Team Members

1. Abdul Moiz - Roll No 2502
2. Sameer Ali - Roll No 2531
3. Khadija Ismail - Roll No 2503
4. Taha Qureshi - Roll No 2529
5. Eman Fatima - Roll No 2508
6. Rida Ali - Roll No 2519
7. Ahmad Raza - Roll No 2520
8. Sohaib Ajmal - Roll No 2525
9. Areesha Fatima - Roll No 2534
10. Uzair Iqbal - Roll No 2539
11. Hafsa Bint-e-Wajahat - Roll No 2544
12. Abeeha Munir - Roll No 2516
13. Abeeha Noor - Roll No 2536
14. Rai Muhammad Arslan - Roll No 2506
15. Umaima Sohail - Roll No 2540
16. Nimra Farooq - Roll No 2522

## Features

- Role-based access control (Admin, Teacher, Student)
- Course management and enrollment
- Attendance tracking
- Marks/Grade management
- Fee management
- Announcements system
- Dark/Light theme support

## Getting Started

### Prerequisites

- Python 3.11+
- PostgreSQL
- pip (Python package manager)

### Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd college-erp
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables:**
   Create a `.env` file in the root directory with the following:
   ```
   FLASK_ENV=development
   DATABASE_URL=postgresql://user:password@localhost/college_erp
   SECRET_KEY=your-secret-key-here
   ```

5. **Initialize the database:**
   ```bash
   python init_db.py
   python seed_db.py
   ```

6. **Run the application:**
   ```bash
   python app.py
   ```

   The application will be available at `http://localhost:5000`

### Running in Production (Railway)

The project is configured for deployment on Railway using Gunicorn:

1. Set up environment variables in Railway dashboard
2. Deploy using the Procfile and runtime.txt
3. Railway will automatically run: `gunicorn "app:create_app()"`

## Technology Stack

- **Backend:** Flask 3.0.0
- **Database:** PostgreSQL
- **ORM:** psycopg2
- **WSGI:** Gunicorn
- **Frontend:** HTML, CSS, JavaScript

## License

This project is created as a semester assignment for DBMS course at BZU.

