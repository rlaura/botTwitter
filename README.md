# botTwitter
Algunos ejemplos de bots para twitter en Python (utilizando la librería twython)


#miPrimerBot
  - Es un bot muy sencillo para listar ordenadamente los seguidores que tenemos. Es útil y funciona perfecto si tenemos pocos seguidores.
  
#botVerSeguidores
  - Similar al anterior, pero permite separar por páginas. Es útil para ver mayor cantidad de seguidores, separa el contenido en páginas. Se puede ajustar el tiempo (time.sleep()) para no exceder el límite de request máxima que permite twitter. 

#botGuardaSeguidores
  - Permite guardar en un archivo .txt la lista de seguidores del usuario seleccionado. Muestra la fecha en la que se generó dicha lista, el usuario al que pertenece y luego, los seguidores con el siguiente formato: id, nombre de usuario, lugar.

#botPosteaAleatorio
  - Postea cada 15 minutos un post aleatorio. 
    En este caso tenemos dos categorías (tema1 y tema2) contenido en la lista temas. Con la función random.choice(temas) se elige alguno y se guarda en la variable tema. Luego, se vuelve a usar la función radom.choice pero con el nombre de la lista seleccionada como parámetro.
    Se twittea esta frase aleatoria y se borra de la lista, para que no se repita. Para no tener errores de lista vacía, cada una de las listas deberían contener más elementos de los que se van a twittear en total (ej si voy a twittear 5 frases, cada una de las listas debería contener 5 o 6 frases). Se puede agregar una verificación de lista vacía si no.
    La variable x cuenta las vueltas (cantidad de veces que se posteó). En caso de que la vuelta sea par, se twittea solo una frase. En caso de que sea impar, se twittea una frase y una foto, que también elige aleatoriamente. 
