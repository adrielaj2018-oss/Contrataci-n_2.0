CAMBIOS APLICADOS - GESTIÓN CONTRATACIÓN PRO

1. Indumentaria y fotocheck
- Se agregaron desplegables para tallas de polo, pantalón, botas, casaca, guantes y estados de gorro/lentes/fotocheck.
- Se corrigió la columna Eliminar para que aparezca junto al estado y sea visible.

2. Nuevos / Reingresantes
- Se agregó control de doble registro por DNI: si el DNI ya existe, actualiza el registro operativo en lugar de duplicarlo.
- Se amplió la ficha con distrito, provincia, departamento, estado civil, sistema pensionario, última empresa, discapacidad y cantidad de hijos.
- Se reemplazó Jefe inmediato por Sistema pensionario en la ficha principal.
- La foto tomada queda enlazada con fotocheck.
- Se dejó preparado el botón de conexión del huellero ZK9500/API biométrica.

3. Docs postulante
- Se agregó base de trabajadores registrados similar a NEXT, con filtros por DNI/nombres/requerimiento y selección masiva.

4. Fotocheck
- Se agregó base de trabajadores registrados con columnas: foto, DNI, trabajador, requerimiento, cargo, estado de foto, estado fotocheck y acción.
- Se agregó preparación de conexión Zebra ZC300 por USB/driver/Browser Print.
- Se dejaron opciones de generar PDF, imprimir seleccionados, reimpresión y cargo firmado.

5. Interfaz general
- Se reforzó contraste de etiquetas para que no desaparezcan.
- Se mejoraron tablas, filtros, botones y scroll horizontal para no cortar columnas.

Validado con python -m py_compile app.py y prueba de rutas principales con 200 OK.
