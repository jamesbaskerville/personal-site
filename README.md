# Personal Website

A full-stack personal website built with FastAPI and React.

## Project Structure

```
.
├── backend/
│   ├── app/
│   │   ├── main.py
│   │   └── routers/
│   ├── tests/
│   └── requirements.txt
└── frontend/
    ├── public/
    ├── src/
    │   ├── components/
    │   ├── pages/
    │   └── assets/
    └── package.json
```

## Setup Instructions

### Backend Setup
1. Create a virtual environment:
   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate  # On Windows: .\venv\Scripts\activate
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the FastAPI server:
   ```bash
   uvicorn app.main:app --reload
   ```

### Frontend Setup
1. Install dependencies:
   ```bash
   cd frontend
   npm install
   ```

2. Start the development server:
   ```bash
   npm start
   ```

## Development

- Backend API runs on: http://localhost:8000
- Frontend development server runs on: http://localhost:3000
- API documentation available at: http://localhost:8000/docs