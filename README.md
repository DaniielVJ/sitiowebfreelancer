**Proyecto para practicar HTML & CSS**

- Estructurar el contenido: es agrupar los elementos de la pagina web en etiquetas contenedoras, que indican a que pertenece cada elemento html que definimos.

- Displays: 
    - Flex: Permite que alineemos los elementos hijos de un contenedor en 2 direcciones, horizontal (row) o vertical (column)
    - Grid: 


- Formas de escribir CSS:
    - BEM: se define una clase para el bloque que contiene todos los elementos EJ:
        - .card {}, representa el bloque completo que se compondra de elementos como un titulo, imagen, descripcion, boton.
        - .card__titulo {}, se crea una clase para cada elemento del contenedor o bloque, con el nombre del bloque seguido del elemento.
        - .card__imagen{}
        - .card__descripcion{}
        - .card__boton {}
        - .card__boton--degradado{}, Modificador se añade cuando uno de los elementos tendra un estilo diferente del resto
    - Utilify First: Se usa cuando creamos clases que solo aplican un unico estilo o 1 propiedad (Tailwind CSS). EJ:+
        - p-3: para dar un padding de 3
        - bg-green: para dar un background verde, etc.
    - Modulo: Este enfoque se define una clase para el bloque que contiene todos los elementos y luego cada elemento del bloque se selecciona por su etiqueta. EJ:
        - .card{}, clase del bloque o contenedor de los elementos.
        - .card h2{}, seleccionamos el elemento html en especifico de .card al cual queremos dar estilo.
 