# Proyecto: Telecom X

Este proyecto tiene como objetivo investigar y detectar patrones asociados a la **evasión de clientes** en la empresa ficticia **Telecom X**. A través de un análisis exploratorio de datos (EDA), se busca identificar factores que influyen en el abandono del servicio, considerando variables como género, edad, tipo de contrato, servicios contratados, antigüedad, entre otros.

El análisis se apoya en visualizaciones estructuradas y comentarios detallados, lo que permite obtener **hallazgos claros y útiles** que pueden respaldar decisiones estratégicas del área de retención de clientes.

---

## Acceso al proyecto

El proyecto completo puede ser consultado directamente en este repositorio de GitHub:  
**[https://github.com/DanielRaiicHu/TelecomX](https://github.com/DanielRaiicHu/TelecomX)**

También se ha preparado un documento con el desarrollo detallado del análisis, el cual incluye comentarios, descripciones y la narrativa completa del proceso. Este documento se encuentra disponible en el siguiente enlace:  
**[Documento del proyecto - Google Docs](https://docs.google.com/document/d/186CAhCGVB2N7Hof8RCiZHcpigviXK2FL/edit?usp=sharing&ouid=108651758326944747752&rtpof=true&sd=true)**

---

## Ejecución del análisis

El archivo principal del proyecto es un notebook en formato `.ipynb`. Si bien el objetivo es la presentación del informe, cualquier persona interesada puede clonar este repositorio y ejecutar el análisis en Google Colab o en un entorno local compatible con Jupyter.

Para ello, puede copiar el contenido del notebook y pegarlo en Google Colab. Al hacerlo, se generarán automáticamente todas las visualizaciones desarrolladas durante el análisis, listas para ser interpretadas o exportadas.

---

## Estructura del proyecto

A continuación, se describen las secciones principales incluidas en el análisis:

### 1. Objetivo y archivo del proyecto
- Descripción del propósito del análisis y archivo base original.

### 2. Extracción de datos
- Lectura de los datos.
- Normalización de nombres de columnas.

### 3. Análisis y limpieza de datos
- Detección de valores inconsistentes.
- Decisiones sobre limpieza y tratamiento de datos.

### 4. Transformación de datos
- Conversión de columnas clave (`SeniorCitizen`, `Charges.Total`, `Churn`).
- Traducción de valores y columnas al español.
- Creación de nuevas variables (`CuentasDiarias`).
- Reset del índice y revisión de cambios.

### 5. Carga y análisis gráfico
- Revisión del DataFrame (duplicados, estructura).
- Separación de clientes que abandonan y que permanecen.
- Definición de colores institucionales para las visualizaciones.
- Desarrollo de análisis gráfico en torno a 7 temáticas principales:

#### Análisis gráfico de los datos:
1. Proporción de evasión de clientes  
2. Antigüedad vs evasión  
3. Distribución por género  
4. Adultos mayores  
5. Pareja y dependientes  
6. Tipo de contrato y servicios contratados  
7. Métodos de pago y cobros

---

## Exportación y reutilización de gráficos

Se incluyen funciones reutilizables para generar todos los gráficos de forma ordenada, facilitando su exportación y análisis independiente. Estas funciones están organizadas en grupos temáticos y fueron diseñadas para facilitar la presentación de resultados en informes o presentaciones ejecutivas.

---

## Archivos descargables

Se encuentra disponible un archivo comprimido `.zip` con todos los gráficos exportados del análisis, organizados y listos para utilizarse:  
**[Descargar gráficos y documento](https://github.com/DanielRaiicHu/TelecomX/raw/main/graficos.zip)**

> Este archivo también contiene una copia del documento en formato Word.

---

## Conclusión

Este proyecto es una muestra de análisis exploratorio aplicado al sector de telecomunicaciones, con un enfoque práctico y visual orientado a comprender mejor los factores que contribuyen a la pérdida de clientes. Puede servir como base para análisis más profundos o para integrar modelos predictivos en etapas posteriores.

---

## Autor

Daniel Aranzáez A.
