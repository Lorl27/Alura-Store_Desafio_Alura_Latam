# Análisis de Desempeño de Tiendas - Cadena Alura Store

## Descripción
Este proyecto consiste en un análisis exhaustivo de las ventas, rendimiento y opiniones de clientes de las cuatro tiendas que forman la cadena Alura Store. El objetivo es ayudar al Sr. Juan a decidir cuál de estas tiendas debería vender para invertir en un nuevo emprendimiento.

---

## Objetivos

- Evaluar el desempeño de cada tienda a partir de cinco aspectos clave:  
  1. Ingresos totales por tienda.  
  2. Categorías de productos más y menos vendidas.  
  3. Calificaciones promedio de los clientes.  
  4. Productos más y menos vendidos.  
  5. Costo promedio de envío.

- Generar visualizaciones que permitan entender claramente el desempeño y tendencias de cada tienda.

- Formular una recomendación basada en el análisis de datos y visualizaciones, para que el Sr. Juan tome una decisión informada sobre qué tienda vender.

---

## Funcionalidades y Análisis Realizados

- **Cálculo de ingresos totales:** Suma de los precios de todos los productos vendidos en cada tienda.  
- **Conteo de ventas por categoría:** Identificación de las categorías de productos más populares en cada tienda.  
- **Calificación promedio:** Cálculo del promedio de las evaluaciones de los clientes para cada tienda.  
- **Identificación de productos más y menos vendidos:** Conteo de unidades vendidas por producto para detectar productos destacados y rezagados.  
- **Costo promedio de envío:** Análisis del gasto promedio en logística por tienda.

---

## Visualizaciones

Se generaron al menos tres gráficos distintos para complementar el análisis:

1. **Gráfico de barras** para comparar ingresos totales entre tiendas.  
2. **Gráfico circular (pie chart)** para mostrar la distribución de ventas por categoría en las tiendas.  
3. **Gráficos de barras horizontales** para visualizar productos más y menos vendidos por tienda.  
4. Adempas de otros gráficos para mostrar calificaciones promedio y costos de envío.

---

## Informe Final y Recomendación

Después de analizar los datos, se concluye que la tienda que debería ser vendida es **la Tienda 4**, ya que:

- Presenta el ingreso total más bajo en comparación con las otras tiendas.  
- Aunque tiene el costo promedio de envío más bajo, esto no compensa su bajo volumen de ventas.  
- La calificación promedio de sus clientes es media, sin destacarse.  
- Las categorías y productos no logran generar un volumen de ventas competitivo.

Vender esta tienda permitirá al Sr. Juan concentrar sus recursos en las tiendas con mayor rentabilidad y satisfacción de clientes, optimizando el potencial de la cadena Alura Store.

---

## Cómo ejecutar el análisis

1. Cargar los datos de las cuatro tiendas en formato DataFrame de pandas.  
2. Ejecutar las funciones para calcular ingresos, ventas por categoría, calificaciones, productos y costos de envío.  
3. Generar las visualizaciones correspondientes con matplotlib.  
4. Consultar el informe final para entender la recomendación.

---

## Requisitos

- Python 3.x  
- Pandas  
- Matplotlib  
- Jupyter Notebook o Google Colab (recomendado)
- Seaborn (Solo si planeas visualizar el Extra)

