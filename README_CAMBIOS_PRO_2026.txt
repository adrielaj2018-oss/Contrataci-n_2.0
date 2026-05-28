CAMBIOS APLICADOS - GESTION CONTRATACION PRO

1. Dashboard principal ajustado solo a Gestion Contratacion.
   - Se retiraron referencias visuales de Gestion Documental y Gestion Vacacional del dashboard de contratacion.
   - Se agregaron KPIs del embudo: Tickets, Nuevos/Reingresantes, Aptos Medicos, Lotes NISIRA y avance operativo.

2. Ticket de contratacion.
   - Tabla con accion Eliminar.
   - Filtro rapido de busqueda.
   - Mantiene crear/guardar ticket y actualizacion por mismo codigo de ticket.

3. Nuevo/Reingresante.
   - Formulario reorganizado y mas compacto.
   - Campos agregados: DNI, trabajador, celular, correo, direccion, puesto/cargo, sede, area, actividad, modalidad, fecha ingreso, jefe inmediato, cuenta bancaria, talla de indumentaria, contacto emergencia, requerimiento, foto camara, huella/biometria y observacion.
   - Preparado para lector biometrico ZK9500/API mediante adjunto de huella y estado biometrico.
   - La foto tomada queda vinculada para uso posterior en fotocheck.

4. Fotocheck.
   - Se agrego descripcion para flujo con Zebra ZC300: foto desde alta, plantilla CR80, impresion, reimpresion, cargo firmado y exportar lote.
   - Preparado para integracion posterior con Zebra Browser Print/driver oficial.

5. Base de datos.
   - Migraciones livianas agregadas para nuevos campos en trabajadores e ingresos de contratacion.
   - Acciones de eliminacion para requerimientos, ingresos, medico, capacitacion, indumentaria y checklist.

6. Render.
   - Se mantiene Procfile, runtime, requirements y estructura de despliegue.
