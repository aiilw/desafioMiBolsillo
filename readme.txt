El programa est� hecho en Ruby. Para ejecutarlo, se requiere tener instalado el ruby. Se puede ejecutar haciendo doble click sobre el archivo DesafioMiBolsillo.rb o sobre el archivo ejecutable por lotes runner.bat. Cualquiera de las dos formas debe dar el mismo resultado.

La soluci�n al desaf�o se ha trabajado en primer lugar desde las clases base y, en base a ellas, se ha ido construyendo el c�digo que permite dar respuesta a cada �tem. 

Para resolver el desaf�o se ha asumido que cada nodo est� identificado por una cadena de un solo car�cter, esto es, por una sola letra siendo diferentes las may�sculas que las min�sculas. Del mismo modo, se ha asumido que el input es v�lido y no se ha empleado ning�n tipo de validaci�n sobre lo que el usuario ingrese.

El input es a partir del terminal o consola. Se requiere que sea una lista separada por comas de los v�rtices del grafo, tal como aparece en el caso de prueba del enunciado del desaf�o.

El programa para los outputs 1-5 emplea una funci�n gen�rica para cualquier ruta fija. Para los outputs 6 y 7 emplea otra funci�n que calcula el n�mero de rutas que terminan en un determinado nodo dado un nodo inicial y una cantidad de saltos.

Para los outputs 8 y 9, se desarroll� una rutina que calcula la ruta m�s corta en distancia entre dos nodos. Finalmente, se escribi� un procedimiento espec�fico para el output 10 que emple� una b�squeda en anchura primero y luego en profundidad.