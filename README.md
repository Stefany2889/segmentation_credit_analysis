# Segmentación de Clientes y Scoring de Riesgo Crediticio


Se presenta el análisis del comportamiento crediticio y características de una población por medio de la segmentación de clientes y un modelo predictivo dentro de un único notebook.

Para esto realizamos decodificación del dataset 'German Credit Data (UCI)'
El dataset se obtuvo de la siguiente fuente: kaggle https://www.kaggle.com/datasets/ewelinak/german-credit-dataset-orginal-from-uci, también puedes encontrar la información para decodificar y la base de datos en otros formatos en la fuente: Hofmann, H. (1994). *Statlog (German Credit Data). UCI Machine Learning Repository. https://doi.org/10.24432/C5NC77


Se aplicaron las técnicas siguientes:

Decodificación y limpieza de datos
Análisis exploratorio (EDA)
Visualización de datos
Preprocesamiento 
Segmentación mediante KMeans y PCA
Evaluación de modelos de riesgo (Regresión logistica y Random forest)

Obtuvimos las siguientes conclusiones generales:

- Se encontraron 2 segmentos característicos en el dataset
- Estos segmentos se diferencian principalmente en el tipo de producto que adquirieron.
- Se encontró que los créditos cortos y de menor costo tienen una menor tasa de malos que los créditos largos y de mayor costo.
- Una de las principales características para clasificar a los clientes malos es la variable `checking_acc_status_no_checking_acc`.
- El modelo de regresión logística tuvo el mejor desempeño distinguiendo los clientes ‘buenos’ de los clientes ‘malos’ con AUC = 0.807.
