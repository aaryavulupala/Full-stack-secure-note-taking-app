# SecureNotes: Full-Stack Web Application with Django & React

A full-stack web application for managing notes, built with **Django** (backend) and **React** (frontend). Implements **JWT-based authentication** for secure user login and registration. The project includes deployment setup and follows best practices for scalable, production-ready code.

---

## 🚀 Features

- **User Authentication:** Secure login and registration using **JWT tokens**.  
- **Backend:** Django REST API for CRUD operations on notes and user management.  
- **Frontend:** React application with reusable components, protected routes, and Axios for API requests.  
- **Responsive UI:** Interactive pages for notes, forms, navigation, and a 404 page.  
- **Deployment:** End-to-end deployment setup for backend and frontend, fully functional in production.  
- **Scalable Codebase:** Modular and maintainable code structure for long-term development.

---

## 🛠️ Installation

1. Clone the repository:
```bash
cd backend
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

cd frontend
npm install
npm start

