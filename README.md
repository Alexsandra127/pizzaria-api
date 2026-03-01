# API Pizzaria
API backend com FastAPI para gerenciar pizzas, pedidos e estoque.

- Conceitos:
    - REST
    - Endpoints
    - Request / Response
    - Status Codes
- **Banco de Dados**
    - SQL (iniciante)
        - SELECT
        - INSERT
        - UPDATE
        - JOIN (básico)
    - NoSQL (conceitual)
        - DynamoDB (teórico por enquanto)
- **Concorrência e Async**
    - Threads
    - Locks
    - Semáforos
    - Async / Await
    - Queues

**🍕 Pizzaria API**

Backend API for a pizza shop application built with **FastAPI**, focusing on clean architecture, good practices, and REST principles.

This project was created for **study and portfolio purposes**.

---

**🚀 Technologies**

- Python 3
- FastAPI
- SQLAlchemy
- SQLite
- Alembic
- Pydantic
- Uvicorn
- Passlib (bcrypt)

---

**📂 Project Structure**

```
pizzaria-api/
├── app/
│   ├── main.py
│   ├── core/
│   │   └── security.py
│   ├── database/
│   │   └── dependencies.py
│   ├── models/
│   │   └── models.py
│   └── routes/
│       ├── auth_routes.py
│       └── order_routes.py
├── banco.db
├── alembic.ini
├── README.md
├── requirements.txt
└── .env
```

⚙️ How to Run the Project

1. Clone the repository git clone https://github.com/Alexsandra127/pizzaria-api.git cd pizzaria-api
2. Create and activate virtual environment (Windows) python -m venv venv venv\Scripts\activate
3. Install dependencies pip install -r requirements.txt
4. Run the application uvicorn app.main:app --reload

📄 API Documentation

After running the project, access:

Swagger UI: http://127.0.0.1:8000/docs

OpenAPI JSON: http://127.0.0.1:8000/openapi.json

🔐 Features (in progress)

User authentication

Password hashing with bcrypt

User registration

Order creation

Order listing

Database persistence with SQLAlchemy

🧠 Notes

Passwords are securely hashed using bcrypt

The project follows a modular structure with routers and dependencies

Designed for learning and backend portfolio demonstration