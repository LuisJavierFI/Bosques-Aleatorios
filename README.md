<h1 align="center"> Bosques Aleatorios </h1>
El objetivo de un árbol es construir estructura jerárquica eficiente y escalable que divide los datos  en función de determinadas condiciones. Para esto se utiliza la estrategia: divide y vencerás. En algunas ocasiones los árboles de decisión tienen la tendencia de sobreajuste (overfit). Esto  significa que tienden a aprender muy bien de los datos de entrenamiento, pero su generalización  pudiera ser no tan buena.
Una forma de mejorar la generalización de los árboles de decisión es combinar varios árboles. A esto  se conoce como Bosque Aleatorio (Random Forest), el cual es un poderoso algoritmo de aprendizaje  automático, ampliamente utilizado en la actualidad. Los bosques aleatorios tienen una capacidad  de generalización alta.
El obejtivo de los bosques aleatorios es Construir un conjunto (ensamble) de árboles de decisión combinados. Al combinar lo que en realidad está pasando es que distintos árboles ven distintas porciones de los datos.


Ningún árbol ve todos los datos de entrenamiento, sino cada uno se entrena con  distintas muestras para un mismo problema. Al combinar los resultados, los errores se  compensan con otros y se tiene una predicción  (pronóstico o clasificación) que generaliza  mejor al problema.
Por lo que, los bosques aleatorios son una variación moderna, que agrupan varios árboles de decisión para producir un modelo generalizado con el objetivo de reducir la tendencia al sobreajuste

** Ventajas**

• Funciona bien para problemas de  clasificación y regresión (pronóstico).

• Al utilizar múltiples árboles se reduce considerablemente el riesgo de  sobreajuste.

• Es estable con nuevas muestras.

**Desventajas**

• Es mayor el costo computacional en comparación con la creación y ejecución de un árbol de decisión.

• Puede requerir mayor tiempo de entrenamiento.

• Puede ser difícil de interpretar debido a las decenas de árboles de decisión creados en el bosque.

### **Contexto** 
Estudios clínicos a partir de imágenes digitalizadas de pacientes con cáncer de mama de Wisconsin (WDBC, Wisconsin Diagnostic Breast Cancer).

Objetivo. Clasificar registros clínicos de tumores malignos y benignos de cancer de mama a partir de imágenes digitalizadas.

## Conclusión 
El algoritmo de bosques aleatorios de decisión es unaextensión de lo que vienen siendo los árboles de decisión, pues iterativamente hacen el mismo proceso de pronóstico o clasificación a una escala mayor revolviendo problemas como el sobreajuste y entregando modelos más efectivos al momento de predecir. Es posible concluir que se tiene mayor eficiencia en los árboles de clasificación que en los de predicción.
## Referencia

https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)
