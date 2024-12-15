# **5 Exámenes en CCOM**

## **¿Qué es 5 Exámenes en CCOM?**

### (INSERTAR LOGO AQUÍ)

### 5 Exámenes en CCOM es nuestro proyecto final para el curso de CCOM4995: Diseño de Videojuegos. Parte de nuestra inspriación viene de la icónica franquicia Five Nights at Freddy's de Scott Cawthon.

![image](https://github.com/user-attachments/assets/f9a7dfb9-efb6-4a2f-aab8-ba2999ad24d0)

### Este juego simula una pesadilla clásica para los estudiantes de Ciencia de Cómputos de la UPR-RP: ¡enfrentar un examen sin haber estudiado y depender de copiarse para pasar! Aunque toma elementos de horror y humor, 5 Exámenes en CCOM es único en sus mecánicas y está diseñado como un tributo a los estudiantes y profesores del Departamento de CCOM.

## **Objetivo del juego**
### Eres un estudiante desesperado en busca de 3 libretas con las respuestas del examen. Pero cuidado: el profesor, junto con un invitado especial, patrullan el salón para asegurarse de que nadie se copie.

## **Reglas principales:**
### Recoge al menos 1 libreta para avanzar al siguiente nivel. Si no recoges ninguna, pierdes. Ser atrapado por el profesor resulta en una derrota inmediata. Ademas, tienes un tiempo limitado para completar tu misión en cada nivel.

## **Sistema de calificación:**
### 1 libreta = C
### 2 libretas = B
### 3 libretas = A
### A medida que avanzas por las cinco escenas, la dificultad aumenta, reflejando la dificultad de los cursos a lo largo del Bachillerato en Ciencia de Cómputos.

# **Creación del Juego**

## **Assets Utilizados de la Tienda de Unity:**
### Desks Starter Collection
### GUI Parts
### Horror School Props
### Robot Hero: PBR HP Polyart
### Staff of Pain
### Animals_FREE
### Fire_Extinguiser
### NPC
### School Props
### AllSkyFree
### TextMeshPro

## **Escena Principal: Salón A-143**
### El mapa principal del juego es una réplica fiel del Salón A-143 del Departamento de CCOM. Para garantizar el mayor realismo, tomamos fotografías de múltiples ángulos y objetos presentes en el salón, recreándolo con precisión en Unity.
![Salon](https://github.com/user-attachments/assets/f44e5be1-1298-416e-8b57-b47024ff8575) 

## Escena principal: Salon A-143: 
### El mapa principal del juego es una réplica del Salón A-143 del Departamento de CCOM. Para lograr el mayor realismo posible, tomamos fotografías de múltiples ángulos y de los objetos presentes en el salón. Esto nos permitió recrear el espacio con precisión, añadiendo detalles visuales que reflejan el ambiente del aula original.
![Salon](https://github.com/user-attachments/assets/f44e5be1-1298-416e-8b57-b47024ff8575) 

### Para organizar la construcción, dividimos el salón en cinco subcategorías principales: piso, mesas, paredes, techo, decoraciones e iluminación.

## **Paso 1: Piso**

### El piso del salón es cuadriculado en la vida real. Iniciamos insertando un terreno ajustado y lo dividimos en cuadrículas utilizando una textura adecuada. Esto sirvió como base para construir el resto del salón.
![1](https://github.com/user-attachments/assets/380d2c70-98b8-4644-bd9d-966403c6028f)

## **Paso 2: Inserción de Personajes**

### Aprovechamos esta etapa para incluir los personajes principales que se usarán durante la escena:
### Jugador principal: Perro antropomórfico (primera persona).
### Thor: Perro animalístico, mascota del profesor Edusmildo Orozco.
### Profesores: Representados como figuras humanas.
![2](https://github.com/user-attachments/assets/a60e3d70-3b23-4b5e-ad2e-d4a2338aa8fe)

## **Paso 3: Mesas y Sillas**

### Creamos los prefabs de las mesas y sillas del salón. Este paso fue crucial porque determinó las proporciones internas del espacio. Las texturas se obtuvieron de fotografías tomadas directamente del salón. Una vez diseñados los prefabs, los duplicamos y posicionamos con distancias adecuadas entre ellos, incluyendo mesas auxiliares.
![3](https://github.com/user-attachments/assets/4cb7ce47-315d-44ae-b833-d06ecfaa18e5)
![4](https://github.com/user-attachments/assets/947d4f77-72f6-4683-9207-2b4cdf4c041d)

## **Paso 4: Paredes**

### Pared Izquierda
### La creación de las paredes no fue complicada, a excepción de la pared que contiene las ventanas del salón (la pared de la izquierda, considerando que la pared frontal es la que contiene las pizarras). Esta pared requirió mayor atención debido a que contiene ventanas, cortinas y espacios internos con muchas esquinas. Utilizamos figuras ajustadas con las herramientas de Game Object para crearla.
![5](https://github.com/user-attachments/assets/b6b56553-b39f-4030-b28b-e564e7924176)

### Pared Frontal
## Contiene pizarras y el whiteboard utilizado para proyectar presentaciones.
![6](https://github.com/user-attachments/assets/eed6ac13-1b36-4a49-afe9-b0ece6e85dc1)

### Pared Derecha
### No requirió muchos detalles adicionales, más allá de decoraciones menores.
![7](https://github.com/user-attachments/assets/f2c29fdc-a88b-44c7-b9d7-5ae3c4ade52d)

### Pared Trasera 
### Incluye interruptores, sensores de temperatura, pupitres adicionales, receptáculos eléctricos y un extintor con su cartel correspondiente.
![8](https://github.com/user-attachments/assets/4382ec98-52cb-4cf5-833c-f3830f668c29)

### Al finalizar las paredes, el salón comienza a tomar forma.
![9](https://github.com/user-attachments/assets/1e1f5649-bf55-48b1-a73a-8ca2f46e033e)

## **Paso 5 Techo**

### Creamos el techo utilizando un plano dividido en cuadrículas con la herramienta ProBuilder de Unity. Aplicamos texturas obtenidas de fotografías y ajustamos los espacios en la pared izquierda. Además, se añadieron elementos como luces, puntos de acceso WiFi y rejillas de ventilación. Posteriormente, colocamos scripts para que las luces hagan efectos de parpadeo.
![10](https://github.com/user-attachments/assets/6cd4d872-8373-4a2b-814c-e16d858b1cd4)
![11](https://github.com/user-attachments/assets/dfedcb29-15e2-4568-a465-8efe16fda338)

## **Paso 6: Decoraciones**

### En la pared trasera incluimos breakers, sensores, pupitres adicionales y un extintor con cartel.
![12](https://github.com/user-attachments/assets/8c8077cc-2ec9-4039-b92d-b35cc1114254)

### Para la pared de la izquierda, añadimos una silla azul y receptáculos eléctricos.
![13](https://github.com/user-attachments/assets/a4a32124-0d39-4661-bea9-545931af3fbe)

### Finalmentem en la pared frontal, mejoramos el whiteboard, añadimos el proyector, receptáculos, extintor y carteles de noticias.
![14](https://github.com/user-attachments/assets/8bdae88d-8aca-40bd-95de-9eaf78e06327)

### Finalmente, en la pared de la derecha, solo se añadió un receptáculo adicional.
![15](https://github.com/user-attachments/assets/8fda4a91-05fd-4d94-8643-bfcab0a456c9)

## **Paso 7: Iluminación**
### Optamos por hacer un salon oscuro para aumentar la susension y el temor. Decidimos aplicar un skybox de noche para que haya escasez de luz. Ademas anadimos un script de parpadeo para cada luz de tal modo que la unica ilumanicion que existira en el juego sera inconsistente. 

### Por ultimo, colocamos colliders a todos los objetos del salon que el jugador puede interactuar, concluyendo la creacion. Para los demas niveles, lo que hicimos fue mover sillas y desorganizarlo un poco para hacerlo mas retante. Originalmente pensabamos que iba a quedar mas tecato la escena, pero estamos bastante orgullosos con el resultado final. Mostramos la siguiente foto para comparar con la tomada al principio.
![16](https://github.com/user-attachments/assets/d389b14b-d70e-4fa6-bf52-f8d42b649460)


## **Escena Principal: Salón A-143**
### El mapa principal del juego es una réplica fiel del Salón A-143 del Departamento de CCOM. Para garantizar el mayor realismo, tomamos fotografías de múltiples ángulos y objetos presentes en el salón, recreándolo con precisión en Unity.

## Proceso de Creación
### Organizamos el trabajo en las siguientes categorías: piso, mesas, paredes, techo y decoraciones, en ese orden.
### Debido a que el piso del salon en vida real es cuadriculado, comenzamos insertando un terreno ajustado y lo dividimos en grids usando una textura.
![1](https://github.com/user-attachments/assets/380d2c70-98b8-4644-bd9d-966403c6028f)

### Aprovechamos esta oportunidad para ir insertando los personajes que utilizaremos durante la escena. El perro antropomorfico sera el jugador principal (en primera persona), el perro animalistico sera Thor, la mascota del profesor Edusmildo Orozco, y el hombre seran los profesores.
![2](https://github.com/user-attachments/assets/a60e3d70-3b23-4b5e-ad2e-d4a2338aa8fe)

### Una vez colocados los personajes, proseguimos a hacer los prefabs de la mesas, junto con las sillas, del salon de clases. Consideramos que este paso es sumamente importante debido a que determinara el tamano del salon por dentro. Hicimos las mesas a un tamano apropiado para nuestro personaje. Las texturas se obtuvieron fotografiando el salon de clases, como previamente mencionado.
![3](https://github.com/user-attachments/assets/4cb7ce47-315d-44ae-b833-d06ecfaa18e5)

### Una vez hecho el prefab, duplicamos las demas mesas y las distanciamos entre si. Esto incluye las otras mesas distintas a las comunes del salon de clases. Esto concluye este paso.
![4](https://github.com/user-attachments/assets/947d4f77-72f6-4683-9207-2b4cdf4c041d)

### La creacion de las paredes no fue complicado, a excepcion de la pared que contiene las ventanas del salon (la pared de la izquierda si la pared de al frente es la que contiene las pizarras). Esta requirio mas atencion debido a que contiene ventanas, cortinas y espacios internos con muchas esquinas. Utilizamos y ajustamos las figuras ofrecidas en Game Object para crear esa pared, al igual que las siguientes.
![5](https://github.com/user-attachments/assets/b6b56553-b39f-4030-b28b-e564e7924176)

### La siguiente pared, la pared frontal, contiene las pizarras y el whiteboard donde se proyectan las presentaciones y eso. Mas adelante le anadiremos mas detalles.
![6](https://github.com/user-attachments/assets/eed6ac13-1b36-4a49-afe9-b0ece6e85dc1)

### No hay que decir mucho de la pared lateral derecha. Aqui esta 
![7](https://github.com/user-attachments/assets/f2c29fdc-a88b-44c7-b9d7-5ae3c4ade52d)

### Similar a la anterior, esta pared no contiene varios objetos unicos, a excepcion de la decoracion.
![8](https://github.com/user-attachments/assets/4382ec98-52cb-4cf5-833c-f3830f668c29)

### COncluimos el paso de crear las paredes. A continuacion mostramos un angulo de como va quedando la escena principal.
![9](https://github.com/user-attachments/assets/1e1f5649-bf55-48b1-a73a-8ca2f46e033e)

### Para crear el techo, utilizamos un plano y lo dividimos en cuadriculas con la herramienta de ProBuilder de Unity. Le aplicamos la textura del techo del salon de clases mediante fotografias. Ademas, debido a los espacios que hay en la pared izquierda, rellenamos esos espacios con cubos ajustados.
![10](https://github.com/user-attachments/assets/6cd4d872-8373-4a2b-814c-e16d858b1cd4)

### Aprovechamos esta oportunidad para rellenar el techo con sus apropiadas cosas, como las luces, el access point de wifi y las rejillas de ventilacion del aire acondicionado. Mas adelante le colocaremos luces scripts para que hagan flickering. Colocamos el techo justo encima de las paredes, concluyendo este paso.
![11](https://github.com/user-attachments/assets/dfedcb29-15e2-4568-a465-8efe16fda338)

### Las siguientes imagenes consistiran de las decoraciones que le dimos al salon de clases para darle flare y un touch. Comenzando con la  pared de atras, anadimos los breakers, los sensores de temperatura, pupitres adicionales, receptaculos y el fuego extintor junto con su cartel.
![12](https://github.com/user-attachments/assets/8c8077cc-2ec9-4039-b92d-b35cc1114254)

### La pared de la izquierda no contiene muchos detalles a excepcon de la silla azul y los receptaculos.
![13](https://github.com/user-attachments/assets/a4a32124-0d39-4661-bea9-545931af3fbe)

### Para la pared frontal, mejoramos la pizarra con el proyector el whiteboard, los receptaculos, el fuego extinor y los carteles cuyo continenen noticias y anuncios.
![14](https://github.com/user-attachments/assets/8bdae88d-8aca-40bd-95de-9eaf78e06327)

### La pared de la derecha se mantuvo igual, solo anadimos un receptaculo que le pertenece
![15](https://github.com/user-attachments/assets/8fda4a91-05fd-4d94-8643-bfcab0a456c9)

### Por ultimo, colocamos colliders a todos los objetos del salon que el jugador puede interactuar, concluyendo la creacion. Para los demas niveles, lo que hicimos fue mover sillas y desorganizarlo un poco para hacerlo mas retante. Originalmente pensabamos que iba a quedar mas tecato la escena, pero estamos bastante orgullosos con el resultado final. Mostramos la siguiente foto para comparar con la tomada al principio.
![16](https://github.com/user-attachments/assets/d389b14b-d70e-4fa6-bf52-f8d42b649460)

## Iluminacion:

## Jugador:

## Enemigos:

## Pantallas de Victoria y Derrota
### Uno de los elementos más creativos de 5 Exámenes en CCOM son las pantallas finales, creadas con la colaboración de profesores del Departamento de CCOM. Estas incluyen fotografías en dos versiones: una feliz y otra molesta. Las imágenes fueron decoradas con elementos humorísticos, como objetos, imágenes y videos, para mantener un tono ligero y respetuoso hacia los profesores. Además, utilizamos una tipografía similar a la de Five Nights at Freddy's, obtenida de www.dafont.com, para reforzar la estética del juego.

### Tipos de Escenas: 
### Escena introductoria: Antes de cada partida, se muestra la clase, el curso, el profesor y la hora.

### Victoria final: Una pantalla cómica que celebra el triunfo del jugador.

### Derrota 1: Si no recoges ninguna libreta, se refleja el fracaso con un mensaje irónico.

### Derrota 2: Si te atrapan copiándote, el profesor aparece molesto por tus acciones. 

### (INSERTA GIF'S AQUI)

## Agradecimientos
### Agradecemos profundamente a los siguientes profesores del Departamento de Ciencias de Cómputos por su apoyo y colaboración al permitir el uso de sus imágenes en el juego:

### Edusmildo Orozco y su perro Thor
### Rafael Arce
### David Flores
### Ivelisse Rubio
### José Ortiz
### Humberto Ortiz
### Lillian González
