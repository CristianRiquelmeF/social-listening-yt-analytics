# Termómetro Digital de Audiencias: Análisis de Sentimiento con IA

Herramienta de análisis de opinión pública diseñada para medios de comunicación, centrado en scraping desde Youtube.
Permite extraer, procesar y visualizar el sentimiento de la audiencia en tiempo real utilizando Inteligencia Artificial.

## Características
* **ETL Automatizado:** Extracción de comentarios de YouTube sin uso de API Keys (Scraping).
* **NLP Avanzado:** Uso de modelos Transformers (BERT) pre-entrenados en español para detección de sentimiento y confianza.
* **Data Cleaning:** Algoritmo de limpieza de métricas de interacción ("Likes" K/M).
* **Visualización:** Generación automática de dashboards de distribución y tablas de "Top Influencers".

## Stack Tecnológico
* **Lenguaje:** Python 3.10+
* **IA/ML:** `pysentimiento` (RoBERTa-BNE), `transformers`
* **Data:** `pandas`, `youtube-comment-downloader`
* **Viz:** `matplotlib`, `seaborn`

## Caso de Uso
Diseñado para equipos editoriales que requieren feedback inmediato post-emisión, superando la latencia de las encuestas tradicionales.


## Reporte de Impacto en Audiencia Digital 

* *Se observa la clasificación semántica (Positivo/Negativo/Neutro) realizada por el modelo BERT.*
<img width="1466" height="578" alt="Sin título" src="https://github.com/user-attachments/assets/e11c526e-d504-45f9-b313-6019cd7d340e" />

* *Identificación de comentarios con mayor validación social (Likes) y su nivel de confianza algorítmica.*
<img width="1348" height="480" alt="imagen" src="https://github.com/user-attachments/assets/86bbd49c-6ea7-445f-9a63-6f11ed2c40ed" />

> **Nota Metodológica:** La columna *Confianza* indica la seguridad del modelo (0-100%) al clasificar el texto, permitiendo filtrar opiniones ambiguas para el análisis editorial.

---
*Desarrollado por Cristian Riquelme F.*
