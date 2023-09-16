# U2_Informe_03


Problema 3

Teorema del Límite Central

El Teorema del Límite Central es uno de los más importantes en la inferencia estadística y habla sobre la convergencia de los estimadores como la proporción
muestral a la distribución normal. Algunos autores afirman que esta aproximación es bastante buena a partir del umbral n>30.

Pasos sugeridos

a. Realice una simulación en la cual genere una población de n = 1000(Lote), donde el porcentaje de individuos (supongamos plantas) enfermas sea del 50%.

b. Genere una función que permita:

* Obtener una muestra aleatoria de la población y
* Calcule el estimador de la proporción muestral p^ para un tamaño de muestra dado n.

c. Repita el escenario anterior (b) n = 500 veces y analice los resultados en cuanto al comportamiento de los 500 resultados del estimador p^. ¿Qué tan simétricos o sesgados son los resultados obtenidos? y ¿qué se puede observar en cuanto a la variabilidad?. Realice en su informe un comentario sobre los resultados obtenidos.

d. Repita los puntos b y c para tamaños de muestra n = 5, 10, 15, 20, 30, 50, 60, 100, 200, 500. Compare los resultados obtenidos para los diferentes tamaños de muestra en cuanto a la normalidad. Utilice pruebas de bondad y ajuste (shapiro wilks : shspiro.test() ) y métodos gráficos (gráfico de normalidad: ggnorm()). Comente en su informe los resultados obtenidos
e. Repita toda la simulación (literales: a y d), pero ahora para lotes con 10% de plantas enfermas y de nuevo para lotes con un 90% de plantas enfermas. Concluya sobre los resultados del ejercicio.

Nota:

1. funciones recomendadas : rbinom() , data.frame(), apply()
