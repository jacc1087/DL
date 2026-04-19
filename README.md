# Proyecto de Deep Learning

## Descripción
<p> Eres el principal Data Scienctist de la compañía 'Toby Carvery' perteneciente al sector de 'Restaurants & Bar'. El
director de Customer Experience (CX) ha pedido que analizar las reseñas que tiene la compañía en Trust pilot.

## Extracción de datos
<p> Los archivos se han comprimido para no superar el límite de 100 MB que tiene Github, solamente hay que descomprimir el archivo 'trustpilot-reviews-123k.csv' una vez descargada la carpeta del proyecto para que carguen correctamente.

## Limpieza de datos
<p> En el cuaderno se crea una función que prepara el dataset para el análisis del sentimiento de las reseñas, donde se tratan espacios y saltos de línea, tildes, stopwords con la librería NLTK y se pasa todo a minúscula para un mejor análisis.
<img width="1052" height="192" alt="Captura de pantalla 2026-04-19 a las 12 41 11" src="https://github.com/user-attachments/assets/d72fa02c-d7db-4f03-a43e-55d8f0dd838e" />

## Sentimiento de las reseñas
<p> Tras probar con NLTK mediante VADER y SPACY, se comprueba que el modelo que mejor rendimiento saca de estas reseñas es Transformers de Torch, saca un alto porcentaje de acierto de sentimiento del usuario sobre > 80%.

## Detección de topics
<p> Con BERTOPIC, se analizan las diferentes reseñas para extraer los diferentes topics sobre lo que opinan los usuarios, se configura para que haya un mínimo de 8 repeticiones para que se considere topic.

## Visualización 
<p> Se utiliza la librería wordcloud para crear nubes de palabras de cada uno de los topics creados.

## Presentación del proyecto
<p> Se utiliza la web loom para crear un vídeo donde se presente el proyecto y las conclusiones obtenidas, tanto aquí como en la entrega del proyecto se deja el enlace.
https://www.loom.com/share/8a63df981e614c41a67b53a5b3746607
