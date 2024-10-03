<p align="center">
  <img src="https://github.com/juanramosdataexpert/NortenoInsights/blob/main/Src/Img/Norte.jpg" alt="Norteño Insights" width="40%"">
</p>

# Norteño Insights: Análisis de Datos de la Música Norteña Colombiana

Este proyecto tiene como objetivo explorar el fascinante mundo de la promoción de la música norteña colombiana a través del análisis de datos. Utilizando técnicas de ETL y visualización, buscamos descubrir tendencias, patrones y oportunidades en esta vibrante industria musical.

## ¿Qué encontrarás aquí?
**Análisis exhaustivo:** Hemos analizado las últimas 20 publicaciones de los principales artistas del género norteño colombiano (Los Hermanos Ariza Show, Uriel Henao, Grupo Dominio y Los 5 del Norte).

**Comparación con referentes:** Para obtener una perspectiva más amplia, hemos comparado estos datos con 8 artistas de géneros similares, tanto colombianos como mexicanos.

**Visualizaciones impactantes:** Un informe detallado en PDF (NorteñoInsights.pdf) presenta visualizaciones claras y concisas que revelan insights valiosos.

**Código reproducible:** Los notebooks de Jupyter (en la carpeta Notebooks) contienen todo el código utilizado para la descarga, transformación, análisis y modelado de los datos.

## Estructura del Repositorio
- **Data:** Contiene los archivos CSV con los datos descargados de Instagram mediante InstagrAPI.
- **Docs:** Aquí encontrarás el informe final en PDF y el archivo Quarto (qmd) utilizado para generarlo.
- **Notebooks:**
  - **Descarga y transformación - extract_data.ipynb:** Código para obtener y preparar los datos.
  - **Análisis de datos - analysis.ipynb:** Exploración y análisis de los datos.
  - **Modelado - build_model.ipynb:** Experimentos con modelos de machine learning (aunque los resultados no fueron concluyentes debido a la limitada cantidad de datos).
- **Sources - Img:** Contiene la imagen utilizada como portada.

## Resultados clave
Nos encontramos con 4 perfiles de Instagram muy diferentes, con particularidades muy específicas que se hace clara con una media de 221.31 likes por publicación, pero una desviación estándar de 191.89 likes. Justamente por esta razón, no fue posible encontrar relaciones matemáticas concluyentes que pudieran construir un modelo de Machine Learning de Regresión efectivo. También vimos una Correlación de Pearson del 0.5483 entre el número de seguidores de los perfiles y el número de likes de las publicaciones, mostrando una relación positiva con una fuerza media. Los perfiles más importantes en términos de desempeño de nuestro género norteño colombiano son los de Los Hermanos Ariza Show y Uriel Henao. Además, podemos afirmar, con una mediana de 4 comentarios por publicación que, el público de este género no comenta las publicaciones, en general. Finalmente, vale la pena mencionar que el principal tipo de contenido son los Reels, seguidos muy de cerca por los Carruseles.

## Tecnologías utilizadas
- **Python:** Lenguaje de programación principal.
- **Pandas y Numpy:** Manipulación y análisis de datos.
- **InstagrAPI:** Descarga de datos de Instagram.
- **Matplotlib:** Visualización de datos.
- **Scipy:** Pruebas estadísticas.
- **SciKit-Learn:** Modelos de Machine Learning de Regresión.
- **Quarto:** Generación de informes.
