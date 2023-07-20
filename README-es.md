# Avisos ciudadanos

¿Prefieres leer esta documentación en español o en inglés?

- [Haz clic aquí para ver la versión en español](README-es.md)
- [Click here to view the English version](README.md)

## Índice
- [👋 Introducción](#introducción)
- [📑 Descripción](#descripción)
- [🌟 Características](#características)
- [ℹ️ Sobre la base de datos](#sobre-la-base-de-datos)
- [⚙️ Configuración del proyecto](#configuración-del-proyecto)
- [⚖️ Licencia](#licencia)
- [📫 Contacto](#contacto)

## 👋 Introducción
¡Bienvenido al repositorio de nuestro proyecto de Avisos de los Ciudadanos! Este proyecto fue realizado por @flotrigo y yo como parte de nuestro programa universitario de Ingeniería Matemática Aplicada al Análisis de Datos (Data Science) en la Universidad Europea de Madrid durante el segundo año de nuestra carrera, desde septiembre de 2022 hasta diciembre de 2022.

## 📑 Descripción
El propósito de este proyecto es buscar una base de datos abierta y someterla a una serie de procesos, que incluyen la limpieza de datos, el análisis exhaustivo y la extracción de conclusiones significativas.

En este proyecto, nos centraremos en obtener una base de datos relevante y confiable. A continuación, aplicaremos técnicas de limpieza de datos para garantizar que los datos sean consistentes y estén libres de errores. Una vez completada la etapa de limpieza, llevaremos a cabo un estudio minucioso de los datos, aplicando técnicas y métodos de análisis adecuados para extraer información valiosa.

Nuestro objetivo final es obtener conclusiones significativas a partir de esta base de datos. Al analizar los datos de manera sistemática y profunda, podremos descubrir patrones, tendencias y relaciones que nos permitan obtener conocimientos y tomar decisiones fundamentadas.

## 🌟 Características
- Utilización de las bibliotecas **pandas** y **numpy** para la preparación de los datos.
- Realización de un **análisis exploratorio** de las variables y visualización de gráficos (como gráficos de dispersión, de barras y de cajas o bigotes) con las bibliotecas **matplotlib** y **plotly**.
- **Comparación de resultados** en los años 2020, 2021 y 2022. *Nota: Los datos del año 2022 del archivo CSV adjunto solo están disponibles hasta septiembre*.
- Realización de **web scraping** sencillo en Wikipedia para obtener la lista de distritos de la Comunidad de Madrid, junto con sus respectivos datos de población.
- Creación de **mapas interactivos** de la Comunidad de Madrid y **mapas de calor** utilizando la biblioteca **folium**, donde los puntos representados varían en tamaño según la cantidad de casos.
- Además, se crea un conjunto de datos de los distritos de la Comunidad de Madrid de forma manual ya que no existe: [Distritos de Madrid - Latitud y Longitud](https://www.kaggle.com/datasets/jjnscjj/distritos-de-madrid-latitud-y-longitud).
- Información detallada sobre la **seguridad y privacidad** en el proyecto.

## ℹ️ Sobre la base de datos
La base de datos seleccionada ha sido recogida de la siguiente página del ayuntamiento: [Avisos ciudadanos](https://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/?vgnextoid=fd6112695c6bb410VgnVCM1000000b205a0aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD&vgnextfmt=default). Esta base de datos se centra en los informes de incidencias comunicados por los ciudadanos de la Comunidad de Madrid y en aquellas incidencias resueltas por el Ayuntamiento. Son dos conjuntos de datos relacionados con los informes de incidencias en la vía pública, que abarcan áreas como la limpieza, los parquímetros, el alumbrado, la recogida de residuos, las aceras y las calzadas, las zonas verdes y otros. Estos informes han sido transmitidos al Ayuntamiento a través de varios canales, como el número telefónico 010-Línea Madrid, la aplicación móvil 'Avisos Madrid' y el sitio web www.madrid.es.

Uno de los conjuntos de datos contiene los informes recibidos durante un período de tiempo específico, mientras que el otro conjunto de datos incluye los informes tramitados durante ese período, independientemente de la fecha de apertura de los mismos.

## ⚙️ Configuración del proyecto
Para instalar y probar el proyecto de manera local, sigue estos pasos:

1. Clona el repositorio con el siguiente comando: `git clone https://github.com/smwko/avisos-ciudadanos.git`.
2. Instala las bibliotecas requeridas utilizando `pip install [nombre de la biblioteca]` si estás utilizando la terminal o `!pip install [nombre de la biblioteca]` si estás utilizando el cuaderno Jupyter (.ipynb).
3. Accede al cuaderno llamado reporte-incidencias.ipynb abriendo Jupyter Notebook o buscando en el navegador: `http://localhost:8888/tree`.

## ⚖️ Licencia
Este proyecto está bajo una licencia [Creative Commons Attribution-NonCommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/deed.es_ES). Esto significa que puedes usar, modificar y distribuir el proyecto, siempre y cuando no sea con fines de lucro o comerciales. Además, si utilizas este proyecto, se requiere que se atribuya a los autores originales.

## 📫 Contacto
Si tienes alguna pregunta, sugerencia u opinión, ¡no dudes en ponerte en contacto con nosotros!

---

Trabajemos juntos para crear espacios públicos más seguros, limpios y vibrantes. ¡Muchas gracias por tu interés!
