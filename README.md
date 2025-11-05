📊 Análisis Alura Store - Decision Estratégica de Ventas
# AluraStoreChallenge
Desarrollo de análisis con Python a través de Google Colab.

🎯 Propósito del Proyecto:

Este proyecto analiza el desempeño de 4 tiendas (tienda1, tienda2, tienda3, tienda4) para identificar cuál debe ser vendida, basándose en un análisis integral de 5 criterios clave establecidos por el señor Juan.

📋 Criterios de Análisis
- Facturación total por tienda
- Categorías más populares de productos
- Calificación promedio de clientes
- Productos más y menos vendidos
- Costo promedio de envío

⚙️ Instalación y Configuración
Prerrequisitos
- Python 3.7+
- Google Colab o Jupyter Notebook

Instalación de Dependencias
- pip install pandas matplotlib

Ejecución
1. Abrir analisis_alura_store.ipynb en Google Colab o Jupyter Notebook
2. Ejecutar las celdas en orden secuencial
3. Los datos se cargan automáticamente desde URLs públicas

📊 Metodología de Análisis
1. Exploración Inicial
- Estructura de datos y calidad
- Estadísticas descriptivas básicas
- Identificación de variables clave

2. Análisis por Criterio
- Facturación: Suma total de ingresos por tienda
- Categorías: Ventas por tipo de producto
- Satisfacción: Calificaciones promedio de clientes
- Productos: Top 5 más y menos vendidos
- Costos: Promedio de envíos por tienda

3. Visualización
- Gráfico de barras: Ranking de facturación
- Gráfico de barras agrupadas: Facturación vs Satisfacción
- Gráfico de líneas: Tendencias trimestrales

🎯 Resultados y Decisión
Recomendación Final: VENDER tienda4
Justificación:
- Menor facturación total ($1,038M vs $1,150M de tienda1)
- Costos de envío más bajos pero no compensan baja facturación
- Satisfacción media (4.00/5) sin ventajas competitivas
- Sin especialización distintiva en categorías o productos

📈 Hallazgos Clave
- tienda1: Mayor facturación pero menor satisfacción
- tienda2: Balance entre facturación y satisfacción
- tienda3: Mejor satisfacción pero facturación media
- tienda4: Menor facturación sin ventajas compensatorias

🛠️ Tecnologías Utilizadas
- Python 3.7+
- Pandas: Manipulación y análisis de datos
- Matplotlib: Visualizaciones y gráficos
- Google Colab: Entorno de ejecución

📁 Datos
Los datos se cargan automáticamente desde:
- 4 archivos CSV correspondientes a cada tienda
- Datos consolidados en un solo DataFrame
- Estructura: Productos, precios, envíos, fechas, calificaciones

🚀 Cómo Ejecutar
1. Abrir en Google Colab:
from google.colab import drive
drive.mount('/content/drive')
2. Ejecutar análisis completo:
- Ejecutar todas las celdas en orden
- Revisar resultados en consola y gráficos
- Leer informe final integrado

3. Resultados esperados:
- Análisis exploratorio completo
- 3 gráficos estratégicos
- Recomendación fundamentada

📝 Notas Técnicas
- Optimización: Variables globales reutilizables
- Mínimas dependencias: Solo pandas y matplotlib
- Código documentado: Comentarios explicativos
- Análisis reproducible: Mismos resultados en cada ejecución

🤝 Contribuciones:

Este proyecto fue desarrollado como parte del Challenge Alura Latam de Data Science.

📄 Licencia:

Proyecto educativo desarrollado para fines académicos.

Desarrollado como parte del Alura Latam Data Science Challenge 🚀
