-DEPORTISTAS DEL MES (Dylan): Las tarjetas de deportistas los parti en dos divs clase deportista y un div clase deportistaPrincipal. Este deportistaPrincipal va ser el unico que se muestre en version movil y los otros deportista permanecen ocultos hasta salir de la version movil.

Para el ocultamiento, el elemento clase deportista no se muestra (display: none) y se define como elemento flexbox cuando está en version de escritorio, con las mismas caracteristicas que el elemento clase deportista principal.

Por ultimo para que todas las tarjetas de deportistas se muestren de manera correcta, en la version movil se configura para que el main axis sea column y en escritorio para a ser el main axis row.