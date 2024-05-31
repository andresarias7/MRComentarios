# IAComentarios

Este proyecto analiza comentarios de clientes utilizando técnicas de Procesamiento de Lenguaje Natural (NLP) y modelos de Tópicos Latentes Dirichlet Allocation (LDA) para identificar temas recurrentes en las opiniones sobre una marca de ropa. El análisis se realiza en Google Colab para aprovechar su entorno interactivo y los recursos en la nube.


### Contenido del Proyecto:

1. **IAComentarios**: Carpeta que contiene el notebook de Google Colab con el código.
2. **README.md**: Este archivo.

1. **Carga y Preprocesamiento de Datos**
    - Importación de las librerías necesarias.
    - Carga del dataset con comentarios de clientes.
    - Limpieza y preprocesamiento de los comentarios (eliminación de signos de puntuación, conversión a minúsculas, tokenización y lematización).

2. **Análisis Exploratorio de Datos (EDA)**
    - Visualización de datos para entender la distribución de comentarios y palabras más frecuentes.
    - Generación de nubes de palabras para visualizar términos comunes en los comentarios.

3. **Modelo LDA**
    - Entrenamiento de un modelo LDA para identificar temas recurrentes en los comentarios.
    - Visualización e interpretación de los temas generados por el modelo LDA.

4. **Evaluación y Resultados**
    - Presentación de los temas identificados con una breve descripción de cada uno.


### Pasos para Ejecutar el Código en Google Colab:

1. **Abrir el Notebook en Google Colab:**

    - Abre Google Colab en tu navegador.
    - Haz clic en "Archivo" -> "Subir notebook" y selecciona el notebook de Google Colab `IAComentarios.ipynb` .
    - El notebook se abrirá en una nueva pestaña.

2. **Ejecutar el Código:**

    - Ejecuta cada celda en orden para cargar los datos, entrenar los modelos y generar visualizaciones. Puedes hacerlo haciendo clic en el botón de reproducción en cada celda o presionando Shift + Enter.

3. **Interpretación de Resultados:**

    - Una vez que hayas ejecutado todas las celdas, revisa los resultados de los modelos y las visualizaciones generadas para comparar su desempeño.

### Cómo Compartir el Notebook en Google Colab:

1. **Guardar el Notebook en Google Drive:**

    - Después de haber ejecutado todas las celdas y revisado los resultados, guarda el notebook en Google Drive haciendo clic en "Archivo" -> "Guardar una copia en Drive".

2. **Obtener el Enlace Compartido:**

    - En tu Google Drive, haz clic derecho en el notebook y selecciona "Obtener enlace".
    - Cambia los permisos para que cualquiera con el enlace pueda ver el notebook.

3. **Compartir el Enlace:**

    - Comparte el enlace del notebook con otras personas para que puedan ver y ejecutar el código en Google Colab.
## Prerrequisitos

- Una cuenta de Google para usar Google Colab.
- Familiaridad con Python y bibliotecas como pandas, numpy, matplotlib, seaborn, nltk y gensim.