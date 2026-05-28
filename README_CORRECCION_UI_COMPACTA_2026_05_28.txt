CORRECCIÓN UI COMPACTA 2026-05-28

Se trabajó sobre el ZIP adjunto sin modificar la lógica funcional.
Cambios aplicados en app.py solo a nivel visual/CSS:

1. Panel lateral
- Ancho reducido y fijo.
- Eliminado espacio muerto entre sidebar y contenido.
- Menú compacto con iconos y textos ajustados.
- Scroll lateral sin huecos blancos.

2. Cards / recuadros
- Reducción de padding, altura mínima, separación y sombras.
- Cards y módulos más compactos.
- Grillas responsive para desktop y celular.

3. Contenido principal
- Contenedor principal al 100% del ancho disponible.
- Menos margen lateral y mejor aprovechamiento del espacio.
- Dashboard y módulos más cercanos al panel.

4. Formularios / tablas
- Etiquetas e inputs más bajos.
- Botones compactos.
- Tablas con padding reducido y scroll horizontal controlado.

5. Responsive
- Sidebar móvil corregido sin espacios raros.
- Formularios en una columna en celular.
- Textos, botones y cards compactos en pantalla pequeña.

Validación:
- app.py compila correctamente con python -m py_compile.
- Se renderizaron rutas principales de Gestión Contratación con test_client sin error 500.
