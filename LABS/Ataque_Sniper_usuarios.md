## Conocer usuarios

Para este metodo hay que mirar elresultado de unas credenciales cuando el usuario es incorrecto, por ejemplo podemos ver que el usuario admin con password admin nos da un invalid username and password, entonces poedmos aprovechar esto para conocer un usuario.

Nos ponemos en esucha con burp y hacemos peticion post con unas credenciales.

Lo metemos al intruder y selecionamos ataque sniper, de payload metemos la worlist de usuarios.

Después añadimos a la derecha le damos a grep Extract y ponemos el msj de invalid username and password 

Podemos hacer lo mismo para el password
