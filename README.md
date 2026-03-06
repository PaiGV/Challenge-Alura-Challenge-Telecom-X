📊 Proyecto: Análisis de Churn en Telecom X

Este proyecto forma parte del Challenge de Alura. El objetivo principal es analizar el comportamiento de los clientes de una empresa de telecomunicaciones para identificar los factores que influyen en la evasión (Churn) y proponer estrategias de retención.

📁 Estructura del Proyecto

* Limpieza de Datos: Transformación de un dataset JSON con estructuras anidadas a un formato tabular de 7,032 registros y 21 columnas.
* Ingeniería de Características: Creación de variables como Cuentas_Diarias y estandarización de categorías a formato binario (1 y 0).
* Análisis Exploratorio: Visualización de patrones de comportamiento mediante gráficos de distribución, cajas y densidad.

🔍 Hallazgos Principales

* Tasa de Abandono: Se identificó una evasión del 26.6%.
* Contratos Críticos: Los clientes con contratos mes a mes representan el mayor volumen de fugas.
* Riesgo por Antigüedad: La mayor probabilidad de abandono ocurre durante los primeros 12 meses de servicio.
* Sensibilidad al Precio: Existe una correlación entre cuotas mensuales altas (rango de $70 a $100) y el abandono del servicio.

🛠️ Tecnologías Utilizadas

* Python (Pandas, Numpy)
* Visualización: Matplotlib y Seaborn
* Entorno: Google Colab / Jupyter Notebook

📈 Conclusiones

El análisis sugiere que para reducir el churn, la empresa debe incentivar la migración a contratos anuales y reforzar la fidelización de clientes nuevos mediante el monitoreo de aquellos que pagan tarifas premium.
