# ML_modulo2_UsoDeFrameWork_A00828570

# Momento de Retroalimentación: Módulo 2 Uso de framework o biblioteca de aprendizaje máquina para la implementación de una solución. (Portafolio Implementación)
# Nombre del proyecto: FINAL_DecisionTrees_UsoDeFramework_A00828570


Concentración: Inteligencia Artificial Avanzada para la ciencia de datos

Descripción de la entrega: Usa un marco de trabajo o framework para implementar una técnica o algoritmo de aprendizaje máquina como: regresiones, árboles, clusters, etc...

# Modelo de aprendizaje supervisado implementado: Decision Trees

Con el fin de comparar ambos desempeños con el mismo clasificador, fueron utilizados 2 datasets siendo: 
* iris.csv (Obteniéndose un Accuracy: 1.00)
*  wine.data (Obteniéndose un Accuracy: 0.94)

# 5 predicciones de prueba (con el dataset de Wine): 

## Primera predicción de prueba

Valores de entrada:

* Alcohol = 13.64
* Malic acid =  3.1 
* Ash =    2.56 
* Alcalinity of ash =   15.2  
* Magnesium =  116. 
* Total phenols = 2.7  
* Flavanoids =  3.03   
* Nonflavanoid phenols =   0.17 
* Proanthocyanins = 1.66 
* Color intensity = 5.1
* Hue = 0.96  
* OD280/OD315 of diluted wines = 3.36
* Proline = 845.

Valor esperado: Cultivar 1 | Pred: Cultivar 1

## Segunda predicción de prueba

* Alcohol = 14.21  
* Malic acid = 4.04   
* Ash = 2.44   
* Alcalinity = 18.9  
* Magnesium = 111.      
* Total phenols = 2.85    
* Flavanoids = 2.65    
* Nonflavanoid phenols = 0.3     
* Proanthocyanins = 1.25
* Color intensity = 5.24    
* Hue = 0.87    
* OD280/OD315 of diluted wines = 3.33 
* Proline = 1080.  

Esperado:  Cultivar 1  | Pred:  Cultivar 1

## Tercera predicción de prueba

* Alcohol = 12.93   
* Malic acid  = 2.81   
* Ash = 2.7   
* Alcalinity = 21.    
* Magnesium = 96.     
* Total phenols = 1.54   
* Flavanoids = 0.5    
* Nonflavanoid phenols = 0.53   
* Proanthocyanins = 0.75   
* Color intensity = 4.6
* Hue =  0.77   
* OD280/OD315 of diluted wines = 2.31 
* Proline = 600.  

Esperado:  Cultivar 3  | Pred:  Cultivar 3

## Cuarta predicción de prueba

* Alcohol = 13.73   
* Malic acid  = 1.5     
* Ash = 2.7    
* Alcalinity = 22.5   
* Magnesium = 101.      
* Total phenols = 3.      
* Flavanoids = 3.25    
* Nonflavanoid phenols = 0.29    
* Proanthocyanins = 2.38
* Color intensity = 5.7     
* Hue =  1.19    
* OD280/OD315 of diluted wines = 2.71 
* Proline = 1285.  

Esperado:  Cultivar 1  | Pred:  Cultivar 1

## Quinta predicción de prueba

* Alcohol = 12.37   
* Malic acid  = 1.17   
* Ash = 1.92  
* Alcalinity = 19.6   
* Magnesium = 78.     
* Total phenols = 2.11   
* Flavanoids = 2.     
* Nonflavanoid phenols = 0.27   
* Proanthocyanins = 1.04   
* Color intensity = 4.68
* Hue =  1.12   
* OD280/OD315 of diluted wines = 3.48 
* Proline = 510.  

Esperado:  Cultivar 2  | Pred:  Cultivar 2




# Librerías utilizadas:
- from sklearn import tree <-- Método de Decision Tree
- from sklearn import preprocessing
- from IPython.display import Image
- import pydotplus
- import matplotlib.pyplot as plt

- from sklearn.model_selection import train_test_split 
- from sklearn import metrics
- from sklearn.metrics import accuracy_score
- from sklearn.metrics import confusion_matrix

- import numpy as np
- import pandas as pd



