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
![](/imgP3/pregunta1-1p3.png)
![](/imgP3/pregunta1-2p3.png)
#### 2. Crear almenys una base de dades nova.
![](/imgP3/pregunta2-1p3.png)
![](/imgP3/pregunta2-2p3.png)
#### 3. Afegir almenys una base de dades. Podeu anar http://pgfoundry.org/projects/dbsamples/ i descarregar la bases de dades de prova ( pagila). Trobareu un zip amb un fitxer sql, schema i altre data.
![](/imgP3/pregunta3-1p3.png)
![](/imgP3/pregunta3-2p3.png)
![](/imgP3/pregunta3-3p3.png)
#### 4. Configurar els permisos i roles segons la descripció feta en l’apartat 2.
![](/imgP2/pregunta1-2p2.png)
![](/imgP2/pregunta2-2p2.png)
![](/imgP2/pregunta1-2p2.png)
#### 5. Instal.lar i configurar el programa phppgadmin: que ens donara accés via web al nostre gestor
![](/imgP3/pregunta5-1.png)
![](/imgP3/pregunta5-2.png)

#  4 Utilització bàsica Postgresql 
#### 1. Cerqueu en internet i proveu les instruccions més usuals en consola del SGBD.( Ex: \dt, \du, exit...)
![](/imgP4/p1-1p4.png)
![](/imgP4/p1-2p4.png)
![](/imgP4/p1-3p4.png)
#### 2. Executeu algunes instruccions sql en el terminal del SGBD. ( les instruccions SQL acaven en ;)
![](/imgP4/p2-1p4.png)
#### 3. Crear un fitxer sql, utilitzant per exemple geany, i carregar-lo des de consola utilitzant la instrucció \i script1.sql ( vigileu el path). Podeu utilitzar com referència els fitxers de la base de dades pagila descarregada en activitats anteriors
![](/imgP4/p3-1p4.png)
![](/imgP4/p3-2p4.png)
#### 4. Expliqueu alguns paràmetres de psql i el que fa realment ( sistema)
- psql -l -> serveix per veure les base de dades creades 
- psql "nom de la db" -> serveix per entrar a la base de dades 
- \d -> per veure les relacions amb el schema, name, type, owner
- etc .....
