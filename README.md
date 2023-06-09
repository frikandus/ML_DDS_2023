# ML_DDS_2023
Práctica final asignatura DDS sobre ML con la dataset de KDD CUP 99

El código proporcionado es un script escrito en R que tiene como objetivo realizar un estudio de un subconjunto del Dataset KDD CUP 99 y determinar el mejor conjunto de variables para utilizar en un modelo de Machine Learning de clasificación.

El documento comienza cargando los paquetes necesarios y estableciendo algunas constantes utilizadas en el programa, como el número máximo de árboles para el modelo de Random Forest y el número mínimo de muestras para considerar una variable como autónoma.

Luego, se describe el objetivo del programa, que es mejorar el valor obtenido por el script del enunciado mediante la identificación del mejor conjunto de variables y el entrenamiento de un modelo de Machine Learning de clasificación.

El documento se divide en varias secciones:

Análisis y preprocesamiento de los conjuntos de datos: Esta sección carga los conjuntos de datos "Dataset Global" y "Dataset Muestra" y realiza un análisis exploratorio para comprender su estructura y contenido. También se realiza un preprocesamiento de los datos para asegurarse de que sean adecuados para su uso en el entrenamiento de modelos de Machine Learning.

Selector de variables: En esta sección se implementa un selector de variables utilizando el algoritmo de Random Forest. Se comparan diferentes modelos de Machine Learning utilizando diferentes conjuntos de variables y se optimiza el modelo seleccionando el mejor conjunto de variables.

Mejora de la información y valor añadido: En esta sección se realizan estudios exploratorios de las variables y se agrega información adicional a los datos utilizando los estándares Mitre ATT&CK y CWE.

El documento utiliza varios paquetes de R, como "readr", "caret", "randomForest", "nnet", "e1071", "dplyr", "ggplot2", "doParallel", "corrplot", "class", "data.table", "kableExtra" y otros, para cargar los datos, realizar análisis exploratorios, entrenar modelos de Machine Learning y visualizar los resultados.

En resumen, el programa busca mejorar un modelo de clasificación de Machine Learning utilizando un subconjunto del Dataset KDD CUP 99. Utiliza técnicas de análisis exploratorio de datos, selección de variables y optimización de modelos para lograr este objetivo.
