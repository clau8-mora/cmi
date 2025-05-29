## Memory cromático invertido

Proyecto de Creación Multimedia Interactiva de la  Facultad de Bellas Artes de la Univesidad de Granada

# 1 Datos 

**Titulo** : Memory cromático invertido

**Web:**   https://clau8-mora.itch.io/memory-cromtico-invertido

**Autor:**  Claudia Mora García

**Resumen** : Este proyecto busca explorar la percepción visual, la memoria y la relación entre el arte urbano y la estética digital. Al invertir los colores de las imágenes, se desafía al jugador a observar más allá de la apariencia superficial, promoviendo una apreciación diferente de los grafitis como forma de expresión artística.

**Estilo/género:** juego de cartas

**Logotipo** : 

![portada](https://github.com/clau8-mora/cmi/blob/master/portadajuego.jpg)

**Resolución:** 800x600px tamaño fijo 

**Probado en:** Google Chrome 

**Tamaño proyecto:** 125MB 

**Licencia** Este proyecto tiene una Licencia CC Reconocimiento Compartir igual (CC BY-SA)

**Fecha** : 29/05/2025

**Medios** 

- Github: https://github.com/clau8-mora/cmi


# 2. Memoria del proyecto 

### 2.1 Storyboard: 
1. Portada / Pantalla de Bienvenida
Visual: Fondo artístico con estética urbana y grafiti.
Texto principal: “Bienvenidos al Memory Cromático Invertido”

Elementos:
Botón (Bote de pintura): Lleva al menú.
Texto ‘Skip’: Permite saltar la intro directamente al menú.
Sonido: Música de fondo comienza a reproducirse.
Animación: Transición fluida al menú al pulsar el botón.

2. Menú Principal
Visual: Fondo con mural de grafitis, botones con animación flotante.
Texto descriptivo del juego
Botones interactivos:
Marco (Galería): Transición suave a galería de 6 imágenes de los grafitis originales (no invertidas) que se deslizan una por una.
Claqueta de cine (Video): Abre un video de YouTube en pantalla (tipo tráiler o referencia a otro juego de cartas).
Incluye botón de Pausar/Reproducir. Un reloj de arena para pausar y un rayo para reproducir.
Bote de pintura (Jugar): Lleva a la pantalla de juego.
Estrella (Créditos): Transición a pantalla con créditos deslizándose de arriba hacia abajo.
Extra: En cada pantalla aparece un icono de casita que devuelve al menú.

3. Pantalla de Juego



![juego](https://github.com/clau8-mora/cmi/blob/master/juego.jpg)




Visual: Cartas dispuestas boca abajo, llevan un dibujo de estrella y pone memory cromático.
Interacciones:
Clic en cartas y se giran.
Si son pareja, desaparecen con animación.
Si no, se giran de nuevo tras breve pausa.
Elemento adicional:
Ardilla: Sigue el cursor del ratón por la pantalla.
Sonido:Fondo ambiental.
Efecto sonoro al hacer clic en los botones.
Final de partida:
La ardilla aparece celebrando.
Texto: “¡Bien hecho! juego completado

4. Pantalla de Créditos 
Visual: Fondo de collage con todas las cartas, las originales y las invertidas con efecto difumino.
Animación: Texto con créditos deslizándose desde la parte superior hacia abajo.
Incluye: Título del juego,nombre del desarrollador, motor de juego,tipografía, programación y diseño, imágenes y año.



  ![creditos](https://github.com/clau8-mora/cmi/blob/master/creditos.jpg) 

  


### 2.2. Esquema de navegación 
![esquema](https://github.com/clau8-mora/cmi/blob/master/Diagramadraw.jpg) 


# 3. Metodología

Para este proyecto se pensó en un público joven y creativo, interesado en juegos de memoria visual con un estilo artístico.
Diseño del concepto:
Se definió una mecánica simple: encontrar parejas de imágenes entre grafitis originales y con colores invertidos, fomentando la atención visual.
Prototipado y pruebas:
Se diseñaron las pantallas y la navegación directamente en el entorno de desarrollo (Godot). Las decisiones de diseño se tomaron de forma iteractiva durante la construcción del juego, basadas en la lógica.
Ajustes e iteraciones:
Gracias a las pruebas, se mejoraron los botones, transiciones, sonidos y se agregó el botón de "volver al menú" (la casita).
Resultado final:
Un juego claro, visualmente atractivo y fácil de entender, con una navegación intuitiva.



### Etapa 1: Ideación de proyecto

**Investigación de campo** Para este proyecto me inspiré en elementos visuales como:

Juegos clásicos de memoria como base para la mecánica principal de emparejar cartas.
Arte urbano y grafitis, utilizados como imágenes para las cartas, buscando un estilo visual llamativo y contemporáneo.
Colores invertidos, aplicados para crear un reto visual diferente y estimular la percepción del jugador.
Videos en YouTube sobre juegos de cartas y de memoria visual, que sirvieron como referencia para estructurar la dinámica general.

**Motivación de la propuesta** 

Este proyecto me parece interesante porque combina una mecánica de juego clásica con una propuesta visual original. Al utilizar grafitis reales y sus versiones con colores invertidos, se crea un reto de memoria que también estimula la percepción visual, cromática y el reconocimiento de patrones. Además, integra elementos como la ardilla que sigue al cursor y transiciones animadas, haciendo la experiencia más atractiva y dinámica. Es un proyecto que busca ser entretenido y visualmente diferente, conectando el arte urbano con el mundo digital.

**Publico / audiencia**

Orientado a personas jóvenes y adultas interesadas en juegos casuales, arte visual y desafíos de memoria. También se puede utilizar para fines educativos.


### Etapa 2: Desarrollo / actividades realizadas

Juego: Se desarrolló la mecánica de emparejar cartas, incluyendo efectos visuales, detección de parejas y una ardilla que sigue el cursor.
Vídeo: Se integró un video de YouTube dentro del menú, con opción de pausa y reproducción.
Instrucciones: Se añadió una breve explicación del juego en el menú principal para guiar al usuario.
Menú y botones: Se crearon botones animados con sonidos, cada uno con un ícono representativo (bote, marco, claqueta, estrella). Se añadió un botón de casita en todas las pantallas para volver al menú.
Galería: Se incluyó una galería con 6 imágenes de grafitis, accesible desde el menú.
Créditos: Se diseñó una pantalla donde los créditos bajan desde arriba de forma automática.
Sonido y animaciones: El juego tiene música de fondo, efectos al pulsar y animaciones en los botones.




### Etapa 3: Problemas identificados
Fondos poco trabajados:
Los fondos de algunas pantallas no están suficientemente integrados con el estilo visual del juego, lo que puede afectar la coherencia estética.
Sin opción para quitar el sonido:
No existe un botón o menú para desactivar la música o los efectos del sonido, esto puede ser incómodo para algunos usuarios.
Falta de sonido al girar cartas:
El giro de las cartas no tiene efectos sonoros.
Movimiento lento de la ardilla:
La ardilla que sigue al cursor a veces se mueve con retraso y no acompaña bien la interacción, especialmente al hacer clic en las cartas rápidamente.
Reconocer las parejas con los colores invertidos:
Algunos usuarios pueden tener dificultad para identificar las parejas por el cambio de colores y resultarles más difícil.


# 4. Conclusiones 
El desarrollo de este juego "Memory Cromático" ha sido una experiencia creativa que combina juego, fotografía y arte urbano. Considero que el resultado es funcional y original.Sencillo pero entretenido.
Durante el proceso he detectado varios aspectos que podrían mejorarse, como ya he dicho anteriormente, la falta de opción para silenciar el sonido, la falta de sonido al girar las cartas, la lentitud del personaje (la ardilla) y algunos fondos que podrían trabajarse mejor para dar más coherencia visual y que quede más estético.
En el futuro, me gustaría pulir esos detalles, añadir configuraciones básicas (como control de sonido) y adaptar la experiencia para más dispositivos. También sería interesante realizar pruebas con usuarios reales para recoger opiniones y seguir mejorando.


# 5 Referencias 

UNIQUE Cards & CARD FLIP Animation - Godot 4 Card Game Tutorial #6  subido por 
Barry's Development Hell 8 noviembre 2024 https://www.youtube.com/watch?v=L1dEuHr5AGU 

Q Memory Juego de mesa - Vídeo tutorial subido por Consola y Tablero el 7 de julio de 2021
https://www.youtube.com/watch?v=fYOKB-fp_I0

Cómo usar Godot y Aprender desde CERO a hacer juegos subido por findemor el 24 de abril de 2024 https://www.youtube.com/watch?v=-_LiMyZGoXw
Chat gpt(comunicación personal) como ayuda para los códigos en la creación del juego en Godot.

**Recursos y materiales audiovisuales:**

* Música: Free ambiente sound
* Imágenes: Fotografías propias. Realizadas por Claudia Mora García.
* Tipografía: CascadiaCode
 Elemento ardilla: Imagen digital (Pinterest)

**Herramientas utilizadas**

- Hippani Animator 5.1
- Godot

![licencia](https://github.com/clau8-mora/cmi/blob/master/licencia%20.jpg)
![licencia](https://github.com/clau8-mora/cmi/blob/master/LICENSE)
Mayo 2025
