# Wizarding Academy Hub

Wizarding Academy Hub es un sistema de gestión académica desarrollado con Flask, diseñado para administrar estudiantes, profesores, cursos y el registro de calificaciones de manera eficiente. La aplicación ofrece una interfaz moderna, responsiva y profesional, optimizada para su uso en diversos dispositivos.

## Funcionalidades Principales

El sistema integra las siguientes capacidades operativas:

- Gestión completa de estudiantes y profesores (CRUD).
- Clasificación de cursos por categorías académicas.
- Registro y actualización de matrículas y calificaciones.
- Generación automatizada de certificados académicos en formato PDF.
- Interfaz de búsqueda dinámica para la recuperación rápida de información.

## Requisitos del Sistema

Para la ejecución del proyecto, se requiere contar con los siguientes componentes:

- Python 3.10 o superior.
- Flask y dependencias listadas en el archivo de requerimientos.
- SQLite para la persistencia de datos.

## Instalación y Configuración

Siga estos pasos para desplegar el entorno de desarrollo:

1. Clone el repositorio en su máquina local.
2. Configure un entorno virtual de Python.
3. Instale las dependencias necesarias: `pip install -r requirements.txt`.
4. Ejecute la aplicación mediante el comando: `python run.py`.

El servidor se iniciará de forma predeterminada en `http://127.0.0.1:5000`.

## Estructura del Proyecto

La arquitectura del proyecto sigue las mejores prácticas de Flask:

- `/app`: Directorio principal de la aplicación.
- `/app/templates`: Plantillas HTML procesadas con Jinja2.
- `/app/static`: Recursos estáticos (CSS, Imágenes, PDFs).
- `run.py`: Punto de entrada del servidor.

## Tecnologías Utilizadas

- **Backend**: Flask (Python).
- **Frontend**: HTML5, CSS3 (Custom Grid/Flexbox), JavaScript (jQuery para AJAX).
- **Base de Datos**: SQLite3.
- **Generación de Reportes**: ReportLab.

Esta plataforma ha sido diseñada con un enfoque en la mantenibilidad y la escalabilidad, asegurando una base técnica sólida para futuras expansiones académicas.

---
**Desarrollado por Enmanuel Fuenmayor 2024**
