CORRECCIONES APLICADAS 28/05/2026

1. Requerimientos/Tickets:
   - Se retiraron los campos visibles Cargo y Cantidad del formulario principal.
   - Se agregó bloque de escaneo DNI/código de barras dentro del módulo Requerimientos.
   - Al escanear/digitar DNI se conecta al ticket seleccionado.
   - Si el DNI existe en trabajadores, queda como REINGRESANTE y jala datos base.
   - Si no existe, crea base mínima del trabajador con DNI para completar luego en Nuevos/Reingresantes.

2. Nuevos/Reingresantes:
   - Se retiró el enfoque de escaneo directo de este módulo.
   - Queda como ficha para completar datos del trabajador conectado al ticket.

3. Inducción / Cursos:
   - Se separó la navegación en Inducción y Cursos / Capacitación.
   - Se conservan videos del administrador y evaluación preparada para trabajador.

4. Tablas:
   - Columna Eliminar corregida para mostrarse al costado de Estado.
   - Botón eliminar reducido a icono para evitar que sobresalga.

5. Validación:
   - Probados módulos principales en test client: 200 OK.
