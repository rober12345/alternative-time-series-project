<!-- hide -->
# Series temporales
<!-- endhide -->

- Comprender un dataset nuevo.
- Analizar la serie temporal y estudiar sus características.
- Entrenar un modelo para predecir el gasto de memoria a futuro.

## 🌱  Cómo iniciar este proyecto

Esta vez no se hará Fork, tómate un tiempo para leer estas instrucciones:

1. Crear un nuevo repositorio basado en el [proyecto de Machine Learing](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) [haciendo clic aquí](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Abre el repositorio creado recientemente en Codespace usando la [extensión del botón de Codespace](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository).
3. Una vez que el VSCode del Codespace haya terminado de abrirse, comienza tu proyecto siguiendo las instrucciones a continuación.

## 🚛 Cómo entregar este proyecto

Una vez que hayas terminado de resolver los ejercicios, asegúrate de confirmar tus cambios, hazle "push" al fork de tu repositorio y ve a 4Geeks.com para subir el enlace del repositorio.

## 📝 Instrucciones

### Sistema de detección de anomalías en el uso de la CPU

Queremos entrenar un sistema que sea capaz de predecir cuál puede ser el gasto computacional de la CPU de un ordenador en función de sus datos históricos. Para ello, hemos capturado algunos datos durante cada minuto varios días para tratar de entrenar un modelo.

#### Paso 1: Carga del conjunto de datos

El conjunto de datos ya está dividido en entrenamiento y prueba y se puede encontrar en esta carpeta de proyecto bajo los nombre `cpu-train.csv` y `cpu-test.csv`. Puedes cargarlos en el código directamente desde los enlaces (`https://raw.githubusercontent.com/4GeeksAcademy/alternative-time-series-project/main/cpu-train.csv` y `https://raw.githubusercontent.com/4GeeksAcademy/alternative-time-series-project/main/cpu-test.csv`) o descargarlo y añadirlo a mano en tu repositorio.

#### Paso 2: Construye y analiza la serie temporal

Construye la estructura de datos válida para la serie temporal, grafícala y, a continuación, analízala y responde a las siguientes preguntas:

- ¿Cuál es el tensor de la serie temporal?
- ¿Cuál es la tendencia?
- ¿Es estacionaria?
- ¿Existe variabilidad o presencia de ruido?

> NOTA: Un `tensor` en una serie temporal es la unidad de tiempo mínima para la cuál hay datos. Puede ser cada segundo, minuto, hora, día, semana, mes...

#### Paso 3: Entrena un ARIMA

Utiliza los datos de entrenamiento para encontrar la mejor parametrización de tu modelo ARIMA.

#### Paso 4: Predice con el conjunto de test

Ahora utiliza el modelo entrenado con el conjunto de prueba y compara los puntos con los reales. Mide el rendimiento de la serie temporal.

#### Paso 5: Guarda el modelo

Almacena el modelo en la carpeta correspondiente.

> NOTA: Solución: https://github.com/4GeeksAcademy/alternative-time-series-project/blob/main/solution.ipynb