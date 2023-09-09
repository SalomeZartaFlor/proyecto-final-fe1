-DEPORTISTAS DEL MES (Dylan): Las tarjetas de deportistas los parti en dos divs clase deportista y un div clase deportistaPrincipal. Este deportistaPrincipal va ser el unico que se muestre en version movil y los otros deportista permanecen ocultos hasta salir de la version movil.

Para el ocultamiento, el elemento clase deportista no se muestra (display: none) y se define como elemento flexbox cuando está en version de escritorio, con las mismas caracteristicas que el elemento clase deportista principal.

Por ultimo para que todas las tarjetas de deportistas se muestren de manera correcta, en la version movil se configura para que el main axis sea column y en escritorio para a ser el main axis row.

-bannerFinal (Dylan):
Se desarrolla solo con un H2 y un boton que cambia las caracteristicas de apariencia y el main axis segun el modo de visualizacion.

FOOTER:

    -Formulario (Dylan):
    No se le pone la propiedad tapindex dado que solo tiene un campo.
    No le identificamos un label para anidar el input con la propiedad for.

    -barraNavegacionFooter (Dylan):
    Dentro de la balla de navegacion, dividimos la lista en dos para poderlas acomodar como dos columnas y que estuvieran dentro del mismo contexto de esta barra de navegacion.
    Usamos la propiedad flex-wrap:wrap para que se respete el tamaño de las dos listas y estas quedaran una al lado de la otra.

    -redes (Dylan):
    Es un contenedor article que contiene los iconos de las redess y que se emplea para asegurar que los iconos se organicen siempre de forma horizontal.

    -CAMBIO MOVIL-DESKTOP:
    Para hacer el cambio de movil a desktop usamos la propiedades flex-direction: column-reverse y      flex-wrap: wrap-reverse, para ordenar los elementos del footer en forma de columna con orden de abajo para arriba y el flex-warp para que los acomodara de la misma forma. Lo crucial fue darle un ordena los elementos flex para que el ultimo elemento en modo movil era el "copy rights" pasara a ser el primero en modo desktop.