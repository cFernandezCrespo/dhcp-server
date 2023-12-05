# dhcp-server

Vamos a modificar un ubuntu server para hacer un server dhcp.
Lo primero será dentro de la maquina virtual instalar un isc-dhcp con la linea que aparece a continuación:

![install isc](imagenes/Screenshot_20231204_170652.png)

hecho esto hacemos un :
~~~
nano /etc/default/isc-dhcp-server
~~~

Entonces nos aparecera un documento tal como muestra la siguiente imagen, En este documento lo que estas configurando son los puertos por donde van a salir las ips.

![Conf isc-dhcp](imagenes/Screenshot_20231204_171401.png)

Ahora vamos a configurar el dhcpd.conf de la siguiente manera:

![conf dhcpd](imagenes/Screenshot_20231204_171149.png)

![conf iptables](imagenes/Screenshot_20231204_171537.png)

![conf netplans](imagenes/Screenshot_20231204_171741.png)

![test da ip](imagenes/Screenshot_20231204_172054.png)

![conf ip mac](imagenes/Screenshot_20231204_174617.png)

![conf dhcp](imagenes/Screenshot_20231204_174617.png)

![test da ip](imagenes/Screenshot_20231204_175134.png)








