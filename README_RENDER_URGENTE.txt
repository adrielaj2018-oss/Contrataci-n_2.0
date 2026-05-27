PORTAL HR PRO - Gestión de Contratación solamente

Start Command en Render:
gunicorn app:app --workers 1 --threads 2 --timeout 120

Environment:
PYTHON_VERSION=3.11.9
APP_TIMEZONE=America/Lima
SECRET_KEY=portal_hr_pro_2026

Login admin:
Usuario: admin
Clave: admin123

Corrección aplicada:
- Se eliminó el bloqueo que causaba ERR_TOO_MANY_REDIRECTS en /admin y /admin/contratacion.
- Solo queda habilitado Gestión de Contratación.
- Login con letras más suaves y título PORTAL HR PRO.
