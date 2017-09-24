## 6. El servei de MySQL (mysqld) escolta al port 3306. Quina modificació/passos caldrien fer per canviar aquest port a 33306 per exemple?  

Afegint a l’arxiu /etc/my.cnf aquesta línia:  
&nbsp;&nbsp;&nbsp;&nbsp;port = 33306  
El guardem i reiniciem el servei amb la comanda:  
&nbsp;&nbsp;&nbsp;&nbsp;service mysqld restart   
