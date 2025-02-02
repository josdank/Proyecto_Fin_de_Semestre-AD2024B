# Proyecto de Análisis de Datos - Escuela Politécnica Nacional

Este repositorio contiene el proyecto final de análisis de datos desarrollado por estudiantes de la Escuela Politécnica Nacional. El proyecto está dividido en varias secciones, cada una enfocada en un tema específico, aplicando diversas técnicas de análisis de datos para extraer conclusiones relevantes a partir de fuentes variadas.

## 🔍 Tabla de Contenidos
- [Descripción General](#descripción-general)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Instrucciones de Instalación](#instrucciones-de-instalación)
- [Guía de Uso](#guía-de-uso)
- [Análisis por Secciones](#análisis-por-secciones)
  - [Eventos Deportivos](#eventos-deportivos)
  - [Actividades y Hobbies](#actividades-y-hobbies)
  - [Restaurantes y Sitios](#restaurantes-y-sitios)
  - [Conciertos y Eventos Públicos](#conciertos-y-eventos-públicos)
  - [Análisis de Métricas de Valve](#análisis-de-métricas-de-valve)
- [Herramientas Utilizadas](#herramientas-utilizadas)
- [Créditos](#créditos)

## 📊 Descripción General

Este proyecto tiene como objetivo aplicar técnicas de análisis de datos para extraer información valiosa de diferentes fuentes. Cada sección aborda un tema distinto, utilizando métodos de recolección, limpieza, visualización y análisis de datos. Se emplean técnicas estadísticas y de machine learning para obtener conclusiones basadas en datos reales.

## 📁 Estructura del Proyecto

```
Proyecto_Fin_de_Semestre-AD2024B-main/
├── 1. Eventos_Deportivos-DMejia/
├── 2. Actividades_y_Hobbies-ESarango/
├── 3. Restaurantes_y_Sitios-SCumbal/
├── 4. Conciertos-y-Eventos_publicos-JGuerra/
└── 6. Analisis_metricas_Valve-ARamos/
```

Cada carpeta contiene notebooks de Jupyter, scripts en Python y archivos de datos utilizados para el análisis.

## 🚀 Instrucciones de Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/Proyecto_Analisis_Datos.git
   ```
2. Accede al directorio del proyecto:
   ```bash
   cd Proyecto_Analisis_Datos
   ```
3. Instala las dependencias necesarias:
   ```bash
   pip install -r requirements.txt
   ```

## 📚 Guía de Uso

Cada carpeta contiene notebooks de Jupyter con código para:
- Recolección de datos desde APIs, archivos CSV o web scraping.
- Limpieza y preprocesamiento de datos para asegurar su calidad.
- Análisis exploratorio de datos (EDA) para identificar patrones y anomalías.
- Visualización de resultados mediante gráficos y dashboards interactivos.

Ejecuta los notebooks usando:
```bash
jupyter notebook
```

## 🌐 Análisis por Secciones

### 🏀 Eventos Deportivos
- **Descripción:** Análisis de estadísticas de la NBA, evaluando el rendimiento de equipos y jugadores.
- **Procesos:** Análisis de tendencias de victorias, eficiencia de jugadores y predicciones de resultados.
- **Herramientas:** Uso de Power BI para la creación de dashboards interactivos que permiten visualizar métricas clave de rendimiento.
- **Datasets:** Incluyen información sobre partidos, estadísticas de jugadores y clasificaciones de equipos.

![Dashboard Power BI](img/eventos_deportivos_dashboard.png)

### 🌸 Actividades y Hobbies
- **Descripción:** Estudio de tendencias en actividades recreativas y hobbies populares.
- **Procesos:** Análisis de encuestas de participación, frecuencia de actividades y preferencia por región.
- **Dataset:** [Sports and Outdoors (Kaggle)](https://www.kaggle.com/datasets/)

![Análisis de Actividades](img/actividades_hobbies_analisis.png)

### 🍽️ Restaurantes y Sitios
- **Descripción:** Evaluación de datos relacionados con restaurantes, su popularidad y calidad del servicio.
- **Procesos:** Análisis de reseñas de clientes, calificaciones promedio y patrones de consumo en diferentes ubicaciones.
- **Contenido:** Conexión a bases de datos SQL, análisis de datos geoespaciales y gráficos de dispersión.

![Mapa de Restaurantes](img/restaurantes_map.png)

### 🎙️ Conciertos y Eventos Públicos
- **Descripción:** Análisis de datos de eventos y conciertos para identificar patrones de asistencia y popularidad.
- **Procesos:** Limpieza de datos, análisis de sentimientos en reseñas de eventos y predicciones de asistencia.
- **Dataset:** Datos extraídos de plataformas de eventos y redes sociales.

![Análisis de Sentimientos](img/conciertos_sentimientos.png)

### 🎮 Análisis de Métricas de Valve
- **Descripción:** Estudio del comportamiento de los usuarios de juegos de Valve mediante análisis de reseñas y métricas de uso.
- **Procesos:** Extracción de datos de Steam, análisis de sentimientos en reseñas y visualización de patrones de juego.
- **Dataset:** [Steam Reviews (Kaggle)](https://www.kaggle.com/datasets/andrewmvd/steam-reviews)

![Gráficos de Métricas](img/valve_metricas.png)

## 🛠️ Herramientas Utilizadas

- **Python:** Lenguaje principal para el análisis de datos.
- **Jupyter Notebook:** Para la creación y ejecución de análisis interactivos.
- **Pandas y NumPy:** Manipulación y análisis de datos.
- **Matplotlib y Seaborn:** Visualización de datos.
- **Scikit-learn:** Modelado predictivo y análisis estadístico.
- **Power BI:** Visualización avanzada de datos para análisis de eventos deportivos.
- **APIs externas:** Para la recolección de datos en tiempo real.

## 🎥 Guía para Video de YouTube

1. **Introducción:** Breve descripción del proyecto y sus objetivos.
2. **Estructura del Repositorio:** Mostrar la organización de carpetas y explicar el propósito de cada una.
3. **Análisis de Datos:** Demostrar el proceso de carga de datos, análisis exploratorio y visualización de resultados.
4. **Dashboards en Power BI:** Explicar cómo se crearon los dashboards y qué información presentan.
5. **Conclusiones:** Resaltar los hallazgos más relevantes del análisis.
6. **Cierre:** Agradecimientos y llamado a la acción para visitar el repositorio en GitHub.

## 👥 Créditos

Proyecto realizado por estudiantes de la Escuela Politécnica Nacional:
- **D. Mejia** - Análisis de Eventos Deportivos (uso de Power BI)
- **E. Sarango** - Estudio de Actividades y Hobbies
- **S. Cumbal** - Evaluación de Restaurantes y Sitios
- **J. Guerra** - Análisis de Conciertos y Eventos Públicos
- **A. Ramos** - Análisis de Métricas de Valve
