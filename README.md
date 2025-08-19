# 📉 Análisis y Predicción de Churn en Clientes de TELECOM_X

## 📝 Descripción del Proyecto
Este proyecto de ciencia de datos se enfoca en la **predicción del abandono de clientes (`churn`)** de una empresa de TELECOM_X. El objetivo principal es identificar a los clientes con alto riesgo de irse para implementar estrategias de retención. Se construyeron y evaluaron varios modelos de *machine learning* para encontrar el que mejor se adaptara al problema, priorizando el `recall` sobre la `precisión`.

### 🚀 ¿Qué se hizo?
* **Análisis Exploratorio de Datos (EDA):** Se exploró la relación entre las variables de los clientes y el `churn`.
* **Preprocesamiento:** Se aplicaron transformaciones a los datos, como `OneHotEncoding` para variables categóricas y `StandardScaler` para las numéricas.
* **Balanceo de Clases:** Se utilizó la técnica de **oversampling con SMOTE** para abordar el desbalance de clases en la variable objetivo (`churn`).
* **Modelado y Evaluación:** Se entrenaron y compararon tres modelos principales:
    * **Random Forest** (optimizado y sin optimizar)
    * **Árbol de Decisión** (optimizado)
    * **K-Vecinos Más Cercanos (KNN)** (optimizado)
* **Validación Cruzada y Optimización:** Se utilizó `StratifiedKFold` para una evaluación robusta y `GridSearchCV` para la optimización de hiperparámetros.
* **Resultados:** Se identificó que el **Árbol de Decisión Optimizado** era el mejor modelo para el problema de negocio, logrando un `recall` del **81%**.

### 🛠️ Tecnologías y Librerías
* **Lenguaje:** Python
* **Librerías:**
    * `pandas`: Manipulación y análisis de datos.
    * `numpy`: Computación numérica.
    * `scikit-learn`: Modelado y evaluación de *machine learning*.
    * `imblearn`: Manejo de desbalance de clases (`SMOTE`).
    * `matplotlib` y `seaborn`: Visualización de datos y resultados.

### ⚙️ Cómo Utilizar el Repositorio
1.  **Clonar el repositorio:**
    ```bash
    git clone (https://github.com/RamiroCabri1/Telecom_X_parte_2.git)
    ```
2.  **Instalar las dependencias:**
    ```bash
    pip install pandas numpy scikit-learn imblearn matplotlib seaborn
    ```
3.  **Descargar el archivo de datos:**
    * El archivo `df_telecomX.csv` se encuentra en este repositorio. Puedes descargarlo directamente.

4.  **Ejecutar el Jupyter Notebook:**
    * Abre el archivo `.ipynb` en Google Colab o Jupyter Notebook y ejecuta las celdas de código de forma secuencial.

---

### ✍️ Autor
**Ramiro Hernan Cabri**
* [GitHub](https://github.com/RamiroCabri1))
