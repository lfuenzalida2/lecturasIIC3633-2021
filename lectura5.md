## Lukas Fuenzalida
### Numero de alumno: 17625378
<hr>

## **Combining Predictions for Accurate Recommender Systems**
<hr>

Básicamente lo que trata este paper es sobre como es que este grupo de personas combinó los resultados de distintos algoritmos de recomendación para dar resultados a un algoritmo mas pontente y preciso. Además de eso, hablan explicitamente de que algoritmos usaron, como lo ensamblaron y que combinaciones trataron. 

En las sección *GE (global effects)* el autor habla sobre el nacimiento de *GE* (su primera descripción) y de otros 6 *GE* descritos (siempre dando las referencias), pero luego habla de que el RMSE de 16 *GE* fue de 0.95, sumando y restando faltan una cantidad significativa de *GE*'s que el autor no menciona y que considero que deberían estar (dado que es el recomendador que mayor RMSE tiene de todos).

En la sección *Combinations* dicen *"We found that item-item KNNs are most effective, when they are applied on residuals of RBMs."*, lo cual es bueno, pero no dan una conclusión un poco mas profunda de porque pudo haber pasado, con eso el lector puede asumir que tuvieron un golpe de suerte o que para obtener los mejores resultados simplemente hay que hacer todo tipo de combinaciones hasta tener la combinación que mejor se adapte a tu *dataset* (esto ultimo puede ser cierto, pero tampoco lo dejan explícito y es algo que se debería mencionar).

