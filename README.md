# AI News Automation to Notion
Pipeline de automatización que extrae noticias tecnológicas, las resume mediante el LLM **Gemini 1.5 Flash** y las clasifica automáticamente en una base de datos de **Notion**.

##  Tecnologías utilizadas
* **Python 3.x**
* **APIs:** NewsAPI, Google Gemini AI, Notion API.
* **Librerías:** `requests`, `google-generativeai`, `notion-client`.

## Cómo funciona
1. **Extracción:** Conexión con NewsAPI para obtener titulares de innovación.
2. **Procesamiento:** Uso de Ingeniería de Prompts con IA para generar resúmenes de 2 líneas.
3. **Carga (ETL):** Inserción automatizada en Notion mediante su API oficial.
