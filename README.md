# wine-ml

## Proyecto de Machine Learning para predecir la calidad del vino en función de sus propiedades fisicoquímicas.

En este repositorio encontraras:
1. Notebook con análisis exploratorio de datos, modelos de Machine Learning utilizados y feature importance.
2. Presentación con los resultados más importantes.

### Resumen

La industria del vino representa un sector importante en la economía de España y Portugal. El sector vinícola ha crecido mucho en los últimos años y para continuar con este crecimiento ha invertido en nuevas tecnologías para mejorar la elaboración y venta del vino. Es importante evaluar la calidad del vino para mejorar el proceso de elaboración al identificar los factores más importantes para hacer un buen vino, y también para estratificar a los vino en marcas premium, útil para fijar precios.

La evaluación de la calidad de los vinos es realizada por catadores expertos. Sin embargo, clasificar a los vinos según su calidad puede ser un proceso difícil, ya que las relaciones entre las distintas variables fisicoquímicas del vino y sus efectos en el sentido del gusto son complejas y no se entienden completamente.

Para facilitar el proceso de clasificación de los vinos, testeamos distintos modelos de Machine Learning (ML) utilizando 11 variables fisicoquímicas del vino (% alcohol, densidad, acidez, etc.) para predecir su calidad (en un puntaje del 1-10). El modelo de Random Forest obtuvo la mejor métrica, logrando un 63% de precisión con un margen de error de ± 1 punto. El contenido de alcohol fue la variable que más influenciaba la calidad del vino, seguida de la proporción de dióxido de azufre libre/dióxido de azufre total y contenido de ácidos volátiles.

En conclusión, este modelo de ML puede ser útil para ayudar a los catadores del vino durante el proceso evaluación de calidad, y los resultados del feature importance pueden guiar a los productores de vino a mejorar sus procesos.

</br>
</br>


Fuente de los datos [aquí](http://www3.dsi.uminho.pt/pcortez/wine/)
