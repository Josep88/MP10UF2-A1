## 1. Un cop realitzada la instal·lació realitza una securització de la mateixa. Quin programa realitza aquesta tasca? Realitza una securització de la instal·lació indicant que la contrasenya de root sigui patata.

El programa es mysql_secure_installation.  
El primer que hi ha que fer per poder possar la contrasenya 'patata' es modificar la politica de seguretat de les contrasenyes, per aixó hem de modificar el fitxer de configuració _my.cnf_ i afegir les linies d'abaix de _[mysqld]_:
> ![1](https://image.ibb.co/gFWgUQ/Captura.png)  

Ara podem executar la comanda i ens pregunta la nova contrasenya del root:  
> ![1](https://i.imgur.com/POrffOl.png)  
  
Ens pregunta per fer altres configuracions que no volem modificar a aquet exercici:  
> ![2](https://i.imgur.com/RTPzSBi.png)  
  
Un cop ha acabat ja podrem entrar amb la nova contrasenya al mysql:  
> ![3](https://i.imgur.com/PM5Obyd.png)  

***
[Torna enrere](https://github.com/Josep88/MP10UF2-A1)
