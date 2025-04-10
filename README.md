

# 🚀 FastAPI CRUD API

This is a simple FastAPI project demonstrating basic CRUD (Create, Read, Update, Delete) operations using **FastAPI**. It serves as a boilerplate or starter template for building RESTful APIs quickly and efficiently.

## 📦 Features

- ⚡ FastAPI for high-performance APIs
- 🧠 Pydantic for data validation
- 🗃️ In-memory data store (or mention your DB if you're using one)
- 📘 Auto-generated OpenAPI documentation
- 🔁 CRUD operations (Create, Read, Update, Delete)

## 🛠️ Tech Stack

- **Python 3.9+**
- **FastAPI**
- **Uvicorn** (for ASGI server)
- **Pydantic**

## 📂 Project Structure

```
.
├── main.py              # Entry point for FastAPI app
├── models.py            # Pydantic models
├── crud.py              # CRUD logic/functions
├── database.py          # (Optional) DB connection or mock data
├── requirements.txt     # Project dependencies
└── README.md
```

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/thedarkking01/FastAPI-Practice
cd fastapi-crud-api
```

### 2. Create virtual environment and install dependencies

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Run the FastAPI server

```bash
uvicorn main:app --reload
```

Visit `http://127.0.0.1:8000/docs` to view the interactive API docs 🚀

## 📬 API Endpoints

| Method | Endpoint       | Description           |
|--------|----------------|-----------------------|
| GET    | `/items/`      | Get all items         |
| GET    | `/items/{id}`  | Get a single item     |
| POST   | `/items/`      | Create a new item     |
| PUT    | `/items/{id}`  | Update an existing item |
| DELETE | `/items/{id}`  | Delete an item        |



---
