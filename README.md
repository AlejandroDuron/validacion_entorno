# verificacion_entorno

Bitacora de errores
1- 

Síntoma: The named parameter 'IconButton' isn't defined.
Try correcting the name to an existing named parameter's name, or defining a named parameter with the name 'IconButton'.
Causa identificada: Al parecer los nombres con los que se definen los parametros deben seguir ciertos estandares dentro de 'Scaffold'
Solución aplicada: Cambiar el nombre a floatingActionButton
Verificación: El mensaje de error cambio

2- 

Síntoma: The argument for the named parameter 'floatingActionButton' was already specified.
Try removing one of the named arguments, or correcting one of the names to reference a different named parameter.
Causa identificada: No pueden existir 2 floating action button al mismo tiempo, se deben agregar identificadores unicos y añadirlos en una columna. 
Solución aplicada: Cambio de estrategia para colocar los botones. En vez de intentarlos colocar juntos mejor que el boton de resetear estado vaya en el App Bar, alineado con el contenido.
Verificación: Ya no sale el mensaje de error y el boton es funcional.