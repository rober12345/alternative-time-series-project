<!-- hide -->
# Tutorial de Proyecto de Series Temporales Alternativas
<!-- endhide -->

- Este proyecto le permitirá practicar sus nuevas habilidades para manejar el pronóstico de series de tiempo, mediante la creación de un modelo de detección de anomalías en el uso de la CPU.

## 🌱  Cómo iniciar este proyecto

1. Crea un nuevo repositorio basado en el [proyecto de machine learning](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) haciendo [clic aquí](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Abre el repositorio creado recientemente en Gitpod usando la [extensión del botón de Gitpod](https://www.gitpod.io/docs/browser-extension/).
3. Una vez que Gitpod VSCode haya terminado de abrir, comienza tu proyecto siguiendo las instrucciones a continuación.

## 🚛 Cómo entregar este proyecto

Una vez que hayas terminado de crear tu modelo de detección de anomalías, asegúrate de confirmar tus cambios, hazle push a tu repositorio y ve a 4Geeks.com para entregar y cargar el enlace de la aplicación web.

## 📝 Instrucciones 

**Detección de anomalías en el uso de la CPU**

Detección de anomalías significa identificar eventos inesperados en un proceso. Significa detectar amenazas a nuestros sistemas que pueden causar daño en términos de seguridad y fuga de información importante, pero la importancia de la detección de anomalías no se limita a la seguridad. Los datos de este proyecto se basan en métricas por minuto de la utilización de la CPU del host.

Enlaces de conjuntos de datos:

cpu-train-a: https://raw.githubusercontent.com/oreilly-mlsec/book-resources/master/chapter3/datasets/cpu-utilization/cpu-train-a.csv

cpu-train-b: https://raw.githubusercontent.com/oreilly-mlsec/book-resources/master/chapter3/datasets/cpu-utilization/cpu-train-b.csv

cpu-test-a: https://raw.githubusercontent.com/oreilly-mlsec/book-resources/master/chapter3/datasets/cpu-utilization/cpu-test-a.csv

cpu-test-b: https://raw.githubusercontent.com/oreilly-mlsec/book-resources/master/chapter3/datasets/cpu-utilization/cpu-test-b.csv

**Paso 1:**

En Machine Learning, el modelo ARIMA es generalmente una clase de modelos estadísticos que brindan resultados que dependen linealmente de sus valores anteriores en la combinación de factores estocásticos.

Necesitamos visualizar los datos para analizar las tendencias, las estacionalidades y los ciclos.

Comenzaremos importando las bibliotecas necesarias.

**Paso 2:**

Carga los conjuntos de datos.

**Paso 3:**

Usando matplotlib visualiza los datos.

**Paso 4:**

Utiliza el modelo ARIMA para ajustar los datos.

**Paso 5:**

Evalua el desempeño

**Paso 6:**

Ejecuta la predicción real utilizando los 100 puntos de datos observados más recientes seguidos de los 60 puntos predichos.

**Paso 7:**

Realicemos la misma detección de anomalías en otro segmento del conjunto de datos de uso de CPU capturado en un momento diferente mediante el uso de cpu-train-b

¿Puedes visualizar alguna anomalía que ocurra poco tiempo después del período de entrenamiento?

**Paso 8:**

Pon sus conclusiones en el archivo README como resumen. Y no olvides crear este modelo en tu archivo app.py.