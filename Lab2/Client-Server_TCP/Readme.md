Código de ejemplo de una comunicación Cliente-Servidor sobre una conexión TCP.

Este código sirve como base para el deber de laboratorio, el mismo que consiste de una simple suma de dos números. Básicamente el procedimiento a seguir sería al siguiente:

1) En el cliente, se debe obtener los números que el usuario desea sumar. Por ejemplo el usuario ingresa por consola o mensaje de dialogo los valores *a* y *b*

2) El cliente debe enviar los valores de *a* y *b* al servidor

3) En el servidor, se debe obtener los valores *a* y *b* para sumarlos es decir *c = a + b*

4) El servidor debe enviar el resultado *c* al cliente

5) El cliente despliega el resultado *c* en un mensaje


***********************************************************************************************
Si se requiere eliminar procesos en Windows:

a. Identificar el proceso con el comando *netstat -ano*

b. Eliminar el proceso con el comando *taskkill -pid <#proceso> /f*

Si se requiere eliminar procesos en Linux:

a. Identificar el proceso con el comando *lsof -i:<port>*

b. Eliminar el proceso con el comando *kill <#proceso>*
