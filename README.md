# eBazaar
Where Machine Customers Revolutionize Shopping

# Development Environment Setup
1. Create Virtual Environment <br>
    python -m venv venv <br>
    source venv/bin/activate  # On macOS/Linux <br>
    venv\Scripts\activate     # On Windows <br>
2. Install Dependencies <br>
    pip install -r requirements.txt <br>
3. Run the Application <br>
    uvicorn main:app --reload <br>
4. freeze dependencies <br>
    pip freeze > requirements.txt <br>

# API Documentation
- Swagger UI: http://{host}:{port}/docs <br>
- ReDoc: http://{host}:{port}/redoc <br>