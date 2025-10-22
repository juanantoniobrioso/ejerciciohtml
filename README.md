# Ejercicio HTML

En este ejercicio creamos 3 HTMLs relacionados en los que debemos hacer uso
de las etiquetas que nos han enseñado como <header>, <nav>, etc.

## General

En todos los html hemos hecho una estructura similar. Primero en el head ponemos todos
los datos relevantes para la página, como el meta charset="UTF-8" para poder escribir con
casi todos los carácteres; el meta name="viewport" para hacer un diseño responsive y que se vea en 
todos los dispositivos y el titulo y la descripción de la página.

Además en el body comenzamos con un header donde ponemos en un h1 el nombre de la página o el nuestro
en el caso del index, y una lista mediante <nav> de las otras páginas para poder navegar por ellas sin problema.

En el footer he añadido una señal de copyright ya que nos lo pide el enunciado.

Por último, en algunos casos he utilizado palabras como &iacute para poner tildes ya que nos lo han enseñado
y he querido ponerlo en práctica y comprobar que funciona. Pero hacer esto con todas las tildes de todos los 
párrafos supone que el código pierda mucha legibilidad, así que solo la he puesto en elementos que contengan
palabras sencillas, porque después de todo tenemos el meta charset="UTF-8" lo que nos permite leer casi todos los
carácteres especiales que usamos normalmente.

## Index

En el index o página de inicio ponemos dentro de la etiqueta <main> 3 secciones <section> siendo cada una un tema.
En la primera hablo sobre mí con el título "Sobre mí" en un encabezado h2, seguido de un párrafo donde hablo sobre mí,
y haciendo lo mismo en la sección de Mi formación.

En la de mi intereses he usado una lista no numerada mediante <ul> y los elementos de la lista mediante <li>

## Proyectos

Aquí en lugar de dividirse por secciones, se divide por 3 artículos <article>. Cada artículo tiene en su header
un encabezado h3 con el título del proyecto seguido de un párrafo con la explicación de este.

Por último, utilizamos el elemento <figure> para añadir una imágen para ese artículo y <figcaption> para añadir
texto descriptivo legible en la página de forma normal para cada imágen.

## Contacto

En este html se hace uso de los formularios <form>. Este cuenta con una lista no numerada en la que sale 
nombre, email, asunto y mensaje, seguido de un campo de texto para rellenar. La etiqueta <label> es útil 
porque en dispositivos táctiles puedes acceder a la caja de texto a la que está asociada haciendo
click en el texto (por ejemplo, puedes darle a la caja de Nombre dando click al texto "Nombre" además
de la caja). Esto es bastante útil ya que facilita a los usuarios interactuar con el formulario.

El input type indica de que tipo es, siendo texto en todo excepto en email donde al decir que el tipo es
email, te obliga a que sea un texto que contenga un arroba (@) en el medio, que es el formato de los correos
electrónicos.

el id y name son para relacionarlos con el <label>.

El placeholder es el texto que sale en gris claro dentro del campo de texto antes de que el usuario escriba nada,
esto es útil para indicar en el usuario que tiene que escribir exactamente en cada campo.

Por útlimo, el required indica que no te dejará enviar nada hasta que ese campo no esté vacío, para que a nadie se le 
olvide rellenar algo que es necesario.







_Juan Antonio Brioso García_