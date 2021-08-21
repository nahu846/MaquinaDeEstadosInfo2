# Maquina De Estados

### Memoria descriptiva:

Este sistema representa un control de acceso de una puerta. Para poder iniciar el sistema primero se debera cerrar la puerta, luego sera necesario ingresar una clave, que en caso de ser correcta, abrira la puerta. Inmediatamente despues de que la fuerta fue abierta se iniciara un conteo para una alarma de puerta abierta, la cual una vez cerrada la puerta se detendra.

Se va a utilizar un display LCD, un teclado matricial numerico, un sensor para la verificacion del estado de la puerta, y una cerradura automatica.

![alt text](https://github.com/nahu846/MaquinaDeEstadosInfo2/blob/master/files/DiagramaDeEstados.png)

* SET: Bandera de fin de inicialización
* sensor: sensor posicion de la puerta
* pwd: clave a ingresar
