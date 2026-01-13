# AuthFlow-DR 🔐

A professional full-stack authentication system built with **Django REST Framework** and **React**. This project serves as a robust boilerplate for implementing secure JWT-based user flows.

---

## 🏗️ Repository Structure
The project is split into a decoupled backend and frontend architecture:
*   `django-auth/`: RESTful API powered by Django.
*   `react-auth/`: Modern frontend interface built with React.

## 🚀 Key Features
- **JWT Authentication**: Secure stateless authentication using `djangorestframework-simplejwt`.
- **Decoupled Architecture**: Independent frontend and backend for maximum scalability.
- **Form Validation**: Comprehensive client and server-side validation.
- **Responsive UI**: Authentication screens optimized for all devices.

## 🛠️ Tech Stack
- **Backend**: Python 3.x, Django 4.2+, Django REST Framework (DRF).
- **Frontend**: React, Axios for API calls, CSS Modules/Tailwind.
- **Security**: JWT (Access/Refresh tokens), CORS handling.

## ⚙️ Getting Started

### Backend Setup (`django-auth/`)
1. Navigate to folder: `cd django-auth`
2. Create virtual environment: `python -m venv venv`
3. Activate venv: `source venv/bin/activate` (Mac/Linux) or `venv\Scripts\activate` (Win)
4. Install dependencies: `pip install -r requirements.txt`
5. Run migrations & start server:
   ```bash
   python manage.py migrate
   python manage.py runserver
