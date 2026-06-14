# AirlineSupportSystem

# Run fast API
uvicorn main:app --host 0.0.0.0 --port 8000

# Streamlit frontend
streamlit run ui/streamlit_app.py --server.port 8501 --server.enableCORS false

