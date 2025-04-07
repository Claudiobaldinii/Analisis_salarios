📊 Análisis de Salarios - Data Analytics & Data Science

Este proyecto corresponde a un Análisis Exploratorio de Datos (EDA) aplicado a un conjunto de datos salariales de profesionales del área de datos (Data Analytics y Data Science). El objetivo del EDA es comprender mejor la distribución de los salarios, identificar patrones por categorías como nivel de experiencia, tipo de jornada, modalidad de trabajo o tamaño de la empresa, así como observar la evolución salarial a lo largo de los años.

El análisis se realizó en Excel, donde se aplicaron procesos de limpieza, transformación y segmentación de los datos, para luego representar los resultados mediante un dashboard interactivo con filtros y gráficos dinámicos. Este tipo de análisis permite obtener insights clave para la toma de decisiones, además de servir como base para futuros análisis más profundos o modelos predictivos.

📁 Estructura del Proyecto
El análisis se realizó íntegramente en Microsoft Excel, desde la limpieza de datos hasta la creación de dashboards interactivos. La estructura del proyecto es la siguiente:

📁 Analisis_salarios/
├── datos_originales_convertidos_a_tabla.xlsx      # Datos en bruto (formato original convertido desde CSV)
├── Data_science_vs_data_analytics.xlsx            # Archivo principal con transformación de datos y dashboards
├── Data_science_salaries.csv                      # Archivo inicial recibido en CSV (delimitado por comas)
├── README.txt                                     # Documento explicativo del proyecto

🧹 Limpieza de Datos

Se agruparon puestos de trabajo similares en grandes grupos y nos centramos específicamente en dos grupos:

Data Analyst: Incluye títulos como Business Analyst, BI Analyst, Data Specialist, entre otros con funciones centradas en análisis de datos.

Data Scientist: Incluye roles como ML Engineer, AI Specialist, Research Scientist, etc., relacionados con ciencia de datos y machine learning.

Esta agrupación permitió simplificar el análisis y enfocar la comparación entre los dos perfiles principales del sector.

Se transformaron columnas como:

- Conversión de salarios a euros (agregando columna de tasa de cambio).
- Normalización de categorías (por ejemplo: niveles de experiencia).

Se filtraron los datos para centrarse exclusivamente en Estados Unidos debido a que la mayor cantidad de datos provienen de empresas de ese país, lo que podría afectar negativamente el promedio de salarios de otros países al no contar con una muestra representativa.

En la pestaña "Estadísticas principales", se observa que EE.UU. representa aproximadamente el 82% de los datos en ambos grupos, mientras que los demás países apenas superan el 2%. Por ello, se toma Estados Unidos como base del análisis para obtener resultados más realistas.

🔍 Análisis Realizado

Se analizaron los salarios en función de:

- Nivel de experiencia (junior, medio, senior, ejecutivo)
- Tipo de empleo (freelance, contrato, jornada completa, jornada parcial)
  *Nota:* En el dashboard no se incluyeron los empleos por contrato debido a la escasa muestra, ya que generaban valores atípicos que distorsionaban el promedio. Sin embargo, se dejó la opción para filtrarlos si se desea incluirlos.
- Modalidad de trabajo (presencial, híbrido, remoto)
- Tamaño de la empresa (menos de 50, 50–250, más de 250 empleados)
- Año (2020 a 2024)

📊 Visualizaciones

Se crearon dos dashboards interactivos en Excel:

🟦 Data Analytics
- Promedio salarial: 112.920 €
- Salario mínimo: 18.600 €
- Salario máximo: 651.000 €

🟨 Data Science
- Promedio salarial: 157.502 €
- Salario mínimo: 18.600 €
- Salario máximo: 697.500 €

Cada dashboard incluye gráficos de barras y líneas para visualizar la evolución y distribución de salarios según los factores mencionados anteriormente.

Además, se incorporaron dos macros para alternar entre Data Science y Data Analytics de manera rápida.

Los datos se incluyen en la pestaña "Estadísticas principales", donde también se calcula la mediana para observar su relación con el promedio. En este caso, como no hay gran diferencia entre ambos, se utiliza el promedio como referencia. También se incluye un boxplot para visualizar valores atípicos que, aunque alejados del promedio, se mantienen en el análisis por ser datos reales.

Se analizaron también las variaciones, ya que múltiples factores pueden generar brechas salariales importantes, lo que permite identificar oportunidades o anomalías.

💡 Conclusiones

- Los profesionales en Data Science presentan un salario promedio mayor que los de Data Analytics en todos los niveles de experiencia.
- Las modalidades de trabajo en sitio y remoto tienden a tener mayores salarios que las híbridas.
- Las empresas grandes (más de 250 empleados) ofrecen los mejores salarios, especialmente en roles científicos de datos. La mayor diferencia se observa frente a empresas con menos de 50 empleados, donde los salarios son significativamente menores.
- Los contratos de jornada completa son los mejor remunerados frente a freelance o jornada parcial.
- El nivel de experiencia influye considerablemente en el salario, incrementándose en cada tramo.
- Podemos ver cómo en Data Analytics el salario presenta incrementos significativos año tras año hasta estabilizarse en 2022–2023, con una ligera baja en 2024. En cambio, en Data Science los salarios fueron más altos en 2020, pero disminuyeron después de forma notable, lo que podría ser objeto de análisis futuro.

Este análisis exploratorio permite entender mejor las dinámicas salariales del sector de datos y puede ser útil tanto para profesionales que buscan posicionarse mejor en el mercado como para empresas que deseen ajustar sus políticas de compensación.

✅ Recomendaciones

Todas las recomendaciones y ayudas serán bienvenidas para que este análisis pueda seguir evolucionando y sea mas completo.
