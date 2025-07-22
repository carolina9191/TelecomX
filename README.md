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
Análisis grafico 1

El gráfico muestra el número de clientes masculinos y femeninos, desglosado por si se dieron de baja ("Yes") o no ("No").

Clientes Femeninos: Hay 2.549 clientas que no se dieron de baja y 939 clientas que sí lo hicieron.

Clientes Masculinos: Hay 2.625 clientes masculinos que no se dieron de baja y 930 clientes masculinos que sí lo hicieron.

En resumen, el número de clientes que se dieron de baja es muy similar entre géneros (939 mujeres vs. 930 hombres), lo que sugiere que el género no parece ser un factor significativo para predecir la fuga de clientes basándose en estos datos. Ambos géneros tienen un número considerable de clientes que no se dieron de baja en comparación con los que sí lo hicieron.



<img width="688" height="525" alt="newplot" src="https://github.com/user-attachments/assets/56dfd30b-4f19-4413-8a4b-26d2f6fca7cb" />



