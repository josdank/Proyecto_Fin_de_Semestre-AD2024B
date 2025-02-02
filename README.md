
# Proyecto de Análisis de Datos - Escuela Politécnica Nacional

Este repositorio contiene el proyecto final de análisis de datos realizado por los estudiantes de la Escuela Politécnica Nacional. A través de este proyecto, se aplican técnicas avanzadas para extraer conclusiones relevantes de una variedad de fuentes de datos, abordando diversos temas como deportes, hobbies, gastronomía, y más.

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
- [Enlaces a Videos](#enlaces-a-videos)
- [Créditos](#créditos)

## 📊 Descripción General

Este proyecto tiene como objetivo aplicar técnicas de análisis de datos para extraer información valiosa de diversas fuentes. Cada sección aborda un tema distinto, utilizando métodos de recolección, limpieza, visualización y análisis de datos. Se emplean técnicas estadísticas, de machine learning y análisis exploratorio para obtener conclusiones basadas en datos reales, lo que permite generar informes de valor práctico para los usuarios.

## 📁 Estructura del Proyecto

```
Proyecto_Fin_de_Semestre-AD2024B-main/
├── 1. Eventos_Deportivos-DMejia/
├── 2. Actividades_y_Hobbies-ESarango/
├── 3. Restaurantes_y_Sitios-SCumbal/
├── 4. Conciertos-y-Eventos_publicos-JGuerra/
└── 6. Analisis_metricas_Valve-ARamos/
```

Cada carpeta contiene notebooks de Jupyter, scripts en Python y archivos de datos utilizados para el análisis. Estos elementos se organizan para facilitar la ejecución y reproducibilidad de los experimentos realizados.

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

Este proyecto utiliza notebooks de Jupyter para:
- **Recolección de datos:** Desde APIs, archivos CSV, o scraping web.
- **Limpieza y preprocesamiento de datos:** Asegurando la calidad y precisión de los datos.
- **Análisis exploratorio de datos (EDA):** Identificación de patrones y tendencias.
- **Visualización de resultados:** Creación de gráficos interactivos y dashboards.

Para ejecutar los notebooks, usa:
```bash
jupyter notebook
```

## 🌐 Análisis por Secciones

### 🏀 Eventos Deportivos

**Descripción:**  
Análisis de las estadísticas de la NBA, evaluando el rendimiento de equipos y jugadores. Se utilizan datos históricos de partidos y estadísticas individuales para analizar tendencias y predecir resultados futuros.

**Procesos:**  
- Análisis de victorias y derrotas de equipos.
- Evaluación de la eficiencia de los jugadores mediante métricas avanzadas.
- Visualización de los resultados utilizando dashboards interactivos con Power BI.

**Herramientas:**  
- Power BI para visualización.
- Python para procesamiento y análisis de datos.

![Dashboard Power BI](https://via.placeholder.com/600x300.png?text=Ejemplo+de+Dashboard+Power+BI)

### 🌸 Actividades y Hobbies

**Descripción:**  
Estudio de las tendencias en actividades recreativas y hobbies populares. Se analiza la participación en diversas actividades, la frecuencia con que se realizan y las preferencias por región.

**Procesos:**  
- Análisis de encuestas de participación y preferencias.
- Identificación de tendencias en hobbies y actividades recreativas.

**Dataset:**  
[Sports and Outdoors (Kaggle)](https://www.kaggle.com/datasets/)

![Análisis de Actividades](https://via.placeholder.com/600x300.png?text=Ejemplo+de+Análisis+de+Actividades)

### 🍽️ Restaurantes y Sitios

**Descripción:**  
Evaluación de datos relacionados con restaurantes y su popularidad. Se analiza la calidad del servicio y las reseñas de los clientes para identificar patrones en la elección de restaurantes.

**Procesos:**  
- Recolección de datos de restaurantes y su calificación.
- Análisis de reseñas y patrones de consumo.
- Gráficos geoespaciales y dispersión de datos.

**Herramientas:**  
- Bases de datos SQL.
- Python y pandas para análisis.

![Mapa de Restaurantes](https://via.placeholder.com/600x300.png?text=Mapa+de+Restaurantes)

### 🎙️ Conciertos y Eventos Públicos

**Descripción:**  
Análisis de datos sobre conciertos y eventos públicos para identificar patrones de asistencia, popularidad y análisis de sentimientos a partir de reseñas.

**Procesos:**  
- Limpieza de datos.
- Análisis de sentimientos de reseñas de eventos.
- Predicción de asistencia a eventos futuros.

**Dataset:**  
- Datos extraídos de plataformas de eventos y redes sociales.

![Análisis de Sentimientos](https://via.placeholder.com/600x300.png?text=Análisis+de+Sentimientos)

### 🎮 Análisis de Métricas de Valve

**Descripción:**  
Estudio del comportamiento de los usuarios en los juegos de Valve, utilizando análisis de reseñas y métricas de uso en plataformas como Steam.

**Procesos:**  
- Extracción de datos de Steam.
- Análisis de las reseñas y patrones de uso de los juegos.
- Visualización de métricas clave de los jugadores.

**Dataset:**  
[Steam Reviews (Kaggle)](https://www.kaggle.com/datasets/andrewmvd/steam-reviews)

![Gráficos de Métricas](https://via.placeholder.com/600x300.png?text=Gráficos+de+Métricas)

## 🛠️ Herramientas Utilizadas

- **Python:** Lenguaje principal para la implementación de modelos y análisis de datos.
- **Jupyter Notebook:** Para la creación y ejecución de notebooks interactivos.
- **Pandas y NumPy:** Manipulación y análisis de datos.
- **Matplotlib y Seaborn:** Para la visualización de datos.
- **Scikit-learn:** Para la creación de modelos predictivos.
- **Power BI:** Para la visualización interactiva en eventos deportivos.
- **APIs externas:** Para la recolección de datos en tiempo real.

## 🎥 Enlaces a Videos

A continuación, se incluyen los enlaces a los videos explicativos de los análisis realizados en este proyecto:

- [Video 1: Análisis de Datos y Resultados](https://youtu.be/enlace1)
- [Video 2: Visualización de Resultados y Conclusiones](https://youtu.be/enlace2)

## 👥 Créditos

Este proyecto fue realizado por los siguientes estudiantes de la Escuela Politécnica Nacional:
- **D. Mejia** - Análisis de Eventos Deportivos (uso de Power BI)
- **E. Sarango** - Estudio de Actividades y Hobbies
- **S. Cumbal** - Evaluación de Restaurantes y Sitios
- **J. Guerra** - Análisis de Conciertos y Eventos Públicos
- **A. Ramos** - Análisis de Métricas de Valve
