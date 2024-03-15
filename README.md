# Validacion de Hipotesis

La validación de hipótesis es un proceso fundamental en la toma de decisiones basadas en evidencia, y no solamente en creencias u opiniones. En el análisis de datos, es común plantear suposiciones o hipótesis sobre relaciones, tendencias o diferencias entre las variables de los datos disponibles. La validación de estas hipótesis (confirmar o refutar) se consigue con técnicas y métodos diseñados para determinar si los resultados observados en los datos, son estadísticamente significativos o si pueden atribuirse al azar.

# Resumen/Contexto

En un mundo en el que la industria musical es extremadamente competitiva y está en permanente evolución, la capacidad de tomar decisiones basadas en datos se ha convertido en un activo invaluable.

En este contexto, una discográfica se enfrenta al emocionante desafío de lanzar un nuevo artista en el escenario musical global.

Con la ayuda de un dataset de Spotify con información sobre las canciones más escuchadas en 2023 valide y refute las hipotesis planteadas por la discografica  mediante el análisis de los datos, y proporcione recomendaciones estratégicas basadas en los hallazgos para que la discográfica y el nuevo artista puedan tomar decisiones informadas que aumenten sus posibilidades de conseguir el “éxito”

# Datasets

Utilice 3 datasets, una con información relacionada con las canciones reproducidas en Spotify (nombre de la canción, nombre del artista, # de streams enla plataforma, etc), otra con información del comportamiento de las canciones en otras plataformas (Apple Music y Deezer) y otra con la información sobre las caracteristicas técnicas de las canciones (dance, liveness, speechness, etc). 


# Objetivo

Basando en el analisis de los datos comprobe y refute las siguientes hipotesis:

    • Las canciones con un mayor BPM (Beats Por Minuto) tienen más éxito en términos de cantidad de streams en Spotify.
    • Las canciones más populares en el ranking de Spotify también tienen un comportamiento similar en otras plataformas como Deezer.
    • La presencia de una canción en un mayor número de playlists se relaciona con un mayor número de streams.
    • Los artistas con un mayor número de canciones en Spotify tienen más streams totales.
    • Las características de la música influyen en el éxito en términos de cantidad de streams en Spotify.

# Proceso

- ETL: identificación de nulos, duplicados, datos fuera de alcance, creación de nuevas variables, etc. En BigQuery (SQL).
- Técnicas de Análisis:
    - Segmentación de categorías.
    - Validación de hipotesis: Correlación de variables.
    - Prueba de significancia: Test de Wilcoxon. Para reafirmar la hipotesis.
    - Regresión lineal.
 
# Insides

- Hipotesis:
- Las canciones con un mayor BPM (Beats Por Minuto) tienen más éxito en términos de cantidad de streams en Spotify = Hipotesis Rechazada.
- Las canciones más populares en el ranking de Spotify también tienen un comportamiento similar en otras plataformas como Deezer = Hipotesis Rechazada.
- La presencia de una canción en un mayor número de playlists se relaciona con un mayor número de streams = Hipotesis Aceptada.
- Los artistas con un mayor número de canciones en Spotify tienen más streams totales = Hipotesis Rechazada.
- Las características de la música influyen en el éxito en términos de cantidad de streams en Spotify = Hipotesis Rechazada.
- Se presentaron recomendaciones para el lanzamiento del nuevo artista.
   
# Herramientas Utilizadas
   
    •  Big Query (SQL).
    •  Google Colab (Python).
    •  Power BI.
    •  Google Slides.
    •  Loom.
