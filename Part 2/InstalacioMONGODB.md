# INSTAL·LACIÓ SGBD NoSQL MongoDB
***  

Primer de tot hi ha que crear un fitxer per poder instal·lar el MongoDB directament:  
>![1]()  

I al fitxer hi posem aquest contingut:
>![2]()

I ja podem executar la comanda per instal·lar-lo:
>![3]()

Un cop ha acabat la instal·lació hi ha que modificar el fitxer _/etc/selinux/config_ i modificar el SELINUX a disabled:
>![4]()

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
