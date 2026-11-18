# EV-PRAC-01: Procesos y el Framework de IR

Práctica enfocada en la comprensión conceptual, definición, análisis, síntesis y producción de requisitos utilizando procesos y el framework de ingeniería de requisitos.

## 📍 Ruta del Repositorio
- **Ruta:** `ISR401-RIVASJORDY/tree/main/EV-PRAC-01`

## Estructura del Proyecto
- `main.tex`: Código fuente en LaTeX con la transcripción completa de la prueba y el anexo de evidencias.
- `main.pdf`: Documento compilado final.
- `evidencias/`: Carpeta que contiene las fotografías originales de la práctica (`hoja-01.jpg`, `hoja-02.jpg`, `hoja-03.jpg`, `hoja-04.jpg`).

## Información Técnica

### Compilador
- **pdflatex** (compatible con MiKTeX / TeX Live)

### Archivo Principal
- `main.tex`

### Dependencias / Paquetes de LaTeX utilizados
El documento requiere los siguientes paquetes estándar:
- `inputenc` (codificación UTF-8)
- `babel` (idioma español)
- `geometry` (configuración de márgenes y tamaño de página)
- `array` (personalización avanzada de tablas y anchos de columna)
- `amsmath` (entornos y símbolos matemáticos)

### Orden de Comandos para Compilar
Para compilar el documento de forma local desde la terminal, asegúrate de estar ubicado en la carpeta de la práctica y ejecuta los siguientes comandos en orden:

```bash
cd EV-PRAC-01
pdflatex main.tex
pdflatex main.tex  # Segunda pasada para consolidar tablas, referencias y anchos de columna
