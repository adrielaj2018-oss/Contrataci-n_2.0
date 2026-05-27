GESTION DE CONTRATACION - RENDER

Proyecto depurado para subir a Render.

Incluye solo el modulo visible de Gestion de Contratacion:
- Login administrador
- Menu lateral solo Gestion Contratacion
- Flujos, carga masiva, reportes
- Datos maestros
- Gestion documentaria
- Plantillas de contratacion
- Firma / Facial / Digital

Render:
Build Command: pip install -r requirements.txt
Start Command: gunicorn app:app --workers 1 --threads 2 --timeout 120

Ruta admin: /admin/login
Ruta principal admin despues del login: /admin/contratacion
