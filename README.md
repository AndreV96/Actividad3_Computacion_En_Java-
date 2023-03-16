# Actividad3_Computacion_En_Java

## Descripción
### Descripción de la baraja de poker
Una baraja de poker consta de 52 cartas únicas divididas entre palos (tréboles, corazones, picas o diamantes), colores (rojo, negro) y el valor de la carta (2 al 10, A, J, Q o K). Cada carta tiene uno de cada uno de estos atributos y no hay cartas repetidas en un deck de 52 cartas. El objetivo de este programa es simular la creación de una baraja de poker siguiendo las reglas de sus atributos y valores únicos y asignarle una serie de acciones posibles que son la mezcla (shuffle()), tomar cinco cartas (hand()), lo que se considera una mano, tomar la siguiente carta del deck (head()) y finalmente seleccionar una carta al azar del deck (pick()).
### Descripción del programa
Este programa crea una clase llamada Deck que contiene dos atributos, el primero es un ArrayList (formado por objetos de la clase Card con los atributos de las cartas ante mencionados.), un atributo tomado de la Collection Framework que nos funciona de excelente manera para crear un programa que simule fielmente un deck de cartas. Esto ya que nos permite tener un control preciso del orden en el que están las cartas y tiene métodos como (pick, remove) que nos ayudan enormemente para hacer las acciones a simular de la manipulación del deck. El otro atributo es un int que nos informa el número de cartas disponibles en el deck.
Esta clase contiene todas los métodos descritos arriba y permite su ejecución de la misma manera que se haría con una baraja de cartas física. Es importante notar que con cada ejecución se altera el atributo que contiene el arraylist con las cartas y se retiran las cartas específicas con cada acción así como se actualiza el número de cartas disponibles, mostrando cada vez este número en la terminal.
El programa ejecuta la clase main donde, a través del constructor de Deck, se crea un deck de cartas, para crear el ArrayList con todas las cartas se hizo un loop dentro de otro for loop que toma los valores de los atributos de las cartas (palo, color y valor) y crea una clase de Card, agregando con cada iteración una carta al ArrayList. Finalmente al tener el ArrayList con todas las 52 cartas y sus respectivos atributos, inicializa un objeto Deck. Después, para simular y comprobar que la clase Deck fue codificada correctamente se ejecuta cada una de los métodos definidos que van mostrando en la terminal las cortas tomadas y la cantidad de cartas faltantes en el deck que se va actualizando con cada movimiento.
