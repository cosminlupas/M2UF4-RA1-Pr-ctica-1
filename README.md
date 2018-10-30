# 1 Instal.lació SGBD Postgresql en entorn virtual
#### 1. Instal.lació d’un sgbd Postgresql en un entorn virtual Ubuntu Server 16.04.03
![](/imgP1/pregunta1p1.png)
#### 2. Aneu a la pàgina: https://www.ubuntu.com/download/server i descarregeu la darrera versió LTS de Server.
![](/imgP1/pregunta2p1.png)
#### 3. A partir d’una instal.lació mínima, feu la instal.lació dels paquets necessaris per poder funcionar ( paquet LAMP).
![](/imgP1/pregunta3p1.png)
#### 4. Per facilitar la feina i fer més intuitiu i visual el sistema, instal.leu i configureu un escriptori gràfic. Es recomana utilitzar XFCE ( el més lleuger i menys ocupa).
![](/imgP1/pregunta4p1.png)
#### 5. Es recomana així mateix instal.lar els programes Synaptic ( gestió de paquets) i geany (editor de text). 
![](/imgP1/pregunta5p1.png)

# 2 Configuració sistema
#### 1. AdministradorSistema : tindrà els permisos de root en el sistema ( en particular instal.lar programas, accedir carpetes del sistema, crear usuaris...), però en el SGBD serà un usuari «normal». 
![](/imgP2/pregunta1-1p2.png)
![](/imgP2/pregunta1-2p2.png)
#### 2. AdministradorBD: en el sistema tendrà permisos de usuari normal i en la base de Dades «superuser»: podra crear bases de dades, crear taules i crear usuaris/roles. 
![](/imgP2/pregunta2-1p2.png)
![](/imgP2/pregunta2-2p2.png)
#### 3. Usuari: No tindrà permisos especials ni en el sistema ni en el SGBD, però podra accedir a tots dos.
![](/imgP2/pregunta3-1p2.png)
![](/imgP2/pregunta1-2p2.png)

#  3 Configuració SGBD Postgresql 
#### 1. Per accedir per primer cop al SGBD haurieu d’entrar com usuari postgres utilitzant la instrucció: sudo -i -u postgres, i un cop estem com usuari postgres fem psql per connectarnos a la base de dades.
