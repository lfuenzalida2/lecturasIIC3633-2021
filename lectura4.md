## Lukas Fuenzalida
### Numero de alumno: 17625378

En la formula (10.1) no entiendo porque se usa el logaritmo, entiendo que pueda "amortiguar" el crecimiento del peso de una palabra que aparecer muchas veces, pero eso es parte de que se utilice mucho esa palabra, siento, tal ves que con esto se está intentando disminuir la desviación estandar del peso de las palabras encontradas, lo cual sirve para tener una respuesta mas conservadora y "segura", pero tampoco es explicado de forma explicita en el paper y se debe deducir el porque se usa, lo cual no me gusta mucho.

En general las ideas que da el autor del paper son buenas, son distintas formas de hacer *Content-Based Recommendations*, pero me hubiese gustado ver algunos analisis basados en datos, haber hecho alguna experimento práctico y gráficar sus resultados para así saber realmente cual acercamiento es mejor que otro y en que situaciones.

Me hubiese gustado ver una comparativa entre el *Content-Based Recommendation* y el *Item-based Recommendation*, este último no va muy al caso en el paper, pero en varias situaciones se dice que uno puede pasar de un *Content-Based Recommendation* a un *Item-Based Recommendation* si es que hacemos una métrica *rating* a partir de los *features* de un producto (10.10 Limitations and Extensions) y podría ser interesante revisar si es que ese estimado de *rating* puede ser otra forma de obtener el *rating* de un *item*.