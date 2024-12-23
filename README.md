# eBazaar
Where Machine Customers Revolutionize Shopping

# Development Environment Setup
1. Create Virtual Environment
    python -m venv venv
    source venv/bin/activate  # On macOS/Linux
    venv\Scripts\activate     # On Windows
2. Install Dependencies
    pip install -r requirements.txt
3. Run the Application
    uvicorn main:app --reload
4. freeze dependencies
    pip freeze > requirements.txt

# API Documentation
- Swagger UI: http://{host}:{port}/docs
- ReDoc: http://{host}:{port}/redoc