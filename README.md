# Análisis de Eficiencia Operativa en Telecomunicaciones

### Descripción del Proyecto
En este proyecto, trabajé como parte del equipo de análisis de datos de una empresa ficticia de telecomunicaciones llamada CallMeMaybe, cuyo objetivo era desarrollar una funcionalidad que permitiera a los supervisores identificar a los operadores más y menos eficaces. El análisis se centró en la eficiencia operativa de los operadores de atención telefónica, considerando múltiples métricas clave como el número de llamadas perdidas, el tiempo de espera de los usuarios y la cantidad de llamadas salientes realizadas.

### Objetivos
* Identificar operadores ineficientes a través de indicadores clave como:
    * Número de llamadas entrantes perdidas (con o sin tiempo de espera del usuario).
    * Duración promedio de espera por parte de los usuarios.
    * Bajo volumen de llamadas salientes.

* Probar hipótesis estadísticas para evaluar si existen diferencias significativas en los tiempos de espera según el plan tarifario de los usuarios.

### Metodología
Para llevar a cabo este proyecto utilicé Python como herramienta principal para el procesamiento y análisis de datos. Las etapas incluyeron:

   * Análisis exploratorio de datos: limpieza de valores nulos, identificación de duplicados, análisis de distribución y creación de nuevas métricas.
   *  Definición de métricas de ineficiencia: establecí umbrales para definir cuándo un operador debía ser considerado ineficaz.
   * Análisis estadístico: utilicé pruebas como Shapiro-Wilk, Levene y Mann-Whitney para verificar la normalidad, homogeneidad de varianzas y diferencias significativas entre grupos.
   * Visualización de datos: se desarrollaron gráficos interactivos con Tableau y Plotly para mostrar el comportamiento de los operadores y el tiempo de espera según el plan tarifario.

### Conclusiones
* Se identificó que 17 operadores ineficientes que incumplían en todos los criterios establecidos (más de 3 llamadas perdidas, llamadas perdidas con tiempo de espera, menos de 60 llamadas salientes).
* Se evidenció que los usuarios con el plan A experimentan significativamente más tiempo de espera en comparación con los de los planes B y C.
* Se encontró que algunos operadores dejaron a los usuarios en espera por más de 45,000 segundos, lo cual es alarmante.
* Las diferencias entre los grupos tarifarios fueron estadísticamente significativas en cuanto al tiempo de espera, lo que sugiere un trato desigual que podría deberse a priorización operativa o gestión de recursos.

### Lenguajes y Herramientas Utilizadas
Python (Pandas, NumPy, Seaborn, Plotly, SciPy, StatsModels)

### Tableau para visualización de KPIs
https://public.tableau.com/app/profile/angel.hernandez.sosa/viz/Proyectofinal14_17490762916930/Dashboard1?publish=yes

### Jupyter Notebook para la documentación del flujo de trabajo

Este análisis ofrece una base sólida para la toma de decisiones estratégicas orientadas a la mejora del desempeño de los operadores, la experiencia del usuario y la optimización del servicio en el sector de telecomunicaciones.
