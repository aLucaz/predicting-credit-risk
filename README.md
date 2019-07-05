# MODELOS PREDICTIVOS PARA LA CLASIFICACIÓN BINARIA DE RIESGOS CREDITICIOS

En este repositorio, se han desarrollado 4 modelos predictivos de clasificación:
- Árbol de decisión CART
- Random forest
- K-Nearest Neighbors
- Neural Networks 

Todos dentro de la categoría de Aprendizaje Supervisado.

La data utilizada es [german credit risk](https://www.kaggle.com/uciml/german-credit), la cual muestra 1000 observaciones con 9 atributos relacionados a las personas que han realizado una solicitud crediticia.

El target presenta dos clases (binario):
- Good risk
- Bad risk

|   | Age | Sex    | Job | Housing | Saving accounts | Checking account | Credit amount | Duration | Purpose             | Risk | 
|---|-----|--------|-----|---------|-----------------|------------------|---------------|----------|---------------------|------| 
| 0 | 67  | male   | 2   | own     | NA              | little           | 1169          | 6        | radio/TV            | good | 
| 1 | 22  | female | 2   | own     | little          | moderate         | 5951          | 48       | radio/TV            | bad  | 
| 2 | 49  | male   | 1   | own     | little          | NA               | 2096          | 12       | education           | good | 
| 3 | 45  | male   | 2   | free    | little          | little           | 7882          | 42       | furniture/equipment | good | 
| 4 | 53  | male   | 2   | free    | little          | little           | 4870          | 24       | car                 | bad  | 
| 5 | 35  | male   | 1   | free    | NA              | NA               | 9055          | 36       | education           | good | 
| 6 | 53  | male   | 2   | own     | quite rich      | NA               | 2835          | 24       | furniture/equipment | good | 
| 7 | 35  | male   | 3   | rent    | little          | moderate         | 6948          | 36       | car                 | good | 
| 8 | 61  | male   | 1   | own     | rich            | NA               | 3059          | 12       | radio/TV            | good | 
| 9 | 28  | male   | 3   | own     | little          | moderate         | 5234          | 30       | car                 | bad  | 


## OBJETIVO
Obtener el mejor modelo que clasifique correctamente a los solicitantes de acuerdo a la data presente.

Para realizar esta comparación, se utilizarán diversas métricas para modelos de clasificación.

Por otro lado, también se busca identificar cuáles son los atributos más influyentes para la clasificación presentes en los modelos implementados.