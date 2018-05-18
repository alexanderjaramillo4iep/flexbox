# Guía flexbox

## Paso 8

Todas las propiedades que hemos visto hasta el momento, se utilizan en el contenedor padre

Ahora, vamos a ver algunas propiedades que tienen los hijos; es decir los componentes <code>.item</code>

## ________________________________
### Propiedad de orden de los hijos

<code>order: 2; </code> (el valor por defecto es 0) en el <code>.item</code> y se le pone a cada elemento diciendo en que orden aparecerá

### Recomendaciones
* para probar ésta propiedad, lo podemos hacer con estilos en línea; es decir, con el atributo style de cada elemento item

### Propiedad de la forma de crecer de los hijos

<code>flex-grow: 1; </code> (el valor por defecto es 0) en el <code>.item</code> y se le pone a cada elemento diciendo los tamaños proporcionales de cada elemento dentro de el contenedor

Ejemplo:
Si quiero que todos los elementos queden del mismo tamaño y ocupen todo el ancho, en el css de <code>.item</code> ponemos <code>flex-grow: 1;</code>
Si quiero que alguno de los elementos crezca el doble, al elemento en particular, le ponemos <code>flex-grow: 2;</code>

### Recomendaciones
* para probar ésta propiedad, podemos agregar un borde al item para identificar sus dimensiones con <code>border: solid 1px;</code> en nuestro css de <code>.item</code>

Puedes tomar el ejemplo de 
[éste link de referencia](index.html)

[paso 9](https://github.com/alexanderjaramillo4iep/flexbox/tree/master/paso9/)