
# XGBoost Project - Diabetes Prediction

## Project Description

This project utilizes the XGBoost algorithm to predict the probability of diabetes in individuals based on various medical variables. Input data includes information such as the number of pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, body mass index (BMI), diabetes pedigree function, age, and the outcome (Outcome), indicating whether the person has diabetes or not.

## Input Data

The dataset has the following characteristics:

### Numeric Variables

- Pregnancies: Number of pregnancies.
- Glucose: Glucose level.
- BloodPressure: Blood pressure.
- SkinThickness: Skin thickness.
- Insulin: Insulin level.
- BMI: Body mass index.
- DiabetesPedigreeFunction: Diabetes pedigree function.
- Age: Age.
- Outcome: Target variable indicating whether the person has diabetes (1) or not (0).

### Data Summary

- No null values in the dataset.
- There are 9 numeric variables and one target variable (Outcome).
- The dataset contains a total of 768 entries.

### Categorical Variables

There are no categorical variables in this dataset.

## Initial Conclusions

- **Exploration of Null Values:** No null values were found in any of the variables, facilitating data processing and analysis.

- **Numeric Variables:** Numeric variables represent relevant medical measures and provide valuable information for predicting diabetes.

- **Categorical Variables:** There are no categorical variables in this dataset, implying that there is no need for label encoding or handling categorical variables.

## Usage of XGBoost

XGBoost is a machine learning algorithm based on decision trees and has been employed in this project to model the probability of diabetes based on the aforementioned variables. Its robustness and ability to handle complex datasets make XGBoost a solid choice for such classification problems.

#---------------------------------------------------------------------------------------------------------------------------------------

# Proyecto de XGBoost - Diabetes Prediction

## Descripción del Proyecto

Este proyecto utiliza el algoritmo de XGBoost para predecir la probabilidad de diabetes en individuos basándose en varias variables médicas. Los datos de entrada incluyen información como el número de embarazos, niveles de glucosa, presión arterial, grosor de la piel, insulina, índice de masa corporal (BMI), función de pedigree de diabetes, edad, y el resultado (Outcome), que indica si la persona tiene diabetes o no.

## Datos de Entrada

El conjunto de datos tiene las siguientes características:

### Variables Numéricas

- Pregnancies: Número de embarazos.
- Glucose: Nivel de glucosa.
- BloodPressure: Presión arterial.
- SkinThickness: Grosor de la piel.
- Insulin: Nivel de insulina.
- BMI: Índice de masa corporal.
- DiabetesPedigreeFunction: Función de pedigree de diabetes.
- Age: Edad.
- Outcome: Variable objetivo que indica si la persona tiene diabetes (1) o no (0).

### Resumen de los Datos

- No hay valores nulos en el conjunto de datos.
- Hay 9 variables numéricas y una variable objetivo (Outcome).
- El conjunto de datos contiene un total de 768 entradas.

### Variables Categóricas

No hay variables categóricas en este conjunto de datos.

## Conclusiones Iniciales

- **Exploración de Valores Nulos:** No se encontraron valores nulos en ninguna de las variables, lo que facilita el procesamiento y análisis de datos.

- **Variables Numéricas:** Las variables numéricas representan medidas médicas relevantes y proporcionan información valiosa para predecir la diabetes.

- **Variables Categóricas:** No hay variables categóricas en este conjunto de datos, lo que implica que no es necesario realizar codificación de etiquetas o manejar variables categóricas.

## Uso de XGBoost

XGBoost es un algoritmo de aprendizaje automático basado en árboles de decisión y se ha utilizado en este proyecto para modelar la probabilidad de diabetes en función de las variables mencionadas anteriormente. La robustez y la capacidad de manejar conjuntos de datos complejos hacen que XGBoost sea una elección sólida para este tipo de problemas de clasificación.
