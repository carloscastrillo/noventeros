# NOVENTEROS

Panel público del equipo NOVENTEROS: calendario, resultados, clasificación y estadísticas individuales. Se publica en GitHub Pages sin contraseña por indicación del propietario.

`index.html` es autónomo y permite consultar los datos sin peticiones a Swish. `noventeros.ics` contiene únicamente los partidos con fecha publicada. No se incluyen contraseñas, tokens, SQLite o capturas de sesión.

Los datos proceden de capturas autorizadas de Swish/NBN23 del 16 de noviembre de 2026 y de la plantilla del equipo. El panel no es una aplicación oficial de NBN23. La actualización automática de los lunes todavía no está activada.

El pipeline Python, los contratos y las evidencias se mantienen en el proyecto de investigación original. Para actualizar esta web se regeneran HTML/ICS allí y se sustituyen estos dos archivos. El diseño conserva el logotipo del equipo y la atribución de Unslop incluida en el pie.

El panel adapta la navegación al espacio disponible. En pantallas estrechas el calendario se presenta como agenda mensual; en ordenador conserva la cuadrícula cuando cabe. Las tablas permiten desplazamiento propio con los jugadores fijos a la izquierda, y la búsqueda, los filtros y las fichas siguen disponibles. La revisión se realiza en Chrome con tamaños móviles y de escritorio; no equivale a una prueba en Safari de un iPhone físico.
