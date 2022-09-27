# ConfigSimulacionRedLAN
Clase: Redes y Comunicación de datos.

- Se Montó la topología en CISCO Packet Tracer, Utilizando los modelos solicitados como se muestra en el video.
- Se realizo la configuracion basica de los switches y del rauter.
- Se asignaron las IP correspondientes del direccionamiento de la red LAN, segun se muestra la tabla:

![image](https://user-images.githubusercontent.com/110790300/192428182-25bdffd6-8fc3-4363-89c8-a03639577c4f.png)

- Se hace una validación de las direcciones IP de los PCs. utilizamos el comando TCP/IP (ip config), para verificar que las direcciones IP correspondan.
- Se crearon las VLANs correspondiantes (Tecnología, Marketing, Tesoreria) con su respectivos puertos, IDs y asignados a los PCs correspondientes, como se muestra en la siguiente tabla.

![image](https://user-images.githubusercontent.com/110790300/192429028-3db675fe-292f-48f7-870c-af9da3dafb2c.png)

- Se hace un Ping por cada VLAN para verificar que cada una este bien conectada, el ping se hace de un PC a otro, que compartan la misma VLAN, si es excitoso, significa que el proceso a sido el correcto. de esta forma podemos verificar la conectividad entre la VLANs y los PCs.




6. Verifique que haya conectividad entre las PCs pertenecientes a la misma VLAN. ¿Qué comandos TCP/IP debe utilizar? ¿Los PCs tienen conectividad con su puerta de enlace? ¿Por qué? ¿Existe conectividad entre PCs pertenecientes a VLAN distintas? ¿Por qué? Capture la verificación realizada.

7. Si en el punto 6 encuentra problema(s) de conectividad, proponga y configure una solución al problema(s) identificado(s). Realice nuevamente las pruebas de conectividad para verificar su configuración. Capture la verificación realizada.

8. Verifique que el protocolo STP esté configurado. ¿Qué comando CISCO debe utilizar? ¿Cuál Switch fue asignado como puente raíz? ¿Por qué? Capture la verificación realizada.

9. Verifique que sea posible hacer Telnet desde un PC a los demás switches y al router R1. ¿Qué comando TCP/IP debe utilizar? Capture la verificación realizada.

