**🚀 Predicción de Abandono de Clientes (Churn Prediction)**

Este proyecto nació con una pregunta clara: ¿Por qué se van nuestros clientes y cómo podemos saber quién será el siguiente? A través de un análisis de datos y el uso de Inteligencia Artificial, hemos creado un sistema que identifica los patrones de fuga y nos ayuda a tomar decisiones para retener a los usuarios antes de que digan adiós.



**📊 ¿Qué se hizo?**

Limpieza de Datos: Recibimos una base de datos con información de clientes (contratos, servicios, pagos). Limpiamos los valores vacíos y preparamos todo para que las computadoras pudieran entenderlo.
Análisis Visual: Creamos gráficos para entender la relación entre el dinero que pagan, el tiempo que llevan con nosotros y la decisión de cancelar el servicio.
Entrenamiento de Modelos: Pusimos a prueba dos "cerebros" digitales:
Regresión Logística: Excelente para entender qué factores "empujan" al cliente a irse.
Random Forest: Un modelo basado en árboles de decisión que es muy bueno encontrando patrones complejos.



**🧠 Resultados del Análisis**

Logramos una exactitud del 79%. Esto significa que el modelo es capaz de predecir correctamente el destino de casi 8 de cada 10 clientes.

**Las pistas más importantes:**

**El tipo de contrato:** Los clientes con contratos mes a mes son los más propensos a irse. No tienen "ataduras" y cualquier inconveniente los hace buscar otra opción.
La antigüedad (Tenure): Los primeros 6 meses son críticos. Si un cliente supera este periodo, su lealtad aumenta drásticamente.
**El factor económico:** El precio mensual es la variable que más ayuda a distinguir a un cliente que está a punto de cancelar.



**🛠️ Herramientas Utilizadas**

Python: El lenguaje de programación base.
Pandas & NumPy: Para el manejo y limpieza de las tablas de datos.
Seaborn & Matplotlib: Para crear las gráficas y mapas de calor.
Scikit-Learn: Para construir y evaluar los modelos de Inteligencia Artificial.



**📈 Conclusiones y Próximos Pasos**

Los datos nos dicen que para reducir el abandono debemos:
* Lanzar campañas de fidelización enfocadas exclusivamente en clientes nuevos (0 a 6 meses).
* Incentivar el cambio de contrato mensual a anual mediante descuentos, ya que esto asegura la permanencia.
* Revisar la competitividad de los precios en los servicios que presentan mayor tasa de fuga (como la Fibra Óptica).



**Cómo usar este proyecto**

Instala las librerías: pip install pandas scikit-learn seaborn matplotlib
Ejecuta el notebook principal para ver el análisis y las predicciones.
