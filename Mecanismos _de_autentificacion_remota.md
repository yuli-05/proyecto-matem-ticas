# Mecanismo de autenticación
Un mecanismo de autenticación define reglas sobre información de seguridad, como si una credencial es reenviable a otro proceso de Java™ y el formato de cómo se almacena la información de seguridad en credenciales y señales. Puede seleccionar y configurar un mecanismo de autenticación utilizando la consola administrativa

*Autenticación* es el proceso de establecer si un cliente es quién o qué dice estar en un contexto determinado. Un cliente puede ser un usuario, una máquina o una aplicación. Un mecanismo de autenticación en WebSphere Application Server normalmente colabora estrechamente con un registro de usuarios. El registro de usuarios es el repositorio de cuentas de grupos y usuarios con el que se consulta el mecanismo de autenticación al realizar la autenticación. El mecanismo de autenticación es responsable de crear un credencial, que es una representación de producto interno de un usuario cliente autenticado satisfactoriamente. No todas las credenciales se crean por igual. Las habilidades de la credencial se determinan mediante el mecanismo de autenticación configurado.

## Opciones para la autenticación web:
* Autenticar sólo cuando el URI está protegido
* Utilizar datos de autenticación disponibles cuando se accede a un URI no protegido
* Autenticación sólo cuando el URI está protegido
* Autenticar cuando se accede a cualquier URI
