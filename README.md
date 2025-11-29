# PYSCHEDULIZE – Automated Timetable Generator

## Features
- Add Faculty
- Add Courses
- Assign Faculty to Courses
- Auto-generate Timetable
- Clash-free Scheduling
- MongoDB Storage
- Flask Backend
- Simple HTML/CSS UI

## Project Structure
PYSCHEDULIZE/
│
├── app.py
├── db.py
├── scheduler.py
│
├── templates/
│ ├── index.html
│ ├── add_faculty.html
│ ├── add_course.html
│ ├── assign_faculty.html
│ ├── generate.html
│ └── timetable.html
│
├── static/
│ ├── styles.css
│ └── script.js
│
├── requirements.txt
└── README.md

git clone https://github.com/your-username/PYSCHEDULIZE.git
cd PYSCHEDULIZE
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

sudo systemctl start mongod



python app.py

http://127.0.0.1:5000


