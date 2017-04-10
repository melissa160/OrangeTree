# Orange Tree Javascript

## App preview
![App Preview](./app/images/preview.jpg?raw=true "Orange App Preview")

## Resumen

Modelar un árbol de naranjas. Nuestro árbol tiene las siguientes funcionalidades:

* El Arbol puede envejecer
* Por cada año que el árbol envejece hasta llegar a su edad de dar frutos, este debe crecer de altura.
* Después de que este llega a su edad de dar frutos, este puede crear naranjas.
* El árbol genera un numero al azar de naranjas cada año, después de llegar a su edad de dar frutos.
* Cada naranja tiene un diámetro al azar
* Es posible recoger todas las naranjas que crezca el árbol durante el año
* Todas las naranjas que no se recojan antes de que el árbol crezca otro año, se mueren cuando este crece otro año
* El árbol muere después de llegar a su maxima edad, y no puede dar mas frutos después de esto.


## Elementos


### 1: Pruebas con Jasmine. Ver [solution-spec.js](./spec/solution-spec.js)


### 2: Javascript Funciones constructoras. Ver [solution.js](./javascripts/solution.js)


### 3: La vista. Ver [view.js](./javascripts/view.js)

* La aplicacion permite `plantar` un árbol al presionar un botón. Este hace un árbol visible en la pantalla.

* El árbol envejece al presionar un botón.
Si el árbol envejece lo suficiente como para empezar a dar frutos, aparecen naranjas en el árbol 

* Al dar click en cada naranja esta se cosecha por tanto la cantidad de naranjas disminuye

