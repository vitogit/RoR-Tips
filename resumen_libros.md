## Libro Clean Code

* La ley del boyscout: Siempre deja el codigo mejor que lo encontraste. Si tienes que modificar algo, intenta mejorar la claridad del codigoa su alrededor 
* Las funciones tienen que tener pocas lineas con pocos argumentos y hacer una unica cosa
 (everything should do only one thing, do it well, and have no side effects)
* Variables
  * Es mejor nombres largos y descriptivios
  * Ser concistente (ej: no usar get y retrieve  para lo mismo. Usar siempre get)
  * Usar constantes con nombre descriptivo (( en vez de poner <10, poner < MAX_NUMBER_LINES)
* Comentarios
  * Es mejor expresar bien una funcion que escribir un comentario
  * Los comentarios desinforman por que muchas veces no se actualizan y dicen cosas que la funcion no hace.
  * En vez de escribir un comentario en una funcion fea, refactorea la funcion para que exprese su intencion claramente
* Clases
  * Mantener las clases chicas (menos de 200 lineas)
  * El ancho de linea menor a 120

## Clean Coder

* Se profesional
  * Aprender a decir no a tu jefe
  * Slaves are not allowed to say no. Laborers may be hesitant to say no. But professionals are expected to say no.
  * Si te presionan mantente firme en las estimaciones. No puedes codificar mas rapido ni resolver problemas mas rapido. Si lo intentas seguramente enlentescas todo y termines apurando las cosas escribiendo codigo que no funcionara.
  * Trabaja horas extras solo si tu jefe tiene un resplado de que hacer si las cosas fallan. Y solo si son menos de 2 semanas. Mas tiempo arruina todo.

* Estimaciones
  * Las estimaciones no son numeros fijos, es una distribucion de probabilidad. Decir que tenes algo pronto en 3 dias, quiere decir que hay 60% que lo hagas en 3 dias, 20% que lo hagas en 4 y 5% que lo hagas en 10 dias.
  * Estima para mejor caso, normal y peor caso. Actualizalo diaramente.
  * Estimar 3 valores. muy optimista , normal, muy pesismista.. (Clean coder pagina 142)Three Point Estimate = (O + 4M + P ) / 6
  * Si para una tarea estimas: 8/12/20 , y tienes que presentar algo en 10 dias, date cuenta que no lo vas a lograr. Informa y haz que todos entiendan la situacion.
  *  Solo podes compromenterte a realizar una tarea en un tiempo especifico si estas seguro que la vas a completar en ese tiempo. Seria no profesional decir que podes y despues no llegar.
  *  Parte una tarea en pequenias tareas y estimas estas. Esto da un valor mucho mas acertado pues se integran los posibles tiempos perdidos.

* Usa TDD (test drive development) . Codifica los test primero, y luego pasalos. En ciclos cortos de 30 segundos. Esto da confianza al codigo, por que sabes que nada se puede rompe
* Aprender en el dojo. Practicar katas (pagina 91 de clean coder) .
* considera contruibuir a algun proyecto open source de un lenguaje que quierasn aprender 

* I learned that their vision of the features does not often survive actual contact with the computer. Cuando el cliente ve a su feature en accion le da mas infomracion de la que tenia y seguramente la cambie por otra que le parezca mejor.

* Tener un Continuous Build engine, que con un solo click te haga el build de todo.
* Refactor
  * antes de refactorial algo , tener una buena base de test para lo que se va a cambiar
  * clase muy grande
  * funciones con muchos parametros
  * funciones muy grandes
  * codigo duplicado
