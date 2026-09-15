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

Para esta población encontramos que los segmentos de malos y buenos tienen como caracteristcas principales el tipo de producto, teneiendo también entre su principal ditintivo para clasificar los clientes malos la varibale `checking_acc_status_no_checking_acc`.