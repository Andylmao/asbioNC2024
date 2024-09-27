# asbioNC2024
# ASBIOpractNocheCiencia2024

**Descripción del Proyecto**
Este proyecto está dividido en tres partes principales:

- Captura de video desde la cámara web: Utilizando OpenCV, se captura un video desde 
la cámara web del equipo por una cantidad determinada de tiempo.
- Procesamiento del video: Se analiza cada fotograma del video para calcular la luminosidad promedio, 
y se genera un archivo CSV con los resultados.
- Visualización interactiva: Usando Plotly, se genera una gráfica interactiva para visualizar la intensidad de luz en el tiempo, tanto en forma de puntos (scatter) como en línea continua.


**Archivos**
- video_output.avi: Video grabado desde la cámara web.
- luminosity_data.csv: Archivo CSV con los valores de tiempo e intensidad de luz por fotograma.
- README.md: Este archivo con la documentación.

**Consideraciones**
- La grabación de video solo funcionará si tienes una cámara web disponible.
- Para ejecutar este código en Jupyter o un entorno local, asegúrate de que OpenCV pueda acceder a los dispositivos de video de tu equipo.
- 
**Futuras Mejoras**

- Agregar opciones para elegir diferentes fuentes de video.
- Incluir un análisis más detallado de las fluctuaciones en la luminosidad.
- Permitir diferentes formatos de video para la salida.


**Licencia**
Este proyecto está bajo la licencia MIT. Siente libre de modificar y usar el código según tus necesidades.
