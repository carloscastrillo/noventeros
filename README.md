# NOVENTEROS

Panel público del equipo NOVENTEROS: calendario, resultados, clasificación y estadísticas individuales. Se publica en GitHub Pages sin contraseña por indicación del propietario.

`index.html` es autónomo y permite consultar los datos sin peticiones a Swish. `noventeros.ics` contiene únicamente los partidos con fecha publicada. No se incluyen contraseñas, tokens, SQLite o capturas de sesión.

Los datos proceden de capturas autorizadas de Swish/NBN23 del 16 de noviembre de 2026 y de la plantilla del equipo. El panel no es una aplicación oficial de NBN23. La actualización automática de los lunes todavía no está activada.

El pipeline Python, los contratos y las evidencias se mantienen en el proyecto de investigación original. Para actualizar esta web se regeneran HTML/ICS allí y se sustituyen estos dos archivos. El diseño conserva el logotipo del equipo y la atribución de Unslop incluida en el pie.

La cabecera muestra el logotipo centrado y los seis iconos de navegación aparecen en una barra inferior flotante. El calendario mantiene los filtros Todos y Próximos y muestra el nombre del rival y su posición en la clasificación de la captura del 16/11/2026, no una posición histórica. La tabla de jugadores conserva la ordenación y las fichas; se han retirado los controles de búsqueda y filtrado de esa tabla. La revisión se realiza en Chrome con tamaños móviles y de escritorio; no equivale a una prueba en Safari de un iPhone físico.

La tipografía Manrope se incluye en el HTML y no hace peticiones a Google Fonts al consultar la web. Copyright 2018 The Manrope Project Authors; licencia SIL Open Font License 1.1 en [OFL-Manrope.txt](OFL-Manrope.txt), también incluida en el HTML.

La tabla compacta muestra PAR JUG, MIN JUG y PT; minutos y puntos son promedios por partido. 5I se conserva como dato no disponible, sin convertirlo en cero. Los nombres completos se mantienen en las fichas. El resumen de temporada muestra posición, últimos cinco resultados, victorias, derrotas y balance de puntos de la captura.
