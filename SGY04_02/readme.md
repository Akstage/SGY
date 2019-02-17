# SGY04_02 PfSense.

### 1. Preparativos.
Descargamos la ISO del [pfSense](https://www.pfsense.org/download/) desde Internet.

>Nota: Elegimos la arquitectura AMD64 (64-bit) y el instalador como CD Image (ISO) Instaler.

`Para las configuraciones e instalaciones hemos seguido un manual que nos ha proporcionado el profesor.`

#### 1.1 Preparando la MV.

Tenemos que poner la primera interfaz de red en modo puente.

![img](/img/1.png)

Y la segunda en red interna.

![img](/img/2.png)

### 2. Congiguración de la red.

Para la **WAN** hemos utilizado la red de clase que tiene conexión a Internet, mientras que para la **LAN** hemos ultilizado una red que será la interna.

![img](/img/3.png)

### 3. MV Windows.

Para esta hemos puesto la interfaz de red en modo interno con el mismo nombre que le dimos a la segunda tarjeta de red de la máquina pfSense.

![img](/img/4.png)

Comprobamos que desde la MV Windows hace ping a la MV pfSense.

![img](/img/5.png)

Vía navegador Web entramos a la MV.

![img](/img/6.png)

Ya podemos ver el panel de configuración de la MV pfSense.

![img](/img/7.png)
