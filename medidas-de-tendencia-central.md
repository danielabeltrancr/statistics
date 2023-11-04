# Estadística Descriptiva

## 🔻 Medidas de tendencia central y dispersión

### Conceptos básicos

#### Número de clases

El número de clases en estadísticas se refiere a la cantidad de divisiones o intervalos en los que se divide un conjunto de datos al crear un histograma o realizar un análisis de distribución de frecuencias. La ***regla de Sturges***, es una forma común de determinar el número de clases.

- **Regla de Sturges:** La regla de Sturges es una regla empírica utilizada en estadísticas y análisis de datos para determinar el número apropiado de intervalos en un histograma al representar una distribución de datos. La regla de Sturges sugiere que el número óptimo de intervalos (k) en un histograma se puede calcular mediante la siguiente fórmula:

![Regla de Sturges](images/regla_de_struges.png)

Donde **"ni"** es el número de intervalos, y **"n"** es el número de observaciones en el conjunto de datos. El resultado se redondea al número entero más cercano, ya que el número de intervalos debe ser un número entero.

#### Amplitud del intervalo aproximado

La amplitud de intervalo aproximada se refiere al tamaño o la longitud de cada intervalo en un histograma o en un análisis de distribución de frecuencias. En otras palabras, es la distancia entre los límites superior e inferior de cada clase en un histograma.

Para calcular la amplitud del intervalo se usa la siguiente fórmula:

![Fórmula para calcular la amplitud del intervalo](images/amplitud_del_intervalo.png)

Donde **"c"** es el número de intervalos o clases en que se dividió el conjunto de datos para su análisis.

#### Límites inferior y superior

- **Límite Inferior:** El límite inferior es el valor más pequeño o el punto de inicio de un intervalo o clase en un histograma. Representa el valor mínimo que puede estar incluido en ese intervalo. Todos los valores iguales o mayores que el límite inferior, pero menores que el límite superior, se agrupan en ese intervalo. Por lo tanto, el límite inferior establece el punto de partida para la clasificación de datos en un intervalo particular.
- **Límite Superior:** El límite superior es el valor más grande o el punto final de un intervalo o clase en un histograma. Representa el valor máximo que puede estar incluido en ese intervalo. Todos los valores iguales o menores que el límite superior, pero mayores que el límite inferior, se agrupan en ese intervalo. El límite superior define el extremo superior del intervalo y, junto con el límite inferior, delimita el rango de valores incluidos en ese intervalo.

#### Frecuencia

La frecuencia se refiere al número de veces que ocurre un valor específico o una categoría en un conjunto de datos.

Hay dos tipos principales de frecuencias:

1. **Frecuencia absoluta:** La frecuencia absoluta es simplemente el recuento de cuántas veces se repite un valor o una categoría en un conjunto de datos. Por ejemplo, si estás analizando las edades de un grupo de personas y quieres saber cuántas personas tienen 25 años, la frecuencia absoluta para 25 años sería el número de personas en el grupo que tienen esa edad.
2. **Frecuencia relativa:** La frecuencia relativa es una medida de la proporción o el porcentaje de veces que un valor o categoría ocurre en relación con el total de observaciones en el conjunto de datos. Se calcula dividiendo la frecuencia absoluta de un valor por el tamaño total de la muestra y multiplicando por 100 para obtener el porcentaje. Esto te proporciona información sobre la proporción de observaciones que corresponden a una categoría en relación con el total de observaciones.

#### Frecuencia acumulada, distribución de frecuencias relativas y frecuencia relativa acumulada

1. **Frecuencia acumulada:** La frecuencia acumulada es el total acumulado de observaciones que se encuentran en o por debajo de un determinado valor en un conjunto de datos. Se calcula sumando las frecuencias absolutas de todas las categorías o valores hasta el punto en cuestión. La frecuencia acumulada es útil para identificar cuántas observaciones se encuentran por debajo de o son iguales a un valor específico en la distribución de datos.

2. **Distribución de frecuencias relativas:** La distribución de frecuencias relativas es una forma de resumir la distribución de datos en un conjunto de datos expresando las frecuencias relativas en lugar de las frecuencias absolutas. Las frecuencias relativas se obtienen dividiendo la frecuencia absoluta de una categoría por el tamaño total de la muestra. Esto proporciona la proporción de observaciones que caen en cada categoría y permite comparar la importancia relativa de cada categoría en la distribución.

3. **Frecuencia relativa acumulada:** La frecuencia relativa acumulada es el total acumulado de frecuencias relativas hasta un valor específico en un conjunto de datos. Se calcula sumando las frecuencias relativas de todas las categorías o valores hasta el punto en cuestión. La frecuencia relativa acumulada muestra la proporción acumulativa de observaciones que son iguales o menores a un valor particular en la distribución.

### Medida de tendencia central

Una medida de tendencia central o de posición, es un valor que se calcula para un grupo de datos y que se utiliza para describirlos de alguna manera.

Las medidas de tendencia central son:

- Media aritmética
- Media ponderada
- Media
- Mediana
- Moda

#### Media aritmética
