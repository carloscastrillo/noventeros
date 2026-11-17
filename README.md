# NOVENTEROS

Panel público del equipo NOVENTEROS: calendario, resultados, clasificación y estadísticas individuales. Se publica en GitHub Pages sin contraseña por indicación del propietario.

`index.html` es autónomo y permite consultar los datos sin peticiones a Swish. `noventeros.ics` contiene únicamente los partidos con fecha publicada. No se incluyen contraseñas, tokens, SQLite o capturas de sesión.

Los datos proceden de las actas propias del 16 de noviembre y del calendario y clasificación públicos del 17 de noviembre de 2026, además de la plantilla del equipo. El panel no es una aplicación oficial de NBN23. La actualización automática de los lunes todavía no está activada.

El pipeline Python, los contratos y las evidencias se mantienen en el proyecto de investigación original. Para actualizar esta web se regeneran y publican el HTML y los archivos ICS allí. El diseño conserva el logotipo del equipo y la atribución de Unslop incluida en el pie.

El botón «Añadir siguiente partido» descarga `noventeros-siguiente.ics`, con el siguiente encuentro publicado. En iPhone se ha comprobado la vista previa en Calendario; en Android la apertura depende de la aplicación instalada. Google Calendar permite importar archivos desde un ordenador. Importar repetidamente puede duplicar eventos. El archivo no se actualiza automáticamente tras importarlo; los datos y su publicación siguen siendo manuales. Se conservan las direcciones `noventeros-proximos.ics` y `noventeros.ics` para quienes ya las utilizan. Los ICS públicos omiten los detalles técnicos de procedencia, que se conservan en el proyecto de investigación.

La cabecera muestra el logotipo centrado y los seis iconos de navegación aparecen en una barra inferior flotante. El calendario mantiene los filtros Todos y Próximos y muestra el nombre del rival y su posición en la clasificación de la captura del 16/11/2026, no una posición histórica. La tabla «Estadísticas generales» conserva la ordenación y las fichas; la ficha inicial corresponde al primer dorsal de la tabla; se han retirado los controles de búsqueda y filtrado de esa tabla. La revisión se realiza en Chrome con tamaños móviles y de escritorio; no equivale a una prueba en Safari de un iPhone físico.

La tipografía Manrope se incluye en el HTML y no hace peticiones a Google Fonts al consultar la web. Copyright 2018 The Manrope Project Authors; licencia SIL Open Font License 1.1 en [OFL-Manrope.txt](OFL-Manrope.txt), también incluida en el HTML.

La tabla compacta muestra PAR JUG, MIN JUG y PT; minutos y puntos son promedios por partido. 5I se conserva como dato no disponible, sin convertirlo en cero. Los nombres completos se mantienen en las fichas. El resumen de temporada muestra posición, últimos cinco resultados, victorias, derrotas y balance de puntos de la captura.

## Scouting y evolución (17 de noviembre de 2026)

El panel incorpora un mapa técnico de datos y evidencias al pie, scouting por cualquiera de los 13 equipos de Primera y evolución individual en las fichas. El scouting utiliza el calendario público capturado el 17/11: 156 cruces entre equipos, 34 resultados, 26 pendientes con fecha y 96 sin fecha. Se excluyen 26 huecos sin dos equipos. La clasificación y los resultados del calendario son fuentes distintas; dos equipos presentan discrepancias entre partidos jugados y victorias más derrotas en la clasificación publicada.

La evolución individual conserva únicamente las cinco actas propias capturadas el 16/11; los partidos sin acta no se convierten en ceros. Los minutos interpretan el tiempo como segundos por coherencia de las capturas, pendiente de contraste visual. Los fallos de tiro de campo, rebotes y asistencias no están verificados como completos. No se infieren estadísticas individuales rivales ni resultados futuros. Los datos son una fotografía y no se actualizan automáticamente.
