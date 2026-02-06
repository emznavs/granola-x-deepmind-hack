# granola-x-deepmind-hack (simple starter)

Quickstart:
1. cd backend
2. python -m venv venv
3. source venv/bin/activate    # on mac/linux
   .\\venv\\Scripts\\activate  # on Windows (PowerShell)
4. pip install -r requirements.txt
5. uvicorn app:app --reload --port 8000
6. curl -F "file=@../demo/sample_telemetry.csv" http://127.0.0.1:8000/analyze


