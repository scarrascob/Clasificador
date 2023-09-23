
Hola! Mi nombre es Sebastián Carrasco Bravo y soy ingeniero civil industrial 🏭, actualmente me encuentro cursando un magister en ciencias de datos para la innovación en la Universidad de Concepción, Chile 🔴⬜🔷.
Actualmente me desempeño como analista de control de gestión en entel, donde mis fortalezas son el análisis de datos para la toma de decisiones y la automatización de procesos.

# Clasificación de Imágenes (Perros y Gatos) 🐕🐈‍⬛

Este proyecto se presenta como parte de un trabajo de clasificación de imágenes de perros y gatos utilizando Python y TensorFlow. Este trabajo fue hecho en base a tutoriales de internet, debido a que se basa en un proyecto personal y de autoaprendizaje, dirigido especialmente a un ramo del master.
El proyecto se basa en un dataset de imagenes de perros y gatos, en donde se utilizan redes neuronales para entrenar distintos modelos densos y convolutivos.
# ¿En que consisten estos modelos? 🧠

## Modelo Denso (Red Neuronal Totalmente Conectada):

En un modelo denso, todas las neuronas de una capa están conectadas a todas las neuronas de la capa siguiente. Esto significa que cada entrada afecta a todas las neuronas de la siguiente capa, lo que resulta en un gran número de parámetros entrenables en la red.
Los modelos densos son apropiados para tareas en las que la relación entre las entradas y las salidas es compleja y no se pueden asumir patrones locales. Por ejemplo, en problemas de procesamiento de lenguaje natural, donde las palabras en una oración pueden influir en el significado de otras palabras en la misma oración.
Estos modelos son conocidos por su capacidad de aprender representaciones complejas de datos, pero también pueden requerir un gran conjunto de datos y tiempo de entrenamiento para converger.

## Modelo Convolutivo (Red Neuronal Convolucional o CNN):

Un modelo convolutivo utiliza capas convolucionales que aplican operaciones de convolución a las entradas. Estas capas son efectivas para identificar patrones locales y características en los datos, como bordes, texturas y formas.
Las CNNs son ampliamente utilizadas en tareas de visión por computadora, como clasificación de imágenes, detección de objetos y segmentación semántica, debido a su capacidad para capturar características jerárquicas en las imágenes.
Las capas convolucionales se combinan típicamente con capas de agrupación (pooling) para reducir la dimensionalidad y capas completamente conectadas al final de la red para tomar decisiones basadas en las características extraídas por las capas convolucionales.
Las CNNs suelen requerir menos parámetros entrenables que las redes densas, lo que las hace más eficientes en términos de memoria y tiempo de entrenamiento.

## Cómo Utilizarlo 💡

1. Descargar el repositorio: Copia o descarga el repositorio en tu PC 💻.

2. Iniciar un servidor local: Este proyecto utiliza TensorFlow.js para cargar el modelo de clasificación. Para ejecutarlo, necesitas un servidor local. Puedes hacerlo de la siguiente manera:

   - Asegúrate de tener Python instalado en tu PC.
   - Abre una terminal y navega hasta la carpeta donde descargaste el repositorio (La ruta es variable y depende netamente de tu PC).
   - Ejecuta el siguiente comando: `python -m http.server 8000`
   - Abre un navegador web y accede a `http://localhost:8000`.

## Uso en Dispositivos Móviles 📱

Si deseas utilizar la aplicación en tu dispositivo móvil, ten en cuenta que la cámara del dispositivo se utiliza para la clasificación de imágenes. Para habilitar el uso de la cámara en dispositivos móviles, sigue estos pasos:

1. Descarga ngrok en tu computadora y descomprímelo.

2. Abre una terminal y navega hasta la carpeta donde descargaste ngrok.

3. Ejecuta el comando: `ngrok http 8000`.

Asegúrate de mantener activos tanto el servidor Python como el túnel de ngrok.

En la terminal de ngrok, encontrarás un enlace HTTPS. Abre un navegador en tu dispositivo móvil y accede a este enlace. Puedes usar la cámara para capturar imágenes de perros o gatos, y la aplicación proporcionará predicciones.

## Notas Importantes 📝

- Este proyecto es una implementación básica con fines educativos y de autoaprendizaje y no garantiza una clasificación perfecta.

¡Gracias por utilizar esta aplicación de clasificación de imágenes!
