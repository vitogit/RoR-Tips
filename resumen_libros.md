## Libro Clean Code

* La ley del boyscout: Siempre deja el codigo mejor que lo encontraste. Si tienes que modificar algo, intenta mejorar la claridad del código a su alrededor 
* Las funciones tienen que tener pocas líneas con pocos argumentos y hacer una única cosa
 (everything should do only one thing, do it well, and have no side effects)
* Variables
  * Es mejor nombres largos y descriptivos
  * Ser consistente (ej: no usar get y retrieve  para lo mismo. Usar siempre get)
  * Usar constantes con nombre descriptivo ( en vez de poner <10, poner < MAX_NUMBER_LINES)
* Comentarios
  * Es mejor expresar bien una función que escribir un comentario
  * Los comentarios desinforman porque muchas veces no se actualizan y dicen cosas que la función no hace.
  * En vez de escribir un comentario en una función fea, refactoriza la función para que exprese su intención claramente
* Clases
  * Mantener las clases chicas (menos de 200 líneas)
  * El ancho de línea menor a 120

## Clean Coder

* Se profesional
  * Aprender a decir no a tu jefe
  * Slaves are not allowed to say no. Laborers may be hesitant to say no. But professionals are expected to say no.
  * Si te presionan mantente firme en las estimaciones. No puedes codificar más rápido ni resolver problemas más rápido. Si lo intentas seguramente enlentezcas todo y termines apurando las cosas escribiendo código que no funcionara.
  * Trabaja horas extras solo si tu jefe tiene un respaldo de qué hacer si las cosas fallan. Y solo si son menos de 2 semanas. Más tiempo arruina todo.

* Estimaciones
  * Las estimaciones no son números fijos, es una distribución de probabilidad. Decir que tenes algo terminado en 3 días, quiere decir que hay 60% que lo hagas en 3 días, 20% que lo hagas en 4 y 5% que lo hagas en 10 días.
  * Estima para mejor caso, normal y peor caso. Actualizalo diariamente.
  * Estimar 3 valores. muy optimista , normal, muy pesimista. (Clean coder pagina 142) Three Point Estimate = (O + 4M + P ) / 6
  * Si para una tarea estimas: 8/12/20 (días), y tienes que presentar algo en 10 dias, date cuenta que no lo vas a lograr. Informa y haz que todos entiendan la situación.
  *  Solo podes comprometerte a realizar una tarea en un tiempo específico si estas seguro que la vas a completar en ese tiempo. Seria no profesional decir que podes y despues no llegar.
  *  Divide una tarea en pequeñas tareas y estimalas. Esto da un valor mucho más acertado pues se integran los posibles tiempos perdidos.

* Usa TDD (test drive development) . Codifica los test primero, y luego pasalos. En ciclos cortos de 30 segundos. Esto da confianza al código, porque sabes que nada se puede romper
* Aprender en el dojo. Practicar katas (pagina 91 de clean coder) .
* considera contribuir a algún proyecto open source de un lenguaje que quieras aprender 

* I learned that their vision of the features does not often survive actual contact with the computer. Cuando el cliente ve a su feature en acción le da más información de la que tenía y seguramente la cambie por otra que le parezca mejor.

* Tener un Continuous Build engine, que con un solo click te haga el build de todo.
* Refactor
  * antes de refactorial algo , tener una buena base de test para lo que se va a cambiar
  * clase muy grande
  * funciones con muchos parametros
  * funciones muy grandes
  * codigo duplicado


