# botTwitter
Algunos ejemplos de bots para twitter en Python (utilizando la librería twython)


#miPrimerBot
  - Es un bot muy sencillo para listar ordenadamente los seguidores que tenemos. Es útil y funciona perfecto si tenemos pocos seguidores.
  
#botVerSeguidores
  - Similar al anterior, pero permite separar por páginas. Es útil para ver mayor cantidad de seguidores, separa el contenido en páginas. Se puede ajustar el tiempo (time.sleep()) para no exceder el límite de request máxima que permite twitter. 

#botGuardaSeguidores
  - Permite guardar en un archivo .txt la lista de seguidores del usuario seleccionado. Muestra la fecha en la que se generó dicha lista, el usuario al que pertenece y luego, los seguidores con el siguiente formato: id, nombre de usuario, lugar.
