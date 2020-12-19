# Instalacion y configuración


## Pasos
1.  - Instalamos dnsmasq
	
     ![1](https://github.com/jesusromero92/dnsmasq/blob/main/Fotos/1.png)

2.  - Configuramos los DNS del servidor.Hay que poner unos externos para que pueda salir a internet **(/etc/resol.conf)**

     ![2](https://github.com/jesusromero92/dnsmasq/blob/main/Fotos/2.1.png) 

3.  - Configuramos los DNS del cliente,colocando la IP del servidor.Esto hará que el servidor le ofrezca el DNS **(/etc/resol.conf)**

     ![3](https://github.com/jesusromero92/dnsmasq/blob/main/Fotos/2.2.png)
     
4.  - Y ya está configurado

5.  - Podemos configurar el archivo **/etc/hosts** para ver que realmente funciona el dns

     ![3](https://github.com/jesusromero92/dnsmasq/blob/main/Fotos/4.png)
