## Matemáticas para Data Science
### ¿Qué es la probabilidad?
Incertidumbre y probabilidad
- **Incertidumbre**: Tomar decisiones con información incompleta
" El azar no es más que la medida de nuestra ignorancia. Los fenómenos fortuiros son, por definición, aquellos cuyas leyes o causas simplemente ignoramos "
- **Probabilidad**: Es un lenguaje que nos da herramientas para cuantificar la incertidumbre.

La probabilidad es realmente, una creencia que tenemos sobre la ocurrencia de eventos elementales

### Probabilidad en Machine Learning
**Fuentes de incertidumbre**:
- Datos
- Atributos del modelo
- Arquitectura del modelo
<<<<<<< HEAD

### TIPOS DE PROBABILIDAD
- Conjunta (joint)
- Marginal
- Condicional

### Ejemplos de cálculo de probabilidad
Correlaciones de evento
- A = resultado de lanzar un dado y sea 4
- B = resultado de lanzar un dado y sea par
- C = resultado de lanzar un dado y sea impar
=======
>>>>>>> 7dd5b45d1b646c589029d481b75711d4f400550f

### Ejemplos avanzados con probabilidad
Paradoja ¿niño o niña?
- Una mujer tiene dos bebés donde el mayor es un varón
- Una mujer tiene dos bebés donde uno de ellos es varón.


### ¿Que es una distribución?

X -> Variable aleatoria
x -> Valores posibles en el espacio muestran

### Distribuciones discretas
Distribución de Bernoulli
Variables con ocurrencias binarias
P(X = 1) = p
P(X =0) = 1 - p 

Distribución Binomial
Secuencia repetitiva de eventos tipo bernoulli
Todos los eventos igualmente probables
P(2 caras | 3 lanzamiento) = 3/8

Otras ditribuciones:
- Poisson
- Geométrica
- Hipergeométrica
- Binomial negativa

## MLE
Es un framework para estimación de densidades de probabilidad.

### Elementos de MLE
- **Escoger la distribución**:
Teniendo solo una muestra de los datos
- **Escoger los parámetros de la distribución**:
Que mejor ajustan la distribución a los datos.

### Teorema de Bayes
Inferencia Bayesiana

- Frecuentistas vs Bayesianos

**P(A|B) = P(B|A)P(A) / P(B)** 