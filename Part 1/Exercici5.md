## 5. Crea un usuari anomenat asix en el sistema operatiu i en SGBD de tal manera que aquest usuari del sistema operatiu no hagi d'introduir l'usuari i password cada vegada que cridem al client mysql?  

Cream l’usuari i contrasenya al sistema operatiu amb l'usuari 'root':
>![5](https://i.imgur.com/RsfSVbK.png)  

I al MySQL també els creem amb l'usuari 'root':  
>![52](https://image.ibb.co/gxWbw5/Captura.png)  

Ens conectem al usuari ‘asix’ i amb el programa mysql_config_editor creem l’entrada:  
>![53](https://i.imgur.com/M0T2TpA.png)  

Com es veu a la imatge, despres de fer la comanda de mysql_config_editor s'ha entrat al MySQL amb tan sols la comanda mysql.

***
[Torna enrere](https://github.com/Josep88/MP10UF2-A1)
