# PIA-2E
Segundo entregable del PIA de Programación para Ciberseguridad!

Este repositorio contiene los 2 módulos correspondientes al segundo entregable del PIA de Programación para Ciberseguridad.

Contiene los siguientes módulos:

1. PortScan
2. HoneypotCreation

======================================================

En cuanto a las funciones individuales de los módulos:

PortScan: Escanea los puertos de la dirección IP que indique el usuario, así como un rango de puertos. Se le da la opción adicional al usuario de mandar los resultados a un archivo txt.

HoneypotCreation: Inicia una honeypot en el puerto indicado por el usuario, así como imprimir en la consola un reporte con cualquier intento de conexión al honeypot. Adicionalmente, se le da la opción al usuario de reiniciar el honeypot con otros puertos.

======================================================

Aclaraciones para correr los scripts correctamente:

Para el módulo 'PortScan': En caso de que no esté iniciado el servicio ssh, el primer módulo no funcionará. Se necesita correr la línea 'sudo systemctl start ssh.service' antes de correr el módulo.

Para el módulo 'HoneypotCreation': Al revisarse logs del sistema, se necesitan permisos de superuser (sudo). En caso de que no se muestren los logs, ejecute el script con 'sudo'.

======================================================

Realizado en conjunto por el equipo 5:

Santiago B.

Chris T.

Alexander T.
