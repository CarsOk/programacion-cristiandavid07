## Clase 17 Marzo 2022 

### programación orientada a objetos
En esta clase estuvimos viendo:
- #### Que es una clase: 
Una clase es algo así como un molde de galletas, el molde es la clase y con él puedes hacer muchas galletas que tengan dicha forma.
##### ejemplo de como crear una clase
Para crear una Clase en Dart, necesitamos usar la palabra reservada Class y luego indicar el nombre de la clase. Por ejemplo:

class Dog {

}
Con esto podemos crear cualquier Dog(Perro) que queramos. Pero hay más, nuestro perro necesita un nombre, así que vamos a crear una variable que le asigne ese nombre.

class Dog {
  String name = "Rocky";
} 

##### propiedades
Las propiedades de una clase son variables declaradas al interno de una clase. Por ejemplo, si tenemos una clase Car (Carro), el color del carro puede ser una variable String con el valor Blue (Azul).

##### constructor
Los constructores nos ayudan a inicializar los valores de nuestros objetos. Cuando creamos una clase y pasamos como variable algún parámetro, estamos usando un constructor.

- #### Que es el método en una clase:
En la programación, un método es una subrutina cuyo código es definido en una clase y puede pertenecer tanto a una clase, como es el caso de los métodos de clase o estáticos, como a un objeto, como es el caso de los métodos de instancia. Análogamente a los procedimientos en lenguajes imperativos, un método consiste generalmente de una serie de sentencias para llevar a cabo una acción, un juego de parámetros de entrada que regularán dicha acción o, posiblemente, un valor de salida (o valor de retorno) de algún tipo.

- ##### Que es un metodo estatico
Un método estático es un método que pertenece a una clase, pero no pertenece a una instancia de esa clase y este método se puede llamar sin la instancia u objeto de esa clase. 