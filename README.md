# Darukaa.Earth AI

Evidence-backed biodiversity and environmental reasoning prototype.

## Run on Windows PowerShell

    python -m venv .venv
    .venv\Scripts\Activate.ps1
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    python -m backend.ingest
    python -m uvicorn backend.main:app --reload --port 8000

Open http://localhost:8000/docs

In a second terminal:
    .venv\Scripts\Activate.ps1
    streamlit run frontend/app.py

Open http://localhost:8501
