
# Assignment 9: FastAPI Calculator with PostgreSQL and pgAdmin

This project demonstrates a containerized full-stack application using **FastAPI**, **PostgreSQL**, and **pgAdmin**. It includes a web-based calculator, a relational database backend, and a browser-accessible database management interface. The project also includes SQL operations for creating, querying, updating, and deleting records.

---

## 🚀 Project Structure

| Service       | Description                                      | Port        |
|---------------|--------------------------------------------------|-------------|
| `fastapi_calculator` | FastAPI web app with calculator frontend and API | `8000`       |
| `postgres_db`        | PostgreSQL database for storing calculations     | `5432`       |
| `pgadmin`            | Web-based GUI for managing PostgreSQL           | `5050`       |

---

## 🧰 Technologies Used

- Python 3.13
- FastAPI
- PostgreSQL 15
- pgAdmin 4
- Docker & Docker Compose
- Playwright + Pytest for E2E testing

---

## 🐳 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/assignment9.git
cd assignment9
```

### 2. Start the Containers
```bash
docker compose up --build
```

### 3. Access the Services
- FastAPI: [http://localhost:8000](http://localhost:8000)
- pgAdmin: [http://localhost:5050](http://localhost:5050)

> **pgAdmin Login:**
> - Email: `admin@admin.com`
> - Password: `admin`

> **PostgreSQL Connection:**
> - Host: `db`
> - Port: `5432`
> - Username: `postgres`
> - Password: `postgres`
> - Database: `fastapi_db`

---

## 🧪 Running Tests

### Unit, Integration, and E2E Tests
```bash
# Activate virtual environment
source venv/bin/activate

# Run all tests
pytest
```

> Includes full coverage of calculator logic and browser-based E2E tests using Playwright.

---

## 🗃️ SQL Operations

Executed via pgAdmin Query Tool:

- ✅ Create `users` and `calculations` tables
- ✅ Insert sample records
- ✅ Query all users and calculations
- ✅ Join users with their calculations
- ✅ Update a calculation result
- ✅ Delete a calculation record

Screenshots of each step are included in the project documentation.

---

## 📸 Documentation

See `Assignment9_Report.pdf` for:

- SQL query screenshots
- Captions and explanations
- Reflection on the assignment

