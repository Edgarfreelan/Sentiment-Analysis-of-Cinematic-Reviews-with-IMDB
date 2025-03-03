Análisis de Sentimientos en Reseñas Cinematográficas con IMDB
Descripción
Este proyecto realiza un análisis de sentimientos en reseñas de películas utilizando el conjunto de datos IMDB. Usando técnicas de procesamiento de lenguaje natural (PLN) y aprendizaje automático, se clasifican las reseñas en positivas o negativas. El análisis incluye visualizaciones como nubes de palabras y distribuciones de la longitud de las reseñas, junto con un modelo de clasificación basado en Naive Bayes.

Tecnologías Utilizadas
Python 3.x
Pandas
Matplotlib
Seaborn
Scikit-learn
WordCloud
Instrucciones de Instalación
1. Clonar este repositorio:
bash
Copiar
git clone https://github.com/tuusuario/IMDB-Sentiment-Analysis.git
cd IMDB-Sentiment-Analysis
2. Instalar las dependencias necesarias:
bash
Copiar
pip install -r requirements.txt
3. Descargar el Conjunto de Datos IMDB:
El conjunto de datos puede ser descargado desde IMDB Dataset.

Coloca el archivo IMDB Dataset.csv en la carpeta del proyecto.

4. Ejecutar el análisis:
bash
Copiar
python sentiment_analysis.py
Este comando procesará las reseñas y generará las visualizaciones, así como los resultados del modelo entrenado.

Estructura del Proyecto
bash
Copiar
IMDB-Sentiment-Analysis/
│
├── sentiment_analysis.py       # Script principal para el análisis de sentimientos
├── IMDB Dataset.csv            # Conjunto de datos de reseñas de películas IMDB
├── requirements.txt            # Librerías de Python necesarias
└── README.md                   # Documentación del proyecto
Resultados
El análisis produce:

Nubes de Palabras: Visualizaciones de las palabras más comunes en reseñas positivas y negativas.
Distribución de la Longitud de las Reseñas: Comparación entre la longitud promedio de reseñas positivas y negativas.
Clasificación de Sentimientos: Un modelo entrenado de Naive Bayes que clasifica las reseñas como positivas o negativas.
Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.

