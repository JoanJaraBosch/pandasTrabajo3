# Trabajo 3: Análisis de datos con Numpy y Pandas

Este proyecto tiene como objetivo analizar los datos de ventas, inventarios y satisfacción del cliente de una cadena de tiendas minoristas. Para ello se utilizan las librerías **Pandas** para la manipulación y análisis de datos, y **Numpy** para realizar cálculos estadísticos y simulaciones. El fin es ayudar a optimizar el rendimiento de las tiendas a partir del análisis de esta información.

---

## Objetivos del proyecto

1. **Carga y manejo de datos con Pandas**
   - Cargar los datos desde los archivos CSV (`ventas.csv`, `inventarios.csv`, `satisfaccion.csv`) en DataFrames.
   - Limpiar los datos eliminando filas con valores nulos.
   - Verificar que los DataFrames tengan la estructura correcta para el análisis.

2. **Análisis de datos con Pandas**
   - Calcular ventas totales, rotación de inventarios y niveles de satisfacción por tienda.
   - Filtrar tiendas con inventarios críticos (menos del 10%) y baja satisfacción (menos del 60%).

3. **Cálculos estadísticos con Numpy**
   - Calcular la mediana y desviación estándar de las ventas totales usando Numpy.

4. **Simulación de datos con Numpy**
   - Simular proyecciones futuras de ventas usando arrays aleatorios.
   - Calcular estadísticas básicas sobre estas simulaciones.

---

## Requisitos

- Lenguaje: Python.
- Librerías: Pandas y Numpy.
- Entorno: Visual Studio Code con plugin Jupyter.
- Archivos CSV ubicados en:
  - `/workspace/ventas.csv`
  - `/workspace/inventarios.csv`
  - `/workspace/satisfaccion.csv`

---

## Estructura del proyecto

### 1. Preparar el entorno
- Crear un archivo Jupyter Notebook llamado `analisis_red_tiendas.ipynb`.
- Importar las librerías Pandas y Numpy.

### 2. Cargar y limpiar los datos
- Leer los archivos CSV en tres DataFrames.
- Eliminar filas con valores nulos usando `dropna()`.
- Asegurar que los datos estén listos para análisis.

### 3. Exploración y análisis con Pandas
- Calcular ventas totales por producto y por tienda.
- Calcular ingresos totales por tienda.
- Generar resumen estadístico de ventas.
- Agrupar y calcular ventas por categoría y tienda.
- Calcular rotación de inventarios y agregar columna en DataFrame.
- Filtrar tiendas con inventarios críticos (< 10%).
- Analizar satisfacción del cliente y filtrar tiendas con satisfacción < 60%.

### 4. Cálculos numéricos con Numpy
- Convertir columna de ventas totales a array de Numpy.
- Calcular mediana y desviación estándar.
- Generar simulaciones de ventas futuras con arrays aleatorios.
- Usar semilla para resultados reproducibles.

---

## Resultados esperados

- DataFrames limpios y listos para análisis.
- Informes de ventas, inventarios y satisfacción.
- Estadísticas descriptivas y simulaciones que apoyen decisiones estratégicas.
- Código organizado y comentado, documentado en el notebook.

---

## Contexto empresarial

RetailNow es una cadena de tiendas minoristas que busca optimizar su rendimiento a través del análisis de sus datos de ventas, inventarios y satisfacción de clientes. Este proyecto contribuye a identificar áreas críticas y oportunidades de mejora mediante técnicas de análisis de datos y simulación.
"""

path = "/mnt/data/README.md"
with open(path, "w", encoding="utf-8") as f:
    f.write(readme_content)
path
