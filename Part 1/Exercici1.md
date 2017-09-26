## 1. Un cop realitzada la instal·lació realitza una securització de la mateixa. Quin programa realitza aquesta tasca? Realitza una securització de la instal·lació indicant que la contrasenya de root sigui patata.

El programa es mysql_secure_installation.  
El primer que hi ha que fer per poder possar la contrasenya 'patata' es modificar la politica de seguretat de les contrasenyes, per aixó hem de modificar el fitxer de configuració _my.cnf_ i afegir les linies d'abaix de _[mysqld]_:
> ![1](https://raw.githubusercontent.com/Josep88/MP10UF2-A1/master/Part%201/img/11.png)  

Ara podem executar la comanda i ens pregunta la nova contrasenya del root:  
> ![1](https://raw.githubusercontent.com/Josep88/MP10UF2-A1/master/Part%201/img/12.png)  
  
Ens pregunta per fer altres configuracions que no volem modificar a aquet exercici:  
> ![2](https://raw.githubusercontent.com/Josep88/MP10UF2-A1/master/Part%201/img/13.png)  
  
Un cop ha acabat ja podrem entrar amb la nova contrasenya al mysql:  
> ![3](https://raw.githubusercontent.com/Josep88/MP10UF2-A1/master/Part%201/img/14.png)  

***
[Torna enrere](https://github.com/Josep88/MP10UF2-A1)
