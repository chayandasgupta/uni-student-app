# Student Portal

A Django-based web application for university or college students to register, log in, and access key academic information such as dashboard, profile, course list, notices, and class routines.

## Features

- 🔐 Student Registration & Login
- 👤 Student Dashboard & Profile View
- 📢 Notice Board
- 🕒 Class Routine Viewer
- 📚 Course List Display
- 🔄 Session Management
- ✅ Simple File-Based Data Storage (users.json)

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/student-portal.git
cd student-portal
```

### 2. Create & Activate a Virtual Environment (Recommended)
```
python -m venv venv

# On Windows:
venv\Scripts\activate

# On macOS/Linux:
source venv/bin/activate
```

### 3. Install Dependencies
```
# If requirements.txt is present:
pip install -r requirements.txt

# If not, install Django manually:
pip install django
```

### 4. Run the Django Development Server
```
python manage.py runserver
```

### 5. Open in Browser
```
# Navigate to:
http://127.0.0.1:8000/
```

### File-Based Authentication
- No database setup is required.
- All user data (including login info and profiles) is stored in users.json.
- Django sessions track logged-in users.
- Data is loaded and passed to templates on each request.

### Screenshots
<p float="left">
  <img src="https://github.com/user-attachments/assets/6f3bd63b-5db9-4fa1-aa31-5b15945cf934" width="250" height="250" style="object-fit: cover; margin-right:10px;" />
  <img src="https://github.com/user-attachments/assets/93f34937-28fc-481c-ac25-4525b87f2a9e" width="250" height="250" style="object-fit: cover; margin-right:10px;" />
  <img src="https://github.com/user-attachments/assets/c66f9668-89d6-4ff0-a270-0f7749d29b7e" width="250" height="250" style="object-fit: cover; margin-right:10px;" />
  <img src="https://github.com/user-attachments/assets/e37345d0-8043-4f56-a6b5-edaf336b995e"  width="250" height="250" style="object-fit: cover; margin-right:10px;" />
  <img src="https://github.com/user-attachments/assets/5d4b79d3-9f4d-4a62-9a89-50d2ca04570e"  width="250" height="250" style="object-fit: cover; margin-right:10px;" />
  <img src="https://github.com/user-attachments/assets/00b6c106-4e71-4069-bae8-74b7da2215f6"  width="250" height="250" style="object-fit: cover; margin-right:10px;" />
  <img src="https://github.com/user-attachments/assets/1871c989-80ba-478d-91bc-006fbb3186fa"  width="250" height="250" style="object-fit: cover; margin-right:10px;" />
  <img src="https://github.com/user-attachments/assets/e44d9300-162e-4ece-aaf2-79c0b45fd477"  width="250" height="250" style="object-fit: cover; margin-right:10px;" />
</p>
