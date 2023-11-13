# clase
# analizador de imagenes
Este código fuente sirve como apoyo para el video de exportación de modelos de Tensorflow a Tensorflow.js, del canal de YouTube [Ringa Tech](https://youtube.com/RingaTech)

Se trata de un clasificador de imagenes escritas, en donde puedes dibujar en el explorador ropa y al dar clic en predecir intentará decir qué ropaes, utilizando Tensorflow.js, en base aun modelo entrenado en Python con Tensorflow

## Probar en vivo
Puedes probar este proyecto en vivo [aquí](https://ringa-tech.com/exportacion/numeros/)

## Cómo utilizarlo

### Descargar el repositorio
Descarga el repositorio donde gustes en tu computadora

### Inicia un servidor en la carpeta
Este proyecto utiliza un modelo de Tensorflow.js, el cual para cargarse requiere que el acceso sea por medio de http/https.
Para eso puedes usar cualquier servidor, pero aquí hay una forma de hacerlo:
- Descarga Python en tu computadora
- Abre una línea de comandos o terminal
- Navega hasta la carpeta donde descargaste el repositorio
- Ejecuta el comando `python -m http.server 8000`
- Abre un explorador y ve a http://localhost:8000
### Uso
Dibuja con el mouse o tu dedo en el canvas cuadrado un tipo de prenda y da clic en "Predecir". Para limpiar el canvas da clic en "Limpiar".


