# Assessment

## EDA

Lo hace Tomás y consiste en:

- Plot de los datos como serie temporal.
- Ver si existen ciclos por año. En ese caso, borrar variable año.
- Borrar la variable día.
- Estudiar si borrar la variable fecha o si quedarnos con mes (y año si no hay ciclo)
- Usar `pandas.melt` para cargarnos las variables IRRADHXX y UTILHXX y sustituirlas por una columna HORA y una única de IRRAD o UTIL.
- Poquito más

## MODELOS

Lo hacemos todos y consiste en entrenar y hacer gráficos de los resultados. Los modelos que vamos a hacer son:

- Bagging y RF --> Pablo
- Boosting y Gradient boosting --> Elena
- XGBoost --> Tomás
- Stacking --> Miguel Ángel

## CONCLUSIONES

Lo hace Miguel Ángel y consiste en comparar los resultados obtenidos en los distintos modelos y determinar cuál es mejor para el problema. 