# INSTAL·LACIÓ SGBD NoSQL MongoDB
***  

Primer de tot hi ha que crear un fitxer per poder instal·lar el MongoDB directament:  
>![1](https://raw.githubusercontent.com/Josep88/MP10UF2-A1/master/Part%202/img/01.PNG)  

I al fitxer hi posem aquest contingut:
>![2](https://raw.githubusercontent.com/Josep88/MP10UF2-A1/master/Part%202/img/02.PNG)

I ja podem executar la comanda per instal·lar-lo:
>![3](https://raw.githubusercontent.com/Josep88/MP10UF2-A1/master/Part%202/img/03.PNG)

Un cop ha acabat la instal·lació hi ha que modificar el fitxer _/etc/selinux/config_ i modificar el SELINUX a disabled:
>![4](https://raw.githubusercontent.com/Josep88/MP10UF2-A1/master/Part%202/img/04.PNG)

Un cop fet hi ha que reiniciar el servidor per a que surti efecte la modificació.
Un cop reiniciat, podem utilitzar les comandes:
&nbsp;&nbsp;Iniciar el servei del MongoDB  
>&nbsp;&nbsp;&nbsp;&nbsp;service mongod start  
  
&nbsp;&nbsp;Comprovar l'estat del servei  
>&nbsp;&nbsp;&nbsp;&nbsp;systemctl status mongod  

&nbsp;&nbsp;Parar el servei del MongoDB  
>&nbsp;&nbsp;&nbsp;&nbsp;service mongod stop  
***
[Torna enrere](https://github.com/Josep88/MP10UF2-A1)
