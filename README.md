# FastAPI Mini Project - Have created this project to learn FastAPI.

[![Python](https://img.shields.io/badge/python-3.10%2B-blue?logo=python)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-%2300FFFF?logo=fastapi&logoColor=black)](https://fastapi.tiangolo.com/)


## 🚀 Project Overview

This repository contains a **FastAPI-based REST API** Project. The goal of this project is to demonstrate practical backend development using FastAPI, including database integration, authentication, file uploads, 
and API operations that you'd expect in a production-ready service.

---

## 
This project covers the following key concepts:

- FastAPI basics: routes, request/response, status codes  
- Pydantic models for data validation  
- Database connection (ORM)  
- CRUD operations (Create, Read, Update, Delete)  
- File upload/image handling  
- Authentication with JWT tokens  
- Securing routes and role-based access  
- Connecting to a Front_End

---

## 📌 Features

| Feature | Status |
|--------|--------|
| GET / Retrieve resources | ✅ |
| POST / Create a resource | ✅ |
| PUT / Update a resource | ✅ |
| DELETE / Delete a resource | ✅ |
| JWT Authentication | ✅ |
| User Login & Signup | ✅ |
| Database Integration | ✅ |
| File Upload (Images, Videos) | ✅ |
| Swagger / OpenAPI Docs | 🔁 |

---

## 🛠 Tech Stack

- **FastAPI** – Python-based high-performance API framework
- **Uvicorn** – ASGI server to run FastAPI apps  
- **SQLAlchemy / ORM** – Database ORM  
- **Pydantic** – Data validation and serialization  
- **JWT Tokens** – Authentication  
- **ImageKit (optional)** – Media upload service (if used) 

---

## 📁 Project Structure

📦 fastapi-project
├── app/
│ ├── main.py # FastAPI app entrypoint
│ ├── models.py # Database models
│ ├── schemas.py # Pydantic data models
│ ├── crud.py # CRUD operations
│ ├── auth.py # Auth utilities + JWT logic
│ ├── routers/
│ │ ├── users.py # User-related endpoints
│ │ └── posts.py # Post-related endpoints
│ └── utils/ # Helpers (file upload, logging, config)
├── requirements.txt # Python dependencies
├── Dockerfile (optional) # Docker build instructions
├── README.md # This file
└── .env # Environment variables
