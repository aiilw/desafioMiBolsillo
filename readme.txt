El programa está hecho en Ruby. Para ejecutarlo, se requiere tener instalado el ruby. Se puede ejecutar haciendo doble click sobre el archivo DesafioMiBolsillo.rb o sobre el archivo ejecutable por lotes runner.bat. Cualquiera de las dos formas debe dar el mismo resultado.

La solución al desafío se ha trabajado en primer lugar desde las clases base y, en base a ellas, se ha ido construyendo el código que permite dar respuesta a cada ítem. 

Para resolver el desafío se ha asumido que cada nodo está identificado por una cadena de un solo carácter, esto es, por una sola letra siendo diferentes las mayúsculas que las minúsculas. Del mismo modo, se ha asumido que el input es válido y no se ha empleado ningún tipo de validación sobre lo que el usuario ingrese.

El input es a partir del terminal o consola. Se requiere que sea una lista separada por comas de los vértices del grafo, tal como aparece en el caso de prueba del enunciado del desafío.

El programa para los outputs 1-5 emplea una función genérica para cualquier ruta fija. Para los outputs 6 y 7 emplea otra función que calcula el número de rutas que terminan en un determinado nodo dado un nodo inicial y una cantidad de saltos.

Para los outputs 8 y 9, se desarrolló una rutina que calcula la ruta más corta en distancia entre dos nodos. Finalmente, se escribió un procedimiento específico para el output 10 que empleó una búsqueda en anchura primero y luego en profundidad.