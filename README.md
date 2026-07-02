# Alumni Connect Portal

A web-based platform that connects students and alumni for mentorship, networking, and career opportunities. Built as an academic project at Sree Narayana Gurukulam College of Engineering.

---

## Features

- *Role-based access* for three user types — Admin, Alumni, and Student — each with its own permissions and views
- *Secure user authentication* — registration and login
- *Alumni–student networking* for mentorship and career guidance
- *Job and internship postings* shared by alumni and the institution
- *Event management* for college and alumni events

## Tech Stack

- *Backend:* Python, Flask
- *Database:* MySQL
- *Frontend:* HTML, CSS, JavaScript

## Getting Started

### Prerequisites
- Python 3.x
- MySQL

### Installation

1. Clone the repository:
   bash
   git clone https://github.com/AthiraR2002/Alumni-connect-portal.git
   cd Alumni-connect-portal
   

2. (Recommended) Create and activate a virtual environment:
   bash
   python -m venv venv
   venv\Scripts\activate       # Windows
   source venv/bin/activate    # macOS / Linux
   

3. Install the dependencies:
   bash
   pip install -r requirements.txt
   

4. Set up the database:
   - Create a MySQL database for the project
   - Update the database connection settings in the app's configuration
   - Import the schema if a .sql file is included

5. Run the application:
   bash
   python app.py
   

6. Open the app in your browser at http://localhost:5000.

## User Roles

- *Admin* — manages users, postings, and events
- *Alumni* — shares job/internship opportunities, mentors students, and joins events
- *Student* — connects with alumni, views postings, and registers for events

## Author

*Athira R*
[GitHub](https://github.com/AthiraR2002) · [LinkedIn](https://linkedin.com/in/athira-r-275534351)
