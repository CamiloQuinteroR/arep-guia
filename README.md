# Guía de contenidos del repositorio

**Autor:** Camilo Andrés Quintero Rodriguez

Este repositorio contiene los cuadernos (notebooks) de Jupyter que son tutoriales desarrollados en clase para trabajar con APIs de IA, LangChain y Hugging Face. Debajo se describe brevemente cada archivo principal para facilitar su uso y navegación.

## Notebooks y descripción

- **`Guia3_IntroAPIsAI_Notebook.ipynb`**: Introducción a las APIs de Inteligencia Artificial. Contiene explicaciones y ejemplos básicos para consumir servicios de IA vía APIs (autenticación, endpoints, formatos de petición/respuesta). 

- **`Guia4_Introduccion_LangChain_OpenAI.ipynb`**: Guía práctica sobre LangChain y su integración con OpenAI. Incluye ejemplos de cadenas de herramientas (chains), prompt engineering y cómo orquestar llamadas a modelos para tareas de generación y QA. 

- **`Guia5_HuggingFace_Intro.ipynb`**: Guía práctica para entender el ecosistema de Hugging Face. Contiene secciones sobre instalación, uso de `transformers`, `datasets`, tokenización, pipelines, embeddings y la Inference API. 

- **`hello_ai.ipynb`**: Notebook de ejemplo minimalista para saludar y probar una primera inferencia con un modelo o pipeline sencillo. 

- **`setup_hello_ai.ipynb`**: Notebook orientado a la configuración del entorno (instalación de dependencias, comprobación de versiones, configuración de tokens y caches).

- **`Tutorial LangChain LLM.ipynb`**: Tutorial más extenso sobre LangChain aplicado a modelos de lenguaje (LLMs). 


## Guía de instalación del entorno virtual

Creamos y activamos un entorno virtual en Windows desde consola:

- 1) Crear el entorno virtual (desde la raíz del proyecto):

```bash
python -m venv .venv
```

- 2) Activar el entorno virtual:


```bash
source .venv/bin/activate
```

