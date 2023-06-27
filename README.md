# Objetivos del proyecto

    ¿Qué variables tienen mayor correlación con Purchased Bike y cómo se relacionan con esta?
    ¿Predecir la probabilidad que la variable Purchased Bike sea 1?

# Nombre de los alumnos participantes
    Torres Paniagua, César Augusto
    Ramirez Sarmiento, Joseph Rafael
    Camargo Ramírez, Enzo Fabricio
# Breve descripcion del conjunto de datos
   | Columna | Descripcion |
   | ------- | ----------- |
   | ID: | El identificador del comprador. |
   | Marital Status: | El estado civil del comprador, puede ser casado(‘married’) o soltero(‘single’). |
   | Gender: | El género del comprador, puede ser hombre(‘male’) o mujer(‘female’). |
   | Income: | Los ingresos del comprador en un determinado tiempo. |
   | Children: | El número de hijos que tiene el comprador. |
   | Education: | La formación educativa del comprador. |
   | Occupation: | El trabajo o ocupación del comprador. |
   | Home Owner: | Si el comprador tiene o no una casa propia. |
   | Cars: | Número de carros del comprador. |
   | Commute Distance: | La distancia entre la residencia y la empresa del comprador. |
   | Region: | Determina la región donde vive el comprador. |
   | Purchased Bike: | Si el comprador adquirió la bicicleta o no. |
# Concluciones 
* Variables como Income resultaron dar más valor cuando se aplica un suavizado por logaritmo natural; sin embargo, esto compromete parte de  la precisión sobre valores atípicos.
* Las variables Income y Age son constantemente las más relevantes para el modelo de predicción.
* Para el tratamiento eficaz de los datos atípicos se requiere tomar en cuenta las prioridades de la empresa, políticas empresa, para determinar si la precisión respecto a esos casos es más importante que la efectividad general del modelo de predicción.
* El aplicar técnicas de suavizado que modifica severamente la distribución de una variable conlleva reducir el ROC del modelo final. 
* Observamos que en el modelo hemos tenido un resultados de ROC por debajo del 70% dando entender que se debería mejorar las transformaciones o crear columnas nuevas en caso contrario una menor selección de columnas
* Se dará prioridad a la atención de los clientes de los grupos 1 y 2, ya que tiene una tendencia a completar la compra de una bicicleta, seguido de los grupos 3 al 7 como los clientes comunes y finalmente los clientes desestimados del 8 hasta el 10.