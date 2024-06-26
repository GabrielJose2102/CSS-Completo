
# Documentación CSS

**CSS Principiante:**

En este nivel introductorio, se cubren los conceptos básicos de CSS y se enseña cómo aplicar estilos a elementos HTML. Se comienza con una introducción al curso y se explica cómo configurar un editor de texto para escribir código CSS. Luego, se abordan temas como la estructura de un archivo CSS, los selectores para apuntar a elementos específicos, la especificidad de los estilos y la metodología BEM (Block Element Modifier). También se exploran unidades de medida, propiedades de texto, tipografías externas, la normalización de estilos con Normalize, el modelado de cajas (padding, width, height, margin, bordes, sombras, outline) y las diferentes posiciones de los elementos en la página.

**CSS Intermedio:**

En este nivel, se profundiza en diferentes aspectos de CSS, como el manejo del flujo de elementos con display, el control del desbordamiento de contenido con overflow y el uso de float para el posicionamiento. Se exploran los pseudoelementos y pseudoclases, así como las propiedades de objeto fit y objeto position. También se cubren temas como el cursor, la colorización de elementos con diferentes formatos de color, los conceptos básicos de diseño responsivo, la creación de menús responsivos y la introducción a Flexbox. Se enseñan los conceptos esenciales de Flexbox, cómo alinear elementos, controlar el crecimiento y el encogimiento, gestionar el orden de los elementos y crear formularios utilizando Flexbox. Además, se introduce el concepto de Grid para el diseño de estructuras más complejas.

**CSS Avanzado:**

En este nivel avanzado, se exploran características más avanzadas de CSS. Se cubren temas como las transiciones y animaciones CSS, el uso de funciones de cubic bezier, las transformaciones de elementos, los recortes con clip path, los fondos, el uso de variables CSS, los filtros de imagen y su práctica, la dirección del texto, el espaciado entre letras, el comportamiento de desplazamiento, la selección de texto por parte del usuario y se realiza una práctica final integrando todos estos conceptos. Se concluye el curso destacando la importancia de seguir aprendiendo y manteniéndose actualizado.
## Contenido

   **CSS Principiante**

- Introducción
- Comienzo del Curso
- Editor de texto
- Estructura
- Selectores
- Especificidad
- Metodología BEM
- Unidades
- Propiedades de Texto
- Tipografías externas
- Normalize
- Cajas
- Padding
- Width y Height
- Box Sizing
- Margin
- Bordes
- Box Model
- Sombras
- Outline
- Position
- Position Static
- Position Relative
- Z Index
- Position Absolute
- Position Fixed
- Position Sticky


**CSS Intermedio**

- Display
- Overflow
- Float
- Pseudoelementos
- Pseudoclases
- Objet Fit
- Objet Position
- Cursor
- Colorización (ColorName, Hex, RGB/A)
- Conceptos Básicos de Responsive
- Menu Responsive
- Introducción a Flexbox
- Conceptos de Flexbox
- Display Flex
- Flex direction
- Flex wrap
- Alineacion en Flex
- Flex Grow
- Flex Basis
- Flex Shrink
- Order
- Formulario con Flex
- Conceptos de Grid  
- Display Grid
- Grid Templates
- Medidas especiales de Grid
- Grid Gap
- Asignación de espacios
- Repeat()
- Grid Implícito y Explícito
- Grid Auto
- Grid Dinámico
- Alineación en Grid
- Galería en Grid
- Grid Areas
- Nombrar Grid Lines
- Grid Shorthands
- Responsive Design
- Estructura Responsive Básica


**CSS Avanzado**

- Transition
- Animaciones
- Cubic Bezier
- Transform
- Clip Path
- Background
- Variables
- Filtros
- Práctica con Filter
- Direction
- Letter Spacing
- Scroll Behavior
- User Selected
- Práctica Final
- Continua Aprendiendo


## Instalacion y Ejecucion de Herramientas

 [Descargar Visual Studio Code](https://code.visualstudio.com/)

- Visita el sitio web oficial de Visual Studio Code.
- Descarga el instalador correspondiente a tu sistema operativo (Windows, macOS o Linux).
- Ejecuta el archivo de instalación.
- En Windows: Sigue las instrucciones del instalador para completar la instalación.
- En macOS: Arrastra la aplicación a la carpeta de Aplicaciones.
- En Linux: Sigue las instrucciones específicas para tu distribución.
- Una vez instalado, puedes abrir Visual Studio Code desde el menú de inicio o el escritorio.
## Resumen Parte I

1.Estructura de CSS : Se compone la estructura del (Selector de la etiqueta, Llaves, Propiedad que se añadira y valor de la prioridad).



2.Selectores : Se usa para seleccionar el elemento al que se le quiere aplicar los atributos css y hay varios tipos de Selectores    (Universal, de tipo, Clases, ID, decendientes y pseudo-clases).



3.Especificidad : Es la jerarquia que le da css a un selector para ejecutar los estilos y estos van asi en orden decendente (pseudo-elementos, elementos), (atributos, pseudo-clases, clases), (identificadores), (estilos en linea), (!important) cada nivel esta por encima en prioridad del otro, y las jerarquia no es lo mismo que las cascada, ya que la cascada es cuando dos selectore uno se impone sobre el otro porque esta por debajo de el.

Cuando se esta aplicando la jerarquia, la cascada no funciona porque si un selector con mayor gerarquia esta arriba de otro con menos jerarquia no se aplicara los cambios si son el mismo atributo del de abajo, hay desaparece la cascada.



4.Metodologia BEM (Block, Element, Elemnt--Modifier) : Se usa para evitar problemas de Especificidad ya que al momento de de estructurar el html se van ordenando los elementos con clases de acuerdo si son Block, si son Element o si son Element--Modifier Ejemplo:

    <Block class="bloque">
        <Element class="bloque__elemento"></Element>
        <Element class="bloque__elemento"></Element>
        <Element class="bloque__elemento"></Element>
        <Element class="bloque__elemento"></Element>
        <Element class="bloque__elemento"></Element>
        <Element--Modifier class="bloque__elemento--modificado"></Element--Modifier>
    </Block>



5.Unidades de medidas en CSS : Es la forma de medir el tamaño de los elementos html que hay en la pagina, para esto tenemos varios tipos de medidas con los cuales usamos para trabajar el resposive design de la pagina y asi optimizar tanto en pc como en movil. tenemos medidas en:

Pero el control del valor del em lo controla en contenedor del elemento dependiendo del tamaño del contenedor sera el tamaño de la fuente.

En cuanto al % esta medida se trabaja de acuedo a la caja que la contiene.

medidas fijas: (ml, cm, pt, px)
medidas relativas: (rem, em, %, vh, vw) 1em = 16px, vh = alto de la pagina, vw = ancho de la pagina.



6.Propiedades de texto : Se usan para manejar los estilos de las letras que contiene la pagina.

Para controlar los estilos de la letra usamos : (font-size, font-family, line-heigth, font-weigth, font-stretch, font-variant) entre otros.

Aparte de esto podemos cambiar el color de letra, adornarla y mas.

font-size : Se encarga del tamaño de la letra.

font-family : Se encarga de la tipografia de la fuente.

line-heigth : Es el espacio que ocupa en la linea el valor que se le da se divide en la mitad para arriba y la otra mitad para abajo.

font-weigth : Maneja el grosor de la letra, mientras mas alto es el valor mas gruesa es la letra.

color : Lo usamos para cambiar el color de la letra.



7.Tipografias Externas : Son las diferente apariencias que se le puede dar a las letras y podemos encontras estas fuente en googlefont.



8.Normalize : Es un archivo optimizado que reiniciar los estilos que trae por defecto los navegadores, esto se hace para que podamos estaablecer nuestros propios estilos desde cero y asi poder controlar el 100% la apariencia de la pagina.



9.Cajas : Son representadas por 2 tipos en bloques y en linea.
Los elementos que son en bloque ocupan el 100% del ancho de su contenedor y solo puede haber uno de ellos dentro de una linea del contenedor, mientras que los elementos que son en linea solo ocupan el ancho del tamaño de su contenido en el contenedor donde se encuentren y puede haber varios en la misma linea del contenedor.

Estos elementos son modificables, asi que se pueden hacer bloques los que son en linea y hacer en linea los que son bloques.

Dato: Los elementos en linea no se le puede dar heigth ni width y a los elementos en bloque si. 


        __ Propiedades de Cajas __

a.Text-align : Se usa para ajustar la posicion del texto dentro de la caja.

b.Tamaño : Es la posibilidad de ajustar el tamaño de la caja dependiendo del su contenedor y esto se hace con heigth y width.

c.background : Se usa para cambiar el color de fondo o agregar imagenes ademas de otras modificaciones a la caja.

d.color : Se usa para cambiar el color del texto en el interior de la caja.

e.border : Se usa para aplicar estilos a los bordes de la caja, estos bordes son el espacio que delimita el espacio de la caja y posee atributos como: (color, grosor entre otros).

f.border-radius : Se usa para redondear el estilo de los bordes de la caja esto se puede hacer con medidas.

g.padding : Es la distancia que hay por dentro entre un elemento y su caja contenedora.

h.margin : Es el espacio que hay por fuera de la caja, es decir que es el espacios que existe entre cajas y este espacio esta por los cuatro costados y se ajustan los 4 individuales o se pueden ajustar en los ejes (x, y), solo uno tambien se puede.

i.box-shadow : se usa para añadir efectos de sombras a la caja y los atributos que se usan para estos efectos son :

a.Movimiento que tendra la sombra en el eje x.
b.Movimiento que tendra la sombra en el eje y.
c.Radio de desenfoque que poseera.
d.Dispersion de la sombra.
e.Color de la sombra.

j.text-shadow : Son los estilos de sombras que se le puede aplicar a el texto y este solo posee 4 propiedades, no posee la dispersion de la sombra.




10.box-sizing : Se usa para establecer las especificaciones que poseera el ancho o alto de la caja con dos atributos.

a.content-box : toma los espacios extras como padding que puedan hacer la caja mas grande y si lo hay esto se le sumara al tamaño de la caja y por ende el tamaño definido sera mayor al acorado.

b.border-box : Toma los espacios extras y en vez de sumar y hacer que el tamaño de la caja sea mayor al acordado, estos espacios los aplica dentro del espacio definido de la caja.



11.Box model : Esta compuesto por todos los espacios que conforman la caja, tanto por dentro como por fuera estos espacios son (Content, padding, border, margin) y cada uno de esto tiene su jerarquia y posicion en la caja.

a.Content : Es el espacio que tiene el texto y este se puede modificar con el line-heigth.

b.Padding : Es el espacio que hay entre el texto y el border de la caja contenedora.

c.Border : Es el espacio que delimita todo el espacio de la caja.

d.Margin : Es el espacio que hay entre cajas, es decir po fuera de la caja. 



12.outline : Es la forma de mostrar el border pero sin que ocupe espacio para que la caja no mida mas de lo establecido, con "outline" remarcamos los bordes de las cajas pero como no ocupamos mas espacio para esto no es necesario mover las demas cajas ya que no se ocupa espacio extra, el outline es el que traen por defecto los input text. 

Esto lo que hace es remarcar los bordes que se vean pero no se cuentan como medida.



13.position : Cada caja ocupa un espacio definido y de esta manera es la forma de manejar las posiciones de las cajas en la pagina para esto tenemos: (static, relative, absolute, fixed, sticky).

a.Static : Se considera que no esta posicionado ya que no adquiere las propiedades que con las otras 4 si.

b.Relative : Quiere decir que su posicion es relativa y puede moverse por encimas de las demas cajas, puede posicionarse por encima de otra caja y las caja las podemos mover con top, bottom, left, rigth y le damos medidas a estos atributos de esta manera se movera contando desde el espacio que ocupa originalmente.

Cada caja tiene una posicion reservada que ocupa en el espacio de la pagina.

Una vez especificada 2 de las cuatros propiedades top y left que son no se puede asignar bottom y rigth, por eso es recomendable aplicar medidas solo 2 de las propiedades por que las 4 no funcionan.

c.Absolute : Funciona casi igual al relative pero tienes 3 diferencias.

Cuando se da la propiedad "absolute" el espacio reservado que posee cada caja desaparece, esto hace que si hay otra caja que venga despues ocuparan la posicion de la caja que tenga la propiedad absolute.

Tambien cuando se posee la propiedad absolute se toma el punto de partida de la caja basandosee en el punto 0 del contenedor o el viewport y no desde el punto donde esta posicionada la caja. 

Si no se le asignan medidas a la caja su posicionamiento se guiara por el contenedor donde se encuentre, pero si se le asigna ya sea (top, bottom, left o rigth) su posicionamiento dependera del viewport.

d.fixed : Es casi igual a absolute solo que con el fixed queda fijada la caja y al momento de hacer scroll la caja o contenido que se le aplico fixed no se ira con el scroll y queda fija en la pantalla a medida que vas bajando en la pagina y le puedes dar posicionamiento con (top, bottom, left, rigth).

e.sticky : Es parecido a relativa y fixed ya que conserva su espacio reservado como el relativa y se puede establecer en que momento en la pagina se quedara fijo como el fixed se comporta como fixed en el punto de la pagina que se le indique.

14.z-index : Es la forma que usamos para indicar el posicionamiento de las cajas, cual va por encima de cual, estara por delante la caja con el z-index con el mayor valor. 



## Resumen Parte II

**Display**

La propiedad "Display" Se encarga de modificar el comportamiento de las cajas, no de la forma en que interactuan entre ellas sino que en la forma que que interactua la caja con el entorno, si la caja ocupa su linea completa como block o si solo ocupa un espacio suficiente para su contenido y puede haber mas cajas que le sigan en la misma linea, aprate de esto hay mas propiedades del Display que pueden otorgar mas caracteristicas a la caja tanto de como se comporta por fuera como por dentro.


0.none : Es la ausencia de la propiedad, una caja con "Display none" no se ve en pantalla.


1.Block : Esta propiedad hace que la caja ocupe todo el espacio del que dispone a lo ancho asi su contenido no lo necesite y si hay otra caja no puede estar a un lado de la caja con block, debe estar abajo la caja.


2.Inline : Hace que la caja solo ocupe el espacio del tamaño de su contenido, por esto si llega haber mas cajas puede compartir el espacio en la misma linea con esa o esas cajas que halla hasta el final de esa linea una a lado de otra.


3.Inline-block : Esta tiene caracteristicas de las otras dos propiedades como lo son Block e Inline, pero este se diferencia del block por que a esta propiedad si se le puede dar un ancho y alto a la caja y asi podemos controlar el espacio que ocupa, es decir que se comporte como bloque pero que se pueda ajustar el tamaño a su contenido.


4.Table (no se usa ya) : Hace que la caja se comporte como tabla.


5.Inline-Table (no se usa ya) : Se comportara como Tabla en linea.


6.List-Item (no se usa ya) : Hace que los elementos que estan dentro de la caja salgan en modo de lista.


7.Table-Cell (no se usa ya) : Hace que se comporte como cada una de las celdas de una tabla.


8.Table-Row (no se usa ya) : Se comporta como cada una de las filas de la tabla.


9.Table-Column (no se usa ya) : Se comporta como cada una de las columnas de la tabla.


10.Flex : Se usa para ayudar a distribuir el espacio que hay entre los items de una caja, asi de manera flexible poder mover los item y posicionarlos de la manera que mejor nos paresca.

Inline-Flex :


11.Grid : Permite alinear los elementos en filas  columnas y de esta forma podemos dividir la pagina en areas donde podremos manejas el tamaño y posicion de las cajas o elementos html.

Inline-Grid :



        __ OverFlow __

Es un acortador de las propiedades : (OverFlow-x, OverFlow-y), asi que si es necesario se puede aplicar sus propiedades en solo un eje ya sea en x o y.

Se usa para controlar lo que sobra de la caja contenedora, a esto se le puede aplicar OverFlow y se controla esto dependiendo de la propiedad que se le de con el over OverFlow.

La propiedad por defecto de OverFlow es visble.


Propiedades del OverFlow : 

1.Auto : Detecta si el contenido se sale de la caja, entonces contiene dentro de la cajas todo lo que se sale y coloca una barra para scrolear el contenido.


2.Scroll : A diferencia de Auto Scroll coloca la barra de scrolear asi no sea necesario y la cola en los ejes (x, y), no necesita detectar si el contenido se sale de la caja contenedora para colocar las barras del scroll.


3.Hidden : Oculta el contenido que se sale de la caja, es como si lo cortara pero solo es la parte que se sale de la caja.



        __ Float __

Ubica un elemento y lo posiciona a lado izquierdo o derecho del contenedor, permitiendo que los elementos de textos y los elementos en linea se posicionen a un lado del elementos con float y dependiendo del lado al que se mueva el elemento los demas elementos ya sean inline o textos se ocomodaran a su lado envolviendo al elemento que se le aplico float.

1.float: left : Flota ala elemento al lado izquierdo del contenedor y hace que los otros elementos si son de textos o elementos en linea se ajusten a el elementos con float.


2.float: right : Flota ala elemento al lado derecho del contenedor y hace que los otros elementos si son de textos o elementos en linea se ajusten a el elementos con float.


3.float: none : Es la ausencia de esta propiedad.


4.float: inline-start : Hace flotar el elemento al inicio de la linea del contenedor.


5.float: inline-end : Hace flotar el elemento al fin de la linea del contenedor.



        __ Pseudo-Elementos __

Son un mecanismos para acceder a partes del HTML que no tienen asociado un nodo en el DOM. Estos elementos pueden ser la primera  Linea de un parrafo o la primera letra, un texto seleccionado por el usuario, pero tambien swon una forma de introducir un contenido antes o despues de un elemento y esto lo hacemos con (before y after).

Los Pseudo-elementos se aplican a los elementos, para esto se coloca el elementos y luego se le agrega el Pseudo-elemento para seleccionar una caracteristica especifica de ese elementos.


::first-line : (Este elemento si forma parte del DOM) (No funciona en los elmentos inline), Se usa pra seleccionar la primera linea de un parrafo y asi poder editarla de manera individual, no importa si cambia el tamaño de la pagina y esto afecta a la linea ya solo seleccionara a las letras que conformen la primera linea sin importar si estos elementos cambian de cantidad.


::first-letter : (Este elemento si forma parte del DOM) (No funciona en los elmentos inline), Se usa parecido a ::first-line solo que esta propiedad solo selecciona a la primera letra de la primera linea y asi poder aplicar estilos css de manera individual solo a esa letra.


::placeholder : Se usa para seleccionar el texto de ejemplo que se coloca en los input text para poder aplicarles estilos css.


::selection : Se usa para agregar estilos css a un texto seleccionado por el usuario con el mouse y este Pseudo-elemento se comporta como un elemento en linea.


::before : Cuando lo aplicamos, before se crea como si fuera un hijo del elemento al que se le aplica y requieren de la propiedad content.

Se usa para agregar contenido antes de un elementos que especifiquemos, para esto colocamos el elemento mas el Pseudo-elemento before y podemos agregar el contenido antes de ese elemento.

Este Pseudo-elemento no cuenta como parte del DOM asi que su contenido n se puede seleccionar con el mouse y el contenido dentro del content que se le coloque no puede haber etiquetas ya que la interpreta como texto normal.



::after : Cuando lo aplicamos, after se crea como si fuera un hijo del elemento al que se le aplica y requieren de la propiedad content.

Se usa para agregar contenido despues de un elementos que especifiquemos, para esto colocamos el elemento mas el Pseudo-elemento after y podemos agregar el contenido despues de ese elemento.

Este Pseudo-elemento no cuenta como parte del DOM asi que su contenido n se puede seleccionar con el mouse y el contenido dentro del content que se le coloque no puede haber etiquetas ya que la interpreta como texto normal.



        __ Pseudo-Clases __

Se trabajan de manera similar a los Pseudo-Elementos, es decir tambien se aplican a un elementos, pero la diferencia es que las Pseudo-Clases no selecciona una caracteristica especifica del elemento sino que se usan para escuchar un evento, se ejecuata su codigo mendiante el evento al cual esten enlazada.


:hover : Se usa para que se ejecute los cambios en el estilo cuando el mouse pasa por encima del elemento con esta Pseudo-Clases y sirve para todos los elementos a los cuales se le puede modificar los estilos al momento que pasa el evento el tienpo de ejecucion se puede modificar con la propiedad transition y transform.


:link : Se usa para para aplicar estilos css a un link que no ha sido visitado, si el link es visitado ya no se aplican los estilos.


:visited : Se usa para para aplicar estilos css a un link que ya fue  visitado, si el link no se ha visitado antes no se aplican los estilos solo si ya sea visitado antes.


:active : Se ejecuta cuando se deja presionado con el click al elemento que se le otorgo esta clase y mientras se mantenga presionado el elemento se aplicaran los estilos css que posea esta Pseudo-Clase si de deja de presionado el elemento vuelve a sus estilos anteriores.


:focus : Se usa mas que todo con los input ya que se evento se activa cuando se el elemento esta seleccionado con un click que se hace el focus sobre el input por eso no es necesario que se mantenga el click presionado, con solo darle una vez es suficiente y los estilos de la Pseudo-Clase se ejecutaran hasta que se haga focus sobre otro elemento fuera del elemento con focus.


:lang() : Es una funcion la cual requiere que se le pase un parametro, se usa para modiificar el texto de un contenedor lo puede modificar dependiendo de el lenguaje para esto se le debe dar a la etiqueta donde esta el texto un especificador de lenguaje (lang="en") con la abreviatura del lenguaje y en el documento css se le pasa como parametro la misma abreviatura para solo el texto con el lenguaje especificado cambie sus estilos.



        __ Object-Fit __

Es una propiedad que principalmente se aplica a las imagenes, se usa pra modificar la resolucion de las mismas, de esta forma podemos ajustar las imagenes dentro del contenedor para que no se deforme la imagen y se mantenga con una resolucion adecuada. 


1.contain : Es la propiedad que trae por defecto el Object-Fit y se usa para contener la imagen y si el contenedor hace que se deforme la imagen ajusta la imagen en medio y deja el espacio necesario para cuadrar dentro del contenerdo y ajustar tanto el width como el heigth de la imagen y la imagen no ocupara todo el espaciodel contenedor sino que sus cuatro lados seran ajustaran y dejara el espacio 
sobrante del lado que sea necesario.


2.cover : Se usa para que la imagen se ajuste al contenedor al contrario del contain que ajusta la imagen independientemente del contenedor esta propiedad ajusta la imagen si el contenedor el mas grande agranda la imagen para que sea igual de los cuatro lados y recorta los espacio que sobre por ejemplo si el contenedor es de 300x400 hace la imagen de 400px x 400px y del lado del contenedor que es de 300px recorta la imagen 100px.


3.none : Es la ausencia de la propiedad y deja la resolucion de la imagen original.


4.scale-down : Escoje la resolucion que mas le convenga entre contain y none dependiendo del contenedor si contain es mas pequeño usa contain y si la resolucion original de la imagen es mas pequeña usa none, explora esas dos y se queda con la mas pequeña.



        __ Object-Position __

Se usa para mover las imagenes a las cuales ya se le aplico el Object-Fit cover y mostrar mas la parte de la imagen que se le indique ya sea left, rigth, top, bottom dependiendo de la que se le de mostrara mas ese lado de la imagen el cual por el cover estaba siendo ocultada por salirse del contenedor.

Tambien se puede mver la imagen con medidas especificas como (px, em, etc).



        __ Cursor __

Se usa para cambiar la forma del cursor al posicionarse en un elemento especifico, de esta manera el cursor cambiara su forma a la que se le indique cada vez que se posicione sobre el elemento que se le aplico la propiedad cursor.

Link de la lista de formas de cursores : https://aprende-web.net/css/css9_1.php



        __ Colores en css __

En css colores se pueden colocar de diferentes formas las cuales no ayudaria ya que segun las reglas del navegador interpretara el color de una forma diferente si lo colacamos por su nombre que por esto hay diferentes formas mas especificas para colocar el color que queremos y que sea interpretado de la misma forma por todos los navegadores.


1.nombre : Es el nombre normal en ingles del color.


2.rgb : Es la cantidad de color que tendra de red(rojo)-green(verde)-blue(azul) que es lo que significa rgb.


3.rgba : Es igual al rgb solo que se le grega un parametro mas red(rojo)-green(verde)-blue(azul)-alpha(alfa que viene siendo la transparencia del color) que es lo que significa rgba.


4.hexadecimal : Es el codigo del color y dependiendo de el valor que se le de a los colores primarios que son (rojo-verde- azul), la combinacion de estos colores formas los demas colores que existen y estos valores van de (0 a f) siendo en 0 la ausencia del color y la f el maximo de ese color y el color se crea dando uno o dos valores si se quiere ser mas especifico de cada uno de los tres colores primarios el codigo debe llevar un # antes de los valores.


5.hsl : Es otra forma de representar un color es el hsl que significa Hue (tono), Saturation (saturacion) y Lightness (luminosidad).

6.hsla : Es igual al hsl pero se le agrega el valors de transparencia
Hue (tono) - Saturation - (saturacion) - Lightness (luminosidad) - alpha (transparencia).
## Resumen Parte III

 **Conceptos Basicos Resposive**

Se usa para adaptar una pagina a diferentes resoluciones en pantalla ya sea movil, tablet, lapto o pc de escritorio con el resposive hacemos que la parte visual de la pagina se comporte diferente dependiendo de a que resolucion se encuentre y de esta manera sus elementos se acomoden de forma diferente en el espacio de la pagina.

Se basa en adaptar la pagina de resoluciones grandes a pequeñas.


Mobile - First : El Mobile - first por su parte se encarga de adaptar la pagina pero de resoluciones pequeñas a resoluciones mas grandes, es decir de resolucion de movil a una resolucion de escritorio o cualquier otra resolucion que sea mas grande que la de escritorio.


Para trabajar con resposive design se usa una propiedad llamada media Query, los mediaQuery son en los que especificamos la resolucion en la que se aplicara el cambio de la pagina dependiendo de la resolucion, los media Query se encargan de detectar la resolucion en que se encuentra la pagina y aplicar esos cambios la forma de aplicar los media Query es ("@media screen and(resolucion que debe detectar)").



    __ FlexBox __

El uso de las cajas flexible se emplea para acomodar los elementos en la pagina y sustituir a las tablas.

flex necesita de dos cosas que son un flex-container y un flex-item.


a.flex-container : Es el contenedor donde se encuentras todos los items que se desean posicionar con flex, cuando le damos display flex al contenedor se comporta como bloque ese contenedor los cambios se notan adentro del contenedor donde se necesita que los elementos que estan dentro sean flexibles y de esta manera poder acomodarlos.

b.flex-items : Son los elementos que estan dentro del contenedor que se le aplico el display flex pero solos los elementos hijos del que posee el display flex si los elementos hijos tienen otros elementos dentro de ellos a estos no les afecta el display flex a los que si afecta directamente el display flex son a los hijos directos del contenedor haciendolos flexibles para poder movilizarlos dentro del contenedor.


    _ Ejes del flex box _

FlexBox posee dos ejes, asi como en un plano hay  los ejes (x, y) en flexbox tenemos los ejes (main axis(x) y cross axis(y)), los 2 vienen siendo a la direccion a la que apuntan por ejemplo.

main axis(x) apunta en el eje horizontal y va de izquierda a derecha que viene siendo (main-start(izq) y main-end(der)).

cross axis(y) apunta en el eje vertical y va de arriba hacia abajo que viene siendo (cross-start(arr) y cross-end(aba)).

Con el flex-box lo que hacemos es invertir las direcciones en las que apunta el main axis y el cross axis haciendo que se inviertan las posiciones en las que apuntan por ejemplo que main axis apunte en vertical y el cross axis apunte en horizontal y dependiendo hacia donde sea la direccion a la que apuntas de donde sale sera el start y hacia donde va sera el end de cada uno (main y cross).



    __ Display Flex __

Cuando aplicamos Display flex las cajas dentro del elemento con la propiedad flex se adaptan de acorde a su contenido y se posicionan una a lado de otra pero sin el problema de que un contenedor hijo sea mas alto que el otro por que este tenga mas o menos contenido, los contenedores hijos se adaptaran con el mismo tamaña.

Si un contenedor hijo tienes mas contenido que otro se adapta el contenido para que sigan teniendo la misma altura.

Cuando se usa flex si no se le da un width al item no sera visible dentro del contenedor esto es una particularidad de flex.



    -- Propiedades de Flex --

    _ Flex Direction _

Es una propiedad que se le aplica al contenedor pero afecta a los items y se usa para modificar la direccion del "main axis".


1.row : Es el valor que trae por defecto y hace que los items se comporten como si estuvieran en una fila.

2.row-reverse : Cambia la direccion en el mismo eje pero ahora apuntara de derecha hacia la izquierda invierte la fila como si fuera un espejo.

3.column : Hace que los items se comporten como si estuvieran en una columna, es decir el "main axis" corre en la direccion que corria el cross axis.

4.column-reverse : Cambia la direccion en el mismo eje pero ahora apuntara de abajo hacia arriba invierte la columna como si fuera un espejo.



    _ flex-wrap _

1.flex-nowrap : Es el valor por defecto y es la ausencia de la propiedad.

2.wrap : Hace que al reducir el espacio del contenedor los items se acomoden y bajen a la siguiente linea cuando el espacio no es suficiente para su tamaño y para que no pierda el ancho que se le dio al item cuando llegue al espacio limite donde los items es uno a lado de otro y ya no halla mas espacio se pasa a la linea de abajo el item que este es la equina y asi ningun item perdera su ancho.

3.wrap-reverse : Funciona casi igual al flex-wrap pero en vez de irse para abajo se va hacia a arriba la caja de la esquina si no hay espacio suficiente para el tamaño de todos los items.



    __ Flex-Flow __

Es un acortador de las propiedades flex-direction y flex-wrap en donde puedes incluir valores para ambas propiedades.



    __ Justify-Content __

Trabaja en el main axis y se usa para posicionar los items dentro del contenedor, es una propiedad que se le aplica al contenedor pero afecta los items.


1.center : Se usa para centrar los items dentro del contenedor.


2.space-arround : Funciona como el margin-auto dividiendo el espacio que hay en el contenedor entres los items, pero lo unico es que el space-arround solo centra en un solo eje y el margin-auto centra en los dos y se usa para darle un margen automatico a todos los items dentro del contenedor y que todos items tengan el mismo espacio de separacion que se le da por ambos lados, excepto en las esquinas, en el principio y al final los margenes son mas pequeños.


3.space-between : Hace que todos los items esten separados lo mas posibles entre ellos a la misma distancia lo mas posible dentro del espacio del contenedor y los items de las esquinas solo se le da el margen del lado donde halla que separarlo de otro item del lado que esta pegado del contenedor no se le otorga margen. 


4.space-evenly : Funciona parecido a space-arround solo que esta propiedad le da un margen especifico a todos los items para que sea igual de los dos lados tanto de izquierda como de derecha incluso en los lados de las equinas que estan pegadas al inicio y final del contenedor.



    __ Aling-Items __

Se usa solo cuando hay una sola linea que items que son flex-item y se usa para mover los items en el cross axis del contenedor.


1.stretch : Es la propiedad por defecto asi que cuando se esta empleando esta propiedad y no se le otorga un heigth especifico al item ocupa todo el alto del contenedor.


2.flex-start : Se usa para mover los items hacien el principio del cross-axis, es decir el pundo de partida hacia donde este apuntado el cross-axis desde donde arranca.

Cuando se aplica flex-start el item si no se le otorga un heigth especifico solo ocupara un alto del tamaño de su contenido.


3.center : Se usa para centrar los items dentro del contenedor en el eje cross-axis.


4.flex-end : Funciona casi igual al flex-start solo que este mueve los objetos hacia el punto final de donde apunta el cross-axis, es decir el punto de llegada.


5.Baseline : Funciona parecido a flex-start, alinea los items en el contenedor segun la base del contenido de los items del contenedor.

Su uso mas comun es cuando hay un wrap-reverse y se desea que los item se que vallan pasando a otra linea pasen encima de los otros, entonces se combinan Baseline con el wrap-reverse para esto mandara los items para abajo como si se tratara de un flex-end.



    __ Aling-Content __

Se usa cuando hay mas de una linea, depues de la segunda linea deja de funcionar el align-item y es hay donde debemos de aplicar el align-Content para que se haga cargo de poder aplicar las propiedades a las lineas que se vallan creando dentro del contenedor.

Aling-Content funciona con las misma propiedades que Aling-Items solo que estas se aplican para mas lineas.


1.stretch : Es la propiedad por defecto asi que cuando se esta empleando esta propiedad y no se le otorga un heigth especifico al item ocupa todo el alto del contenedor.


2.flex-start : Se usa para mover los items hacien el principio del cross-axis, es decir el pundo de partida hacia donde este apuntado el cross-axis desde donde arranca.

Cuando se aplica flex-start el item si no se le otorga un heigth especifico solo ocupara un alto del tamaño de su contenido.


3.center : Se usa para centrar los items dentro del contenedor en el eje cross-axis.


4.flex-end : Funciona casi igual al flex-start solo que este mueve los objetos hacia el punto final de donde apunta el cross-axis, es decir el punto de llegada.


5.Baseline : Funciona parecido a flex-start, alinea los items en el contenedor segun la base del contenido de los items del contenedor.

Su uso mas comun es cuando hay un wrap-reverse y se desea que los item se que vallan pasando a otra linea pasen encima de los otros, entonces se combinan Baseline con el wrap-reverse para esto mandara los items para abajo como si se tratara de un flex-end.




        -- Propiedades de los Items --

Son propiedades que se le dan directamente a los items de esta manera podemos ajustar o modificar el item sin necesidad de aplicarle las propiedades al contenedor.

Estas propiedades se usan para aplicarle cambios a los items de manera individual, de esta forma podemos escoger un solo item  y aplicarle los cambios a ese item en especifico y no de manera grupal con todos los items del contenedor como con las propiedades (Justify-Content - Aling-items - Aling-Content).

El margin se comporta de forma diferente cuando se usa flex funciona alreves, esto quiere decir que si le decimos que se mueva a la izquierda ira a la derecha, si le decimos que valla hacia arriba ira hacia abajo.

Estas propiedades solo se pueden aplicar a los items si su contenedor es flex.


1.align-self : Se usa para mover un item especifico en el cross-axis el item con align-self se movera independientemente de los otros items del contenedor.

Su valores tambien son (stretch - flex-start - flex-end - Baseline - center)


2.flex-grow : Toma el espacio que sobra en el contenedor y lo reparte entre las cajas asi crecen en tamaño las cajas, se puede hacer que lo reparta en partes iguales para cada caja o repartir de forma desigual, es decir dar mas a una caja que a otra.

Si se aplica el flex-grow al contenedor la reparticion del espacio sobrante sera equitativa pero si se desea que una caja tenga mas espacio que otra se le debe otorgar directamente la propiedad flex-grow al item que se quiere que se quede con mas espacio que los demas.

Individualmente se puede dividir el espacio entre las cajas dandole valores al flex-grow en que cantidad de espacio del que sobra quieres que tenga cada caja.


3.flex-shrink : Se usa para que una caja ceda mas espacio que otra cuando se este haciendo el contenedor mas pequeño, la caja con flex-shrink dependiendo del valor que se le de cuando ya no halla suficiente espacio para mantener el ancho de todas las cajas que halla en una linea y no se aplico la propiedad flex-wrap entonces no se moveran las cajas y se haran mas pequeñas de lo normal entonces es hay donde flex-shrink hace que la caja con esta propiedad ceda mas espacio que las demas cajas haciendo a esta mas pequeña y las otras conservaran mas tamaño.

Al momento de volver a su tamaño original de ancho donde ya halla espacio suficiente para todas las cajas volveran todas al mismo tiempo al ancho que se les otrogo inicialmente sin importar que tengan flex-shrink.   

Tambien con esta propiedad se puede hacer no solo que ceda mas espacio si que tambien lo contrario que ceda menos espacio que las demas cajas.


4.flex-basis : Funciona como si fuera un width, se usa para darle un ancho a los items pero el css toma a flex-basis como mas importante que el width, es decir si se aplican los 2 tanto el width como el flex-basis se le dara prioridad al flex-basis. 


5.flex : Es un acortador de las propiedades (flex-grow - flex-shrink - flex-basis) y empieza a funcionar a partir de un solo parametro que se le pase que es el flex-grow.


6.order : Funciona como el z-index pero en el eje en el que apunta el main-axis, esto quiere decir que el que posea el valor mas alto estara al final de donde apunte el main-axis.

Si se cambian la direccion donde apunta el main-axis cambiara la posicion en la que se posiciona el item con el valor mas alto.
## Resumen Parte IV

**Conceptos Grid**


Grid Es una propiedad de display y se usa para trabajar el layout de la pagina, con grid la trabajamos en forma de grillas(Rejas), esto quiere decir que los elementos se trabajan dentro de Celdas que estas dentro de filas y columnas y a la vez estas estan dentro de un grid container.

1.Grid Container : Es el contenedor del grid que al igual que el display flex cuando aplicamos display grid el contenedor no sufre cambios sino que solos item que estan dentro de ese contenedor el que sufren el cambio.


2.Grid Item : Son todos los elementos que estan dentro del grid container y que son hijos directos del contenedor con display grid y OJO estos no son lo mismo que las celdas, ya que los item son los elementos como las etiquetas imagenes y otros tipos que hay y las celdas estan definidas por el numero de filas y columnas que se coloquen.


3.Grid Cell : Son cada espacio cuadrado que compone y que dividen la grilla(reja), el numero de celdas lo define el numero de filas y columnas que se coloque en el grid container.


4.Grid Tracks (Column y Row) : Son las filas y columnas que hay dentro de cada contenedor grid.


5.Grid Area : Un area es cuando una celda ocupa mas de una fila o columna, estas areas la definimos nosotros y para defininirla deben ser en celdas consecutivas tanto en filas como en columna no pueden estar en (diagonal, L, p o cruses) pueden ser en filas y columnas al mismo tiempo pero en espacios cuadrados o rectagulares.


6.Grid Line (Column Line y Row Line) : Son las filas y columnas que componen la grilla(reja) del grid container cada una de las column line y row line se empiazan a contar desde las esquina del contenedor.



    -- Propiedades --

Una vez que aplicamos el display grid al contenedor en automatico todos los elementos hijos se convierten en grid-item los cuales los podemos modificar con las siguiente propiedades.

1.grid-templete-rows (Grid container) : Se usa para crear filas dentro del contenedor, dandole la medida de la fila o filas que tendra.


2.grid-templete-columns (Grid container) : Se usa para crear columnas dentro del contenedor, dandole la medida de la columna o columnas que tendra.

Unidades "auto" y fr : El fr se usa para repartir el espacion que puede tener la grilla ya sea entre fila o columna, es decir las filas o columnas que sean de medidad fr no poseeran una medida fija sino que dependera del tamano del contenedor y el espacion que ocupen las demas filas o columnas.


repeat (cantidad, tamaño/s) : Se usa para crear varias filas o columnas a la vez solo hay que indicarle la cantidad y el tamaño que tendra y de esta manera abreviamos el escribir una por una las filas o columnas solo lo colocamos en repeat las medidas y la cantidad de veces que se colocara.



3.grid-row-gap (Grid container) : Se usa para separar las filas unas de otras la distancia que le indiquemos pero estas no se separaran de los bordes del contenedor.


4.grid-column-gap (Grid container) : Se usa para separar las columnas unas de otras la distancia que le indiquemos pero estas no se separaran de los bordes del contenedor.


5.grid-gap : row - column (Grid container) : Es un acortador de (grid-row-gap - grid-column-gap) que se usa para separar los grid-item entre ellos se coloca la distancia que se separaran uno de otro, pero estos no se separaran de los bordes del contenedor.



6.grid-row-start (Grid item) : Se usa en el item para indicar desde que linea de las filas empieza el espacio de este item.


7.grid-row-end (Grid item) : Se usa en el item para indicar hasta que linea de las filas terminara el espacio de este item.


8.grid-column-start (Grid item) : Se usa en el item para indicar desde que linea de las columnas empieza el espacio de este item.


9.grid-column-end (Grid item) : Se usa en el item para indicar hasta que linea de las columnas terminara el espacio de este item.


10.grid-row (Grid item) : Es un acortador de (grid-row-start - grid-row-end) se usa para modificar la cantidad de filas que ocupara el item dentro del contenedor, pudiendo incluso desplazar otros item de ser necesario hacia otras filas.


11.grid-column (Grid item) : Es un acortador de (grid-column-start - grid-column-end) se usa para modificar la cantidad de columnas que ocupara el item dentro del contenedor, pudiendo incluso desplazar otros item de ser necesario hacia otras columnas.


   -- Uso de Span  con (grid-row - grid-column) --

Se coloca desde que linea arracara el item y se coloca "span" mas el numero de columnas o filas que ocupara para que tomando el punto de partida ya establecido tome filas y columnas y no sea linea por linea.




    -- Grid Implicito y Explicito --

Grid Implicito : Es el espacio que esta incluido en el contenedor pero sin ser expresado al menos que se le agreguen mas elementos que se salgan de las filas o columnas que ya se establecieron.

    -- Propiedades del Grid Implicito --


1.grid-auto-row (Igual que el template) : Es la forma de hacer que se generen filas automaticas en el espacio implicito si hay mas item que estan quedando por fuera.


2.grid-auto-column (Igual que el template) : Es la forma de hacer que se generen columnas automaticas en el espacio implicito si hay mas item que estan quedando por fuera.


3.grid-auto-flow Row(default), Column y Dense : Se usa para rellenar los huecos que quedan cuando hacemos que celdas ocupen mas espacio que el predeterminado por nosotros, esto hace que se creen mas filas o columnas en el espacio implicito rompiendo la figura de la grilla y hay el dense hace que se rellene esos espacios.



    -- Grid Dinamico --   (Quede aqui)

Hace que la grilla y su contenido se ajusten al tamaño del contenedor y que si se hace grande el contenedor se hara grande el contenido y si se reduce el contenido tambien lo hara y se ajustara dependiendo del tamaño.


1.minmax() : Se usa para establecer un minimo y un maximo en el tamaño que tendra el contenido dentro de la grilla, pasandole dos parametros de medidas que son el minimo de tamaño que puede tener y el maximo de tamaño que puede llegar.


2.min-content : Hace que la celda se ajuste al minimo de tamaño donde quepa su contenido y que pueda tener espacio  para que entre su celda.


3.max-content : Hace que la celda se ajuste al maximo de tamaño donde una linea completa de su contenido que en la celda completamente de hay no se reducira mas de tamaño esa celda.

**cantidad** 

5.auto-fill : Se usa para que genere columnas dinamicamente, las va generando a medida de que se valla haciendo mas espacio en el contenedor y el espacio es suficiente genera otra columna, si el espacio no es suficiente reparte el espacion que hay entre las otras columnas de ser necesario.


6.auto-fit : Es parecido a auto-fill pero esta propiedad cuando se acaban los item y quedan en una sola linea y el contenedor se sigue haciendo mas grande escala los item, es decir los hace mas grande para que abarquen el tamaño de fila.

Igual crea mas columnas pero cuando todos los item estan en una sola columna y sigue incrementando el espacio del contenedor hace los item mas grandes para que se ajusten a la fila.




    ** Alineacion y Control de Flujo **

Diferencia con flex :

_La alineacion es dentro de cada celda y no alineacion total del flex container.

_Cada celda seria un "flex container".



    -- Propiedades del grid Container --


     ** Propiedades para mover los items dentro de las filas **


Estas propiedades seran efectivas siempre y cuando haya espacion en la fila o columna para mover el item sino no.


1.justify-items (Horizontalmente) : Se encarga de mover los items dentro de las columnas en el eje Horizontal, solo los items.


a.stretch (default) : Es la propiedad que trae por default.

b.start : Mueve el item hacia el inicio de su columna en el eje Horizontal.

c.center : Centra el item en el medio de su columna dejando el mismo espacio de separacion de ambos lado de su columna centrandolo solo en el eje Horizontal.

d.end : Mueve el item hacia el fin de su columna en el eje Horizontal.




2.aling-items (Verticalmente) : Se encarga de mover los items dentro de las filas en el eje vertical, solo los items.


a.stretch (default) : Es la propiedad que trae por default.

b.start : Mueve el item hacia el inicio de su fila en el eje vertical.

c.center : Centra el item en el medio de su fila dejando el mismo espacio de separacion de ambos lado de su fila centrandolo solo en el eje vertical.

d.end : Mueve el item hacia el fin de su fila en el eje Horizontal.



3.place-items : Es un acortado de (aling-items - justify-items).


     ** Propiedades Para mover las filas y columnas dentro del contenedor **


Estas propiedades seran efectivas siempre y cuando haya espacion en el contenedor para mover las filas u columnas sino no.


1.justify-content : Se usa para mover la fila dentro del contenedor en el eje Horizontal.


a.stretch (default) : Es la propiedad que trae por default.

b.start : Mueve las columnas hacia el inicio del contenedor en el eje Horizontal.

c.center : Centra las columnas en el medio del contenedor dejando el mismo espacio de separacion de ambos lado del contenedor centrandolo solo en el eje Horizontal.

d.end : Mueve las columnas hacia el fin del contenedor en el eje Horizontal.

e.space-arround : Divide el espacio que hay en el contenedor en partes entre las columnas en el eje horizontal.

f.space-between : Hace que las columnas se separen lo mas que puedan mientra el espacio que haya en el contenedor lo permita solo separa entre columnas y no de las esquinas del contenedor y esto lo hace en el eje horizontal.

g.space-evenly : Separa las columnas en el eje horizontal dandole la misma distancia de ambos lado tanto entre columnas como entre el espacio que hay a las esquinas del contenedor.





2.aling-content : Se usa para mover la fila dentro del contenedor en el eje vertical.

a.stretch (default) : Es la propiedad que trae por default.

b.start : Mueve las filas hacia el inicio del contenedor en el eje vertical.

c.center : Centra las filas en el medio del contenedor dejando el mismo espacio de separacion de ambos lado del contenedor centrandolo solo en el eje vertical.

d.end : Mueve las filas hacia el fin del contenedor en el eje vertical.

e.space-arround : Divide el espacio que hay en el contenedor en partes entre las filas en el eje vertical.

f.space-between : Hace que las filas se separen lo mas que puedan mientra el espacio que haya en el contenedor lo permita solo separa entre filas y no de las esquinas del contenedor y esto lo hace en el eje vertical.

g.space-evenly : Separa las filas en el eje vertical dandole la misma distancia de ambos lado tanto entre filas como entre el espacio que hay a las esquinas del contenedor.




    ** Propiedades de manejo indivial de items **

1.aling-self : Se usa para mover los items de manera individual en el eje vertical.

Posee las propiedades (stretch - start - center - end)


2.justify-self : Se usa para mover los items de manera individual en el eje horizontal.

Posee las propiedades (stretch - start - center - end)


3.place-self : Es un acortado de las propiedades (aling-self - justify-self)

stretch(default) - start- center - end



4.order (igual que en flex) : Se usa para que cuando se le de un valor dependiendo si es mayor o menor esta antes o despues de otro item, es como el z-index pero esta mueve los item en el eje que apunte el track.




    -- Grid Areas --

Es cuando una celda ocupa uno o mas  espacios dentro de las filas o columnas del contenedor, esto lo hacemos declarando el "grid-template-areas" y colocamos variables en los espacio donde queremos que item ocupe en filas y columnas luego declaramos el grid area dentro del item que le queremos asignar ese espacio y le damos como valor el nombre de la variable.

Una vez usado el grid areas se crean las filas y columnas para que los item con grid area abarquen el espacio indicado con el grid-template.areas.



    ** nombre a filas y columnas **

Se le puede colocar nombre a las filas y columnas al momento de declararlas en el grid-template esto se hace con corchetes antes de cada linea y se le coloca el nombre dentro de cada corchetes.



    ** grid-template  Acortador **

Es un acortador que lo usamos para manejar 3 propiedades como lo son:

grid-template-rows
grid-template-columns
grid-template-areas

para usar rows y columns se coloca grid-template y se pasa los valores para crear filas y columnas.
## Resumen Parte IV

**Conceptos Grid**


Grid Es una propiedad de display y se usa para trabajar el layout de la pagina, con grid la trabajamos en forma de grillas(Rejas), esto quiere decir que los elementos se trabajan dentro de Celdas que estas dentro de filas y columnas y a la vez estas estan dentro de un grid container.

1.Grid Container : Es el contenedor del grid que al igual que el display flex cuando aplicamos display grid el contenedor no sufre cambios sino que solos item que estan dentro de ese contenedor el que sufren el cambio.


2.Grid Item : Son todos los elementos que estan dentro del grid container y que son hijos directos del contenedor con display grid y OJO estos no son lo mismo que las celdas, ya que los item son los elementos como las etiquetas imagenes y otros tipos que hay y las celdas estan definidas por el numero de filas y columnas que se coloquen.


3.Grid Cell : Son cada espacio cuadrado que compone y que dividen la grilla(reja), el numero de celdas lo define el numero de filas y columnas que se coloque en el grid container.


4.Grid Tracks (Column y Row) : Son las filas y columnas que hay dentro de cada contenedor grid.


5.Grid Area : Un area es cuando una celda ocupa mas de una fila o columna, estas areas la definimos nosotros y para defininirla deben ser en celdas consecutivas tanto en filas como en columna no pueden estar en (diagonal, L, p o cruses) pueden ser en filas y columnas al mismo tiempo pero en espacios cuadrados o rectagulares.


6.Grid Line (Column Line y Row Line) : Son las filas y columnas que componen la grilla(reja) del grid container cada una de las column line y row line se empiazan a contar desde las esquina del contenedor.



    -- Propiedades --

Una vez que aplicamos el display grid al contenedor en automatico todos los elementos hijos se convierten en grid-item los cuales los podemos modificar con las siguiente propiedades.

1.grid-templete-rows (Grid container) : Se usa para crear filas dentro del contenedor, dandole la medida de la fila o filas que tendra.


2.grid-templete-columns (Grid container) : Se usa para crear columnas dentro del contenedor, dandole la medida de la columna o columnas que tendra.

Unidades "auto" y fr : El fr se usa para repartir el espacion que puede tener la grilla ya sea entre fila o columna, es decir las filas o columnas que sean de medidad fr no poseeran una medida fija sino que dependera del tamano del contenedor y el espacion que ocupen las demas filas o columnas.


repeat (cantidad, tamaño/s) : Se usa para crear varias filas o columnas a la vez solo hay que indicarle la cantidad y el tamaño que tendra y de esta manera abreviamos el escribir una por una las filas o columnas solo lo colocamos en repeat las medidas y la cantidad de veces que se colocara.



3.grid-row-gap (Grid container) : Se usa para separar las filas unas de otras la distancia que le indiquemos pero estas no se separaran de los bordes del contenedor.


4.grid-column-gap (Grid container) : Se usa para separar las columnas unas de otras la distancia que le indiquemos pero estas no se separaran de los bordes del contenedor.


5.grid-gap : row - column (Grid container) : Es un acortador de (grid-row-gap - grid-column-gap) que se usa para separar los grid-item entre ellos se coloca la distancia que se separaran uno de otro, pero estos no se separaran de los bordes del contenedor.



6.grid-row-start (Grid item) : Se usa en el item para indicar desde que linea de las filas empieza el espacio de este item.


7.grid-row-end (Grid item) : Se usa en el item para indicar hasta que linea de las filas terminara el espacio de este item.


8.grid-column-start (Grid item) : Se usa en el item para indicar desde que linea de las columnas empieza el espacio de este item.


9.grid-column-end (Grid item) : Se usa en el item para indicar hasta que linea de las columnas terminara el espacio de este item.


10.grid-row (Grid item) : Es un acortador de (grid-row-start - grid-row-end) se usa para modificar la cantidad de filas que ocupara el item dentro del contenedor, pudiendo incluso desplazar otros item de ser necesario hacia otras filas.


11.grid-column (Grid item) : Es un acortador de (grid-column-start - grid-column-end) se usa para modificar la cantidad de columnas que ocupara el item dentro del contenedor, pudiendo incluso desplazar otros item de ser necesario hacia otras columnas.


   -- Uso de Span  con (grid-row - grid-column) --

Se coloca desde que linea arracara el item y se coloca "span" mas el numero de columnas o filas que ocupara para que tomando el punto de partida ya establecido tome filas y columnas y no sea linea por linea.




    -- Grid Implicito y Explicito --

Grid Implicito : Es el espacio que esta incluido en el contenedor pero sin ser expresado al menos que se le agreguen mas elementos que se salgan de las filas o columnas que ya se establecieron.

    -- Propiedades del Grid Implicito --


1.grid-auto-row (Igual que el template) : Es la forma de hacer que se generen filas automaticas en el espacio implicito si hay mas item que estan quedando por fuera.


2.grid-auto-column (Igual que el template) : Es la forma de hacer que se generen columnas automaticas en el espacio implicito si hay mas item que estan quedando por fuera.


3.grid-auto-flow Row(default), Column y Dense : Se usa para rellenar los huecos que quedan cuando hacemos que celdas ocupen mas espacio que el predeterminado por nosotros, esto hace que se creen mas filas o columnas en el espacio implicito rompiendo la figura de la grilla y hay el dense hace que se rellene esos espacios.



    -- Grid Dinamico --   (Quede aqui)

Hace que la grilla y su contenido se ajusten al tamaño del contenedor y que si se hace grande el contenedor se hara grande el contenido y si se reduce el contenido tambien lo hara y se ajustara dependiendo del tamaño.


1.minmax() : Se usa para establecer un minimo y un maximo en el tamaño que tendra el contenido dentro de la grilla, pasandole dos parametros de medidas que son el minimo de tamaño que puede tener y el maximo de tamaño que puede llegar.


2.min-content : Hace que la celda se ajuste al minimo de tamaño donde quepa su contenido y que pueda tener espacio  para que entre su celda.


3.max-content : Hace que la celda se ajuste al maximo de tamaño donde una linea completa de su contenido que en la celda completamente de hay no se reducira mas de tamaño esa celda.

**cantidad** 

5.auto-fill : Se usa para que genere columnas dinamicamente, las va generando a medida de que se valla haciendo mas espacio en el contenedor y el espacio es suficiente genera otra columna, si el espacio no es suficiente reparte el espacion que hay entre las otras columnas de ser necesario.


6.auto-fit : Es parecido a auto-fill pero esta propiedad cuando se acaban los item y quedan en una sola linea y el contenedor se sigue haciendo mas grande escala los item, es decir los hace mas grande para que abarquen el tamaño de fila.

Igual crea mas columnas pero cuando todos los item estan en una sola columna y sigue incrementando el espacio del contenedor hace los item mas grandes para que se ajusten a la fila.




    ** Alineacion y Control de Flujo **

Diferencia con flex :

_La alineacion es dentro de cada celda y no alineacion total del flex container.

_Cada celda seria un "flex container".



    -- Propiedades del grid Container --


     ** Propiedades para mover los items dentro de las filas **


Estas propiedades seran efectivas siempre y cuando haya espacion en la fila o columna para mover el item sino no.


1.justify-items (Horizontalmente) : Se encarga de mover los items dentro de las columnas en el eje Horizontal, solo los items.


a.stretch (default) : Es la propiedad que trae por default.

b.start : Mueve el item hacia el inicio de su columna en el eje Horizontal.

c.center : Centra el item en el medio de su columna dejando el mismo espacio de separacion de ambos lado de su columna centrandolo solo en el eje Horizontal.

d.end : Mueve el item hacia el fin de su columna en el eje Horizontal.




2.aling-items (Verticalmente) : Se encarga de mover los items dentro de las filas en el eje vertical, solo los items.


a.stretch (default) : Es la propiedad que trae por default.

b.start : Mueve el item hacia el inicio de su fila en el eje vertical.

c.center : Centra el item en el medio de su fila dejando el mismo espacio de separacion de ambos lado de su fila centrandolo solo en el eje vertical.

d.end : Mueve el item hacia el fin de su fila en el eje Horizontal.



3.place-items : Es un acortado de (aling-items - justify-items).


     ** Propiedades Para mover las filas y columnas dentro del contenedor **


Estas propiedades seran efectivas siempre y cuando haya espacion en el contenedor para mover las filas u columnas sino no.


1.justify-content : Se usa para mover la fila dentro del contenedor en el eje Horizontal.


a.stretch (default) : Es la propiedad que trae por default.

b.start : Mueve las columnas hacia el inicio del contenedor en el eje Horizontal.

c.center : Centra las columnas en el medio del contenedor dejando el mismo espacio de separacion de ambos lado del contenedor centrandolo solo en el eje Horizontal.

d.end : Mueve las columnas hacia el fin del contenedor en el eje Horizontal.

e.space-arround : Divide el espacio que hay en el contenedor en partes entre las columnas en el eje horizontal.

f.space-between : Hace que las columnas se separen lo mas que puedan mientra el espacio que haya en el contenedor lo permita solo separa entre columnas y no de las esquinas del contenedor y esto lo hace en el eje horizontal.

g.space-evenly : Separa las columnas en el eje horizontal dandole la misma distancia de ambos lado tanto entre columnas como entre el espacio que hay a las esquinas del contenedor.





2.aling-content : Se usa para mover la fila dentro del contenedor en el eje vertical.

a.stretch (default) : Es la propiedad que trae por default.

b.start : Mueve las filas hacia el inicio del contenedor en el eje vertical.

c.center : Centra las filas en el medio del contenedor dejando el mismo espacio de separacion de ambos lado del contenedor centrandolo solo en el eje vertical.

d.end : Mueve las filas hacia el fin del contenedor en el eje vertical.

e.space-arround : Divide el espacio que hay en el contenedor en partes entre las filas en el eje vertical.

f.space-between : Hace que las filas se separen lo mas que puedan mientra el espacio que haya en el contenedor lo permita solo separa entre filas y no de las esquinas del contenedor y esto lo hace en el eje vertical.

g.space-evenly : Separa las filas en el eje vertical dandole la misma distancia de ambos lado tanto entre filas como entre el espacio que hay a las esquinas del contenedor.




    ** Propiedades de manejo indivial de items **

1.aling-self : Se usa para mover los items de manera individual en el eje vertical.

Posee las propiedades (stretch - start - center - end)


2.justify-self : Se usa para mover los items de manera individual en el eje horizontal.

Posee las propiedades (stretch - start - center - end)


3.place-self : Es un acortado de las propiedades (aling-self - justify-self)

stretch(default) - start- center - end



4.order (igual que en flex) : Se usa para que cuando se le de un valor dependiendo si es mayor o menor esta antes o despues de otro item, es como el z-index pero esta mueve los item en el eje que apunte el track.




    -- Grid Areas --

Es cuando una celda ocupa uno o mas  espacios dentro de las filas o columnas del contenedor, esto lo hacemos declarando el "grid-template-areas" y colocamos variables en los espacio donde queremos que item ocupe en filas y columnas luego declaramos el grid area dentro del item que le queremos asignar ese espacio y le damos como valor el nombre de la variable.

Una vez usado el grid areas se crean las filas y columnas para que los item con grid area abarquen el espacio indicado con el grid-template.areas.



    ** nombre a filas y columnas **

Se le puede colocar nombre a las filas y columnas al momento de declararlas en el grid-template esto se hace con corchetes antes de cada linea y se le coloca el nombre dentro de cada corchetes.



    ** grid-template  Acortador **

Es un acortador que lo usamos para manejar 3 propiedades como lo son:

grid-template-rows
grid-template-columns
grid-template-areas

para usar rows y columns se coloca grid-template y se pasa los valores para crear filas y columnas.
## Ejemplo de Codigo

- Clase Principal 

```css
*{
    margin: 0;
    padding: 0;
    font-family: sans-serif;
    font-weight: 100;
}

.flex-container{
    display: flex;
    height: 25vh;
}

.flex-item {
    background-color: #456;
    color: white;
    text-align: center;
    min-width: 120px;
    height: 100px;
}

/*Uso de margin dentro de los flex-box*/
.orange{
    background-color: orange;
    margin-top: auto;
    margin-left: auto;
}

.green{
    background-color: green;
    margin-bottom: auto;  
    margin-top: auto;
    align-self: flex-start;  
}

/*Uso de flex-wrap para hacer que cuando el elemento sobrepase el ancho
de la pantalla baje a la otra linea */
.flex-container2{
    display: flex;
    height: 25vh;
    flex-wrap: wrap;
}

/*aqui se uso el flex-grow para las 3 cajas contenedoras esto se usa para
    repartir el espacio que sobra en la pagina entre las cajas que contengan
    el flex-grow y dependiendo del numero que tengan sera la partes de 
    espacio que le corresponda.*/
.uso-flex-item{
    background-color: #456;
    color: white;
    text-align: center;
    min-width: 250px;
    height: 100px;
    color: black;
    flex-grow: 1;
    width: 300px;
}

/*se uso la propiedad order que es como z-index pero se orienta dependiendo
    hacia donde este apuntando el main axis*/
.blue{
    background-color: blue;
    /*flex-grow: 1; si lo usamos en un item en particular todo el espacio 
        sobrante lo abarcara es item*/
        order: 200;
}

/*aqui se uso flex-basis que es como usar width pero para flex-item y 
    tiene mayor prioridad
  tambien se uso flex-shrink que el contrario de flex-grow y se usa para
    que las cajas sedan espacio a medida de que se reduce la resolucion
    flex-shrink se nota mas su uso sin la propiedad flex-wrap en ejecucion*/
.yellow{
    background-color: yellow;
    flex-basis: 400px;
    flex-shrink: 2;
    order: 2;
}

.red{
    background-color: red;
    order: 20;
}
```


```css
*{
    font-family: sans-serif;
    font-weight: 100;
}

body{
    background: radial-gradient(circle,#fff,#bbb);
    padding: 20px;
}

.grid-container{
    display: grid;
    /*esta es la forma de crear columnas y filas de manera larga. 
    grid-template-columns: 150px 150px 150px 1fr;
    grid-template-rows: 150px 150px 150px;
    */

    /*Esta es la forma de hacelo acortado
    grid-template-columns: repeat(4 1fr);
    */

    
    grid-template-columns: 150px 150px 150px 1fr;
    grid-template-rows: 150px 150px 150px;
    border: 3px solid #000;
    /*el grid-gap se usa para indicar separaciones entre filas y columnas*/
    grid-gap:10px;
    background: #333;
}

.grid-item{
    border: 1px solid #000;
    background: #999;
}

/*aqui usamos el nombre de la clase mas first-child para seleccionar el 
    primer elemento que esta dentro de esta clase y asi solo otorgarle
    los estilos a esta, se le dio grid-column y grid-row que es para
    la cantidad de filas y columnas que va ocupar la celda*/
.grid-item:first-child{
    background: #900;
    grid-column: 1/3;
    grid-row: 1/3;
}

.grid-item:nth-child(2){
    background: #090;
    grid-column: 3/5;
    grid-row: 1/3;
}

```


```css
*{
    font-family: sans-serif;
    font-weight: 100;
}

body{
    background: radial-gradient(circle,#fff,#bbb);
    padding: 15px;
}
/*uso de min y max content que usamos para otorgar un minimo y 
    un maximo al contenido de la caja contenedora de display grid*/
.grid-container{
    display: grid; 
    grid-template-columns: repeat(auto-fill, minmax(100px, 1fr));
    grid-template-rows: repeat(3,100px);
    grid-auto-rows: 1fr;
    grid-auto-columns: 1fr;
    border: 3px solid #000;
    background: #333;
    grid-auto-flow: dense;
}

.grid-item{
    border: 1px solid #000;
    background: #999;
}
```


```css
*{
    font-family: sans-serif;
    font-weight: 100;
}

.container{
    background: #086f;
    padding: 20px 5px;
}

.caja{
    background: #025;
    height: 80px;
    width: 80px;
    transition-property: left, background;
    transition-duration: 5s, 1s;
    margin: 20px;
    border: 2px solid #000;
    position: relative;
    left: 0;
    color: #fff;
    text-align: center;
    font-size: 70px;
}

.container:hover > .caja{
    left: 80%;
}

.container:hover > .caja:first-child{
    transition-timing-function: linear;
    background: mediumvioletred;
}

.container:hover > .caja:nth-child(2){
    transition-timing-function: ease;
    background: mediumspringgreen;
}

.container:hover > .caja:nth-child(3){
    transition-timing-function: ease-in;
    background: mediumblue;
}

.container:hover > .caja:nth-child(4){
    transition-timing-function: ease-out;
    background: lime;
}

.container:hover > .caja:nth-child(5){
    transition-timing-function: ease-in-out;
    background: gold;
}

```



## Autor

- [@GabrielTorrealba](https://github.com/GabrielJose2102)

