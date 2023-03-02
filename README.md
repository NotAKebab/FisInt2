# Sistemas Físicos interactivos 2

# Galería Cosmere

[Proyecto de Unity](https://github.com/NotAKebab/Cosmere)

Esta es un breve documento de diseño en el que se va a resumir brevemente los avances completados a lo largo del semestre

ID:425705 Esteban Gallón Uribe

ID:425629 Juan Sebastián Giraldo

ID:424790 Sebastián Ayala Arroyave

## Prototipo 1

Para este prototipo, se llevó alrededor de un fin de semana, principalmente al ser la primera vez que trabajamos con un oculus, empezamos por actualizar el software de los oculus, conectar la cuenta a un dispositivo móvil y obviamente, probar lo básico. Esto llevó unas horas en hacer para ser el primer día, de aquí, teniendo la idea planeada en una galería de los planetas del universo de Brandon Sanderson "Cosmere" agarramos la idea de hacerla con el passtrough de las Quest 2, creando una realidad mixta, para tener un sistema más inmersivo, abajo dejaré referencias de los videos que se usaron para estudiar el passtrough

https://www.youtube.com/watch?v=RtoTGYBdGI4

https://www.youtube.com/watch?v=SJANudr3Wu0

https://youtu.be/9u3QQi6Gnx0

En verdad lo que más consumió tiempo fue el setup de todo, unity, oculus, plugins, etc. tras esto faltaba implementar algo más que solo el uso del passtrough, el handtracking para usar en la aplicación, en primera también medio día se fue aprendiendo un poco sobre los development kits que se ofrecían para el handtracking, tanto el propio para las quest 2, como otros, abajo dejo las referencias de los videos estudiados, otro punto a resaltar es que para trabajar en unity con el passtrough no tienes manera de ver una preview de lo que vayas haciendo así que hubo un paso extra para instalar aplicaciones externas (Instalar sidequest, hacer el setup completo para el sidequest, sí, también llevo una o dos horas)

https://www.youtube.com/@dilmerv  (La cantidad de contenido estudiado de este solo canal es bastante)

https://www.youtube.com/@ValemTutorials (De este también, todo lo de SDK Interaction también fue revisado)

https://github.com/microsoft/MixedRealityToolkit-Unity


Nos decidimos por un estilo artistico tipo lowpoly y usamos assets de Unity para los Ambientes

https://assetstore.unity.com/packages/3d/environments/landscapes/lowpoly-environment-pack-99479

https://assetstore.unity.com/packages/3d/environments/landscapes/lowpoly-style-free-rocks-and-plants-145133


## Prototipo 2

Repositorio para los prototipos:
- El código de todos los proyectos de software involucrados.
- Documentar el proceso, pruebas intermedias, qué funcionó, qué no funcionó, qué problemas tuviste, cómo se solucionaron, que material consultaste.
- Documenta en fotos y video (coloca enlaces) del proceso y del resultado final del prototipo.


avance

En la parte narrativa:
El usuario se encontrar en un espacio con tres carpas plegables rodeando una mesita con unos Oculus con unos cascos conectados, un encargado le explicara lo más básico (que entrará a una experiencia interactiva de una parte del Cosmere, el cual es un universo literario creado por Brandon Sanderson y deberá seguir las instrucciones que la experiencia le asigne al usuario).
El usuario al acceder se encontrará entonces con un espacio en blanco y negro que será en realidad aumentada y tres pósters digitales interactivos. De inmediato escuchará la voz de un personaje representativo de la saga, en este caso será Hoid, este le pedirá ayuda entrando a cada mundo para hablar con alguien pero este no especificará para qué.

El usuario procederá a entrar a cada uno de los mundos
Scadrial, mundo en el que transcurre los sucesos de mistborn, al entrar se verá en una calle, pero está llena de Bruma en la que apenas podrá ver, Vin, personaje principal de la primera saga de libros, verá un potencial mágico en el usuario y le explicará la magia del mundo, el poder de acercar y alejar cosas de metal a su alrededor, luego el usuario podrá quedarse a experimentar o pasar al siguiente mundo, para esto Hoid le insistirá en recordar su misión.
![image](https://user-images.githubusercontent.com/68132813/221429010-8af1a900-c665-45e1-9210-60bd7e862f53.png)

Sel, planeta de los sucesos de elantris, en este caso el usuario se encontrará en un espacio similar a un interior de una catedral de mármol donde se cruzará con Raoden, este también le ayudará a aprender a usar sus poderes, en este caso tendrá que hacer símbolos en una tabla en el aire con los dedos, acá podrá seguir practicando, pero Hoid insistirá en que siga en la búsqueda. 
![image](https://user-images.githubusercontent.com/68132813/221429084-1b5b87db-1daa-4335-a283-b514fa39be1e.png)

Por último, Nalthis, mundo de Warbreaker, en este se encontrará en una habitación abandonada, donde se encontrará con Vivenna, esta verá su potencial y le explicarán sobre los "alientos" que los alientos sirven para varias cosas entre otras es ver los tonos perfectos de los colores, detectar los alientos de otras personas, pero principalmente que se le puede dar órdenes a otros objetos gastando los alientos que tienes. Podrás practicar y la voz de Hoid te dirá que salgas para continuar.
![image](https://user-images.githubusercontent.com/68132813/221429157-c916e7c8-75a6-4651-b669-a83c10103a45.png)


Al salir del último de los mundos, una voz te va a reclamar por lo que estás haciendo, Brandon Sanderson, el escritor de todos los libros.

Brandon Sanderson invoca a una criatura para matarte, en este punto el jugador con lo aprendido tiene que deshacerse de la criatura.
![image](https://user-images.githubusercontent.com/68132813/221429180-d3100be3-3a63-49cc-8634-8f95f87ff406.png)
![image](https://user-images.githubusercontent.com/68132813/221429206-fa252d55-3f8b-4439-931a-c05ed8d610ea.png)

Al desterrar a la criatura enviada por Sanderson, oyes la voz de Sanderson nuevamente, diciendo que igualmente iba a recuperar lo robado, siendo él creador de todo lo que hay alrededor, elimina los poderes del usuario y retorna todo al inicio de la experiencia.




![image](https://user-images.githubusercontent.com/68132813/221428710-65e968f3-df28-4678-bf03-6fd1083c3f01.png)


con suficiente playground, mejor iniciar de 0

![image](https://user-images.githubusercontent.com/72229509/221386458-1b9ccd08-b412-4d6e-8cd0-4f26abae516e.png)
![image](https://user-images.githubusercontent.com/72229509/221386462-cc744b5c-b91e-481e-a53d-b822f4527055.png)

Al tener como error principal no haber empezado el proyecto en 3D URP (algo necesario para poder trabajar con el passtrough de los oculus), hacerlo manualmente generaba errores en las texturas, bueno obviamente más assets gratis para tener algo de "idea" que funcione bien lo que queremos lograr

## Links de los assets
* https://assetstore.unity.com/packages/3d/environments/stylize-modular-house-demo-free-erbeilo-3d-220218
* https://assetstore.unity.com/packages/3d/environments/house-pack-35346
* https://assetstore.unity.com/packages/3d/environments/free-medieval-room-131004
* https://assetstore.unity.com/packages/3d/environments/dungeons/ultimate-low-poly-dungeon-143535
* https://assetstore.unity.com/packages/3d/environments/cabin-environment-98014


