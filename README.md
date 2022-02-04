# RTSP a HLS
 
Este proyecto demostrativo muesta cómo mostrar el video de una cámara IP en un navegador web.
<br>
En este proyecto utilizamos el RTSP de las cámaras, luego lo convertimos a HLS mediante el software FFMPEG. Esto se hace así porque los navegadores no soportan nativo el flujo RTSP.
<br><br>
FFMPEG se encuentra disponible gratuitamente para sistemas operativos Windows, Linux y Mac. Se puede obtener directamente en su sitio web: <a href='https://www.ffmpeg.org/download.html'>https://www.ffmpeg.org/download.html</a>
<br>
<h3>Windows</h3>
En esta carpeta se encuentran los archivos .bat con las instrucciones para convertir el flujo RTSP de una cámara ip a flujo HLS, el resultado es un archivo <b>.m3u8</b>
<br><br><b>Importante</b>: El archivo visualizador de videos debe correr en un servidor web. Para windows se puede utilizar XAMPP, LAMPP, WAMPP.

<h3>Linux / Mac</h3>
En esta carpeta se encuentran los archivos .sh con las instrucciones para convertir el flujo RTSP de una cámara ip a flujo HLS, el resultado es un archivo <b>.m3u8</b>
<br><br><b>Importante</b>: El archivo visualizador de videos debe correr en un servidor web.
<br><br>
<h3>Video demostrativo</h3>: <a href="https://www.youtube.com/watch?v=eZUqowKX3GA" target="_blanck">https://www.youtube.com/watch?v=eZUqowKX3GA</a>