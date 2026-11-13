Buenas tardes, profesor.

Durante el desarrollo de las pruebas de campo se nos presentó una dificultad para conseguir las 50 imágenes nuevas solicitadas, debido a que nuestra aplicación trabaja con archivos en formatos `.npy` y `.bin`, y no permite procesar directamente imágenes convencionales como `.jpg` o `.png`. Esto limitó las posibilidades de utilizar fotografías tomadas con celulares u otros dispositivos.

Por esta razón, decidimos realizar una evaluación complementaria utilizando 50 imágenes adicionales del dataset OBAS V2, seleccionadas de la partición de prueba y diferentes de las 20 imágenes que habíamos utilizado anteriormente para verificar el funcionamiento de la aplicación.

Estas imágenes no corresponden a fotografías nuevas tomadas en campo. Además, aunque están identificadas como datos de prueba en el índice espacial del dataset, no pudimos confirmar completamente que ninguna hubiera sido utilizada durante el entrenamiento original del modelo.

Con esta alternativa buscamos ampliar la evaluación, identificar aciertos y errores y analizar el comportamiento del modelo ante diferentes imágenes, dejando documentadas las limitaciones de la prueba y del formato admitido por la aplicación.
