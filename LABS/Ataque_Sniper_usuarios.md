## Conocer usuarios

Para este metodo hay que mirar elresultado de unas credenciales cuando el usuario es incorrecto, por ejemplo podemos ver que el usuario admin con password admin nos da un invalid username and password, entonces poedmos aprovechar esto para conocer un usuario.

Nos ponemos en esucha con burp y hacemos peticion post con unas credenciales.

Lo metemos al intruder y selecionamos ataque sniper, de payload metemos la worlist de usuarios.

Después de eso añadimos en el campo username como variable para que el payload ataque a eso, al finalizar nos fijamos en el lenght que es la respuesta los caracteres y el que esté cambiado será el username correcto.

Podemos hacer lo mismo para el password
