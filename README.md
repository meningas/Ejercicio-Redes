# Ejercicio-Redes
Lo primero de todo he colocado en cisco packet tracert todos los ordenadores, servidores DHCP, servidores Web, servidores DNS, swith, routers, acces point y todo el cableado necesario para realizar el ejercicio.
Una vez todo colocado he echo en un papel aparte las subredes necesarias que pide en el apratado 1 para 100 hosts, 30 hosts y 6 hosts, una vez calculadas, he introducido las ip´s de todos los ordenadores.
A cada grupo de ordenadores les he introducido sus ip´s correspondientes, luego he configurado los routers para que pudieran conectarse entre ellos. También he configurado los servidores DHCP, los Webs y el servidor DNS.
Una vez echo todo he comprobado si entre los ordenadores podia mandar mensajes entre ellos y efectivamente se puede menos la subred de la mascara /25 y la /27 que no tienen que poder comunicarse con las otras redes.
Tambien he comprobado que al introducir en internet el nombre de dominio correspondia al servidor Web y asi ha sido.
Luego he etiquetado cada grupo de ordenadores y los he clasificado por colores para que quede visiblemente mas bonito y mas claro.

La primera subred va desde la 192.168.1.1 hasta la 192.168.1.126
La segunda subred va desde la 192.168.1.129 hasta la 192.168.1.159
La tercera subred va desde la 192.168.1.162 hasta la 192.168.1.168
Los 8 ordenadores de DHCP les he puesto las ip´s con el rango 192.168.80.0
Los 4 ordenadores de DHCP les he puesto las ip´s con el rango 192.168.90.0
Los 4 ordenadores con IP fija, un punto de enlace con 5 ordenadores con DHCP les he puesto las ip´s con el rango 192.168.7.0
Los 5 orddenadores con IP fija les he puesto las ip´s con el rango 192.168.8.0
El DNS es el 192.168.8.11
