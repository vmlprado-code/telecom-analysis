# telecom-analysis
📊 Descripción del Proyecto

Este proyecto realiza un análisis exhaustivo del comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones en Latinoamérica. El objetivo es evaluar patrones de consumo, identificar segmentos de clientes y diseñar estrategias de retención basadas en datos.

Periodo de análisis: Datos registrados hasta el año 2024

🎯 Objetivos Principales

✅ Explorar y limpiar los datos de clientes, planes y uso de servicios

✅ Construir perfiles estadísticos detallados de los clientes

✅ Detectar comportamientos atípicos y patrones de consumo

✅ Segmentar clientes según su perfil y uso

✅ Diseñar estrategias de retención personalizadas

✅ Sugerir mejoras en los planes ofrecidos

Conjuntos de datos

El proyecto utiliza tres DataFrames:

-plans: Información de los planes disponibles (Básico y Premium).
-users: Información demográfica y características de los clientes.
-usage: Historial de consumo de los usuarios entre 2022 y 2026 (aproximadamente 40,000 registros). Para este análisis únicamente se consideró el periodo correspondiente al año 2024.

Tecnologías utilizadas
Python 3
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

Proceso de análisis
Limpieza de datos

Se realizaron las siguientes actividades:

Conversión de tipos de datos.
Filtrado de registros correspondientes únicamente al año 2024.
Tratamiento de valores nulos.
Corrección del valor centinela -999 en la variable age.
Detección y tratamiento de valores atípicos mediante el método del Rango Intercuartílico (IQR).
Estandarización de variables para garantizar la consistencia del análisis.

Análisis exploratorio (EDA)

Durante el análisis se realizaron:

Distribución de clientes por plan.
Segmentación por grupos de edad:
Joven (<30 años)
Adulto (30–59 años)
Adulto Mayor (≥60 años)
Clasificación del nivel de uso (Bajo, Medio y Alto).
Comparación del comportamiento de consumo entre planes.
Visualización mediante histogramas, diagramas de caja y gráficos de barras.

Principales hallazgos:

El plan Básico es el producto con mayor número de clientes en todos los segmentos de edad y niveles de uso.
La categoría de uso medio concentra la mayor parte de los usuarios durante 2024.
Dentro del nivel de uso medio, aproximadamente 1,800 clientes pertenecen al plan Básico, mientras que cerca de 1,000 usuarios utilizan el plan Premium.
El segmento de adultos (30 a 59 años) representa la mayor proporción de la cartera de clientes y concentra principalmente usuarios con niveles de consumo bajo y medio.
Los usuarios menores de 60 años con uso medio del plan Básico constituyen la base más sólida de clientes de Connecta Tel.

Recomendaciones:

Utilizar el plan Básico como producto de entrada para atraer nuevos clientes, ya que presenta la mayor aceptación en todos los segmentos analizados.
Implementar estrategias de upselling para migrar clientes del plan Básico hacia el plan Premium o servicios adicionales de mayor valor.
Diseñar campañas específicas para usuarios con uso medio, debido a que representan el segmento más numeroso y con mayor potencial de crecimiento.
Desarrollar programas de fidelización dirigidos a los clientes menores de 60 años del plan Básico para fortalecer la retención y aumentar el valor del cliente a largo plazo.

Estructura del proyecto

├── S7 Version-Estudiante-Project-ConnectaTel.ipynb

├── README.md

Conclusión

El análisis permitió identificar que el plan Básico constituye el principal motor de captación y permanencia de clientes en Connecta Tel. Asimismo, se observó que los usuarios con nivel de uso medio representan el segmento más importante de la cartera, especialmente aquellos menores de 60 años. Estos hallazgos ofrecen una base sólida para diseñar estrategias de adquisición, fidelización y crecimiento de ingresos mediante la promoción de planes y servicios de mayor valor.
