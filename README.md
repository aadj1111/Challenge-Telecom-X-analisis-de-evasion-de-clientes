<h1 align="center"> Challenge Telecom X: Análisis de evasión de clientes </h1>

<p>
  
El siguiente proyecto, consiste en el análisis exploratorio y visual del fenómeno de *churn: caracterizado por la evasión de clientes,* mediante el uso de un dataset proporcionado por una empresa de telecomunicaciones llamada **Telecom X**.  
Para dicho análisis de datos, se emplean herramientas de Python, tales como: *pandas, matplotlib, seaborn y numpy.*
</p>

<h2> Objetivo del challenge </h2>
<p> 
  
  * Identificar factores que se relacionan con la cancelación de servicios por parte de los clientes.
  * Proponer estrategias de retención basadas en los hallazgos.
</p>

<h2> Contenido del proyecto </h2>
<p> 
  
  * Exploración general del dataset.
  * Limpieza y transformación de variables.
  * Análisis de correlaciones con la variable *churn*.
  * Visualización de patrones importantes.
  * Generación de nuevas variables.
  * Interpretación de resultados y propuesta de acción.
</p>

<h2> Tecnologías y librerías utilizadas </h2>
<p> 

<h2>Construido con 🛠️ </h2>
<p>
  
Lógica de programación: ![Python](https://img.shields.io/badge/logo-python-red?logo=python)

Entorno de desarrollo: Jupyter Notebook / Google Colab ![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=plastic&logo=google-colab&logoColor=white)

Bibliotecas principales:
* Pandas ![Pandas](https://img.shields.io/badge/-Pandas-150458?&logo=pandas) : procesamiento y análisis de datos, 
* Matplotlib ![Matplotlib](https://img.shields.io/badge/-Matplotlib-000000?style=flat&logo=python) : visualización,
* Numpy ![Matplotlib](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white) ,
* Seaborn ![Seaborn](https://img.shields.io/badge/-Seaborn-3776AB?style=flat&logo=python&logoColor=white&size=40x40) : visualizaciones y estadísticas avanzadas.
</p>

<h2> Dataset </h2>
<p> 
Incluye información sobre clientes de Telecom X, tales como:
  
  * Servicios contratados (internet, líneas múltiples, respaldo en línea, etc.).
  * Información demográfica (edad, tipo de contrato, género).
  * Información de facturación.
  * Tiempo de permanencia.
  * Variable objetivo: *churn* (1 = cliente que se fue, 0 = cliente que sigue).
</p> 

<h2> ¿Cómo ejecutar el análisis? </h2>
<p> 

1. Descarga y abre el archivo `.ipynb` en Google Colab o Jupyter Notebook.
2. Ingresa al drive y crea un cuaderno de Google Colab.
3. Conectate al entorno de programación.
4. Ejecuta el notebook desde la primera celda.
</p> 

<h2> Estructura del análisis </h2>
<p> 
<h3> 1. Carga y visualización inicial de datos </h3>
<h3> 2. Limpieza de datos </h3>
<h3> 3. Análisis exploratorio </h3>
<h3> 4. Creación de nuevas variables </h3>
<h3> 5. Visualización e interpretación </h3>
</p>

<h2> Análisis </h2>
<p> 

- Existe una correlación negativa moderada entre `customer_tenure` y `churn`, donde la tendencia es que los clientes nuevos abandonen.
- Los clientes que pagan más al mes tienen más probabilidad de irse.
- A mayor número de servicios contratados, más baja es la tasa de churn.
</p> 

<h2> Propuestas </h2>
<p> 
  
Una vez analizados los datos, se efectúa la siguiente propuesta:
  - Ofrecer bonificaciones o descuentos a clientes con cargos mensuales altos.
  - Implementar una estrategia de seguimiento para nuevos clientes.
  - Incentivar la contratación de más servicios como método de fidelización.
  - Segmentar campañas de retención enfocadas en clientes con pocos servicios activos o con baja antigüedad.
</p> 

<h2>Autor ✒️</h2>
Andrés Duque 
