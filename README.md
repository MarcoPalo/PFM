# PFM
El proyecto está organizado en 9 notebooks. 
* *0 - Descarga Tops SPOTIFY*. En este notebook se descargan, con técnicas de automatización, los rankings de Spotify que serán el centro del estudio. Requiere tener un usuario de Spotify (no de la API) para poder utilizarlo (gratuito). 
* *1 - Comprobación de la base de datos*. Comprueba qué datos hemos conseguido y crea índices de canciones.
* *2 - Descarga Lyrics*. Descarga las letras de las canciones a través de búsquedas automatizadas en Google.
* *3 - Traducción letras*. Detecta qué canciones no están en inglés y las traduce.
* *4 - VADER*. Analiza cómo de positivas o negativas son las letras y crea series temporales.
* *5 - Spotify API* Descarga datos adicionales de las canciones a través de la API de Spotify. Requiere usuario de la API (gratuito).
* *6 - FRED DATA*. Descarga datos económicos necesarios para el estudio a través de la API de FRED. Requiere usuario de la API (gratuito).
* *7 - Merger*. Une bases de datos necesarias para el estudio.
* *8 - Regresiones_monthly*. Regresiones principales con datos de panel y tests de Haussman.
* *9 - Regresiones_weekly*. Regresiones semanales con datos de panel y tests de Haussman, solo para música y COVID (no hay datos semanales económicos).
