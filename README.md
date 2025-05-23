

# Predicción con TensorFlow\.js

## Descripción

Esta plataforma permite entrenar un modelo simple de regresión lineal utilizando TensorFlow\.js, y luego hacer predicciones basadas en valores de entrada proporcionados por el usuario. Se incluye una gráfica que muestra la evolución de la pérdida (loss) durante el entrenamiento del modelo.

## Requisitos

* **Navegador web moderno** (para ejecutar el código JavaScript con TensorFlow\.js y Chart.js).
* **Conexión a Internet** para cargar las bibliotecas de TensorFlow\.js y Chart.js.

## Funcionalidades

1. **Entrenar el Modelo**:

   * Al hacer clic en el botón **"Entrenar Modelo"**, se entrena un modelo de regresión lineal que mapea los valores de entrada x a los valores de salida y según la fórmula y = 3x.
   * El modelo se entrena por 100 épocas y la gráfica de pérdida muestra cómo mejora el modelo con el tiempo.

2. **Hacer Predicciones**:

   * Después de entrenar el modelo, puedes ingresar valores x en el campo de texto.
   * Los valores deben estar separados por comas (por ejemplo: `10, 20, 25`).
   * Al hacer clic en el botón **"Predecir"**, el modelo generará las predicciones correspondientes para cada valor de x

3. **Visualización de la Pérdida**:

   * La plataforma muestra un gráfico que visualiza la **pérdida** durante el entrenamiento.
   * La pérdida indica qué tan lejos está el modelo de las predicciones correctas. Un valor más bajo indica un modelo mejor entrenado.

## Pasos para usar la plataforma

1. **Entrenar el Modelo**:

   * Haz clic en el botón **"Entrenar Modelo"**.
   * Espera a que el modelo se entrene completamente (esto puede tardar algunos segundos).
   * La gráfica de pérdida aparecerá debajo del botón y el estado cambiará a **"Modelo entrenado correctamente"**.

2. **Ingresar Valores para la Predicción**:

   * Ingresa un conjunto de valores de x (por ejemplo: `10, 20, 25`) en el campo de texto.
   * Haz clic en el botón **"Predecir"**.

3. **Ver Resultados**:

   * Los resultados de las predicciones aparecerán debajo del formulario de entrada, mostrando el valor de y correspondiente a cada x.

## Notas

* El botón **"Predecir"** solo estará habilitado después de que el modelo haya sido entrenado.
* Si intentas hacer una predicción antes de entrenar el modelo, aparecerá un mensaje de alerta indicando que el modelo debe ser entrenado primero.


