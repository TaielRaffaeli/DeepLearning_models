# Proyecto de Clasificación con Redes Neuronales

Este repositorio contiene tres proyectos realizados en el ámbito del aprendizaje automático y el Deep Learning, abordando problemas de regresión, clasificación de imágenes y clasificación de variedades de frijoles secos.

---

## Problema 1: Predicción del Índice de Rendimiento Académico

**Descripción:**  
Modelo de regresión con redes neuronales para predecir el índice de rendimiento académico de estudiantes usando variables como horas de estudio, puntuaciones anteriores y actividades extracurriculares.

**Dataset:**  
Variables: Horas de estudio, puntuaciones anteriores, actividades extracurriculares, horas de sueño, cuestionarios practicados, y el índice de rendimiento (10 a 100).

**Objetivo:**  
Desarrollar un modelo de regresión utilizando redes neuronales para predecir el índice de rendimiento académico de los estudiantes. Se implementaron técnicas avanzadas de validación y métricas de evaluación de regresión.

**Incluye:**  
Incluye código fuente en Google Colab con:
- Análisis y preprocesamiento del dataset.
- Definición y entrenamiento del modelo.
- Resultados de la evaluación del modelo con métricas de desempeño y visualizaciones.

## Problema 2: Clasificación de Variedades de Frijoles Secos

**Descripción:**  
Crear un modelo de clasificación para distinguir entre siete variedades de frijoles secos usando un conjunto de datos que contiene atributos geométricos y de forma extraídos de imágenes de frijoles. Se calcularon nuevas características adicionales para mejorar el rendimiento del modelo.

**Dataset:**  
Incluye atributos como área, perímetro y longitud de ejes, y las variedades de frijoles: Seker, Barbunya, Bombay, Cali, Dermosan, Horoz y Sira.

**Objetivo:**  
Desarrollar un modelo de clasificación con redes neuronales para predecir la variedad de frijol basándose en las características extraídas y nuevas características calculadas.

**Incluye:**  
Código fuente en Google Colab con:
- Análisis y preprocesamiento del dataset.
- Definición y entrenamiento del modelo de clasificación.
- Resultados de la evaluación del modelo con métricas y visualizaciones.

## Problema 3: Clasificación de Imágenes de Escenas Naturales

**Descripción:**  
Construir un modelo de clasificación utilizando redes neuronales convolucionales (CNN) para clasificar imágenes de escenas naturales en una de seis categorías predefinidas: buildings, forest, glacier, mountain, sea y street. Se abordaron varios enfoques, incluyendo modelos con capas densas, convolucionales, bloques residuales identidad y transfer learning.

**Dataset:**  
Contiene alrededor de 25,000 imágenes de tamaño 150x150 distribuidas en:
- **Train:** ~14,000 imágenes para entrenamiento.
- **Test:** ~3,000 imágenes para evaluación.
- **Prediction:** ~7,000 imágenes para predicción final.

**Objetivo:**  
Desarrollar y comparar distintos modelos de clasificación de imágenes con CNN y técnicas adicionales como transfer learning.

**Incluye:**  
Código fuente en Google Colab con:
- Análisis y preprocesamiento del dataset.
- Definición y entrenamiento de los modelos.
- Resultados de la evaluación con métricas de desempeño y visualizaciones.

Este repositorio muestra aplicaciones prácticas de redes neuronales en la resolución de problemas de regresión y clasificación, destacando la flexibilidad y potencia de las técnicas de Deep Learning.

---

## Instrucciones para Correr el Código

### Instalación de Librerías de Forma Local

1. **Clona el Repositorio (si aplica)**:
   ```sh
   git clone https://github.com/TaielRaffaeli/DeepLearning_models
   cd DeepLearning_models
   ```

2. **Crear y Activar un Entorno Virtual**:

   ```sh
   python -m venv venv
   .\venv\Scripts\activate
   ```

3. **Instalar Dependencias**:
   ```sh
   pip install -r requirements.txt
   ```

4. **Ejecutar el Código**:
   Ahora puedes ejecutar el código de forma local.


### Instalación de Librerías en Google Colab

1. **Abrir Google Colab**:
   Ve a [Google Colab](https://colab.research.google.com/) y abre una nueva notebook.

2. **Subir el Archivo `requirements.txt`**:
   Sube el archivo `requirements.txt` a tu entorno de Colab usando el icono de carpeta en la barra lateral izquierda para abrir el navegador de archivos y el botón "Subir" para cargar el archivo.

3. **Instalar Dependencias**:
   En la primera celda de la notebook, instala las dependencias:
   ```python
   !pip install -r requirements.txt
   ```

4. **Ejecutar el Código**:
   Ahora puedes ejecutar tu código en la notebook.