# Digital_Wallet_

# FastAPI Wallet Project

## Overview
This is a FastAPI project that manages users and their wallet balances. The project includes APIs to:

1. List users with wallet balances.
2. Create a new user.
3. Update a user's wallet balance.
4. Fetch all transactions of a user.

The APIs are documented and testable in Swagger UI.

---

## Requirements
- Python 3.10+
- FastAPI
- SQLAlchemy
- Pydantic
- Uvicorn

Install dependencies:

```bash
pip install -r requirements.txt


uvicorn app.main:app --reload


http://127.0.0.1:8000/docs

Here you can test all the APIs:

  GET /users → List all users

  POST /users → Create a new user

  PUT /users/{user_id}/wallet → Update wallet balance

  GET /users/{user_id}/transactions → Fetch transactions for a user



