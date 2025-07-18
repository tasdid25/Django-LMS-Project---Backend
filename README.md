# 📚 Learning Management System (LMS) Backend

A robust backend for a **Learning Management System (LMS)** built with **Python**, **Django**, and **Django REST Framework**, secured with **JWT Authentication**. This backend provides APIs to manage courses, lessons, materials, enrollments, and user assessments.

---

## 🚀 Features

- ✅ User registration and authentication (JWT)
- ✅ Role-based permissions (students, instructors/admins)
- ✅ CRUD operations for categories, courses, lessons, and study materials
- ✅ Enrollment management
- ✅ Question & Answer module for assessments
- ✅ Interactive API documentation (Swagger - drf_yasg)
- ✅ Clean, modular, and scalable project structure

---

## 🗂️ Tech Stack

- **Language:** Python 3.x  
- **Framework:** Django, Django REST Framework (DRF)  
- **Authentication:** JWT (SimpleJWT or custom implementation)  
- **Documentation:** drf_yasg (Swagger UI)  
- **Database:** SQLite (default) / PostgreSQL (recommended for production)  
- **Others:** Git, virtualenv

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

bash
git clone https://github.com/your-username/lms_backend.git
cd lms_backend

### 📌 Project Structure
lms_backend/
├── manage.py
├── lms_backend/ # Project settings
├── core/ # LMS app (models, views, serializers, urls)
├── users/ # LMS app (models, views, serializers, urls)
├── requirements.txt
├── ...

