# DIU - Practica 3, entregables

## Análisis de MuseMap   
Inicialmente MuseMap llevo a cabo un **EmpathyMap** para poder identificar rápidamente a sus potenciales usuarios y tener su perfil exacto, seguidamente realizaron una **encuesta** y seleccionaron a los candidatos más prometedores y tras una entrevista y la correspondiente recopilación de datos llevaron a cabo un **Affinity Map**, técnica que les sirvió para ver que había diferencias entre las suposiciones hechas y la realidad y poder identificar los posibles perfiles de usuarios.  
Identificaron dos tipos de usuarios, el primer tipo de usuarios son los que se encuentran el arte por casualidad, Tom, y el segundo tipo de usuario lo busca, Jan, para los dos crearon un **User Personas**.  
Para Tom crearon un **User Journey** y un **Experience Map**, técnicas que ayudaron a identificar el problema principal: la gente de Londres no se involucra lo suficiente con el arte urbano y si lo hace su participación es de poca duración.  
Una vez identificaron el problema y tener las ideas claras era hora de empezar con la fase de diseño, en primer lugar realizaron un **User Flow** para ver como los usuarios realizan las tareas y sacar unos patrones, seguidamente empezaron un **Design Studio** donde se crearon una versión inicial de los bocetos, para poder priorizar las tareas usaron la técnica de **Feature Prioritisation**, que no es más que una matriz donde se clasifican las tareas.  
Finalmente una vez se habían clasificado las tareas empezaron a diseñar y a iterar, en primer lugar se llevo a cabo una primera fase de diseño sobre el papel donde se explicaba todo más detalladamente y su correspondiente **Usability testing** sobre los bocetos de papel y viendo que lo que habían hecho no era adecuado decidieron volver a diseñar los bocetos con una nueva idea y realizar otra vez un **Usability testin** pero esta vez con mejores resultados pero aun con problemas.  
Para mostrar como había evolucionado su maqueta realizaron un **Site Map** y un **Style Guiede**.  
  
En mi opinión las técnicas que más les aportaron fuerón en una fase inicial la **encuesta** y con la consecuente **Affinity Map** para poder ver si sus ideas se correspondían a la realidad después de haber escuchado y analizado la opinión de personas de fuera del entorno y para conseguir una buena identificación de los posibles perfiles de usuarios.  
En una fase más avanzada creo que fuerón cruciales el **Design Studio** junto al **Usability Testing** con el cual se dieron cuenta de que la primera versión era un callejón sin salida.  
Finalmente el **Site Map** es la técnica más útil en la etapa final.

## Propuesta de elementos de diseño o patrones a usar 

## Diseño 

##### Mostrar las características principales 
Para que los usuarios puedan ver las funcionalidades principales una vez abran la aplicación podremos cuatro botones en la parte inferior de la aplicación: Buscar, Añadir actividad, Mis actividades y Perfil; estos botones contendrán texto y iconos que se usan en otras aplicaciones de Android para que sea totalmente intuitivo y el usuario no tenga que aprender otros símbolos.
Además en la parte restante de la pantalla ya aparecerán actividades de la ciudad seleccionada en el registro y si ya se hubierán usado filtros en anteriores búsquedas se guardarían y se aplicarián al cargar la página.

##### Navegación dentro de la apliaciones
La navegación dentro de la aplicación: 
 - En todas las páginas de la aplicación siempre estarán visibles las cuatro opciones nombradas en el apartado anterior y se podrá acceder a ellas pulsándolas.
 - Para navegar dentro de las diferentes pantallas se mantendrá el estandar usado por la aplicaciones de android, es decir, según como deslices el dedo la página se deslizará vertical o horizontalmene y se podrá acceder a diferentes pantallas pulsando sobre los iconos.
 - En todas las pantallas de la aplicación usando el botón disponible en todos los dispositivos Android de 'Atrás' volveremos a la página principal, página que mantendrá las actividades de la última búsqueda. Tendremos varias excepciones:
     * Si nos encontramos dentro de una actividad a la cual hemos accedido por 'Mis Actividades' volveremos a esta página y no a la principal, será necesario darle dos veces al botón 'Atrás'.
     * Si estamos en el momento de pago y volvemos atrás volveremos a la actividad, será necesario darle dos veces para volver a la página principal

##### Formas de pago 
Una vez un usuario se ha decantado por una aplicación podrá acceder a pagarla pulsando el botón 'Compra Ahora' el cual le direccionará a una página donde le aparecerán las siguientes maneras de pagar:
- PayPal
- Visa
- Canjear bono
- Master Card 
- Cuenta Corriente  
De estas cinco maneras de pago saldrá como seleccionada la que tenga establecida en 'Perfil' -> 'Mis preferencias' -> 'Métodos de Pago', página en la cual podrá agregar, modificar y eliminar en cualquier momento cualquier método de pago. Esto evitará que cada vez que el usuario quiera pagar una actividad deba introducir los datos y se solo tenga que seleccionar el método de pago que quiere usar en esa ocasión.

##### Registro
El registro será muy sencillo y se podrá realizar de dos formas:
- Si se tiene una cuenta google se podrá acceder introduciendo el correo y la correspondiente contraseña y seguidamente verificando el correo que enviaremos a su cuenta, nostros nos encargaremos de recoger los datos y añadírselos al perfil de fever.
- Si no se tiene cuenta google se tendrá que rellenar un formulario que tendrá las siguientes características:
    * Los errores en el formulario se mostrarán en tiempo real y no se esperara al final 
    * El teclado que se mostrará coincidirá con las entradas de texto requeridas, es decir, en el caso que se tenga que introducir un número de teléfono aparecerá el teclado numérico.
   
##### Usabilidad y facilidad de compresión
 - En toda la aplicación se utilizará un vocabulario simple e intuitivo con frases como: 'Saber más' o 'Compra Ahora' y en ningún caso se utilizará terminología complicada, se puede dar el caso que dentro de la descripción de una actividad los usuarios si que usen vocabulario o términos de algún tema en específico.
 - Se contará con etiquetas de texto y teclas visuales para conseguir que la aplicación sea mas atractiva visualmente y a la vez más intuitiva de usar .
 - Como hemos nombrado anteriormente  facilidad a la hora de modificar, agregar y eliminar formas de pago.
 - Si durante el uso de la aplicación se accede a otras aplicaciones o se sale de la misma sin llegar a cerrarla se mantendrá la página en la cual estaba el usuario.
 
 ## Elementos visuales del diseño 
 
 ##### Colores 
 Después de haber investigado un poco nos hemos dado cuenta que los colores tienen un papel fundamental en las personas para tomar decisiones, hemos encontrado esta paleta fresca y armoniosa donde predominan el azul claro y el azul turquí y estan complemetados con el blanco y el negro     
 ![Colores](https://paletasdecolores.com/wp-content/uploads/2015/08/cvetovaya-palitra-2275.png)    
  
 
 ##### Iconos 
 Los iconos que utilizaremos en nuestra aplicación serán los msotrados en el **labelling**, aunque puedens sufrir pequeñas modificaciones de tamaño o color ajustandolos a los colores seleccionados en el apartado anterior.
 
  ##### Letras
 Hemos selccionado la tipografía **Alcubierre** tipografía que pertenece a las Sans-Serif 
 ![Colores](https://i2.wp.com/www.dafontfree.io/wp-content/uploads/2017/12/Alcubierre-full-image.jpg?resize=1125%2C7905&ssl=1)



## Historia en Video del UX Case Study


## Documentación. Valoración del equipo sobre la realización de esta práctica o los problemas surgidos

En la realización de esta práctica hemos obtenido dos conocimientos muy valiosos, en primer lugar hemos podido observar el proceso que han seguido los diseñadores de MuseMap y como las diferentes técnicas que han usado les han aportado diferentes conocimiento para ir ajustando su aplicación para lograr una buen producto. En segundo lugar hemos visto como las técnicas que usaban en MuseMap también nos eran de mucha utilidad además de aprender a resumir de una manera atractiva en un video la propuesta de nuestro producto.
El mayor problema que he tenido ha sido a la hora de diseñar los patrones de diseño, ya que, nunca había realizado algo similar y tuve que buscar mucha información y tomar muchas decisiones.
 
