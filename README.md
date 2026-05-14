# 🏥 Patient Management System API

A simple REST API built with FastAPI as a backend learning project.

This project performs basic CRUD operations for managing patient records and also calculates BMI with automatic health status generation.

---

## 🚀 Features

- Create patient records
- View all patients
- View a patient by ID
- Update patient details
- Delete patient records
- Sort patients by height, weight, or BMI
- Automatic BMI calculation
- Input validation using Pydantic

---

## 🛠️ Tech Stack

- Python
- FastAPI
- Pydantic
- Uvicorn
- JSON
- REST API

---

## ▶️ Run Locally

Install dependencies:

```bash
pip install fastapi uvicorn
```

Start the server:

```bash
uvicorn main:app --reload
```

---

## 📌 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/view` | Get all patients |
| GET | `/patient/{id}` | Get patient by ID |
| POST | `/create` | Create patient |
| PUT | `/edit/{id}` | Update patient |
| DELETE | `/delete/{id}` | Delete patient |
| GET | `/sort` | Sort patients |

---

## 📚 What I Learned

- Building APIs using FastAPI
- CRUD operations
- Request validation with Pydantic
- Path & query parameters
- Exception handling
- Working with JSON data

---

## 📖 API Docs

FastAPI automatically provides interactive API documentation:

- Swagger UI → `http://127.0.0.1:8000/docs`
- ReDoc → `http://127.0.0.1:8000/redoc`

---

This project was built for learning purposes while exploring FastAPI 🚀