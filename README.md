# La Parrilla de Rosendo
Rosendo tiene una parrilla y nos pidió un sistema para administrar su menú.

### 1. Platos
Se conoce la información de los diferentes ingredientes que se usan para preparar un plato y qué cantidad de cada uno de ellos se utiliza.
Por ejemplo, una ensalada tiene 50 grs de lechuga, 100 grs de tomate y 5 grs de aceite de oiva (para simplificar todos los ingredientes se expresan en gramos)

De cada plato se requiere obtener: 
- Si es abundante, lo cual es cierto cuando su peso total es mayor a 400 gramos.
- La cantidad de calorías. La cantidad de calorías por gramo de los ingredientes puede ser diferente para cada uno de ellos. Por ejemplo, la lechuga tiene 0.1, el tomate 0.2, y el aceite de oliva 5. A su vez, la cantidad de calorias por gramo que tiene un ingrediente es la misma para cualquier plato que tilice el mismo ingrediente. Por ejemplo, si hubiera otro plato que usa aceite de oliva, también son 5 sus calorias por gramo.
- Si es apto para una dieta en particular. Para que el plato sea apto, todos sus ingredientes tienen que serlo.Las dietas que se conocen son:
    - dieta vegetariana. El origen del ingrediente no puede ser animal.
    - dieta celíaca. El ingrediente no debe contener gluten.
    - dieta religiosa. El ingrediente no debe estar entre los alimentos vedados por la religión correspondiente

### 2. Comensales
Ya tenemos la comida, ahora nos faltan los comensales. 🍴
De cada comensal nos interesa saber:
- Su peso, medido en gramos, que es propio de cada persona.
- Si puede comer o no una comida, lo cual dependerá de qué comensal es: 
    - Popular: Come una comida solamente si abundante. 
    - Con dieta: Solo come las comidas que son aptas para su dieta. 
    - Bajas calorias: Para comer una comida comida requiere que no supere las 1000 calorias
    - Hay también comensales comunes que comen de todo.

- Representar que un comensal coma una comida. En todo caso tiene que verificarse que dicho comensal pueda comer la comida, adviertiendo adecuadamente en caso que no pueda hacerlo y registrando diferentes consecuencias  en caso afirmativo:
    - Todos los comensales aumentan su peso en el 1% del peso del plato.
    - Un comensal popular, además recuerda el plato que comió.
    - Un comensal de bajas calorias, además acumula la cantidad de calorías del plato. 
    - Los demás comensales no registran nada más. 


- La parrilla hace una cena especial con un plato único. Para ello hace que todos los comensales que estén presentes coman dicho plato. 
Asumiendo que los comensales presentes se modelan con una lista. ¿es posible que el orden en que están ubicados los comensales en la lista provoque diferentes consecuencias para el sistema? 


Nota: Un comensal no puede cambiar qué tipo de comensal es en su forma de comer. Sin embargo, el comensal con dieta puede cambiar que dieta sigue. 
