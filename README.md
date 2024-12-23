# Proyecto de Análisis de Imágenes Solares

## **Resumen:**
Este proyecto se centra en el desarrollo de un sistema flexible y robusto para la gestión y análisis de datos de observación solar utilizando **MongoDB** y archivos **FITS**. El objetivo principal es habilitar el almacenamiento, consulta y visualización eficiente de datos astronómicos estructurados y no estructurados. Con la integración de herramientas como **Astropy**, el sistema ofrece capacidades avanzadas para procesar y analizar imágenes solares y sus metadatos.

---

## **Características**
- **Almacenamiento de Datos**:
  - Utiliza **MongoDB** con GridFS para almacenar archivos FITS grandes y sus metadatos.
- **Consultas de Datos**:
  - Admite consultas avanzadas para filtrar imágenes por longitud de onda, rango de fechas y otros metadatos.
  - Implementa pipelines de agregación para análisis estadísticos.
- **Análisis de Datos**:
  - Extrae y analiza parámetros clave como temperatura del CCD, radio solar y longitudes de onda.
  - Proporciona funcionalidades para filtrar y visualizar estos parámetros.
- **Visualización**:
  - Genera gráficos dinámicos para parámetros de metadatos.
  - Muestra imágenes solares directamente desde archivos FITS.

---

## **Tecnologías Utilizadas**
- **MongoDB**:
  - Base de datos para gestionar y consultar metadatos.
  - GridFS para almacenar archivos FITS grandes.
- **Astropy**:
  - Para manejar y procesar archivos FITS.
- **Matplotlib**:
  - Para generar gráficos y visualizaciones.
- **Python**:
  - Lenguaje principal para el procesamiento e implementación del sistema.

---

## **Instalación**
Clonar el repositorio:
   ```bash
   git clone https://github.com/<user>/solar-image-analysis.git
   cd solar-image-analysis




