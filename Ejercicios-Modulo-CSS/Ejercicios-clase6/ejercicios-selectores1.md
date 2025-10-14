`1- Selecciona los elementos div que sean hijos de otro div`
div div {atributo:valor;}

`2- Selecciona los hijos de los elementos p`
p > child {atributo:valor;}

`3- Selecciona los elementos p que sean hijos de article`
article > p {atributo:valor;}

`4- Selecciona los p que esten dentro de un article`
article p {atributo:valor;}

`5- Selecciona los titulos h1 y los h3`
h1, h3 {atributo:valor;}

`6- Selecciona los ol que esten dentro de body`
body ol {atributo:valor;}

`7- Cualquier elemento que tenga la clase "amarillo"`
.amarillo {atributo:valor;}

`8- Los elementos <ul> que sean hijos de <body>`
body > ul {atributo:valor;}

`9- Los elementos <a> que sean hijos de <p>`
p > a {atributo:valor;}

`10- Selecciona el elemento con id "platano"`
#platano {atributo:valor;}

`11- Todos los elementos <div> que sean hermanos de un elemento <h2>`
h2 ~ div {atributo:valor;}

`12- Todos los elementos <p> con clase = paisa, descendientes de un elemento <ul>`
ul p.paisa {atributo:valor;}

`13- Selecciona los <h1>, <h2>, <h3> que tengan la clase "headertitle", hijos del header`
header > h1.headertitle, h2.headertitle, h3.headertitle {atributo:valor;}
