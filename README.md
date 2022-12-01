# Credit-card-fraud

Para el desarrollo de este informe se utilizó la base card_transdata provista por la Diplomatura en Ciencia de Datos e Inteligencia Artificial de la Universidad Nacional de Córdoba. El set de datos cuenta con muchos clientes, existen un millón de transacciones de tarjeta de crédito (número de filas) e incluye siete variables que serán utilizadas como variables explicativas para comprender el comportamiento de la variable dependiente o target (‘fraud’).

Para poder detectar las transacciones fraudulentas se probaron dos familias de algoritmos de clasificación supervisada: Regresión Logística y algoritmos basados en árboles, específicamente un XGBoost (Chen, T., & Guestrin, C. , 2016). Este último dio los mejores resultados de los dos, por lo que fue elegido como el modelo a desarrollar. 

