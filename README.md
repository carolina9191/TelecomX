# TelecomX
challenge telecomX, análisis evasion de clientes

📌 Objetivo del Proyecto


El objetivo principal de este proyecto es recopilar, procesar y analizar datos relevantes utilizando Python y sus principales bibliotecas (como Pandas, NumPy y Matplotlib/Seaborn) para extraer información y patrones valiosos relacionados con la evasión de pagos.

La finalidad de este análisis es proporcionar una base sólida de conocimiento y insights al equipo de Data Science, que les permita posteriormente desarrollar modelos predictivos de evasión más precisos y diseñar estrategias efectivas para la reducción proactiva de este fenómeno, optimizando así la gestión de ingresos y la estabilidad financiera de la organización.

ANALISIS SEGUN ESPECIFICACIONES:
- Comprobacion de incoherencias en los datos.
- Manejo de Inconsistencias
- Columnas de Cuentas Bancarias
- Estandarizacion y Transformacion de datos.

  
📊 Ejemplos de Gráficos Generados en base a carga y analisis.

📌 Distribucion de evasion (grafico barras)


![grafico_evasion_barras](https://github.com/user-attachments/assets/6c96848b-5688-428c-aeda-40f5b618de71)

📌 Distribucion de evasion,proporcion. (gráfico, evasión pie)

![grafico_evasion_pie](https://github.com/user-attachments/assets/9640abc6-1ee1-42ab-b02e-f8a3b4102b12)

📌 Recuento de evasión segun variables categoricas.

![grafico_evasion_genero](https://github.com/user-attachments/assets/e9507f68-4dec-4083-992e-9865c71c5aed)

📌 Conteo de evasión por variables numéricas.

![grafico_evasion_edad](https://github.com/user-attachments/assets/8dae7303-5f0e-49d1-aa15-e7ad78073609)


📈 Hallazgos Principales

1. Proporción General de Evasión de Clientes
   
* La evasión es un problema significativo que afecta a más de una cuarta parte de la base de clientes (25.7%).

2. El "Tipo de Contrato" es un factor determinante en la tasa de evasión.
   
*Los contratos Mensuales son, con mucha diferencia, los más propensos a la evasión (41.3%), representando el mayor riesgo.
*Los contratos Bianuales son los más seguros, con una tasa de evasión mínima (2.8%).

3.El "Método de Pago" interactúa fuertemente con el tipo de contrato para influir en la evasión.

*El "Cheque Electrónico" es el método de pago de mayor riesgo, especialmente para contratos mensuales (¡51.91% de evasión!).
*Para los contratos mensuales, todos los métodos de pago presentan tasas de evasión elevadas, lo que resalta la necesidad de una atención especial en este segmento.
*Para los contratos anuales y bianuales, las tasas de evasión son generalmente bajas en todos los métodos de pago, lo que refuerza su menor riesgo inherente.

Implicaciones para el Equipo de Data Science y Estrategias para Reducir la Evasión:

*Foco en Contratos Mensuales: Cualquier estrategia para reducir la evasión debe priorizar los clientes con contratos mensuales. Aquí es donde se encuentra el mayor potencial de impacto.
*Monitoreo del Cheque Electrónico: Es imperativo investigar las razones detrás de la altísima tasa de evasión asociada al cheque electrónico, especialmente en contratos mensuales. Podría haber problemas técnicos, de comunicación o de proceso.
*Segmentación para Modelos Predictivos: Los modelos predictivos de evasión deben considerar el "Tipo de Contrato" y el "Método de Pago" como características clave. Se pueden desarrollar modelos específicos para clientes con contratos mensuales y aquellos que usan cheque electrónico, o bien incorporar interacciones entre estas variables.

3.Diseño de Estrategias:
*Para clientes mensuales: Implementar recordatorios de pago más frecuentes, opciones de pago automático, o incentivos por pago anticipado.
*Para el método de Cheque Electrónico: Revisar el proceso, mejorar la validación, o incluso considerar alternativas o restricciones si el problema es sistémico.
*Promover contratos Bianuales o Anuales: Si es posible, incentivar a los clientes a optar por tipos de contrato de mayor duración, ya que estos muestran una tasa de evasión significativamente menor.
