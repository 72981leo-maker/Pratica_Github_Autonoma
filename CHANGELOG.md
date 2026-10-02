# Changelog

Todos los cambios notables en este proyecto serán documentados en este archivo.

El formato está basado en [Keep a Changelog](https://keepachangelog.com/es-ES/1.1.0/) y este proyecto adhiere a [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [0.1.0] - 2026-10-01

### Añadido
* **Estructura base del proyecto:** Creación de la arquitectura inicial de directorios y archivos (`data/`, `docs/`, `main.py`).
* **Gestión de dependencias:** 
  * Configuración del entorno virtual (`.venv`).
  * Integración de la biblioteca `rich` para formateo visual en terminal.
  * Generación del archivo `requirements.txt`.
* **Control de versiones:** Archivo `.gitignore` configurado para ignorar archivos de entorno, caché y configuraciones locales (`.venv/`, `__pycache__/`, `.env`, `.vscode/`, entre otros).
* **Documentación:**
  * Archivo `README.md` con la descripción del proyecto, requisitos e instrucciones de instalación.
  * Archivo `docs/alcance.md` detallando la hoja de ruta y funcionalidades de la versión 2.0.
  * Incorporación de documentación adicional en `docs/criterios.md` y `docs/respuestas.md` para ampliar la guía de trabajo y las respuestas esperadas.
* **Datos iniciales:** Archivo `data/recursos.json` con registros de ejemplo para la clasificación de recursos académicos.