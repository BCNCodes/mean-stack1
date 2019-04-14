
# 1. APLICACIONS WEB
Eines que els usuaris poden fer servir mitjançant un navegador web.
## 1.1. Avantatges de les aplicacions web
* **Estalvi** en les **despeses** de maquinari i programari, ja que per accedir-hi únicament necessitem un ordinador, un smartphone o una tauleta amb accés a Internet.
* **Fàcils d’utilitzar**, solament es necessita saber navegar per Internet i disposar d’un correu electrònic per utilitzar-lo com a usuari i rebre les notificacions.
* **Faciliten el treball col·laboratiu**, a distància i asíncron entre diversos usuaris.
* Són **escalables** i de **ràpida actualització **ja que el procés d’actualització és molt ràpid i net en existir únicament una versió de l’aplicació en el servidor; aquest no afecta en res, per tant, ni a l’usuari ni al seu ordinador.
* Es produeixen **menys errors** ja que les aplicacions web tenen menys possibilitats de penjar-se i crear problemes tècnics en no haver-hi cap mena d’implicació en relació amb el maquinari o al sistema operatiu que utilitzi el client.
* La **informació** està **disponible** des de qualsevol dispositiu i lloc que es pugui connectar a Internet
## 1.2. Aplicacions web vs *Apps* de dispositius mòbils
 #| Aplicacions |   Apps
 --- | --- | ---
**Accés als continguts**:| navegador web | apps específiques
**Accés a Internet** |  Sí | Sí
**Instal·lació**|No n'hi ha|Des de l'*App Store*
**Actualització**|Transparent|Requereix autorització

## 1.3. Tecnologia de les aplicacions web

L’arquitectura bàsica d’una aplicació web està formada pels següents elements:

* **Un navegador**: actua com a client i realitza peticions sol·licitant recursos als servidors web. Quan fa una petició a un servidor i li respon enviant-li un recurs, el mostra a l’usuari.
* **Un servidor web**: rep peticions de clients (navegadors) i respon a aquestes peticions enviant un recurs o notificant un error si el recurs no existeix.
* **El protocol http**: és el protocol basat en TCP/IP que s’utilitza perquè el navegador realitzi les peticions als servidor web i aquests li responguin.
* **L’HTML** és el format bàsic dels documents de la web. Es tracta d’un format de text basat en etiquetes que permet estructurar el contingut de la pàgina.

A la següent figura es mostra l'arquitectura d'una aplicació web amb les tecnologies del MEAN-Stack:

![](https://imgur.com/W1awwXv.png)

## 1.4. *Web Responsive*

L’eclosió de l’ús de dispositius mòbils va motivar que les aplicacions web s’haguessin d’adaptar a aquest tipus de dispositius per millorar-ne l’usabilitat mitjançant un canvi en el seu disseny.
Les aplicacions web es van començar a dissenyar en base al **disseny responsive** (*responsive design*).
El contingut pren la forma del contenidor, mostrant la informació segons sigui necessari. Per tant, blocs de text, imatges i columnes senceres s’ajustaran a l’espai disponible —o no apareixeran— en funció de si s’hi accedeix des d’un telèfon, una tauleta o un ordinador.
El disseny web responsive és una tècnica de disseny web orientada a la correcta visualització d’una mateixa pàgina des de diferents dispositius, ja siguin d’ordinadors d’escriptori, telèfons, tauletes… 

### 1.4.1. Diseny responsive vs disseny adaptatiu

El disseny web responsive reestructura els elements de la web en la pantalla del dispositiu per optimitzar tot l’espai disponible i oferir la millor experiència d’usuari. Per aconseguir-ho s’estableixen unes mesures d’amplada i marges de disseny en grandàries proporcionals, en lloc d’establir valors fixes en els píxels.
Un disseny web adaptatiu no és tan flexible com el responsive ja que utilitza grandàries preestablertes per l’ordinador i pels dispositius mòbils.

## 1.5. Posicionament Web

El **SEO** (Search Engine Optimization) és el conjunt d’accions que ens ajuden a millorar la visibilitat d’un lloc web en els resultats de cerca en els diferents cercadors. El motiu pel que és necessari el SEO és perquè optimitza les pàgines web tant pels usuaris com pels motors de cerca ajudant aquests últims a entendre sobre què tracta cadascuna de les pàgines i si és o no d’utilitat pels usuaris.
El **SEM** (Search Engine Marketing) consisteix en el posicionament en cercadors mitjançant enllaços patrocinats o anuncis, que destaquen de la llista de resultats orgànica per estar situats estratègicament, a la part superior o dreta de la mateixa. És a dir, mitjançant anuncis no abusius, la nostra web apareixerà en els nostres primers llocs dels buscadors. Aquesta eina, que funciona mitjançant un sistema de pagament per clic, augmenta la visibilitat de la nostra web i la posiciona en un lloc preferent. Val a dir que, per gestionar aquest tipus de posicionament, va sorgir Google AdWords que permet crear campanyes per monitoritzar la nostra activitat.

## 1.6. Pàgines estàtiques vs interoperabilitat

La **Web 2.0**: surt per potenciar el dinamisme i la interoperabilitat, centrant el disseny en l’usuari i potenciant la col·laboració. Un lloc web 2.0 permet als usuaris interactuar i col·laborar entre ells com a creadors de continguts en una comunitat virtual. En contraposició a les pàgines estàtiques que no més mostren informació als usuaris.

# 2. Front-End

**HTML**, **CSS** y **JavaScript** són un grup de tecnologies i llenguatges que constitueixen el *front end* de les pàgines web. És a dir, la part de les aplicacions web que es visible per els usuaris.
Una aplicació web realitzarà tasques de emmagamatzematge de dades a una base de dades, resposta als requeriments dels usuaris o maneig de sesions (connexió d'usuaris).
Això és el *back end*, i és la part de l'aplicació que l'usuari no veu. 

## 2.2. Anatomia d'una pàgina Web

<!--![L'esquelet](https://imgur.com/yvLsQg1.png { width=50%}-->

<img src="https://imgur.com/yvLsQg1.png" width="50%" alt="l'esquelet" />

El paper qui juguen l'HTML, el CSS i el JavaScript a l'hora de compondre una  pàgina web page seria anàlog a la composició d'un corp humà; essent els ossos, la pell/pèl i els muscles respectivament.

### 2.2.1. Els ossos: HTML

Els ossos donen l'estructura. Sense ells, cauriem al terra formant un toll. L'HTML descriure majoritariament l’estructura dels documents que conformen les aplicacions web.
Donem-li una ullada a la pàgina web de SLACK: [Slack Website's](https://slack.com/intl/es-es/) HTML (per fer això, removem la capçalera de la pàgina, on es troben els estils).
Sense CSS tot es bastant lleig, pero conté tota l'informació per ser-hi un *website* funcional: vincles per navigar per el lloc, *headers* que descriuen el contingut i paràgrafs de text.

### 2.2.2. La pell/el pèl: CSS

Pell, pèl, roba i altres pertinences externes defineixen el nostre *look*. La majoria de la gent té un esquelet similar però tot portem un aspecte únique.
**CSS** s'utilitza per donar un estil únic a la pàgina web.
Tornem a la pàgina del centre...

### 2.2.3. Els músculs: JavaScript

Tenim una estructura i un aspecte, encara ens queda la capacitat que tenim per realitzar tasques: saltar, còrrer, ballar, i els músculs ens donem aquesta habilitat.
JavaScript proporciona l'interacció i el dinamisme als documents web.

<span style="text-decoration:underline">Exemple d'aplicació JavaScript</span>
<span style="font-size:0.75em">Imagineu un formulari de registre d’usuaris per un portal on figuren dos camps, un per posar clau d’usuari i un altre per repetir-la. Si volem verificar que aquesta clau sigui la mateixa abans de ser enviada amb el botó d’enviament de formulari, ho podem fer amb l’ús d’aquest llenguatge. Fins i tot podríem mostrar dinàmicament un missatge d’advertiment o modificar el color de fons d’aquest camp del formulari en cas d’error, per exemple en color vermell.</span>

![formulari](https://imgur.com/bncc5o5.gif)

