# Proyecto Alura Store: Análisis de Rendimiento de Tiendas

## 📋 Propósito del Análisis

El objetivo principal de este proyecto es analizar el rendimiento operativo y financiero de cuatro tiendas (`Tienda 1`, `Tienda 2`, `Tienda 3`, `Tienda 4`) para asesorar al Sr. Juan en la toma de decisiones estratégicas. Específicamente, se busca identificar la tienda que, por diversos factores (ingresos, costos operativos, satisfacción del cliente), sería la más adecuada para vender, optimizando así el portafolio de negocios del Sr. Juan.

El análisis se enfoca en las siguientes métricas clave:
- **Ingresos Totales y Mensuales**: Para entender la rentabilidad y tendencias de ventas.
- **Ventas por Categoría de Producto**: Para identificar el desempeño de diferentes tipos de productos.
- **Calificación Promedio del Cliente**: Para medir la satisfacción y calidad del servicio.
- **Costo de Envío Promedio**: Para evaluar la eficiencia logística y los gastos operativos.
- **Productos Más y Menos Vendidos**: Para entender la dinámica del inventario y la demanda.

## 📂 Estructura del Proyecto y Organización de Archivos

El proyecto se encuentra organizado en un único cuaderno de Jupyter (o Colab) que sigue una secuencia lógica de análisis:

1.  **Importación de datos**: Carga los datasets de cada una de las cuatro tiendas desde URLs de GitHub.
    *   `tienda.csv`
    *   `tienda2.csv`
    *   `tienda3.csv`
    *   `tienda4.csv`
2.  **Exploración de datos**: Realiza un primer vistazo a la estructura, tipos de datos y estadísticas descriptivas de cada dataset.
3.  **Análisis y Visualización de datos**: Esta sección está subdividida en varios puntos de análisis:
    *   Análisis de facturación (ingresos totales y mensuales)
    *   Ventas por categoría
    *   Calificación promedio de la tienda
    *   Productos más y menos vendidos
    *   Envío promedio por tienda
4.  **Informe Final: Recomendación de Tienda**: Sintetiza los hallazgos y presenta la recomendación estratégica al Sr. Juan.

Todas las visualizaciones y cálculos se realizan dentro del mismo cuaderno, utilizando bibliotecas como `pandas` para la manipulación de datos, y `matplotlib` y `seaborn` para la visualización.

## 📊 Ejemplos de Gráficos e Insights Obtenidos

### Ingreso Total por Tienda

Este gráfico de barras muestra los ingresos totales generados por cada tienda, destacando la `Tienda 1` como la de mayor facturación.

![Ingreso Total por Tienda](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/img/ingreso_total_por_tienda.png)

**Insight**: La `Tienda 1` es la que más ingresos brutos genera, seguida de cerca por la `Tienda 2`.

### Ventas Mensuales por Tienda

Estos gráficos de líneas ilustran la evolución de los ingresos mensuales para cada tienda a lo largo del tiempo, permitiendo observar tendencias y estacionalidades.

![Ventas Mensuales](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/img/ventas_mensuales_por_tienda.png)

**Insight**: Todas las tiendas muestran fluctuaciones en sus ventas mensuales, con algunos picos y valles a lo largo del periodo analizado. No se observa una tendencia de crecimiento constante en ninguna de ellas.

### Ventas por Categoría de Producto

Estos gráficos de barras muestran la distribución de ventas por categoría de producto para cada tienda, identificando las categorías más populares.

![Ventas por Categoría](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/img/ventas_por_categoria.png)

**Insight**: Las categorías de `Muebles` y `Electrónicos` son consistentemente las de mayor volumen de ventas en todas las tiendas, con la `Tienda 3` destacándose en `Muebles`.

### Calificación Promedio por Tienda

Este gráfico de barras compara la calificación promedio de los clientes para cada tienda, un indicador clave de satisfacción.

![Calificación Promedio por Tienda](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/img/calificacion_promedio_por_tienda.png)

**Insight**: La `Tienda 3` tiene la calificación promedio más alta (4.05), mientras que la `Tienda 1` registra la más baja (3.98), lo que sugiere posibles problemas de satisfacción del cliente en esta última.

### Productos Más y Menos Vendidos

Estos gráficos de barras muestran los productos individuales con mayor y menor cantidad de ventas en cada tienda.

![Productos Más y Menos Vendidos](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/img/productos_mas_y_menos_vendidos.png)

**Insight**: Los productos más y menos vendidos varían significativamente entre las tiendas, lo que podría indicar diferencias en el inventario o en las preferencias del mercado local.

### Costo de Envío Promedio por Tienda

Este gráfico de dispersión compara el costo promedio de envío para cada tienda, resaltando la eficiencia logística.

![Costo de Envío Promedio por Tienda](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/img/costo_envio_promedio_por_tienda.png)

**Insight**: La `Tienda 1` presenta el costo de envío promedio más alto, lo que, combinado con su calificación más baja, apunta a ineficiencias operativas que afectan la rentabilidad neta y la satisfacción del cliente.

## 💡 Recomendación Final

Basándose en el análisis integral, se recomienda al Sr. Juan **vender la `Tienda 1`**.

**Justificación**:
- **Altos Costos de Envío**: La `Tienda 1` tiene el costo de envío promedio más alto, lo que reduce su margen de ganancia real a pesar de sus altos ingresos brutos.
- **Baja Satisfacción del Cliente**: Su calificación promedio es la más baja entre las cuatro tiendas, indicando posibles problemas en el servicio o la calidad de la entrega que podrían afectar la reputación a largo plazo.
- **Oportunidad de Inversión**: Dada su alta facturación, la venta de la `Tienda 1` podría generar un capital significativo que el Sr. Juan podría reinvertir en las tiendas más eficientes (como la `Tienda 3`, que tiene la mejor calificación y costos de envío moderados) para potenciar su crecimiento y rentabilidad.

## 🚀 Instrucciones para Ejecutar el Notebook

Para ejecutar este cuaderno en Google Colab o un entorno Jupyter, sigue estos pasos:

1.  **Abrir el Cuaderno**: Sube el archivo `.ipynb` a Google Colab o ábrelo en tu entorno Jupyter local.
2.  **Ejecutar Celdas**: Ejecuta cada celda del cuaderno en orden secuencial. Puedes hacerlo seleccionando la celda y presionando `Shift + Enter` o utilizando la opción 'Ejecutar todas las celdas' en el menú.
3.  **Visualizar Resultados**: Los resultados, incluidos los dataframes y los gráficos, se mostrarán debajo de cada celda ejecutada.

**Requisitos (para entorno local)**:
- Python 3.x
- Pandas
- Matplotlib
- Seaborn

Estas librerías pueden instalarse usando `pip`:
```bash
pip install pandas matplotlib seaborn
