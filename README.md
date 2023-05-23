# proyecto_javascript

# 1 calculadora
### paso a paso 

- Creamos los archivos correspondientes, y la carperta de css.
## index.html

- Enlazamos de index.html a los archivos de la carpeta css.

- para poder grupar y darle esa presentacion de calculadora vamos a utlizar table y lo organizamos por bloques.

![table](/img/table.png "table")

- Lo consiguiente por hacer es crear clases y ésta temdra: (coteiner y calculator), tambien se le agregara un activador toggler de tema claro y oscuro.

![clases](/img/clases.png "clases")

- un div para la clase de button donde se encontraran los botones de la calculadora, despues creamos el table donde los botnes estaran. 

- Se le añade un display-scren para que se pueda visualizar los elementos dentro.

![button](/img/button.png "button")

![button2](/img/button2.png "button2")

## script.js
### paso a paso

- Definimos dos constantes.

- seleccionamos un id en especifico que va ser nuestro ("#display").

- seleccionamos todos los botones.

- arreglo generico de botones con la variable constante para recorrer todos lo botones, mediante ((item)=>) mediante la función de flecha podemos sacar toda la informacion de  cada button.

![item](/img/item.png "item")

- extraemos la longitud con string.lengh.

![string](/img/string.png "string")

- Acontinuacion en la imagen se mostrar los codigos para las operaciones en la calculadora.
![codigos](/img/codigos.png "codigos")

## style.css

- Este archivo contiene todo lo que tiene que ver con el diseño de la calculadora.
las margenes, los colores  etc.
![style](/img/style.png "style")
### RESULTADO.
![calculadora](/img/calculadora.png "calculadora")

# 2 menu 1

### paso a paso

- agrgamos un  div de navegacion y otro de menutoggle.
- luego tenemos una lista donde tiene el primer elemento.
- un span que viene siendo donde se agregan los iconos.
- segundo elemento activo que es home, se mostrara  acontinuacion.

![home](/img/home.png "home")

## style.css

- lo primero que tenemos que hacer, es agregar el tipo de letra deseado.
- le siguen las margenes.
- el fondo, con el color que mas te guste.
- seguimos con el div de navegacion, en el vamos a codificar para que la posición no se mueva (fixed).
- Despues de agregar el fonfo la psoción y todo lo que viene siendo como queremos en el menu e sigue el color en este caso es blanco pero si tu deseas puedes cambiarlo.
- la transición; necesitamos que sea suave cuando se expanda.
- lo colocamos en flexible y centramos el texto.


![menu](/img/menu.png "menu")

# DARK THEME

#### C ambiar de tema claro a oscuro.

- Agregamos en el body un div, tambien una clase que va ser un indicator.

- body: por el lado de los styles, un color de fondo; todo lo que viene siendo la altura, el margen, camibio de tema.

- toggle: viene siendo nuestra palanca, le agregamos una posicion relativa, un display, ancho y alto y bordes de 160px, y ahi se va notando que es un tubo, unos cuantos ajustes para que se pueda vizualizar una sombra decorativa con un box-shadow.

![sombra](/img/sombra.png "sombra")

- segumos con la parte interna que viene siendo el indicator que viene siendo la bolita que indica como su nombre lo dice si el tema es oscuro o claro.

![indicator](/img/indicator.png "indicator")

- capturamos la clase body con js y el toggle, donde se va activar con onclick. Es muy bueno porque ya viene en of y solo toca pasarlo en on.

![js](/img/js.png "js")

### RESULTADO

- Tema claro

![resul](/img/resul.png "resul")  

- Tema oscuro

![resul2](/img/resul2.png "resul2")  

# MENU DESPEGABLE 

- index
- Se agrego un toggle (palancas) viene siendo el menu con  sus debidas propiedades.

![toggle](/img/toggle.png "toggle")  

- Cuando la pantalla llega aun minimo de un ancho de 480 px, cambia sus dimensiones y la organizacion de tod el proyecto.

![menuu](/img/menuu.png "menuu")