# Análisis de Inventario y Ventas 2017 - Distribuidora de Productos para Bebé
Este proyecto analiza los inventarios y ventas de una empresa importadora y distribuidora de productos para bebé en los supermercados Olímpica a nivel nacional, durante el período de junio a septiembre de 2017.

**Objetivo**

Identificar la correlación entre inventario y ventas en diferentes ciudades y almacenes, con el fin de optimizar la distribución comercial y detectar patrones útiles para la toma de decisiones estratégicas.

**Descripción del Dataset**

Ventas: Datos por ciudad y por referencia.

Inventario: Información mensual por punto de venta.

Periodo de análisis: Junio - Septiembre 2017.

Formato: Archivos Excel procesados en Python.

**Herramientas Utilizadas**

Python
Pandas
Google Colab (para montar Google Drive)
Visualización con Matplotlib / Seaborn (si se usa más adelante)

**Variables Clave**

ventas_df: Datos de ventas.

final_stock_df: Inventario consolidado.

df_olimpicas_filtrado: Datos filtrados por ciudad.

df_data: Dataset combinado para análisis.

df_combinado: Unión entre ventas e inventario.

**Principales Procesos**

Lectura y limpieza de archivos Excel desde Google Drive.

Filtrado por columnas relevantes (NEGOCIO, REFERENCIA, CANTIDAD, MARCA...).

Combinación de archivos por mes, incluyendo la identificación temporal.

Agrupación por ciudad y referencias para analizar correlaciones.

Visualización de resultados (opcional, si está implementado en el notebook).

**Resultado Esperado**

Descubrir tendencias entre la cantidad de stock disponible y las unidades vendidas por ciudad y por producto, para implementar mejoras logísticas.

