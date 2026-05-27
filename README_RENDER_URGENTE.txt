CORRECCION RENDER

El error de Render era:
ERROR: Could not open requirements file: requirements.txt

Este ZIP ya incluye en la raiz:
- app.py
- requirements.txt
- Procfile
- runtime.txt
- .python-version
- render.yaml

IMPORTANTE:
Sube TODOS estos archivos a GitHub en la raiz del repositorio, no solo app.py.
En Render configura:
Build Command: pip install -r requirements.txt
Start Command: gunicorn app:app --workers 1 --threads 2 --timeout 120 --access-logfile - --error-logfile -
