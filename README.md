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

Avance

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

Acá todo normal, mas que empieza a haber un problema, ninguna textura quería volver a su normalidad, incluso después de muchas posibles soluciones, nada funcionaba y al ser assets ya definidos no teníamos mucho control del material como para moverlo como si nada, entonces, para ahorrar tambien problemas a futuro, se creó un neuvo proyecto de unity.

Igualmente, copiar y pegar lo ya hecho, tampoco era un problema, organicé un espacio distinto de assets dentro del portal ya más adaptado a lo que se quería lograr con los assets gratis

![image](https://user-images.githubusercontent.com/72229509/222336048-eaf7ffe7-ade7-4960-bf11-5af57d02f23a.png)

Incluso, se hicieron los tres portales planeados, aunque sin los assets finales planeados, sin embargo, ya están los tres funcionales para entrar y salir, pero, ahora como hacer para activar un portal u otro?

## Avance 3.1


Se avanzo a la hora de hacer modelos para los personajes que ayudaran al usuario, estos son Vin(Mistborn)
![image](https://user-images.githubusercontent.com/68132813/222533468-d9f00f85-1071-404b-8957-9d221c9f4507.png)
Raoden(Elantris)

![image](https://user-images.githubusercontent.com/68132813/222533640-00a8a78a-7922-45df-aed9-ab684e77c6c9.png)
Vivenna(Warbreaker)

![image](https://user-images.githubusercontent.com/68132813/222533810-452a23e0-5812-46ea-9c5c-a3f5f20d0e0c.png)

Para esto empezamos con un modelo humanoide base
![image](https://user-images.githubusercontent.com/68132813/222534081-b2ee0ff6-dbf1-478f-9b4d-628865918059.png)

y a partir de este empezamos a crear la indumentaria y atuendos, por ahora tenemos una camisilla.

![image](https://user-images.githubusercontent.com/68132813/222534202-fe678aa1-54b9-4f28-92ba-32b97c108929.png)
![image](https://user-images.githubusercontent.com/68132813/222534233-ce73949c-daa4-40f7-adb9-b424cdf31105.png)


Intentando aplicar los assets para cada portal, tuve un error del cual no tenemos solución actual, visualmente las capas del portal 2 está sobre la del 1, sin embargo son funcionales como esperamos
![image](https://user-images.githubusercontent.com/72229509/222536414-324e96e9-d5c2-4db0-a048-e67eef6b7503.png)
![image](https://user-images.githubusercontent.com/72229509/222536696-37ad351e-5167-41c2-8dd2-24f5af62f3fc.png)

Sin embargo,  si no logramos solución para las previews, se está intentando bajo script con una idea en mente.
Narrativamente en el universo existen las esquirlas, que son piedras de la creación, las cuales reciben nombre de una característica o ideal específico, las piedras elegidas de momento son, dotación (verde), devoción (verde/rojo) y conservación (blanco), la idea del script es desactivar las capas y cuando la esquirla toque un collider active las capas del portal correspondiente (no sabemos programar, esperamos tenerlo listo para el prototipo 3 completo)

## Avance 3.2
Se definió como objeto para interactuar tres botones que se conectaran por bluethoot, aun estamos pensando bien en esto, ademas conseguismo terminar el cuerpo de humano base y de enemigo final base(koloss) de este ultimo tuvimos varias variaciones

![image](https://user-images.githubusercontent.com/68132813/224136434-2d157a41-70ca-46e8-9c5f-ef8681d9ad4e.png)
![image](https://user-images.githubusercontent.com/68132813/224136475-5c9fc151-1f1c-4dee-85ae-ce63f6c0527c.png)

de estas nos quedamos con el ultimos

para el modelo del humano creamos esta base y terminamos las primeras prendas

![image](https://user-images.githubusercontent.com/68132813/224136991-f9f1aec4-5e4f-40f6-a922-2c7cdd0bd398.png)

![image](https://user-images.githubusercontent.com/68132813/224136930-d7f48139-b9cf-4b68-a41b-ffca7bf370cd.png)

![image](https://user-images.githubusercontent.com/68132813/224137978-50a0e146-386a-4b39-aa5a-6ad57328ae2f.png)

En la parte técnica se hicieron las esquirlas que activan y desactivan al estar en contacto con un collider, y cambiamos de idea de tener varios portales a tener solo uno para solucionar el bug que teníamos de los múltiples portales con la misma proyección, desde unity, todo funcionaba bien pero tuvimos un error peor al lanzar el ejecutable, nada funcionaba realmente, inicialmente debería iniciar en el passtrough con el portal cerrado gracias al código de las esferas, pero empieza mirando dentro del portal, que se supone que está activo, 

## Prototipo 3
Habián unos errores que nos forzaron a rehacer el proyecto desde 0, cosa que acabó funcionando.

Se hicieron los modelos del Koloss bebé y adulto en lowpoly

se hicieron unos ajustes en la narrativa para que resultara mas consistente con los mundos planteados por Brandon Sanderson:
Ya no tendremos una lucha final con brandon o alguna bestia que este nos lance, sino que cada mundo que visitemos nos pondra en una situacion cable que aparece en los libros, entre mas clave o con mas accion mejor, de esta forma cada mundo nos dara la suficciente accion y contexto, esto puede hacer que la persona se vea mas atraida al libro ya que estuvo en el por asi decirlo, aun hay que trabajar en que partes exactas de los libros, y cual es la motivacion del usuario.

## Avance 4.1
Se hicieron los botones en la App inventor:
Para esto tomamos de base este repositorio del profesor Juan Franco https://github.com/juanferfranco/appSensorActivity.
pero hicimos varias modificaciones, para empezar eliminamos la parte del mensaje porque no lo nececitamos y agregamos el sensor de proximidad.

![image](https://user-images.githubusercontent.com/68132813/227341049-af96d472-3cda-4f55-b859-08f3332e2888.png)

Ademas agregamos el componente de web, esto nos ayudara a crear los objetos json para enviarlo por udp a unity.

![image](https://user-images.githubusercontent.com/68132813/227341526-cc61f011-a1c1-4c21-a10a-aa90baf9c6b7.png)

luego de agregar estos componentes empezaremos a usar los bloques para codificar la aplicacion

![image](https://user-images.githubusercontent.com/68132813/227341716-d9496019-d9de-4e46-9a22-e32b1421d3f9.png)

En resumen, cada vez que se oprima el boton la aplicacion enviare la informacion del ip el cual asignaremos con el hotspot del celular, y la informacion del puerto que asignaremos como 6666, este numero es importante a la hora de hacer el codigo en c#, hay que recordar que para conectar la aplicacion y que funcione hay que apagar el firewall en el pc.

Luego usamos de base el codigo que se encuentra en el repositorio de referencia y modificamos para que la bola aparezca y desaparezca segun la distancia que envie el sensor de proximidad, esta listo para integrarse con todo el proyecto.


Se hizo un prototipo funcional en Unity pero hay que cambiar el hecho de que funciona con botón a que lo haga con temporizador.

Cambiamos la Narrativa y El estilo artístico:
Analizando la narrativa y el flujo del proyecto como gtal nos dimos cuenta que hubo un gran problema en en la motivacion para el usuario, ademas no encontrbamos escenas en el tercer mundo es decir el de warbreaker para que el usuario pudiera interactuar y que fuera atrpante, para esto decidimos eliminar completamente ese mundo quedandonos solo con dos, el de mistborn y elo de elantris.

Para el portal de Mistborn, el usuario entrara al portal y se encontrara en un pasillo de un fuerte, lo primero que encontrara sera un soldado y te dire que uses tus poderes, en los pasillos encontraras clavos y monedas de metal las cuales podras usar de proyectiles, avanzaras por el pasillo y te encontraras con Vin(personaje importante de los libros) y tendras que pelear con ella utilizando las mecanicas aprendidas.

Para el portal de Elantris, el usuario entrara al portal y se encontrara alineado con muchos NPCs relucientes, enfrente de estos se encontrara Galladon(personaje importante de los libros) este le estara enseñando a los NPCs y al usuario a dibujar un Aon(simbolo para poder utilizar la magia de este mundo) este servira para lanzar una bola de energia y hacer daño, luego de una pequeña practica aparece un enemigo este es un monje Dakhor, el cual es un enemigo del libro, estos monjes tienen sus huesos modificados por medio de esta magia que se encuentra en el mundo, haciendolos mas fuertes y mas bestiales. Luego de eliminar a este enemigo el usuario saldra de esta portal y acabara la experiencia.
![image](https://user-images.githubusercontent.com/68132813/228944285-cd029922-d4cf-43ac-ad1b-7d02fc4ecf0e.png)

![image](https://user-images.githubusercontent.com/68132813/228944693-83a3ff36-516b-472e-b795-e8ede01fcaff.png)

![image](https://user-images.githubusercontent.com/68132813/228944777-590589c0-cc95-435d-85b7-5da8c6d71f6c.png)


Aun no tenemos claro como se introducira al usuario ni como se motivara a usar la experiencia, tampoco como finalizara porque esto se ve afectado por lo anterior.

se realizó el modelo del Koloss bebé, aunque con el cambio de narrativa ya no es necesario este personaje.

## Avance 4.2

### 3 Escenas nuevas añadidas

![image](https://user-images.githubusercontent.com/72229509/228946799-81df3d23-58c1-40be-bd9c-5d9f93976806.png)

- En una nueva escena se arregló el problema del portal, queda la escena del portal malo para probar otras cosas.

- Cambiamos la idea de las esquirlas por ahora, para tener integrada la aplicación creada, está el código y la idea es ponerla aprueba en una escena extra.

- En la última escena está el playground con las mecánicas, donde recién se están haciendo pruebas con uno de los poderes, este poder se basa en poder lanzar y atraer monedas y clavos, cosa que, no hemos logrado y aún se siguen moviendo cambios.

En la parte de la narrativa pudimos clarificar y tenerla completa, al menos la base. El usuario al entrar a la experiencia se encuentra con una mesa, esta tendra una piedra, y al frente habran otras dos mesas con un plato cada uno, justo detras habran unos posters con una ilustracion, con el mundo que le corresponde a cada uno, ademas te encontraras con el portal pero estara desactivado y te encontraras con Hoid(Un personaje muy importante en el universo del Cosmere), eres uno de sus estudiantes y te pondra a prueba para seguir estando a su lado y seguir aprendiendo a ser un cuentahistorias de este universo, el te explicara lo basico de las esquirlas, es decir que todos los poderes vienen de esquirlas que contienen pedazos de un dios que due dividido hace mucho tiempo, y usando este poder deberas experimentar partes que el considera de provecho para crear historias, el te motivara a pasar las pruebas en cada mundo, cada mundo sigue igual al avance pasado, cada vez que vas a entrar a uno de estos mundos el te dara una breve explicacion de su magia y te dara una pequeña guia de lo que debes de hacer. al acabar la experiencia Hoid te felicitara por lograr conseguir tanta informacion para contar historias y te dira que puedes seguir siendo su pupilo pero por ahora debes de descansar y ese sera el final.

Hoid:
![image](https://user-images.githubusercontent.com/68132813/228951648-bd6039be-e1dc-4aa3-91af-26810e04ea32.png)


## Prototipo 4

Logramos implementar el portal con el sensor externo de forma correcta, debido a ciertos problemas con la activcion y desactivacion de las capas de los portales decidimos girarlo 180 grados en y de esta manera se vera el passtrough, el sensor al detectar algo en este caso la piedra hara que se gire el portal como si este estuviera activado. ademas agregamos una base del primero mundo, este es una especie de cabaña por dentro, hemos intentado integrar las mecanicas de los metales, pero nos han causado varios problemas por la integracion de las librerias, en este momento estamos intentando arreglar este problema. ademas ya tenemos los bocetos de los mundos completos. Nos falta agregar el sistema de dialogos, para esto usaremos fungus, de esta manera integraremos la narrativa al 100%. Faltan algunos cambios para el primer mundo, como el pasillo, pero en general esta la base. 

Tuvimos problemas con las mecanicas debido a que nos pasan bastantes problemas en el codigo debido a que no logra integrarse con lo que llevamos.

Ademas estuvimos trabajando en el modelo del enemigo del segundo mundo:
![image](https://user-images.githubusercontent.com/68132813/231866830-9feea62b-bd23-46b1-83e3-447112ecf722.png)

Hicimos cambios en el portal, esta hora solo muestra un color que cambia cuando esta activado o desactivado por la aplicacion del celular por color, ademas creamos una aplicacion que cumplira la funcion del master, esta permitira que el portal se active o no ya que le da permiso a la aplicacion del sensor para que pueda afectar el portal. Esto funciono pero a la hora de grabarlo no sabemos porque no se nota el cambio de color.

https://github.com/NotAKebab/FisInt2/assets/68132813/c5481f14-4f26-4334-9b86-688788541928

https://github.com/NotAKebab/FisInt2/assets/68132813/753d974e-3afa-4240-a688-9904f94df871

## Guía para el proyecto

Una guía rápida para entender y realizar de manera autónoma el proyecto es la siguiente:

* Para resumir el primer paso es configurar un proyecto de Unity dedicado a usarse la función del passtrough de los Oculus Quest. (revisar links prototipo 1, acá contienen todos los pasos a detalle y de manera visual)
* Acá los pasos van a variar de lo hecho en el proyecto y lo realmente planeado y ocurrido entre el prototipo 2 y 3, voy a mencionar los pasos para llegar al proyecto actual, el cual es más sencilo, más abajo dejaré una guía de pasos para llegar al proyecto planeado (en este se involucran los errores más por teoría y con mayor conocimiento de unity podría ser realizable), como un segundo paso es hacer un objeto con el componente de trigger, a este le vamos a añadir un código que sirva para activar el portal por medio del contacto con la MainCamera, esto se hace ya que la cámara principal son los Oculus, esto le da una sensación mucho más realista.
* Como tercer paso es crear las aplicaciones del Master y del sensor, estas tienen un script único pensado el cual puede entrar en un Game Object vacío, este va a dar las señales de lo que esté pasando entre las aplicaciones y el unity. (revisar el script "SensorUDP.cs" para entender mejor como funciona)
* Este código fue adaptado a cambiar de material cada que el sensor estuviera en OFF o en ON, sin embargo, esto también depende de el entendimiento del código del sensor.

### Guia Aplicaciones Master y Sensor

Se hicieron los botones en la App inventor:
Para esto tomamos de base este repositorio del profesor Juan Franco https://github.com/juanferfranco/appSensorActivity.
pero hicimos varias modificaciones, para empezar eliminamos la parte del mensaje porque no lo nececitamos y agregamos el sensor de proximidad.

![image](https://user-images.githubusercontent.com/68132813/227341049-af96d472-3cda-4f55-b859-08f3332e2888.png)

Ademas agregamos el componente de web, esto nos ayudara a crear los objetos json para enviarlo por udp a unity.

![image](https://user-images.githubusercontent.com/68132813/227341526-cc61f011-a1c1-4c21-a10a-aa90baf9c6b7.png)

luego de agregar estos componentes empezaremos a usar los bloques para codificar la aplicacion

![image](https://user-images.githubusercontent.com/68132813/227341716-d9496019-d9de-4e46-9a22-e32b1421d3f9.png)

En resumen, cada vez que se oprima el boton la aplicacion enviare la informacion del ip el cual asignaremos con el hotspot del celular, y la informacion del puerto que asignaremos como 6666, este numero es importante a la hora de hacer el codigo en c#, hay que recordar que para conectar la aplicacion y que funcione hay que apagar el firewall en el pc.

Para el master tomamos esta misma base pero cambiamos como se manda el codigo en si, ahora no nececitamos el sensor de proximidad sino dos botones, on y off, estos daran el permiso para que la aplicacion del sensor pueda funcionar y afectar el portal.
![image](https://github.com/NotAKebab/FisInt2/assets/68132813/97ef2356-5893-4fa4-8336-104ef935df7f)
De esta manera se veria la aplicacion, aun tenemos agregado el componente web y el componenete de udp.

![image](https://github.com/NotAKebab/FisInt2/assets/68132813/491830f2-f371-47a9-b692-3e5576e9f432)
Aca se pueden ver la configuracion en bloques, al darle click al boton de send se configura el envio de datos al pc y al darle a on u off, se envia un objeto json que deberemos codificar en unity para que le de permisos a la aplicacion del sensor.

###Guía de lo planeado

* Mismo primer paso, iniciar el proyecto y configurarlo para el passtrough.
* Configurar unas manos de vr con las cuales sea interactuables objetos del mundo.
* En este paso la idea es hacer el portal, el cual nos permite cambiar entre el passtrough y lo que queremos ver, una manera simple de explicarla es que estamos cubriendo las capas de las cosas algo así como limitar su visión según el ángulo, el canal de Valem en youtube, tiene mucho material de referencia para esto. (https://youtu.be/sYBBTYzbZhA de este video fue sacada la idea de como intentar hacerlo)
* Crear un objeto interactuable que sea usable con las manos del personaje y también un segundo objeto, el cual tenga un trigger para abrir el portal. (como estaba planeado es que fuera una piedra la cual se metía en una urna y al estar dentro abrirlo)
* Seguir los pasos de la aplicaciones del master y el sensor.
* Ahora ya no adaptarlo a un cambio de material, y que este active solamente active o desactive el trigger del segundo objeto, así al momento que el Master oprima el OFF o ON tenga control total de si dejar entrar a la persona al mundo.

