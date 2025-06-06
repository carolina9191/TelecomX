# TelecomX, alura Latam
challenge telecomX, análisis evasión de clientes

📌 El objetivo general de estas etapas es comprender y predecir la "evasión" de clientes (también conocida como "churn" o fuga de clientes), utilizando un enfoque estructurado de análisis de datos.

✅ Preparación y Exploración de Datos
El propósito de esta fase es obtener una primera visión de los datos y prepararlos para el análisis, asegurándose de que estén en un formato utilizable y que se comprenda su contenido.

✅ Carga de Datos (Importación directa de la API a Python): El objetivo es acceder a la información de los clientes directamente desde su fuente original (una API), lo cual garantiza que se esté trabajando con los datos más recientes y se automatiza el proceso de adquisición.
Conversión a DataFrame (Datos estructurados en Pandas para fácil manipulación): Se busca organizar los datos de la API en una estructura de tabla (DataFrame de Pandas), que es el formato estándar en Python para el análisis de datos. Esto facilita la selección, filtrado y modificación de la información.

✅ Exploración Inicial (Revisión de columnas y tipos de datos): El propósito es realizar una inspección rápida para entender qué información está disponible (nombres de columnas) y cómo está representada (tipos de datos, como números, texto o fechas). Esto ayuda a identificar posibles problemas o necesidades de limpieza desde el principio.

✅ Diccionario de Variables (Comprensión del significado de cada campo): Se busca documentar qué representa cada columna o campo de datos. Esto es crucial para interpretar correctamente los resultados del análisis y asegurar que todos los involucrados en el proyecto comprendan el significado de la información.

✅ Columnas Relevantes (Identificación de variables clave para el análisis de evasión): El objetivo es determinar cuáles de las columnas disponibles son más importantes para entender por qué los clientes se van o se quedan. Esto ayuda a enfocar el análisis en la información más pertinente, evitando distracciones y optimizando el tiempo.

✅ Limpieza y Transformación de Datos
El propósito de esta fase es mejorar la calidad y el formato de los datos para que sean precisos, consistentes y adecuados para el análisis, lo que permite obtener resultados fiables.

✅ Verificación de Calidad (Detección de valores ausentes, duplicados, errores de formato e inconsistencias): Se busca identificar y diagnosticar problemas en los datos que podrían afectar la precisión del análisis, como información faltante, registros repetidos, o datos en formatos incorrectos.

✅ Corrección de Inconsistencias (Ajuste y estandarización de los datos): El objetivo es resolver los problemas de calidad detectados, por ejemplo, rellenando valores ausentes, eliminando duplicados o corrigiendo formatos. Esto asegura que los datos sean consistentes y confiables.

✅ Creación de 'Cuentas_Diarias' (Cálculo de facturación diaria a partir de la mensual): Se busca derivar una nueva variable ('Cuentas_Diarias') a partir de datos existentes. Esto es una transformación importante que puede ser más relevante para el análisis de patrones de comportamiento del cliente que la facturación mensual.

✅ Estandarización Opcional (Conversión de valores textuales (Sí/No) a binarios (1/0) y traducción de columnas/datos para mayor claridad y facilidad de análisis): El propósito es preparar los datos para algoritmos de análisis que a menudo requieren formatos numéricos (como 1s y 0s para variables categóricas) y mejorar la legibilidad del conjunto de datos al traducir nombres de columnas o valores si es necesario.

👨‍🏫 Análisis Descriptivo y de Evasión

✅ El propósito de esta fase es entender las características principales de la base de clientes y los factores que influyen en la evasión, utilizando estadísticas y visualizaciones.

👨‍🏫 Análisis Descriptivo General (Cálculo de métricas básicas (media, mediana, desviación estándar) para entender la distribución de los datos): El objetivo es obtener un resumen estadístico de las variables numéricas para comprender su tendencia central, dispersión y forma, lo que proporciona una visión general del conjunto de datos.

✅Distribución de 'Churn' (Evasión) (Visualización de la proporción de clientes que permanecieron vs. los que se dieron de baja): Se busca cuantificar y visualizar cuántos clientes se han "evadido" (dado de baja) en comparación con los que se han quedado. Esta es la métrica central del análisis de evasión y su comprensión es fundamental.

✅Evasión por Variables Categóricas (Análisis de patrones de evasión según género, tipo de contrato, método de pago, etc.): El propósito es identificar si hay diferencias significativas en las tasas de evasión entre diferentes categorías de clientes (por ejemplo, si los clientes con un tipo de contrato específico son más propensos a irse). Las variables categóricas son aquellas que representan grupos o categorías (como "género" con valores "masculino" o "femenino", o "método de pago" con "tarjeta", "transferencia", etc.).

✅Evasión por Variables Numéricas (Exploración de la relación entre la evasión y variables como el gasto total o el tiempo de contrato): El objetivo es investigar si existe una relación entre la evasión y variables cuantitativas (números) como el dinero que gastan los clientes o cuánto tiempo han estado con el servicio. Por ejemplo, ¿los clientes que gastan menos o tienen contratos más cortos son más propensos a irse?

En resumen, todas estas etapas buscan construir una base sólida de datos limpios y comprensibles para luego realizar un análisis profundo que revele las causas y los patrones de la evasión de clientes, lo que permitirá a la empresa desarrollar estrategias efectivas de retención.



📌  ![grafico_churn](https://github.com/user-attachments/assets/9f878d65-3c8d-4af4-aaf3-d2f7cd462856)

📌  ![recuento_por_evasion](https://github.com/user-attachments/assets/a9840723-917f-445e-9e0d-abf467c0afde)


🛠️ Herramientas y Librerías Utilizadas

El análisis se llevó a cabo utilizando el entorno de Python, con las siguientes librerías principales:

pandas: Para la manipulación y el procesamiento de datos.
numpy: Para operaciones numéricas eficientes.
matplotlib: Para la creación de gráficos y visualizaciones estáticas.
seaborn: Para la creación de visualizaciones estadísticas atractivas y complejas.

📌 Fuente de datos : 'https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/refs/heads/main/TelecomX_Data.json'

