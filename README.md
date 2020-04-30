# Data Lovers

# RESUMEN 
Este proyecto usa una base de datos de pokémon para que los usuarios de Pokémon GO puedan buscar información que les ayude a obtener pokémon con ciertas características o encontrar las fortalezas en los que ya tienen.

*** 

# PRESENTACIÓN
// IMG APARIENCIA FINAL

***

# INVESTIGACIÓN UX 

 ## PROTOTIPOS 
 
 ### - Prototipo papel y lápiz
 ![screen1](https://github.com/vvaldivi/SCL013-data-lovers/blob/master/img%20readme/papel1.jpeg)
 ![screen1](https://github.com/vvaldivi/SCL013-data-lovers/blob/master/img%20readme/papel2.jpeg)
 ![screen1](https://github.com/vvaldivi/SCL013-data-lovers/blob/master/img%20readme/papel3.jpeg)

 ### - Prototipo en Invision
 ![screen1](https://github.com/vvaldivi/SCL013-data-lovers/blob/master/img%20readme/invision1.jpg)
 ![screen1](https://github.com/vvaldivi/SCL013-data-lovers/blob/master/img%20readme/invision2.jpg)
 ![screen1](https://github.com/vvaldivi/SCL013-data-lovers/blob/master/img%20readme/invision3.png)

 ### - Prototipos en Figma

 #### - Escritorio 
 ![screen1](https://github.com/vvaldivi/SCL013-data-lovers/blob/master/img%20readme/Escritorio1.png)
 ![screen1](https://github.com/vvaldivi/SCL013-data-lovers/blob/master/img%20readme/escritorio2.png)

 #### - Móvil
 ![screen1](https://github.com/vvaldivi/SCL013-data-lovers/blob/master/img%20readme/Celular1.png)
 ![screen1](https://github.com/vvaldivi/SCL013-data-lovers/blob/master/img%20readme/Celular2.png)

 #### - Testeo en usuarios
Se realizó un testeo con usuarios entre 10 a 30 años, quienes nos indicaron que los colores siguen la identidad gráfica de Pokémon, que es agradable e intuitiva. Como sugerencia nos indicaron cambiar la simbología de la ficha del pokémon o que al pasar el cursor explique que son los símbolos ya que pueden ser poco claros.
 
***

 ## USUARIOS
   Los principales usuarios de nuestra web son jugadores de Pokémon Go que deseen saber y conocer a fondo a cada pokémon.
   Definimos que los usuarios parten desde los 10 años aproximadamente hasta usuarios nostálgicos de la serie de unos 45 años.
   Cómo solución a esta necesidad de información se usa una data con pokémones de la región Kanto, donde los usuarios podrán buscar por palabra clave o escoger entre tipo o debilidad del pokémon.


 ### HISTORIAS DE USUARIO

 #### HISTORIA 1 
 - Usuarios del juego Pokémon Go que necesitan información para poder capturar pokemons fuertes o aquellos que aun no capturan. 
 - Ver una web que contenga información Pokémon de la regón Kanto.
   ##### Criterios de aceptación: 
   - Crear un html de inicio con imagen y breve descripción y un footer.
   - Crear un menú con: tipo-debilidad-buscador-retorno al inicio

 #### Historia 2
 - Usuario que quiera clasificar a los pokémones por tipo para conocer la clase de poder de ataque que posee. 
   ##### Criterios de aceptación: 
   - Menú "TIPO" se despliegue con todos los tipos de pokémon.
   - Al escoger una opción se muestren los pokémon que contengan el Tipo seleccionado.

 #### Historia 3
 - Usuario que quiera clasificar a los pokémones por Debilidad para escoger a los pokémons más fuertes en batallas.
   ##### Criterios de aceptación:
   -Menú "DEBILIDAD" despliegue debilidad de cada pokemon por tipo.
   -Al escoger una opción se muestren los pokémon que contengan la DEBILIDAD seleccionado.
 
 #### Historia 4
 - Usuario que quiera conocer información detallada de un pokémon luego de haber realizado su búsqueda.
   ##### Criterios de aceptación:
   - Al seleccionar un pokemon se despliega una ficha con toda la información que la DATA posee sobre ese pokémon (Debilidad, tipo, caramelos, ataques, etc.)
   - Crear un contenedor para mostrar la ficha.
  
 #### Historia 5
 - Usuario que quiera saber la evolución de un pokémon para entrenarlo y conseguir la evolución deseada.
   ##### Criterios de aceptación:
   - En la ficha de datos crear una pestaña se desplegara otra con imágenes y nombres de las evoluciones del pokemon.
   - Poder ingresar desde esa ficha a la del pokémon evolucionado.

 #### Historia 6
 - Usuario que quiera ordenar alfabéticamente el resultado de su búsqueda para encontrar más rápido al pokémon que busca.
   ##### Criterios de aceptación:
   - Crear un select para ordenar alfabéticamente en forma ascendente y descendente una vez que se haya hecho el filtro seleccionado.

 #### Historia 7
 - Usuario que quiere buscar un pokémon por nombre u otra característica sin necesidad de usar el menú para que su búsqueda sea más rápida.
   ##### Criterios de aceptación:
   - Crear un input donde se buscara dentro de la data y mostrará en pantalla según la palabra que ingreso el usuario.

#### Historia 8
 - Usuario usuario que aun no está familiarizado con todos los conceptos de Pokémon GO y quiera saber más acerca del juego para subir de  nivel.
   ##### Criterios de aceptación:
   - Se mostraran tips en el "home" para que el usuario pueda conocer mas sobre los pokémons y así podamos guiar un poco sus búsquedas, se crea una barra lateral con tips, que al ser presionados se despliega la información con ejemplos e imágenes.
