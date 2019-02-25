# SGY04_03 Squid - PfSense.

#### 1. Pestaña System.

En esta nos dirigimos al apartafo de Package Manager.

![img](img/1.png)

Buscamos el servicio a instalar, que en este caso es Squid.

![img](img/2.png)

Confirmamos la instalación.

![img](img/3.png)

Vemos el proceso de la instalación.

![img](img/4.png)

Ya instalado.

![img](img/5.png)

#### 2. Pestaña Services.

Ahora vamos al aparado Squid Proxy Server.

![img](img/6.png)

Vamos a las opciones generales y picamos en Enable Squid Proxy y en Proxy Interfaces elegimos LAN.

![img](img/7.png)

En Transparent Proxy Interfaces LAN también.

![img](img/8.png)

En SSL Man In the Middle Filtering elegimos LAN.

![img](img/9.png)

En Rotate Logs ponemos 7 días.

![img](img/10.png)

Ponemos el lenguaje en Español.

![img](img/11.png)

Guardamos.

![img](img/12.png)

Habilitamos el antivirus.

![img](img/13.png)

Ponemos que se actualice la base cada 24h.

![img](img/14.png)

Guardamos.

![img](img/15.png)

En las ACL's ponemos la red interna que estamos usando.

![img](img/16.png)

Bloqueamos esta URL.

![img](img/17.png)

Guardamos.

![img](img/18.png)

#### 3. Pestaña Status.

Ahora vamos a services.

![img](img/19.png)

Vemos todos los servicios y vamos a iniciar el Squid.

![img](img/20.png)

Comprobamos que está iniciado.

![img](img/21.png)

Comprobamos el puerto del Proxy.

![img](img/22.png)

En el Explorer vamos a las opciones de Internet.

![img](img/23.png)

Configuración de la LAN.

![img](img/24.png)

Usamos nuestro servidor Proxy, poniendo la IP y el puerto de la máquina.

![img](img/25.png)

Comprobamos que no podemos acceder a la URL que pusimos en la lista negra.

![img](img/26.png)
