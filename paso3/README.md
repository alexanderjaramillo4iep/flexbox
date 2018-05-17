# Guía flexbox

## Paso 3

Ahora si, vamos al grano:

Vamos a trabajar flexbox con css en nuestro documento html

Te invito a que tomes de referencia [éste enlace](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) para ver claramente la teoría de flexbox y de la cual iremos siguiendo nuestro paso a paso

Siempre que vayamos a trabajar flexbox, debemos tener un elemento contenedor; en nuestro caso el div.container y éste a su vez tendrá otros elementos hijos (los que están dentro de él) .item

El elemento contenedor en llevará siempre la propiedad css <code>display: flex;</code>

Te sugiero hacerlo de la siguiente manera:
1. En los estilos que tenemos, creemos la propiedad <code>display: flex;</code> en nuestra clase <code>.container</code>
2. Con el numeral 1 vemos que ya nuestros bloques de texto se acomodan de forma horizontal a la derecha, lo que nos da paso a la siguiente propiedad <code>flex-direction: row | row-reverse | column | column-reverse;</code>
3. Modifica la propiedad flex-direction con alguno de sus posibles valores; row, row-reverse, column y column-reverse para que veas la forma en que se comporta

### NOTAS ACLARATORIAS
No es obligatorio utilizar las clases container e item, solo que para nuestro caso, es un poco más fácil de explicar

Puedes tomar el ejemplo de 
[éste link de referencia](index.html)

[paso 4](https://github.com/alexanderjaramillo4iep/flexbox/tree/master/paso4/)