<h1>JAVASCRIPT</h1>


- [1. Arquitectures web](#1-arquitectures-web)
  - [1.1. Arquitectures web. Models](#11-arquitectures-web-models)
    - [1.1.1. El model client-servidor](#111-el-model-client-servidor)
    - [1.1.2. Aplicacions basades en el web](#112-aplicacions-basades-en-el-web)
  - [1.2. Servidors web i d'aplicacions. Instal·lació i configuració bàsica](#12-servidors-web-i-daplicacions-installaci%C3%B3-i-configuraci%C3%B3-b%C3%A0sica)
    - [1.2.1. Servidors web](#121-servidors-web)
    - [1.2.2. Servidors d'aplicacions](#122-servidors-daplicacions)
    - [1.2.3. Servidors de bases de dades](#123-servidors-de-bases-de-dades)
    - [1.2.4. Servidors de fitxers](#124-servidors-de-fitxers)
    - [1.2.5. Servidors de directori](#125-servidors-de-directori)
  - [1.3. Estructura i recursos d'una aplicació web](#13-estructura-i-recursos-duna-aplicaci%C3%B3-web)
    - [1.3.1. Arquitectura multinivell](#131-arquitectura-multinivell)
    - [1.3.2. Arquitectura model-vista-controlador](#132-arquitectura-model-vista-controlador)
- [2. Navegadors web](#2-navegadors-web)
  - [2.1. Arquitectura d'un navegador](#21-arquitectura-dun-navegador)
  - [2.2. El procés de navegació (_browser process_)](#22-el-proc%C3%A9s-de-navegaci%C3%B3-browser-process)
  - [2.3. Navegadors d'ús comú. Comparativa](#23-navegadors-d%C3%BAs-com%C3%BA-comparativa)
  - [2.4. Seguretat en navegadors](#24-seguretat-en-navegadors)
    - [2.4.1. Cross-Site Scripting (XSS)](#241-cross-site-scripting-xss)
    - [2.4.2. Injecció SQL](#242-injecci%C3%B3-sql)
    - [2.4.3. Cross Site Request Forgery (CSRF)](#243-cross-site-request-forgery-csrf)
    - [2.4.4. Altres amenaces](#244-altres-amenaces)
  - [2.5. Conformitat amb estàndards](#25-conformitat-amb-est%C3%A0ndards)
  - [2.6. El motor de JavaScript. Execució de JavaScript en línia d'ordres](#26-el-motor-de-javascript-execuci%C3%B3-de-javascript-en-l%C3%ADnia-dordres)
- [3. JavaScript en les pàgines web](#3-javascript-en-les-p%C3%A0gines-web)
  - [3.1. Integració del codi JavaScript en el codi HTML. Primer exemple](#31-integraci%C3%B3-del-codi-javascript-en-el-codi-html-primer-exemple)
    - [3.1.1. Fitxers JavaScript externs](#311-fitxers-javascript-externs)
  - [3.2. JavaScript: programació dirigida per esdeveniments](#32-javascript-programaci%C3%B3-dirigida-per-esdeveniments)
  - [3.3. Eines i entorns per al desenvolupament web](#33-eines-i-entorns-per-al-desenvolupament-web)
  - [3.4. Sintaxi bàsica del llenguatge JavaScript](#34-sintaxi-b%C3%A0sica-del-llenguatge-javascript)
    - [3.4.1. Sentències, comentaris, variables](#341-sent%C3%A8ncies-comentaris-variables)
    - [3.4.2. Àmbit i visibilitat de les variables](#342-%C3%A0mbit-i-visibilitat-de-les-variables)
    - [3.4.3. Tipus de dades](#343-tipus-de-dades)
    - [3.4.4. Assignacions](#344-assignacions)
    - [3.4.5. Operadors](#345-operadors)
    - [3.4.6. Decisions](#346-decisions)
    - [3.4.7. Bucles](#347-bucles)
    - [3.4.8. Exercici:](#348-exercici)
  - [3.5. Arrays](#35-arrays)
    - [3.5.1. Operacions](#351-operacions)
    - [3.5.2. Accedir als elements](#352-accedir-als-elements)
    - [3.5.3. Afegir Elements](#353-afegir-elements)
    - [3.5.4. Esborrar Elements](#354-esborrar-elements)
    - [3.5.5. Iteració sobre els elements d'un array](#355-iteraci%C3%B3-sobre-els-elements-dun-array)
    - [3.5.6. funció `forEach`](#356-funci%C3%B3-foreach)
  - [3.6. Objectes predifinits de JavaScript](#36-objectes-predifinits-de-javascript)
    - [3.6.1. L'objecte String](#361-lobjecte-string)
    - [3.6.2. L'objecte Number](#362-lobjecte-number)
    - [3.6.3. L'objecte Math](#363-lobjecte-math)
    - [3.6.4. L'objecte Date](#364-lobjecte-date)
    - [3.6.5. L'objecte RegExp](#365-lobjecte-regexp)
  - [3.7. BOM (Browser Object Model)](#37-bom-browser-object-model)
    - [3.7.1. L'objecte window. Jerarquia d'objectes associats al navegador](#371-lobjecte-window-jerarquia-dobjectes-associats-al-navegador)
    - [3.7.2. L'objecte document](#372-lobjecte-document)
    - [3.7.3. L'objecte location](#373-lobjecte-location)
    - [3.7.4. L'objecte history](#374-lobjecte-history)
    - [3.7.5. L'objecte navigator](#375-lobjecte-navigator)
    - [3.7.6. L'objecte screen](#376-lobjecte-screen)
# 1. Arquitectures web

El model d’arquitectura bàsic que hi ha en tota aplicació web és el model anomenat **client-servidor**, en el qual entren en joc diverses màquines o plataformes, cadascuna de les quals desenvolupa un rol diferenciat en l’execució de l’aplicació. Segons les necessitats i la complexitat de l’aplicació, aquest model bàsic d’arquitectura es pot complicar més o menys per tal d’aconseguir una millor distribució de tasques, millor rendiment, fiabilitat, augment de la capacitat de procés, etc.

## 1.1. Arquitectures web. Models

Una aplicació distribuïda està formada per una col·lecció d’ordinadors autònoms enllaçats per una xarxa d’ordinadors i suportats per un programari que fa que la col·lecció actuï com un servei integrat.

### 1.1.1. El model client-servidor

El model **client-servidor** és un model d’arquitectura d’aplicacions en el qual es defineixen o s’assignen principalment dos rols als ordinadors, que són, com el nom del model indica, els rols de **client** i de **servidor** com s'indiqueix a la següent figura:

![](https://imgur.com/3oNzCxz.png)

<p style="line-height:100%;"><em style="font-size:small;">* Els clients fan peticions de servei. Normalment els clients inicien la comunicació amb el servidor.
Servidors: proveeixen serveis. Normalment els servidors esperen rebre peticions. Un cop han rebut una petició, la resolen i retornen el resultat al client. </em></p>

Els servidors poden ser amb **estat** o **sense estat**. Un servidor sense estat no manté cap informació entre peticions, mentre que un servidor amb estat pot recordar informació entre peticions. Per exemple, un servidor sense estat podria ser aquell que conté pàgines web estàtiques. En canvi, un servidor que tingui una pàgina web amb contingut dinàmic seria un exemple de servidor amb estat.

El model client-servidor bàsic de la figura anterior és vàlid per a aplicacions web petites, senzilles i que no tinguin una gran càrrega de treball, és a dir, un nombre petit de clients connectats simultàniament.

### 1.1.2. Aplicacions basades en el web

Un cas particular d’aplicacions client-servidor són les aplicacions que s’executen aprofitant l’arquitectura del web. Aquestes aplicacions es basen en el fet de tenir tota la capacitat de processament en un servidor web (o conjunt de servidors) al qual s’accedeix des d’un navegador web.

Quan un usuari clica sobre un enllaç d’una pàgina web del seu navegador, aquest genera una petició al servidor que conté la informació. Un cop el servidor rep la petició, retorna el contingut. La comunicació entre client i servidor es fa mitjançant el protocol HTTP.

## 1.2. Servidors web i d'aplicacions. Instal·lació i configuració bàsica

Durant les fases de desenvolupament, de posada en producció i de manteniment d’una aplicació web podem trobar-nos amb diversos tipus de servidors que duen a terme tasques concretes dins el funcionament global.

### 1.2.1. Servidors web

Un servidor web és un servidor que permet l’accés a recursos mitjançant el **protocol HTTP** (HyperText Transfer Protocol) d’internet.

La definició original i estricta del concepte de servidor HTTP fa referència a aquells servidors capaços de donar accés i de permetre la gestió d’un conjunt de recursos estàtics com a resposta a peticions rebudes pels clients. És a dir, que permeten consultar, carregar i eliminar recursos del servidor. Aquests recursos solen ser documents d’HTML o variants d’aquest format i continguts adjunts o relacionats amb aquests documents, com poden ser imatges, vídeos, etc.

Aquests recursos solen estar guardats en forma d’arxius a dispositius d’emmagatzematge propis del servidor.

El concepte original de servidor web no contempla la possibilitat de generar de forma dinàmica els continguts a partir de l’execució de codi com a resposta de les peticions. Però, en l’actualitat, la majoria de servidors web admeten la instal·lació de mòduls que permeten que es generin continguts dinàmics a partir de l’execució de programes escrits en diversos llenguatges de programació (PHP, Javascript, Python, Perl, etc.), tot i que aquesta característica és més pròpia dels servidors d’aplicacions.

Alguns exemples de servidors web són Apache HTTP Server, per a sistemes operatius Linux, i Microsoft Internet Information Server, per a Windows.

### 1.2.2. Servidors d'aplicacions

Un servidor d’aplicacions en general és un servidor que ofereix als clients un servei d’execució d’aplicacions. Si ens centrem en les aplicacions web, un servidor d’aplicacions és un programari que controla l’execució de programes. Els clients, des d’un navegador (usant el protocol HTTP), accedeixen a una interfície web des d’on executaran l’aplicació. Normalment, els servidors d’aplicacions s’utilitzen en aplicacions web amb un grau de complexitat elevat.

Un servidor d’aplicacions web es pot entendre com un servidor orientat a l’execució de programes que pot rebre les peticions de servei i retornar els resultats utilitzant els mateixos protocols (HTTP) i formats de dades que els servidors web (HTML). Si el mateix servidor no té la capacitat d’interactuar amb aquests protocols pot treballar conjuntament amb el suport d’un servidor web que faci d’intermediari entre el servidor d’aplicacions i el client. Els servidors d’aplicacions, a més, acostumen a proporcionar un ampli conjunt de serveis complementaris orientats a la persistència de dades, la seguretat, el control de transaccions i concurrència, entre d’altres.

Alguns exemples de servidors d’aplicacions són GlassFish (servidor Java EE, Oracle) o Microsoft Internet Information Server (servidor .NET).

### 1.2.3. Servidors de bases de dades

Un servidor de bases de dades s’utilitza per emmagatzemar, recuperar i administrar les dades d’una base de dades. El servidor gestiona les actualitzacions de dades, permet l’accés simultani de molts servidors o usuaris web i garanteix la seguretat i la integritat de les dades.

Entre les seves funcions bàsiques, el programari de servidors de bases de dades ofereix eines per facilitar i accelerar l’administració de bases de dades. Algunes funcions són l’exportació de dades, la configuració de l’accés dels usuaris i el suport de dades.

Alguns exemples de servidors de bases de dades són Oracle Database, MySQL, Microsoft SQL Server, PostreSQL, MongoDB o Firebase.

### 1.2.4. Servidors de fitxers

Un servidor de fitxers és un servidor que permet gestionar a través de xarxa la càrrega, descàrrega, actualització i eliminació de fitxers emmagatzemats en els seus dispositius des d’ordinadors client.

En l’àmbit de les aplicacions web, els servidors de fitxers s’utilitzen principalment per desplegar les aplicacions sobre el servidor on s’executaran. El desplegament d’una aplicació web sobre els servidors de producció comporta habitualment la càrrega de grans quantitats de fitxers sobre aquests servidors. Com que el desenvolupament i manteniment d’aquestes aplicacions es fa en les màquines dels programadors, cal algun sistema de transferència d’arxius cada cop que es vol actualitzar la versió de producció d’una aplicació.

Un dels protocols més usats per a la transferència de fitxers en el desplegament d’aplicacions web és el protocol FTP (file transfer protocol), amb les seves variants FTPS i SFTP per adaptar-se a les necessitats actuals de seguretat.

Alguns exemples de servidors de transferència de fitxers són ProFTPD o vsftpd, per a sistemes operatius Linux, i Microsoft Internet Information Server, per a Windows.

### 1.2.5. Servidors de directori

Un servidor de directori és un servidor que permet gestionar informació administrativa respecte a l’entorn d’una aplicació web, com poden ser, per exemple, els usuaris ritzats amb els seus rols o permisos, etc.

La utilitat principal dels servidors de directori és facilitar la gestió d’informació relativa a l’explotació d’aplicacions web. L’avantatge de gestionar aquesta informació mitjançant aquest tipus de servidors és la centralització de dades i la facilitat d’accés mitjançant protocols estàndard com LDAP.

Alguns exemples de servidors de directori són OpenLDAP, per a Linux, i Active Directory, per a Windows.

## 1.3. Estructura i recursos d'una aplicació web

Les aplicacions web, a més de presentar un arquitectura client-servidor (fet que no és necessari en el cas de les aplicacions d’escriptori), solen estar estructurades amb una gran quantitat d’arxius i recursos de tipus diferents.

És per això que cal establir unes directrius per tal d’organitzar la ubicació d’aquests components i la seva interrelació durant la fase de desenvolupament, així com també en el moment de posar l’aplicació en producció. En cas contrari, el desenvolupament i manteniment d’una aplicació de mida mitjana o gran es convertirà en una tasca gairebé impossible de gestionar.

Oblidant-nos de l’organització o estructura que imposa el fet d’escollir unes determinades eines de desenvolupament o un determinat servidor web o d’aplicacions, aquestes aplicacions es poden estructurar segons diversos models d’organització dels seus components i recursos. Alguns dels models d’estructuració d’aplicacions web que podem trobar més habitualment són els que es descriuen a continuació.

### 1.3.1. Arquitectura multinivell

L’arquitectura multinivell (multitier architecture) és un tipus concret de l’arquitectura client-servidor en la qual els components i recursos d’una aplicació se separen segons la seva funció. Una de les divisions més utilitzades és la que separa el nivell de presentació, el nivell de lògica d’aplicació i el nivell de gestió de dades.

En aquest cas, l’estructura concreta seria de tres nivells (3-tier architecture). El model es defineix com a N-tier architecture (multinivell), ja que proposa una divisió flexible de les aplicacions en els nivells que calgui per tal de fer més eficient el seu desenvolupament, manteniment i explotació.

En aquest model, la divisió per nivells es fa de forma lineal: el nivell 1 interactua de forma directa i única amb el nivell 2, el nivell 2 interactua amb el 3, i així successivament. A la següent figura es descriu aquesta arquitectura:

![arq-multinivell](https://imgur.com/pjqx1cq.png)

Cal diferenciar entre el concepte multinivell (multitier N-tier) i multicapa (multilayer N-layer). En aquest cas, es considera que en el model multinivell cada nivell, a més d’implementar una funció concreta, és executat per un maquinari diferent de la resta de nivells. En el model multicapa, cada capa desenvolupa una funció concreta que pot ser executada per un mateix ordinador que s’encarrega, també, de l’execució d’altres capes.

### 1.3.2. Arquitectura model-vista-controlador

L’arquitectura model-vista-controlador (**model view controller**) és una arquitectura que separa la representació de la informació i la lògica d’una aplicació de la interacció de l’usuari.

Els tres elements que defineix aquesta arquitectura són:

**Model**: conté les dades de l’aplicació, les regles de negoci o la lògica de l’aplicació i les seves funcions.
**Vista**: és la representació visible de l’aplicació, la sortida de les dades cap a l’usuari, és a dir, la interfície.
**Controlador**: controla la interacció de l’usuari (entrada de dades) i converteix aquesta interacció en ordres o comandes per al model o la vista.
La interrelació entre els elements d’aquesta arquitectura no es fa seguint un model lineal com el model multinivell, sinó que es tracta d’un model circular. Veiem la següent figura:

![mvc](https://imgur.com/V21MWJb.png)

Paral·lelament a l’estructura de l’aplicació, cal tenir en compte que cada nivell, capa o mòdul pot estar format per un gran nombre de components i recursos de diversos tipus: fitxers HTML, CSS, imatges, etc.

Per això és convenient establir un sistema d’organització coherent i eficient per tal d’estructurar tots aquests components que s’acaben generant durant el desenvolupament d’una aplicació web. La majoria de plataformes de desenvolupament avançades imposen mecanismes per tal d’organitzar i descriure de manera sistemàtica la localització, les característiques i la configuració dels components i recursos de les aplicacions.

Entre aquests mecanismes en destaquen dos:

- **Estructura de directoris**: les plataformes avançades de desenvolupament d’aplicacions web acostumen a definir una estructura de directoris mínima que tota aplicació ha de tenir a partir de la qual es despleguen els diversos tipus de components. Els desenvolupadors han de seguir les directrius de cada plataforma.
- **Descriptor de desplegament**: hi ha un fitxer de configuració on es pot especificar el nom, la ubicació i els paràmetres de configuració dels diversos components que formen una aplicació per tal de tenir aquesta informació centralitzada, accessible i actualitzable sense necessitat de fer modificacions en el codi font de l’aplicació. Aquest descriptor descriu com s’ha de desplegar l’aplicació en el servidor.

# 2. Navegadors web

![](https://imgur.com/YdPTRNR.png)

Un navegador web (generalment referit com a navegador) és una aplicació de programari per recuperar, presentar, i intercanviar recursos d'informació en el **_World Wide Web_**. Un recurs d'informació és identificat per un Identificador de Recurs Uniforme (URL/d'URI) i pot ser una pàgina web, imatge, vídeo o altra peça de contingut. Els _hyperlinks_ presents permeten als usuaris navegar fàcilment als recursos relacionats. Tot i que els navegadors són principalment pretès per utilitzar amb la _World Wide Web_, també es poden fer servir per accedir a la informació proporcionada per servidors a xarxes privades o a arxius dins de sistemes d'arxiu.

## 2.1. Arquitectura d'un navegador

Els components principals d'un navegador són:

- **Interfície d'usuari**: L'UI és l'espai a on l'usuari interacciona amb el navegador. Inclou la barra de navegació (URLs), botó enrere/endavant, butó d'inici, refrescar i parar, opcions de favorits, etc. Totes les parts, excepte la finestra on es visualitza la pàgina web requerida.

* **Motor de navegació**: Intermediari entre l'UI i el motor de _renderitzat_. Consulta i manipula el motor de renderitzat.

- **Motor de renderitzat**: interpreta els documents HTML i XML i imatges als que s'ha donat format utilitzant CSS, i genera l'estructura que es desplegarà a l'UI. Els diferents navegadors usan diferents motors de renderitzat:

  - Internet Explorer: _Trident_,
  - Firefox & other Mozilla browsers: _Gecko_,
  - Chrome & Opera 15+: _Blink_,
  - Chrome (iPhone) & Safari: _Webkit_

* **Networking**: Component del navegador que recupera las URLs mitjançant els protocols d'Internet HTTP o FTP. El component _networking_ manega tots els aspects de la comunicació i la seguretat d'Internet. Aquest component pot implementar la caché per recuperar documents i reduir el trànsit de xarxa.

- **JavaScript Interpreter**: motor de interpretació i execució del codi javascript inserit en un document web. El resultat interpretat s'envia al motor de renderitzat per a la visualització. Si el _script_ és extern, aleshores el component _networking_ el recupera en primer lloc. El procès de _parsing_ es detè fins que finalitza l'interpretació.

* **UI Backend**: UI backend is used for drawing basic widgets like combo boxes and windows. This backend exposes a generic interface that is not platform specific. It underneath uses operating system user interface methods.

- **Data Persistence/Storage**: This is a persistence layer. Browsers support storage mechanisms such as localStorage, IndexedDB, WebSQL and FileSystem. It is a small database created on the local drive of the computer where the browser is installed. It manages user data such as cache, cookies, bookmarks and preferences.

![](https://imgur.com/xBfF6kV.png)

## 2.2. El procés de navegació (_browser process_)

Per millorar la seguretat davant els atacs deguts a contingut maliciós es maneja un procés separat per cadascuna de les peticions de contingut. El procés separat es diu procés de renderització (correspon amb cada pestanya del navegador), i té privilegis limitats (i.e, accés limitat).

When one requests for a web site, the render process forwards the request to the browser process which in-turn makes the network calls for the website. After the arrival of the web content, the browser process sends the content to the renderer process. The renderer process parses the HTML,CSS fils, prepares the DOM, maintains the JS run time (V8 instance) and sends the content as a bitmap format to the browser process for displaying it on the UI.

The browser process treats the renderer process as a black box and expects the web content in a certain format from the renderer process. This conversion of web content to the required format includes several sub-components of which layout engine (process) is one.

So, Browser process handles the user privileged resources/requests like access to filesystem, network etc. where as the sandboxed Renderer process is responsible for converting the web pages to a format that browser-process can put it to display in a OS native window manager.

## 2.3. Navegadors d'ús comú. Comparativa

Quan es prepara un lloc web és recomanable comprovar que es visualitza correctament als navegadors més utilitzats. En els anys en els quals els navegadors de Microsoft no respectaven les recomanacions del W3C aquesta tasca no resultava senzilla, però afortunadament en els últims anys les diferències entre els navegadors s'han reduït moltíssim.

Fins fa uns anys també era necessari tenir en compte les versions anteriors dels navegadors, sobretot en el cas d'Internet Explorer, ja que les diferències d'una versió a una altra eren notables. Afortunadament, aquest problema també s'ha reduït ja que els principals navegadors s'actualitzen màticament i el nombre d'usuaris de les versions antigues és irrellevant.

Actualment, el navegador més utilitzat és Google Chrome, amb molta diferència sobre el grup de navegadors minoritaris format per Safari, Firefox, Internet Explorer 11 i Microsoft Edge (vegeu la lliçó sobre l'ús de navegadors). Entre ells, l'únic navegador problemàtic és Internet Explorer 11, ja que encara manté una petita quota de mercat però, a causa de la seva antiguitat (es va publicar en 2013), és el que presenta més diferències amb la resta,

L'enllaç [Diferències entre navegadors](http://www.mclibre.org/consultar/htmlcss/otros/diferencias-listado.html), recull algunes de les diferències de interpretació del HTML y CSS als navegadors.

## 2.4. Seguretat en navegadors

La seguretat eficaç d'un lloc web requereix d'esforços de disseny a tots els àmbits de la web:

- Disseny de l'aplicació web,
- Configuració del servidor web,
- Polítiques de creació i renovació de contrasenyes,
- Codi del costat client.

Si s'utilitza un _framework_ web de servidor, s'habiliten per defecte mecanismes de defensa robusts i ben pensats contra gran quantitat dels atacs més comuns. Altres atacs poden mitigar-se per mitjà de la configuració del servidor web, per exemple habilitant HTTPS. Finalment, hi ha eines d'escanejat de vulnerabilitats disponibles públicament que poden ajudar a esbrinar alguns errors.

A continuació s'exposen algunes de les amenaces més comuns i com mitigar-les:

### 2.4.1. Cross-Site Scripting (XSS)

Tipus d'atac que permet a l'atacant injectar scripts al costat client, utilitzant el lloc web, fins als exploradors d'altres usuaris. Com el codi injectat va del servidor del lloc a l'explorador, se suposa de confiança, i d'aquí que pugui fer coses com enviar a l'atacant la cookie d'rització a el lloc de l'usuari. Una vegada que l'atacant té la \*cookie poden iniciar sessió en el lloc com si fos el veritable usuari i fer qualsevol cosa que pugui fer aquest. Depenent que lloc sigui, això podria incloure accés als detalls de la seva targeta de crèdit, veure detalls de contactes o canviar contrasenyes, etc.

Hi ha dues aproximacions principals per aconseguir que el lloc retorni scripts injectats a l'explorador — es coneixen com a vulnerabilitats XSS reflectides i persistents.

La millor defensa contra les vulnerabilitats XSS és eliminar o deshabilitar qualsevol etiqueta que pugui contenir instruccions per executar codi. Etiquetes com `<script>`, `<object>`, `<embed>`, i `<link>` del HTML.

El procés de modificar les dades de l'usuari de manera que no puguin utilitzar-se per executar scripts o que afectin d'una altra forma l'execució del codi del servidor, es coneix com a "desinfecció d'entrada" (*input *sanitization). Molts \*frameworks web desinfecten màticament l'entrada de l'usuari des de formularis HTML, per defecte.

### 2.4.2. Injecció SQL

Les vulnerabilitats d'Injecció SQL habiliten a usuaris maliciosos per executar codi SQL arbitrari en una base de dades, permetent que es pugui accedir a les dades, es puguin modificar o esborrar, independentment dels permisos de l'usuari. Un atac d'injecció amb èxit, podria falsificar identitats, crear noves identitats amb drets d'administració, accedir a totes les dades en el servidor o destruir/modificar les dades per fer-los inutilitzables.

La manera d'evitar aquesta classe de atac és assegurar que qualsevol dada d'usuari que es passa a una consulta SQL no pot canviar la naturalesa del mateix. Una forma de fer això és eludir ('fuita') tots els caràcters en l'entrada d'usuari que tinguin un significat especial en SQL.

### 2.4.3. Cross Site Request Forgery (CSRF)

Els atacs de CSRF permeten que un usuari maliciós executi accions usant les credencials d'un altre usuari sense el coneixement o consentiment d'aquest.

Aquest tipus d'atac s'explica millor amb un exemple. John és un usuari maliciós que sap que un lloc en particular permet als usuaris que han iniciat sessió enviar diners a un compte específic usant una petició HTTP POST que inclou el nom del compte i una quantitat de diners. John construeix un formulari que inclou els detalls del seu banc i una quantitat de diners com a camps ocults, i ho envia per correu electrònic a altres usuaris del lloc (amb el botó d'Enviar camuflat com a enllaç a un lloc "fes-te ric ràpidament").

Si l'usuari punxa el botó d'enviar, s'envia al servidor una petició HTTP POST que conté els detalls de la transacció i tots els cookies de costat-client que l'explorador associa amb el lloc (afegir cookies associats amb el lloc és un comportament normal dels exploradors). El servidor comprovarà els cookies, i els usarà per determinar si l'usuari ha iniciat sessió o no i si té permís per fer la transacció.

El resultat és que qualsevol usuari que punxi en el botó Enviar mentre té la sessió iniciada en el lloc comercial farà la transacció. John es farà ric!

Nota: El truc aquí és que John no necessita tenir accés als cookies de l'usuari (o accés a les seves credencials) — L'explorador de l'usuari emmagatzema aquesta informació, i la inclou màticament en totes les peticions al servidor associat.

Una manera de prevenir aquest tipus d'atac per part del servidor és requerir que la petició POST inclogui una paraula secreta específica de l'usuari generada pel lloc (la paraula secreta podria proporcionar-la el servidor quan envia el formulari web que s'usa per fer transferències). Aquesta aproximació evita que John pugui crear el seu propi formulari, perquè necessitaria conèixer la paraula secreta que el servidor ha proporcionat per a l'usuari. Fins i tot si conegués aquesta paraula i creés un formulari per a un usuari en particular, no podria usar el mateix formulari per atacar a tots els usuaris.

Els frameworks web inclouen amb freqüència tals mecanismes de prevenció de CSRF.

### 2.4.4. Altres amenaces

Uns altres ataquis/vulnerabilitats inclouen:

- **Clickjacking**. En aquest tipus d'atac, l'usuari maliciós segresta les pulsacions de ratolí dirigides a un lloc visible per sobre dels altres i les redirigeix a una pàgina amagada per sota. Aquesta tècnica s'usaria, per exemple, per presentar un lloc bancari legítim però capturar les credencials d'inici de sessió en `<iframe>` invisible controlat per l'atacant. Alternativament podria usar-se per aconseguir que l'usuari punxés sobre un botó en un lloc visible, però en fer-ho realment estigués sense advertir-ho punxant en un altre botó completament diferent. Com a defensa, el teu lloc pot protegir-se de ser embegut en un `iframe` d'un altre lloc configurant les capçaleres HTTP apropiadament.

* **Denegació de Servei**, (Denial of Service, DOS). DOS s'aconsegueix normalment inundant el lloc objectiu amb peticions il·lógiques de manera que s'interrompi l'accés als usuaris legítims. Les peticions poden simplement ser nombroses, o consumir individualment gran quantitat de recursos (ex. lectures lentes, pujades de grans fitxers, etc.) Les defenses contra DUES normalment treballen mitjançant l'identificació i el bloqueig de tràfic "dolent" permetent no obstant això que travessin els missatges legítims. Aquestes defenses es troben típicament dins o abans del servidor (no són part de l'aplicació web mateixa).

- **Salt de Directoris/Revelació de Fitxers**. En aquest tipus d'atac un usuari maliciós intenta accedir a parts del sistema de fitxers del servidor web als quals no hauria de tenir accés. Aquesta vulnerabilitat ocorre quan l'usuari és capaç de passar noms de fitxer que inclouen caràcters del sistema de navegació (ex. ../../). La solució és desinfectar l'entrada abans d'usar-la.

* **Inclusió de Fitxers**. En aquest atac un usuari és capaç d'especificar, per mostrar o executar, un fitxer "no intencionat per a això" en les dades que li passa al servidor. Una vegada ha estat carregat aquest fitxer podria executar-se en el servidor web o en el costat client (portant a un atac XSS). La solució és desinfectar l'entrada abans d'usar-la.

- **Injecció de Comandos**. Els atacs d'injecció de comandos permeten a un usuari maliciós executar comandos del sistema arbitraris en el sistema operatiu del host. La solució és desinfectar l'entrada d'usuari abans que pugui ser usada en trucades al sistema.

## 2.5. Conformitat amb estàndards

- **Keep Your Code Simple** – Think quality over quantity when it comes to coding. Don’t dedicate ten lines of code to a feature that only needs three. Not only will simple code be more cross-browser friendly, it will also be more maintainable when the time comes that you do have to debug or adjust it for compatibility.

* **Use Frameworks** – CSS frameworks like Foundation and Bootstrap will give you style code to make cross-compatibility easier for you. If you take the time to become familiar with some of the features, building a responsive web application becomes much faster and easier. These will also help you make the application look and behave correctly in mobile browsers.

- **Define Valid Doctype** – The Doctype is the first line in your code which describes the HTML that will be used in your application. Because different browsers have different standards and rules, you need to define the Doctype or the rendering engine will basically guess it for you. Of course, this is what can lead to bugs and inconsistencies that you want to avoid.

* **CSS Reset** – Every browser has different default CSS rules that they follow. This is why you use CSS reset stylesheet to make sure your browsers follow the same basic rules and behave consistently. You want to add one of these as the first stylesheet in order to reset unless you use a framework which will already have one.

- **Validate** – It’s a good idea to validate your HTML and CSS to prevent problems. Use the W3C HTML Validator and CSS Validator to make sure your code is error free and fix it if it’s not.

* **Conditional Comments** – Conditional comments allow you to link style sheets for different browsers, which is especially helpful when it comes to design challenges that are common with Internet Explorer.
  Prepare For Differences – Again, it’s pretty much impossible to have a design that looks the same on every browser unless it’s extremely basic. Details like forms and typography will likely vary no matter what rules you follow. Your main concern should not be making the design look identical on every browser. Instead, you should make sure that it looks acceptable and is usable without having elements that are out of place or that prevent someone from accessing certain functions.

- **Don’t Skip Cross-Browser Testing** – It’s not just enough to keep these tips in mind while developing. As hard as you try to avoid it, it’s easy to accidentally write something that doesn’t work in one browser. This is why you need to check that the site actually works on different browsers before delivery. Using a tool like CrossBrowserTesting gives you access to do this in over 1,500 browsers, so you never have to wonder what users are seeing when they visit your page from a different machine.

## 2.6. El motor de JavaScript. Execució de JavaScript en línia d'ordres

El llenguatge de JavaScript existeix independentment de la web. És necessari recalcar-ho, ja que la manera habitual de treballar és integrant el llenguatge JavaScript dins les pàgines web (HTML).

Quan executem JavaScript dins una pàgina web, per exemple amb el navegador Mozilla Firefox, de l’execució del codi JavaScript se n’encarrega el motor de JavaScript. SpiderMonkey és el motor de JavaScript de Mozilla, que es pot instal·lar de forma independent sense estar associat a un navegador web. Trobareu més informació sobre Spidermonkey i com instal·lar-lo en els següents enllaços:

- http://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey

- http://developer.mozilla.org/En/SpiderMonkey/Build_Documentation

Si s’instal·la, de forma opcional, l’SpiderMonkey (tant per a sistemes Linux com Windows), es pot practicar el llenguatge JavaScript des de la línia d’ordres, en un entorn que res a veure té amb la web. Per tant, JavaScript és un llenguatge que existeix independentment de la web.

# 3. JavaScript en les pàgines web

En l’inici de l’era d’Internet les pàgines HTML eren estàtiques: només hi havia text fix i imatges. Avui dia, tot al contrari, les pàgines web són dinàmiques, amb efectes visuals i interacció amb l’usuari. Això ha estat possibles gràcies a la incorporació de JavaScript: el codi que s’executa dins el navegador web.

- Podem citar algun dels avantatges:

  - JavaScript permet una gran quantitat d’efectes dins les pàgines. Entre d’altres: popups, text que es col·lapsa, capes que es fonen, scrolls, transicions d’imatges…
  - JavaScript afegeix interactivitat amb l’usuari.
  - JavaScript proporciona integració amb d’altres plugins: no proporciona només accés als objectes HTML, també proporciona accés a objectes específics del navegador com ara els plugins Adobe Acrobat, Media Player…
  - JavaScript permet validació dels formularis en el cantó del client. Una validació inicial dels formularis és possible per eliminar simples errors, com assegurar-se de què el format de data, DNI, correu electrònic o telèfon són correctes… Com a resultat, l’usuari té una resposta més ràpida que no pas si el control dels errors el fes el servidor.
  - JavaScript permet accedir a informació del sistema.

- Desavantatges de JavaScript

  - La seguretat és el principal problema a JavaScript. Els fragments de codi JavaScript que s’afegeixen a les pàgines web es descarreguen en els navegadors i s’executen en el cantó del client, permetent així la possibilitat que un codi maliciós es pugui executar en la màquina client i així explotar alguna vulnerabilitat de seguretat coneguda en les aplicacions, navegadors o fins i tot del sistema operatiu. Existeixen estàndards de seguretat que restringeixen l’execució de codi per part dels navegadors. Es tracta sobretot de deshabilitar l’accés a l’escriptura o lectura de fitxers (exceptuant les galetes). Tanmateix, la seguretat a JavaScript continua sent un tema polèmic i de discussió.

  - Un altre desavantatge de JavaScript és que tendeix a introduir una quantitat enorme de fragments de codi en els nostres llocs web. Això es resol fàcilment emmagatzemant el codi JavaScript en fitxers externs amb extensió JS. Així la pàgina web queda molt més neta i llegible. La tendència actual és de fet separar totalment la part del contingut HTML, la part de funcionalitat JavaScript, i la part de disseny i maquetació. De manera que tres perfils d’usuaris diferents (el que genera continguts HTML, el programador web, i el dissenyador) puguin estar treballant en el mateix projecte, i tocant arxius diferents.

Un avantatge de deixar ben net el contingut HTML és que estem facilitant la feina als motors de cerca (com Google), de manera que poden desxifrar fàcilment el contingut de la pàgina web, i aquest contingut es pot indexar correctament en els resultats de les cerques.

## 3.1. Integració del codi JavaScript en el codi HTML. Primer exemple

JavaScript és un llenguatge d’script que existeix i té sentit fora de la web, però que ha pres protagonisme i reconeixement gràcies a la web. Així doncs, és usual associar JavaScript amb una de les tecnologies clau en el desenvolupament d’aplicacions web. Per a nosaltres JavaScript serà un puntal per tal que les nostres aplicacions web es comportin de forma dinàmica i interactiva. El primer que caldrà veure és com conviuen la sintaxi HTML i la sintaxi JavaScript, com es pot integrar JavaScript dins les pàgines web.

La inclusió de la sintaxi de JavaScript es fa mitjançant l’etiqueta `<script>`.

```html
<script>
  let nom = "Rita";
  alert("Hola " + nom);
</script>
```

Podem escriure moltes etiquetes `<script>` en un document, tot i que posar-ne una de sola és un bon hàbit. Aquestes etiquetes les podem posar tant en el `<head>` com en el `<body>`.

A l’hora d’escriure el nostre codi HTML procurarem que compleixi les regles de validació XHTML: etiquetes en minúscula, tota etiqueta que s’obre s’ha de tancar, etc.

```html
<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8" />
    <title>El meu primer exemple</title>
    <script>
      function Funcio() {
        document.getElementById("paragraf").innerHTML =
          "Escrivim en el paràgraf";
      }
    </script>
  </head>
  <body>
    <h1>El meu primer exemple</h1>
    <p id="paragraf">Text original del paràgraf</p>
    <button type="button" onclick="Funcio()">Clica'm</button>
  </body>
</html>
```

Per provar aquest codi, obriu el vostre editor de text preferit. Però ens referim a un editor de text pla, no utilitzeu Openoffice, Microsoft Office o similars. A Linux podeu utilitzar el Gedit, o fins i tot editors de consola: Vim, Nano, Joe. A Windows podeu utilitzar el Notepad. Tot i que els desenvolupadors web utilitzen editors més complets, en aquesta ocasió utilitzareu un editor senzill. Un cop obert l’editor, copieu el codi i reanomeneu-lo a un fitxer HTML, per exemple, boto.html. Tingueu clar en quina ubicació l’heu gravat. Aquest fitxer l’heu d’obrir des del vostre navegador web preferit (preferentment Mozilla Firefox o Google Chrome). Ho podeu fer clicant sobre el fitxer amb el botó dret, o a la barra de navegació del navegador ficar la ruta. Per exemple:

<em>file://ruta_al_fitxer/boto.html</em>

Us ha d’aparèixer una web senzilla. Quan cliqueu sobre el botó, el text del paràgraf ha de canviar. Ja heu fet la vostra primera aplicació JavaScript. Ja heu afegit interacció a una pàgina web. En aquest codi es donen per suposats molts conceptes. Primer de tot s’ha afegit un event a un botó. Un event és la capacitat de respondre a una acció de l’usuari, en aquest cas fer clic sobre un botó. Quan es fa clic, s’executa la funció Funcio() definida entre les etiquetes `<script>`. Aquesta funció el que fa és localitzar l’element definit per l’identificador `id=“paragraf”`, que és un paràgraf (`<p>`), i canvia el seu contingut. Aquest codi també funciona si col·loqueu l’etiqueta `<script>` en una altra banda:

És interessant col·locar l’etiqueta `<script>` a sota de tot del `<body>`. D’aquesta manera no bloquem la càrrega dels elements HTML. Tanmateix, s’ha de donar preferència a col·locar les etiquetes `<script>` a la capçalera `<head>` del document web.

```html
<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8" />
    <title>El meu primer exemple</title>
  </head>
  <body>
    <h1>El meu primer exemple</h1>
    <p id="paragraf">Text original del paràgraf</p>
    <button type="button" onclick="Funcio()">Clica'm</button>
    <script>
      function Funcio() {
        document.getElementById("paragraf").innerHTML =
          "Escrivim en el paràgraf";
      }
    </script>
  </body>
</html>
```

### 3.1.1. Fitxers JavaScript externs

Un fitxer JavaScript, amb extensió JS, és un fitxer de text que conté instruccions JavaScript. Des de l’HTML podem incloure fàcilment un fitxer JavaScript:

`<script src="fitxer_extern.js"></script>`

Així doncs, el contingut de fitxer_extern.js serà:

```javascript
function Funcio() {
  document.getElementById("paragraf").innerHTML = "Escrivim en el paràgraf";
}
```

i el nostre codi quedarà de la següent manera:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8" />
    <title>El meu primer exemple</title>
    <script src="fitxer_extern.js"></script>
  </head>
  <body>
    <h1>El meu primer exemple</h1>
    <p id="paragraf">Text original del paràgraf</p>
    <button type="button" onclick="Funcio()">Clica'm</button>
  </body>
</html>
```

S’entén que el codi HTML ha de localitzar el fitxer JS. En aquest cas els dos fitxers estan en el mateix directori. És habitual que els fitxers JavaScript estiguin en una carpeta js/ que penja del directori principal de l’aplicació. En aquest cas quedaria:

`<script src="js/fitxer_extern.js"></script>`

Quan es fan aplicacions web s’ha de tendir a la separació del contingut, el disseny i la funcionalitat. Això s’aconsegueix fent que el codi HTML sigui el més net possible. Tota la part de JavaScript ha d’anar a fitxers externs, de la mateixa manera que tot el disseny i estil van a fitxers externs CSS. Fixeu-vos en la sentència:

`<button type="button" onclick="Funcio()">Clica'm</button>`

És la definició d’un botó HTML que defineix el comportament d’un event amb una funció JavaScript. Aquí també estem barrejant HTML amb JavaScript i també caldrà evitar-ho.

És molt recomanable ser ordenats a l’hora de posar-li un nom als fitxers, versionant els fitxers. Fixeu-vos que en aquest primer exemple: hem provat el codi de tres maneres diferents, i podeu identificar amb un nom diferent cadascuna de les proves.

## 3.2. JavaScript: programació dirigida per esdeveniments

La programació dirigida per esdeveniments (event-driven programming) és un paradigma de programació en què el flux del programa està determinat per esdeveniments (_events_) com ara accions de l’usuari (típicament moviments del ratolí i ús del teclat). Aquest és precisament el model que es troba en la programació web i en el seu resultat: la navegació per pàgines web. En una pàgina web tenim un contingut estàtic, informatiu, però aquest contingut canvia a mesura que interactuem amb la pàgina web. Quan naveguem per la web, contínuament estem llençant events al motor de JavaScript, que s’encarrega de processar-los. Cliquem sobre un enllaç, fem scroll en la pàgina, passem el ratolí per damunt d’un menú desplegable… tota la interacció que fem amb la pàgina web és recollida pel processador d’events que executa a temps real trossos de codi JavaScript que modifiquen el contingut de la pàgina. Per tant, les pàgines web esdevenen interactives, i el **contingut és interactiu**. Són els conceptes d’hipermèdia i hipertext, en què el consum d’informació no és lineal, sinó que és l’usuari el qui decideix com interactua amb l’aplicació.

En el següent exemple estem associant al botó l’event onclick, de manera que quan cliquem sobre el botó s’executa una sentència JavaScript:

```html
<button onclick="this.innerHTML=Date()">L'hora és ...</button>
```

**`this`** fa referència al propi botó, i té la propietat `innerHTML` que representa l’etiqueta que mostra el botó. El contingut d’aquesta etiqueta canvia pel valor que retorna la funció **Date()**, que és l’hora del sistema.

<iframe height="265" style="width: 100%;" scrolling="no" title="Javascript-Date-Example" src="http://codepen.io/rglepe/embed/bJNogg/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/bJNogg/'>Javascript-Date-Example</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

En aquest exemple fem servir l’event onmouseover associat a la capa (`div`) que conté dos paràgrafs:

<iframe height="265" style="width: 100%;" scrolling="no" title="Javascript-innerhtml" src="http://codepen.io/rglepe/embed/oOgGoK/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/oOgGoK/'>Javascript-innerhtml</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Quan passem el ratolí per sobre la capa, canvia el contingut dels dos paràgrafs.

Si us hi fixeu bé, en els dos exemples mostrats estem barrejant el llenguatge HTML amb sentències JavaScript. Tot i que és usual, la tendència serà separar totalment la part d’HTML de la part de JavaScript.

## 3.3. Eines i entorns per al desenvolupament web

Per programar amb JavaScript es necessita un editor de text. Molts llenguatges de programació es troben suportats amb IDE (Integrated Developement Environment) per tal d’escriure codi més ràpid, accedir a la documentació i evitar errors. En el cas de JavaScript creiem que l’aproximació és diferent. No importa tant l’editor de text que es fa servir, però sí que és necessari un entorn on el programador pugui provar de forma ràpida i còmoda el codi, i pugui depurar els errors. Sortosament, els **navegadors web** (Mozilla Firefox, Google Chrome) ja porten incorporats de forma predeterminada entorns de desenvolupament que ajuden a la programació i depuradors.

Així doncs, per desenvolupar aplicacions amb JavaScript fareu servir un editor de text a escollir, i les eines de desenvolupament integrades en el navegador. En els dos casos haureu d’esmerçar temps a trobar les dreceres de teclat, opcions i possibilitats per treure’n el màxim profit i rendiment, amb la idea de desenvolupar ràpid, i també corregir i depurar els errors amb rapidesa. Així mateix, és recomanable en la mesura del possible treballar amb dues pantalles: una per veure el codi (codi HTML, JavaScript, CSS, eines de depuració…) i una altra per veure el resultat.

Quant als editors, de text tenim diferents opcions. D’un editor de text adaptat al desenvolupament esperem que tingui les següents característiques:

- Elecció de llenguatge de programació. En el vostre cas, JavaScript.
- Coloració sintàctica.
- Autocompleció.
- Eines avançades de cerca i reemplaçament.
- Marcadors (bookmarks). Navegació pels marcadors.
- Autotabulació.
- Agrupament (i desagrupament) de codi.
- Noves funcionalitats amb instal·lació d’extensions (plugins).

Entre els editors que podeu fer servir destaquem:

- Multiplataforma

  - Visual Studio Code
  - Sublime (multiplataforma)
  - Atom
  - Brackets
  - Aptana Studio3

- Linux

  - Notepadqq

- Windows
  - Notepad++

Us podeu registrar en la plataforma **codepen.io**, encara que sense fer-ho també podeu editar directament els exemples, però sense desar-los.

Una altra possibilitat és utilitzar un IDE, com ara _NetBeans_ o _Eclipse_. En el cas de desenvolupar per JavaScript, això només està justificat si coneixeu aquestes eines amb profunditat i fluïdesa perquè les utilitza amb d’altres llenguatges de programació.

De la mateixa manera necessitem entorns per fer proves del nostre codi. El codi JavaScript s’emmarca dins una pàgina web, tanmateix, en comptes de fer una pàgina web cada vegada que vulguem provar codi, hi ha entorns en línia que ens ajudaran a provar el codi de forma ràpida, com ara codepen.io.

Cal tenir present, també, que el codi HTML5 generat ha de complir els estàndards XHTML. El més pràctic és acostumar-se a codificar bé segons les normes. A més, hi ha eines externes de validació XHTML que es poden integrar dins de l’editor que hàgiu escollit.

Exemple d'ús: Visual Studio Code + Chrome Developer Tools

És habitual treballar de forma conjunta amb l’editor de text preferit, i eines de desenvolupament integrades en el navegador web. Els bons editors tenen la possibilitat d’instal·lar plugins que milloren la funcionalitat i productivitat. En el cas de l’editor Visual Studio Code, tenim la possibilitat d’instal·lar un plugin _DevTools for Chrome_ que integra dins de l’editor les eines de desenvolupament del Chrome. D’aquesta manera aconseguim tenir integrades les dues eines en una de sola, i d’aquesta manera podem fer dins del Visual Studio Code:

- Afegir i treure punts de ruptura per poder fer debug pas a pas.
- Veure els missatges de la consola.
- Accedir a les propietats d’un objecte.
- Dins un punt de ruptura, podem veure el valor que prenen les variables.
- Avaluar expressions.
- Ús del LiveReload per refrescar el nostre navegador.

Pàgina oficial d’aqueta extensió: [DevTools for Chrome](https://marketplace.visualstudio.com/items?itemName=codemooseus.vscode-devtools-for-chrome)

## 3.4. Sintaxi bàsica del llenguatge JavaScript

JavaScript està basat en el estàndard ECMA-262, (L’edició actual de l’estàndard ECMA-262 a juny de 2018 és la 9ª) que defineix el llenguatge de propòsit general **ECMAScript**. Ecma International és una associació de la indústria fundada l’any 1961, i dedicada a la estandarització dels sistemes de la informació. Podeu consultar la pàgina web oficial a www.ecma-international.org, i des d’aquí descarregar-vos tot el seu document en format PDF o HTML.
En aquest curs utilitzarem les versions ES6 i superiors, encara que farem referència a versions anteriors.

### 3.4.1. Sentències, comentaris, variables

JavaScript és un llenguatge de programació, és a dir, amb el seu codi d’instruccions podem fer programes informàtics. Aquests programes estaran orientats a fer pàgines web funcionals, atractives i interactives. Un programa es composa d’una llista d’instruccions que seran executades, en aquest cas interpretades, per l’ordinador. Aquestes instruccions són les sentències. Tot i que no és obligatori, ens acostumarem a separar les sentències per punts i coma.

Una cosa important, i que l’usuari aprendrà de seguida, és que JavaScript distingeix entre majúscules i minúscules.

Així doncs, farem el nostre primer programa i l’integrem dins el codi HTML d’una pàgina web:

<div style="background-color:#eee; border: 1px solid"><strong>Normes sobre l'anomenat de les variables</strong>
<p>
Les variables han de ser identificadors únics, i han de complir les següents normes:
<ul>
<li>Només poden contenir lletres, dígits, signe de subratllat (_) i el signe de dòlar ($).</li>
<li>Han de començar amb una lletra, o bé amb el signe de subratllat (_) o el signe de dòlar (%%$%)</li>
<li>Recordar que es distingeix entre majúscules i minúscules (la variable x és diferent de la variable X)</li>
<li>No es poden utilitzar les paraules reservades de JavaScript (while, for, next…)</li>
</ul>
</p>
</div>
<hr>

```html
<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8" />
    <title>El meu primer programa</title>
    <script>
      //declarem una variable
      let x = 3;
      /* Els comentaris també
            poden ser multilínia.
            Declarem una altra variable */
      let y = 5;
      let z = x * y;
    </script>
  </head>
  <body>
    <h1>El meu primer programa</h1>
  </body>
</html>
```

Una **variable** és un contenidor de valors, el contingut de la qual pot variar. Fins a ES5 les variables es declaraven amb la paraula **var**, des de ES6 s'utilitzen **let** i **const**.

En aquest programa hem declarat les **variables** x, y, z. Declarem les variables amb la paraula reservada **let**. Encara que no és obligatori declarar les variables, sí que és convenient fer-ho. A les dues primeres els hem donat un valor, i la tercera l’hem declarat com a producte de les dues primeres.

A més, hem **comentat** el codi, la qual cosa sempre està bé, mai és sobrer. Aquest programa ja fa alguna cosa, però l’usuari espera veure el resultat del producte. De fet, en JavaScript sempre tenim diferent alternatives. Per veure el resultat, podem fer-ho de quatre maneres diferents:

- Escrivint una caixa de text amb window.alert().
- Utilitzant un element HTML com ara un paràgraf.
- Escrivint directament en el document amb document.write().
- Escrivint a la consola del navegador amb console.log().

I sense proposar-nos-ho, aquí introduïm el concepte d’objecte: **window**, **document** i **console** són objectes que tenen els mètodes _alert()_, _write()_ i _log()_. I és que JavaScript també és un llenguatge orientat a objectes, i contínuament haurem de parlar de mètodes i propietats dels objectes.

Aleshores el nostre codi pot quedar de la següent manera:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8" />
    <title>El meu primer programa</title>
  </head>
  <body>
    <h1 id="capcalera">El meu primer programa</h1>
    <script>
      //declarem una variable
      let x = 3;
      /* Els comentaris també
            poden ser multilínia.
            Declarem una altra variable */
      let y = 5;
      let z = x * y;
      document.getElementById("capcalera").innerHTML = z;
      console.log(z);
      window.alert(z);
      document.write(z);
    </script>
  </body>
</html>
```

Com que estem en les primeres proves, us recomanem crear un fitxer HTML, per exemple primer_programa.html, amb l’anterior codi, i executar-lo. Per tal de veure la consola del navegador, en el navegador s’haurà d’anar a les eines de desenvolupament i veure quina és la combinació de tecles adient. Dependrà de si es fa servir Google Chrome o Mozilla Firefox, i fins i tot dependrà de la versió d’aquests programes.

Fixem-nos que l’script està en la part de sota del body. Si el pugem a dalt de tot del body o en el head a la consola obtindrem un missatge d’error:

TypeError: document.getElementById(...) is null
El programa no sap què és id=“capcalera” fins que no s’ha carregat la línia HTML `<h1 id=“capcalera”>`. Sempre s’haurà de tenir ben present que el navegador web carrega la pàgina HTML línia a línia des del principi, i que no podem fer referència a un objecte o element HTML que encara no hem carregat en memòria. Una manera de resoldre aquest conflicte és utilitzar el següent codi, que fa ús de l’event `onload()`:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8" />
    <title>El meu primer programa</title>
  </head>
  <script>
    function carregar() {
      //declarem una variable
      let x = 3;
      /* Els comentaris també
        	poden ser multilínia.
        	Declarem una altra variable */
      let y = 5;
      let z = x * y;
      document.getElementById("capcalera").innerHTML = z;
      console.log(z);
      window.alert(z);
      document.write(z);
    }
  </script>
  <body onload="carregar()">
    <h1 id="capcalera">El meu primer programa</h1>
  </body>
</html>
```

Només quan s’ha carregat tota la pàgina HTML s’executa la funció JavaScript carregar(), que ara sí que ja podem definir en el head, la qual cosa fa que el codi sigui més ordenat.

En aquest segon cas haureu vist que la sortida per pantalla és diferent (només hi ha un valor del 15), i que la consola està buida. Això és degut a què utilitzar document.write() un cop s’ha carregat totalment el document HTML fa que s’esborri la sortida HTML (document.write s’acostuma a utilitzar només per fer proves).

En aquest exemple hem utilitzat el mètode getElementById() de l’objecte document. Aquest mètode, molt útil, ens permet fer una cerca de l’element HTML que té per id=“capcalera”.

Fixem-nos que, pretenent fer una petita introducció a les sentències i variables, hem hagut d’introduir diversos conceptes com ara objectes, mètodes, fins i tot l’event `onload()`.

Us podeu registrar a codepen.io i practicar en aquesta plataforma, tot i que també podreu fer proves amb els exemples tot editant-los i provant-los directament en el navegador.

### 3.4.2. Àmbit i visibilitat de les variables

Quan es declara una variable fora d'una funció s'anomena **variable global**. És a dir, es troba disponible per a qualsevol altre codi del document. Si la variable es declara dins d'una funció, s'anomena **variable local** i només estarà disponible dins de la funció on es va crear.

Abans de ECMAScript 6 una variable declarada dins d'un bloc és local per la funció (o àmbit global) en la que resideix el bloc. Per exemple, el següent codi enregistrarà 5 perquè l'àmbit de x és la funció (o context global) dins de la qual es declara x, no el bloc, que en aquest cas és la **sentencia if**.

```javascript
if (true) {
  var x = 5;
}
console.log(x); // x vale 5
```

Aquest comportament canvia, quan utilitzem la declaració let de ECMAScript 2015.

```javascript
if (true) {
  let y = 5;
}
console.log(y);  // ReferenceError: y no está definida
```

### 3.4.3. Tipus de dades

A JavaScript les variables poden emmagatzemar molts tipus de dades. Evidentment, també números i cadenes de text:

```javascript
let i = 365;
let cad = "JavaScript";
let cad2 = "CIFO";
```

Veiem que els números són sense cometes, i les cadenes de text estan entre cometes simples o dobles. Si posem un número entre cometes, es tractarà com una cadena de text.

```javascript
let i = "365";
let cad = "L'any té " + i + " dies";
```

En l’anterior exemple podeu veure per què és útil que les cadenes es puguin emmarcar entre cometes dobles o simples, tot i que també es pot utilitzar el caràcter d’escapament (contrabarra, ‘\’):

```javascript
let i = "365";
let cad = "L'any té " + i + " dies";
```

Després de declarar una variable aquesta no té valor (o diem que té valor undefined).

```javascript
let color;
console.log(color);
```

Per donar valor a una variable, utilitzem l’operador d’assignació ('=’):

```javascript
color = "blau";
```

Podem declarar moltes variable en una sola sentència:

```javascript
let color1 = "vermell",
  color2 = "taronja",
  color3 = "groc";
```

```html
<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8" />
    <title>Tipus de dades</title>
  </head>
  <script>
    console.clear();

    let i = 365;
    let cad = "JavaScript";
    let cad2 = "CIFO";
    console.log(cad);
    console.log(cad2);

    let i = "365";
    let cad = "L'any té " + i + " dies";
    console.log(cad);

    let i = "365";
    let cad = "L'any té " + i + " dies";
    console.log(cad);

    let color;
    console.log(color);

    let color1 = "vermell",
      color2 = "taronja",
      color3 = "groc";
    console.log(color1);
    console.log(color2);
    console.log(color3);
  </script>
  <body>
    <h1>Tipus de dades</h1>
  </body>
</html>
```

Quan proveu aquest exemple, podeu utilitzar tant la consola integrada en el codepen, com la consola del vostre navegador web.

A part dels números i cadenes (tipus primitius) hi ha molts altres tipus de dades: **Number**, **Strings**, **Arrays**, **Date**, **Boolean**, **Objects**.

```javascript
let animal = "Àliga"; //String
let num_potes = 2; //Number
let especies = ["A. reial", "A. imperial", "A. estepària"]; // Array
let obj = { nomComu: "Àliga reial", nomCientific: "Aquila chrysaetos" }; // Object
let te_bec = true; //Boolean
```

Per operar amb diferents variables, JavaScript ha de conèixer el tipus de dades de les variables, i aleshores pot aplicar les seves regles internes. Per exemple, en JavaScript té sentit fer:

```javascript
console.log(animal + num_potes);
```

Perquè internament num_potes es converteix a cadena, que es concatena amb la variable animal.

Les expressions s’avaluen d’esquerra a dreta. Aquestes dues sentències donen resultats diferents:

```javascript
console.log(num_potes + num_potes + animal);
console.log(animal + num_potes + num_potes);
```

Al contrari que d’altres llenguatges de programació, en JavaScript els tipus de dades són dinàmics, que vol dir que la mateixa variable pot canviar de tipus de dades sense problema:

```javascript
let z = 34;
z = "ara sóc una cadena";
z = true;
z = undefined;
```

<strong style="text-decoration:underline"> Undefined, null</strong>

A JavaScript una variable sense valor té el valor undefined, i la funció `typeof`, que retorna el tipus, també és undefined. Una variable es pot esborrar fent-la undefined. Però no ho hem de confondre amb el valor buit (cadena buida, ””), que és una cadena de text de longitud 0:

```javascript
z = undefined;
console.log(typeof z);
z = "";
console.log(typeof z);
```

La paraula reservada null té un tractament especial, que es presta a confusió. Amb null podem alliberar un objecte, la qual cosa també podem fer amb undefined. però el tipus de dades de null és Object:

```javascript
let animal = undefined;
console.log(typeof animal);
let vegetal = null;
console.log(typeof vegetal);
```

Però null no és ben bé el mateix que undefined, doncs el primer és object i l’altre no. Si fem una comparació dels dos valors el resultat és cert, però si comparem els tipus el resultat és fals. Ho podem veure amb el següent exemple:

console.log (null == undefined); //true
console.log (null === undefined); //false. Compara no només el valors, sinó també el tipus

<strong style="text-decoration:underline">Objectes</strong>

Els objectes els hem de definir entre claus. Dels objectes en podem definir les propietats i els mètodes. Les propietats les escrivim amb parells nom:valor, separat per comes. Per exemple:

```javascript
let animal = { id: 345, nom: "Gos", classe: "Mamífers", familia: "Cànids" };
```

Hem definit quatre propietats de l’objecte animal, i podem accedir fàcilment als seus valors:

```javascript
console.log(animal.id);
```

L’objecte animal té quatre propietats: id, nom, classe, família. I com que és un objecte, també podem definir-ne mètodes. L’exemple més senzill seria:

```javascript
let animal = {
  id: 345,
  nom: "Gos",
  classe: "Mamífers",
  familia: "Cànids",
  get_taxo: function() {
    return this.classe + " - " + this.familia;
  }
};

console.log(animal.get_taxo());
```

<strong style="text-decoration:underline">Strings i Numbers</strong>

Ja hem utilitzat strings, que podem posar entre cometes simples o dobles.

```javascript
let animal = "àliga";
console.log(animal);
```

Amb els strings podem:

```javascript
console.log(animal.length);
console.log(animal.toUpperCase());
```

És a dir, l’string té propietats i mètodes. Per tant, és un objecte, i el podem tractar com a tal. Depenent de com el declarem, el seu tipus serà string o object:

```javascript
let animal = "àliga";
console.log(animal);
console.log(typeof animal);

let vegetal = new String("bleda");
console.log(vegetal);
console.log(typeof vegetal);
```

Aquesta segona forma, però, és més ineficient i, per tant, no la fem servir.

El mateix podem dir per als Numbers, que també són objectes. Per exemple, amb el mètode toFixed(x) podem fixar el número de posicions decimals.

```javascript
let x = 234.6789;
console.log(x.toFixed(2));
```

### 3.4.4. Assignacions

Els operadors d’assignació assignen valor a les variables. A part de l’operador igual ('='), podem utilitzar els següents operadors:

**a += b** equival a a = a + b
**a -= b** equival a a = a - b
**a \*= b** equival a a = a \* b
**a /= b** equival a a = a / b
**a %= b** equival a a = a % b

Posarem un exemple de cada:

```javascript
let a = 100;
a += 10; // 110
a -= 15; // 95
a *= 10; // 950
a /= 2; // 475
a %= 2; //1 (el mòdul és 1, doncs 475 és senar)
```

### 3.4.5. Operadors

Els operadors serveixen per fer operacions entre dues o més variables. El primer operador que s’esmenta és el d’assignació. Després vénen els operadors aritmètics, que serveixen per fer operacions aritmètiques:

- Suma (+)
- Resta (-)
- Multiplicació (\*)
- Divisió (/)
- Mòdul (%)
- Increment (++)
- Decrement (--)

```javascript
let a = 100;
a = (((a + 10 - 15) * 10) / 2) % 1;
```

Com a operador de cadena tenim la concatenació. Es representa amb el símbol + en el sentit que estem sumant cadenes.

```javascript
let cad1 = "Javascript";
let cad2 = " al CIFO";
let cad = cad1 + cad2; // Javascript al CIFO
```

Com que a JavaScript els tipus són dinàmics, si sumem números i cadenes, el més lògic és que el número passi a ser una cadena, per tal de poder fer una concatenació (al revés no té cap sentit):

```javascript
console.log(a + cad);
console.log(cad + a);
```

<strong style="text-decoration:underline">Operadors lògics i de comparació</strong>
Els operadors lògics i de comparació disponibles són:

- igual en valor que (\==)
- igual en valor i en tipus que (=\==)
- no igual en valor que (!=)
- no igual en valor o en tipus que (!==)
- més gran que (>)
- més petit que (<)
- més gran o igual que (>=)
- més petit o igual que (< =)
- conjunció lògica (&&)
- disjunció lògica (||)
- negació lògica (!)
- operador ternari (?)
  <em>L’operador ternari (?) mereix un tractament especial. La seva funció és clara amb els condicionals.</em>

```javascript
let a = 10;
let b = 10;
let c = 20;
let d = "10";

console.log(a == c); // false
console.log(a === b); // true
console.log(a == d); // true
console.log(a === d); // false
console.log(a != c); // true
console.log(a !== d); // true
console.log(a > c); // false
console.log(a < c); // true
console.log(a >= b); // true
console.log(a <= b); // true
```

La comparació entre cadenes es fa alfabèticament:

```javascript
let cad1 = "avió";
let cad2 = "vaixell";
console.log(cad1 > cad2); // false
```

Si fem una comparació entre diferents tipus, com entre cadena i número, podem obtenir resultats inesperats. JavaScript converteix la cadena a número. Si la cadena és no-numèrica es converteix a **NaN** (Not a Number), que sempre serà fals. Si la cadena és buida, es converteix a 0.

<strong style="text-decoration:underline">Els operadors de bit</strong>

Els operadors de bit (bitwise operators) no els veurem ja que difícilment es faran servir en el marc de la programació web. Si voleu aprofundir-hi, trobareu més informació a Bitwise_Operators

```javascript
let a = 10;
let cad1 = "10";
let cad2 = "15";
let str = "cotxe";

console.log(a < cad2); // true. El '15' es converteix a 15
console.log(a == str); // false. La cadena 'cotxe' no es pot convertir a número
console.log(cad1 < cad2); // true. Els dos són cadenes. S'ha de fer una comparació alfabètica. Com que el primer caràcter és el mateix, s'ha de mirar el segon caràcter.
```

### 3.4.6. Decisions

Quan es programa, sovint hem de prendre decisions i bifurcar el codi. Les instruccions condicionals ens ajudaran a fer-ho. Les més habituals són el **if**, **else** i **else if** d’una banda, i la clàusula **switch** d’altra banda.

<strong style="text-decoration:underline">If, else, else if</strong>

Utilitzarem if per especificar un bloc de codi que s’executarà quan es compleixi una determinada condició:

Cal utilitzar la identificació dels blocs per tal que el codi sigui més llegible.

```javascript
let a = 99,
  b = 98;
if (a % 3 == 0) console.log(a + " és divisible per 3");

if (b % 2 == 0) {
  console.log(b + " és divisible per 2");
  console.log(b + " és parell");
}
```

Utilitzarem else per especificar el bloc de codi que s’executarà quan la condició és falsa:

```javascript
if (b % 2 == 0) {
  console.log(b + " és divisible per 2");
  console.log(b + " és parell");
} else {
  console.log(b + " és senar");
}
```

Utilitzarem else if per especificar noves condicions a avaluar després que s’hagin avaluat les prèvies:

```javascript
if (b % 4 == 0) {
  console.log(b + " és divisible per 4");
  console.log(b + " és parell");
} else if (b % 3) {
  console.log(b + " és divisible per 3");
} else if (b % 2) {
  console.log(b + " és divisible per 2");
  console.log(b + " és parell");
} else {
  console.log("un altre cas");
}
```

Evidentment, l’avaluació de la condició pot ser més complicada:

```javascript
let year = 2016;
if ((year % 4 == 0) && ((year % 100 != 0) || (year % 400 == 0)) {
  console.log ("L'any " +  year + " és un any de traspàs.\nPerò això no vol dir que tots els anys de traspàs siguin divisibles per 4.\nL'any 2000 no va ser un any de traspàs!");
  document.write ("L'any " +  year + " és un any de traspàs.<br />Però això no vol dir que tots els anys de traspàs siguin divisibles per 4.<br />L'any 2000 no va ser un any de traspàs!");
} else {
  console.log ("L'any " +  year + " NO és un any de traspàs.");
  document.write ("L'any " +  year + " NO és un any de traspàs.");
}
```

En el context de la consola, per fer una línia nova fem servir el metacaràcter \n. Però en el context de la pàgina web hem de fer servir <br />.

Per tal d’ampliar l’exemple anterior, mirarem si l’any actual és de traspàs, i després mirarem si un any aleatori entre 0 i 2500 també és de traspàs. Hem d’utilitzar els objectes Date i Math, que tots dos tenen la seva col·lecció de propietats i mètodes.

```javascript
let d = new Date();
year = d.getFullYear();
if (year % 4 == 0 && (year % 100 != 0 || year % 400 == 0)) {
  console.log(
    "L'any " +
      year +
      " és un any de traspàs.\nPerò això no vol dir que tots els anys de traspàs siguin divisibles per 4.\nL'any 2000 no va ser un any de traspàs!"
  );
  document.write(
    "L'any " +
      year +
      " és un any de traspàs.<br />Però això no vol dir que tots els anys de traspàs siguin divisibles per 4.<br />L'any 2000 no va ser un any de traspàs!"
  );
} else {
  console.log("L'any " + year + " NO és un any de traspàs.");
  document.write("L'any " + year + " NO és un any de traspàs.");
}

let num = 2500 * Math.random();
year = parseInt(num);
if (year % 4 == 0 && (year % 100 != 0 || year % 400 == 0)) {
  console.log(
    "L'any " +
      year +
      " és un any de traspàs.\nPerò això no vol dir que tots els anys de traspàs siguin divisibles per 4.\nL'any 2000 no va ser un any de traspàs!"
  );
  document.write(
    "L'any " +
      year +
      " és un any de traspàs.<br />Però això no vol dir que tots els anys de traspàs siguin divisibles per 4.<br />L'any 2000 no va ser un any de traspàs!"
  );
} else {
  console.log("L'any " + year + " NO és un any de traspàs.");
  document.write("L'any " + year + " NO és un any de traspàs.");
}
```

I ara és el moment de fer programació estructurada i definir una funció per tal de reutilitzar el codi. A l’hora d’aprendre JavaScript, caldrà aplicar tots els conceptes de programació coneguts:

```javascript
let year = 2016;
mostrar_info(year);

let d = new Date();
year = d.getFullYear();
mostrar_info(year);

let num = 2500 * Math.random();
year = parseInt(num);
mostrar_info(year);

function mostrar_info(year) {
  if (year % 4 == 0 && (year % 100 != 0 || year % 400 == 0)) {
    console.log(
      "L'any " +
        year +
        " és un any de traspàs.\nPerò això no vol dir que tots els anys de traspàs siguin divisibles per 4.\nL'any 2000 no va ser un any de traspàs!"
    );
    document.write(
      "L'any " +
        year +
        " és un any de traspàs.<br />Però això no vol dir que tots els anys de traspàs siguin divisibles per 4.<br />L'any 2000 no va ser un any de traspàs!<br />"
    );
  } else {
    console.log("L'any " + year + " NO és un any de traspàs.");
    document.write("L'any " + year + " NO és un any de traspàs.");
  }
}
```

<strong style = "text-decoration:underline" > Switch</strong>

S’utilitza switch quan tenim una sola expressió que s’ha de comparar moltes vegades, i només una d’elles serà la correcta. En aquest exemple mostrem l’estació de l’any (primavera, estiu, tardor, hivern), en funció del mes, sense tenir en compte que els canvis d’estació es fan el dia 21 de març, 21 de juny, 21 de setembre i 21 de desembre:

```javascript
let mes;

switch (new Date().getMonth()) {
  case 0:
    mes = "Gener";
    estacio = "Hivern";
    break;
  case 1:
    mes = "Febrer";
    estacio = "Hivern";
    break;
  case 2:
    mes = "Març";
    estacio = "Hivern a primavera";
    break;
  case 3:
    mes = "Abril";
    estacio = "Primavera";
    break;
  case 4:
    mes = "Maig";
    estacio = "Primavera";
    break;
  case 5:
    mes = "Juny";
    estacio = "Primavera a estiu";
    break;
  case 6:
    mes = "Juliol";
    estacio = "Estiu";
    break;
  case 7:
    mes = "Agost";
    estacio = "Estiu";
    break;
  case 8:
    mes = "Setembre";
    estacio = "Estiu a tardor";
    break;
  case 9:
    mes = "Octubre";
    estacio = "Tardor";
    break;
  case 10:
    mes = "Novembre";
    estacio = "Tardor";
    break;
  case 11:
    mes = "Desembre";
    estacio = "Tardor a hivern";
    break;
  default:
    console.log(
      "El codi mai passarà per aquí, però en altres casos podem utiltizar la clàusula default"
    );
}

console.log("Mes: " + mes);
console.log("Estació: " + estacio);
```

### 3.4.7. Bucles

Els bucles són necessaris quan volem executar un codi un número determinat o indeterminat de vegades, potser fins que s’acompleixi una condició de sortida. Tenim diferents tipus de bucles:

- for: bucles que repeteixen el bloc de codi un número fix de vegades.
- for/in: bucles que recorren les propietats d’un objecte.
- while: bucles que repeteixen el bloc de codi mentre la condició de sortida sigui certa.
- do/while el mateix que l’anterior, però la condició de sortida s’avalua al final.

<strong style="text-decoration:underline">Bucles for, for/in</strong>

La sintaxi bàsica del bucle for és:

```javascript
for ( expressió1; expressió2; expressió3) {
  bloc de codi a executar;
}
```

L’expressió1 s’avalua a l’inici; l’expressió2 és la condició de sortida del bucle; l’expressió3 s’executa a cada volta del bucle. Un exemple típic:

```javascript
// taula de multiplicar del 6
let cad = "";

for (i = 1; i <= 10; i++) {
  cad += "6 * " + i + " = " + 6 * i + "\n";
}

console.log(cad);
```

I amb dos **bucles for niats** podem fer totes les taules de multiplicar de l’1 al 10:

```javascript
// Taules de multiplicar de l'1 al 10
let cad;

for (j = 1; j <= 10; j++) {
  cad = "";
  for (i = 1; i <= 10; i++) {
    cad += j + " * " + i + " = " + j * i + "\n";
  }
  console.log(cad);
}
```

Les tres expressions dins el for són de fet opcionals. L’única cosa que hem de tenir en compte és de no provocar un bucle sense fi, la qual cosa penjaria el navegador web des del qual estem provant. Per tant, sempre hi haurà d’haver una condició de sortida, i podrem sortir del bucle amb la clàusula break:

```javascript
let i = 0;
for (;;) {
console.log (i);
i++;
if (i>15) break;
}
```

<strong style="text-decoration:underline">Bucles while, do/while</strong>

El cas més senzill és el bucle while. Mentre es compleixi la condició s’executarà el bloc de codi:

```javascript
while (condició) {
bloc de codi
}
```

Un exemple que utilitza la funció `charAt()` dels string. Mostrem la part de la cadena str fins que no trobem el caràcter i:

```javascript
let str = "That is Javascript";
let cad = "";
let i = 0;
let res = "";

while (res != 'i') {
res = str.charAt(i);
cad += res;
i++;
}

console.log (cad);
```

Una variant és el bucle do/while. El bloc s’executa com a mínim una vegada. La condició de sortida s’avalua al final, i es va executant el codi fins que no es compleixi la condició de sortida.

```javascript
do {
bloc de codi
}
while (condició);
```

Per exemple,

```javascript
str = "That is Javascript";
cad = "";
i = 0;
res = "";

do {
res = str.charAt(i);
cad += res;
i++;
} while (res != 'i')

console.log (cad);
```

En aquest cas, tant se val avaluar la condició al principi o al final, el resultat és el mateix.

Podem sortir del bucle en qualsevol moment fent un `break``:


```javascript
str = "That is Javascript";
cad = "";
i = 0;
res = "";

while (res != 'i') {
res = str.charAt(i);
if (res == 'a') break;
cad += res;
i++;
}

console.log (cad);
```

### 3.4.8. Exercici:
Bucle i matrius
L’objectiu d’aquesta activitat és treballar aspectes bàsics de la sintaxi JavaScript, com ara els bucles i les matrius.

En aquesta activitat heu de codificar un script on es defineix en una matriu una llista d’animals, i en una altra matriu la llista de la classe a què pertanyen els animals de la primera matriu: mamífers, ocells, amfibis, rèptils, peixos. Les dues matrius tenen el mateix nombre d’elements. Seguidament definireu un bucle, i en cada passada del bucle es pregunta a l’usuari a quina classe pertany l’animal, escollit de forma aleatòria. Hi haurà un comptador de preguntes, i un comptador de preguntes correctes, per tal de donar un resultat del test. També ha d’haver-hi una condició de sortida del bucle.



## 3.5. Arrays

[Arrays](https://en.wikipedia.org/wiki/Array_data_type) són estructures de dades que ens permeten agrupar col·leccions d'elements en una única variable. Després es poden accedir cadascun dels elements de forma individual mitjançant la seva posició en aquesta estructura, o es poden  passar agrupats com array.

Per exemple, si volem mantenir tots els noms d'un llistat de persones, crearem un *array* enlloc de crear una variable per cadascun dels noms. 
For example, if you have a class of several people and want to keep all their names saved in variables, instead of having one for each you can create one array. Let's take a look at how that works.

### 3.5.1. Operacions

<strong style="text-decoration:underline">Declaració</strong>

Un array es pot declarar buit can be declared empty:

```javascript
let arrayNames = [];
```
O es pot declarar amb els elements:

```javascript
let arrayNames = ["Pedro", "Jake", "Joan", "Mike"];
```
Els elements no cal que siguin del matexi tipus, podem barrejar strings, numbers i qualsevol tipus que vulguem.

```javascript
let arrayNames = ["Pedro", 2, true];
```

### 3.5.2. Accedir als elements

Es pot accedir als elements individuals  mitjançant la seva posició dins de l'array
Per exemple:

| **Index** | 0 | 1 | 2 | 3
|---|---|---|----|---
| **Value** | "Pedro" | "Jake" | "Joan" | "Mike"
 
:::info
:warning: **Zero-Indexed:** Notar com el primer element no és `1` sinó  `0`!
:::

La longitud de l'array és el nombre d'elements emmagatzemat en un moment determinat. Un array de `10` elements, tindrà índexes del `0` al `9` *(Length - 1)*

![](https://i.imgur.com/BG4RUNt.png)

Provem a imprimir *Pedro* per cònsola:

```javascript
let arrayNames = ["Pedro", "Jake", "Joan", "Mike"];

console.log(arrayNames[0]);
// => Pedro
```
Per accedir als elements dins de l'array es referència la seva posició:
.

```javascript
console.log(arrayNames[1]); //= Jake
console.log(arrayNames[2]); //= Joan
console.log(arrayNames[3]); //= Mike
console.log(arrayNames[99]); //= undefined
```

:warning: Si provem a accedir un índex que no existeix es retorna **undefined**.

### 3.5.3. Afegir Elements

Per crear nous elements dins de l'array utilitzarem amb [push](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/Array/push).

```javascript
 let arrayNames = ["Pedro", "Jake", "Joan"];

arrayNames.push("Rachel");

console.log(arrayNames[3]);
```
Ara, arrayNames té un quart element, i si provem a obtenir la quarta posició (índex 3), donarà *Rachel*.

El nou valor s'afegeix al final de l'array, no al començament o a posicions aleatòries. 
Per afegir un element al començament s'utilitza [unshift](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/Array/unshift) enlloc de *push*:

```javascript
let arrayNames = ["Pedro", "Jake", "Joan"];

arrayNames.unshift("Rachel");

console.log(arrayNames[0]);
// => Rachel
```

### 3.5.4. Esborrar Elements

Mitjançant el mètode [splice](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/Array/splice) podem fer-ho:

`array.splice(start, deleteCount)`
*start:* índex al que volem començar a canviar l'array.
*deleteCount:* nombre d'elements per esborrar 

```javascript
let arrayNames = ["Pedro", "Jake", "Joan"];

console.log(arrayNames[0]);
arrayNames.splice(0,1);
console.log(arrayNames[0]);
```

En aquest exemple comencem a l'índex `0` (primer element de l'array) i volem esborrar 1 element. Finalment, si accedim al primer element de nou, obtenim *Jake*, el anterior segon element.

Per esborrar el darrer element utilitzarem [pop](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/Array/pop) i [shift](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/Array/shift) per esborrar el primer.

 **Resum dels mètodes**

| Mètode | Acció
|--------|------------
| push    | Afegir un element al final
| unshift | Afegir un element al començament
| shift   | Esborrar el primer element
| pop     | Esborrar el darrer element
| splice  | Esborrar elements a qualsevol posició de l'array

### 3.5.5. Iteració sobre els elements d'un array

Exemple, si volem sumar tots els nombres d'un array o saludar cadascú dels noms de l'array és útil iterar a sobre d'uns quants o tots els elements d'un array.


You already know what a loop is, for this example, we are going to use the `for` loop. For instance, imagine we want to print all the names inside `arrayNames`. Maybe the first thing you think is:
Si volem imprimir tots els noms de l'array  `arrayNames` la primera cosa sería:

```javascript
console.log(arrayNames[0]);
console.log(arrayNames[1]);
console.log(arrayNames[2]);
```
Però si tenim centenars o milers de noms, la millor manera de aconseguir imprimir els noms seria mitjançant alguna cosa com un loop `for`:

```javascript
let arrayNames = ["Pedro", "Jake", "Joan"];
for(let i=0; i < arrayNames.length; i++) {
  console.log(arrayNames[i]);
}
```

### 3.5.6. funció `forEach`

Javascript ens ofereix una manera més optimitzada per iterar sobre un array. El mètode [forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)

```javascript
let arrayNames = ["Pedro", "Jake", "Joan"];

arrayNames.forEach(function(name){
  console.log(name);
})
```

`forEach` és una funció que recorre tots els elements d'un array, i per cadascun dels elements (**FOR EACH**) de l'array, es crida una altra funció passant l'element.

`forEach` rep un paràmetre: una funció. Aquesta funció no requereix un nom, pero pot tenir cap, un, dos o tres paràmetres:

* **Sense paràmetres**
  
  Es crida a la funció tantes vegadas com elements contè l'array:

```javascript
['a','b'].forEach(function(){
  console.log('hola!');
});
// => hola!
// => hola!
```

* **Un paràmetre: Element**
  
  Si es passa un paràmetre serà l'element a cada iteració:

```javascript
[1,2,3,4].forEach(function(element){
  console.log(element*2); // podem accedir al valor de cada element!
});
// => 2
// => 4
// => 6
// => 8
```

* **Segon paràmetre: Índex**
  
```javascript
let raceResults = ['Hellen', 'John', 'Peter', 'Mery'];
raceResults.forEach(function(elem, index){
  console.log(elem + ' finished the race in ' + (index+1) + ' position!');
});

// => Hellen finished the race in 1 position!
// => John finished the race in 2 position!
// => Peter finished the race in 3 position!
// => Mery finished the race in 4 position!
```

<strong style="text-decoration:underline">Exemple></strong>

Qué imprimirà aquesta funció:

```javascript
function printStars(howMany){
  console.log("*".repeat(howMany));
}

[1,2,3,4,5].forEach(function(num){
  printStars(num)
});
```

## 3.6. Objectes predifinits de JavaScript

Els objectes predefinits de JavaScript són:

+ Objecte **String**: per representar i operar amb cadenes de text.
+ Objecte **Number**: per representar números.
+ Objecte **Math**: per representar constants i funcions matemàtiques.
+ Objecte **Date**: per representar dates.
+ Objecte **RegExp**: per representar expressions regulars.

Com a objectes que són, tots ells tenen unes propietats i uns mètodes. És difícil practicar amb totes les propietats i mètodes dels objectes. El que és important és saber cercar dins de la documentació i saber aplicar les propietats i mètodes d’aquests objectes.

Un enllaç directe on podeu trobar la referència de totes les propietats i mètodes dels objectes predefinits és a [Objetos globales](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales)

### 3.6.1. L'objecte String

L’objecte **String** és un constructor de cadenes. De fet, no és exactament el mateix el tipus primitiu string que un objecte String.

```javascript
let str_prim = 'Javascript';
let str_obj = new String(str_prim);
 
console.log(typeof str_prim); // string
console.log(typeof str_obj);  // object
 
console.log(str_prim == str_obj); //true
console.log(str_prim === str_obj); //false
```

Tot i que normalment no ens n’haurem de preocupar, podem obtenir resultats sorprenents. Per exemple, si utilitzem la funció de JavaScript <code>eval()</code>, que avalua o executa una expressió:

```javascript
let str1 = '2 + 2';    //tipus primitiu de cadena
let str2 = new String('2 + 2'); // objecte String
console.log(eval(str1));        // retorna 4
console.log(eval(str2));        // retorna la cadena "2 + 2"
```

Amb el mètode `valueOf()` podem convertir un objecte al seu tipus primitiu:

```javascript
console.log(eval(str2.valueOf())); //retorna 4 
Propietats de l'objecte String
```

Les propietats principals de l’objecte String són:

* `prototype`: permet afegir propietats i mètodes a l’objecte.
* `constructor`: retorna la funció constructora de la cadena.
* `length`: retorna la longitud d’una cadena.

<strong style="text-decoration:underline;">Mètodes de l'objecte String</strong>

Els principals mètodes que farem servir són els següents.

+ `charAt(x)`: retorna el caràcter a la posició x (començant pel 0).
+ `concat(str)`: concatena la cadena str a la cadena original.
+ `startsWith(str)`: comprova si la cadena comença amb els caràcters o cadena especificats.
+ `endsWith(str)`: comprova si la cadena acaba amb els caràcters o cadena especificats.
+ `includes(str)`: comprova si la cadena conté els caràcters o cadena especificats.
+ `indexOf(str)`: retorna la posició de la primera ocurrència de la cadena que passem com a paràmetre.
+ `lastIndexOf(str)`: retorna la posició de l’última ocurrència de la cadena que passem com a paràmetre.
+ `match(regexp)`: cerca dins una cadena comparant-la amb l’expressió regular regexp, i retorna les coincidències en un array.
+ `repeat(x)`: retorna una nova cadena que és la repetició de la cadena tantes vegades com el valor del paràmetre x.
+ `replace(str1, str2)`: cerca dins la cadena els caràcters (o expressió regular) str1, i retorna una nova cadena amb aquests valors reemplaçats pel segon paràmetre str2.
+ `search(str)`: cerca dins de la cadena els caràcters (o expressió regular) str, i retorna la posició de la primera ocurrència.
+ `slice(x,y)`: extreu una part d’una cadena entre els caràcters x i y, i retorna una nova cadena.
+ `split(car)`: separa una cadena en un array de subcadenes, agafant com a llavor del separador el caràcter car.
+ `substr(x, y)`: extreu caràcters d’una cadena, començant en la posició x, i el número de caràcters especificat per y.
+ `substring(x, y)`: extreu caràcters d’una cadena entre els dos index especificats, x i y.
+ `toLowerCase(str)`: converteix una cadena a minúscules.
+ `toUpperCase(str)`: converteix una cadena a majúscules.
+ `trim()`: elimina els espais en blanc d’ambdós extrems de la cadena.
+ `toString()`: retorna el valor d’un objecte String.
+ `valueOf()`: retorna el tipus primitiu d’un objecte String.

Hi ha altres mètodes que només tenen sentit en el context de la web. Són els wrapper HTML methods. Per exemple, el mètode `bold()` retorna la mateixa cadena embolcallat amb els tags `<b>` i `</b>`, de manera que dins d’una pàgina web la cadena es veu com a negreta. Aquests mètodes no són un estàndard, poden tenir un comportament diferent en diversos navegadors i, a més, la majoria d’ells són obsolets. Els principals mètodes d’embolcall HTML són: `big()`, `bold()`, `fontcolor()`, `fontsize()`, `italics()`, `small()`, que embolcallen la cadena amb tags perquè es mostri, respectivament: amb font gran, en negreta, d’un color determinat, amb una mida determinada, en cursiva i amb font petita.

<div style="border:1px solid; padding:1em;">
Exemple: Una funció per validar el DNI

En el DNI tenim 8 números i una lletra. Per cada número només una lletra és vàlida, i la manera de calcular-la la tenim en la següent funció. S’utilitzen diversos mètodes de String: substr(), charAt() i toUpperCase().
<code>
function validarDNI(dni) {
let lletres = 'TRWAGMYFPDXBNJZSQVHLCKE';
let num_dni=dni.substr(0,dni.length-1);
//la línia següent pot substituir-se per: let lletra_dni=dni.substr(dni.length-1,1).toUpperCase();
let lletra_dni=dni.charAt(dni.length-1).toUpperCase();
if (lletres.charAt(num_dni % 23)==lletra_dni) return true;
return false;
}
console.log(validarDNI('38540343T')); //false
console.log(validarDNI('38540343a')); //true
</code>
</div>

### 3.6.2. L'objecte Number

A JavaScript, a diferència d’altres llenguatges de programació, només hi ha un tipus de dades per als números. Tots els números es guarden en memòria amb una resolució de 64 bits (doble precisió) i coma flotant.

```javascript
let a = 20;
let b = -2.718;
let c = 1e4;
let d = 2.23e-3
```

A part de la notació decimal, podem representar els números en binari, octal o hexadecimal.

```javascript
console.log(0b1010);
console.log(0xFF);
```

I amb el mètode `toString()` podem representar els números en diferents notacions:

```javascript
let num = 76;
console.log(num.toString(16) + " en hexadecimal");
console.log(num.toString(8) + " en octal");
console.log(num.toString(2) + " en binari");    
```

**Infinity** és el valor per representar que hem sobrepassat la precisió dels números (que és fins a 15 dígits en la part entera):

```javascript
console.log (5/0); //retorna Infinity 
```

Not a **Number (NaN)** és una paraula reservada per indicar que el valor no representa un número. Podem utilitzar la funció global isNaN() per saber si l’argument és un número:

```javascript
console.log(3*"a"); //NaN. Recordeu que 3+"a" retorna "3a"
console.log(isNaN(3*4)); //false
console.log(isNaN(3*"a")); //true
```

De la mateixa manera que passa amb les cadenes, a JavaScript normalment els números són tipus primitius, però també els podem crear com a objectes:

```javascript
let x = 25; //tipus primitiu
let y = new Number(25); //objecte
console.log(typeof x); //number
console.log(typeof y); //object
 
console.log (x == y); //true
console.log (x === y); //false
```

Propietats de l'objecte Number
Les propietats més importants són:

prototype: permet afegir noves propietats i mètodes a l’objecte Number.
NaN: representa un valor no numèric.
Mètodes de l'objecte Number
Els principals mètodes de l’objecte Number són:

isFinite(): comprova si un valor és un número finit.
isInteger(): comprova si un valor és un enter.
isNaN(): comprova si un valor és un NaN.
toExponential(x): representa un número amb la seva notació exponencial. Per exemple, 20,31 a 2.031e+1, que significa 2.031 * 10^1.
toFixed(n): formata un número amb una precisió decimal de n dígits. Retorna una cadena que és la representació del número.
toPrecision(n): formata un número a una precisió de n dígits (número total de dígits, incloent la part entera i la decimal).
toString(): converteix un número a una cadena.
parseInt(): converteix un número a enter.
parseFloat(): converteix un número a decimal.
valueOf(): retorna el valor del tipus primitiu del número.

Posem alguns exemples:

console.log((18).toString() + (20).toString());
 
let x = 234.456;
console.log(typeof x); //number
console.log (Number.isInteger(x)); //false
console.log (x.toExponential());
x = x.toFixed(2); // 234.46, arrodoneix de la forma esperada
console.log(x);
console.log(typeof x); //compte! x ara és un string
x = parseFloat(x);
console.log(typeof x); //number. Torna a ser number
 
x = x.toPrecision(6); //234.460
console.log(x);
Podeu veure l’exemple a: http://codepen.io/ioc-daw-m06/pen/VjpGoG.

Paràmetres i valors retornats per funcions

Aquest exemple que acabeu de veure no era trivial. Fixeu-vos que després d’utilitzar toFixed() el resultat és una cadena, i per tant no podem aplicar toPrecision(), que només s’aplica a Numbers. Per convertir a Number tampoc puc utilitzar Number.parseFloat(), que només s’aplica a Number, sinó la funció global parseFloat(x). Un cop tenim Number, ja podem aplicar el mètode toPrecision(). Aquesta manera de raonar és habitual en JavaScript i en d’altres llenguatges de programació. Així doncs, quan us trobeu amb un resultat inesperat no heu de treure conclusions precipitades, i heu d’aprendre a trobar i raonar sobre la causa del problema.

### 3.6.3. L'objecte Math

L’objecte Math permet realitzar tasques matemàtiques, com per exemple crear números aleatoris, realitzar funcions trigonomètriques, etc.

Propietats de l'objecte Math
L’objecte Math és especial en el sentit que no té constructor. No hi ha cap mètode per crear un objecte Math. Podem fer-lo servir sense haver de crear-lo.

JavaScript té emmagatzemades les principals constants matemàtiques (número pi, número e, etc.), i per accedir-hi ho fem a través de les propietats corresponents de l’objecte Math. Així doncs, trobem: Math.E (número d’Euler, 2.718…), Math.LN2 (logaritme neperià de 2), Math.LN10 (logaritme natural de 10), Math.PI (número Pi), Math.SQRT2 (arrel quadrada de 2), i algunes altres més.

Per exemple,

console.log (Math.PI);
Mètodes de l'objecte Math
Amb els següents mètodes de Math podem realitzar operacions matemàtiques usuals:

abs(x): valor absolut.
sin(x), cos(x), tan(x): funcions trigonomètriques de sinus, cosinus i tangent.
asin(x), acos(x), atan(x): retorna en radians l’arcsinus, arccosinus, arctangent.
round(x): arrodoneix x al valor enter més proper.
ceil(x), floor(x): retorna el mateix número però arrodonit a l’enter més proper cap a dalt (ceil) o cap a baix (floor).
truncx(x): elimina la part fraccionària d’un número (i queda només la part entera).
exp(x): retorna el valor $e^x$.
max(a,b,…), min(a,b,…): retorna el valor més gran (o més petit) de la llista de números.
pow(x,y): retorna $x^y$.
log(x): retorna el logaritme natural (base e) de x.
random(): retorna un número aleatori entre 0 (inclòs) i 1 (exclòs).
sqrt(x): retorna l’arrel quadrada de x.
Quan es programa, sovint és necessari obtenir números aleatoris. Per generar-los, JavaScript utilitza una llavor (seed) interna, que no és accessible a l’usuari. En el següent exemple es veu un exemple típic de com es poden generar números aleatoris en diferents rangs:

// Funció que retorna un número aleatori entre 0 (inclusiu) i 1 (exclusiu)
function getRandom() {
  return Math.random();
}
 
// Funció que retorna un número aleatori entre min (inclusiu) i max (exclusiu)
function getRandomArbitrary(min, max) {
  return Math.random() * (max - min) + min;
}
 
// Funció que retorna un número enter aleatori entre min (inclusiu) i max (exclusiu)
function getRandomInt(min, max) {
  return Math.floor(Math.random() * (max - min)) + min;
}
 
// Funció que retorna un número enter aleatori entre min (inclusiu) i max (inclusiu)
function getRandomIntInclusive(min, max) {
  return Math.floor(Math.random() * (max - min + 1)) + min;
}
 
let i;
console.log('\nNúmero aleatori entre 0 (inclusiu) i 1 (exclusiu)');
for (i=0; i<10; i++) {
  console.log(getRandom());
}
 
console.log('\nNúmero aleatori entre 1 (inclusiu) i 5 (exclusiu)');
for (i=0; i<10; i++) {
	console.log(getRandomArbitrary(1,5));
}
 
console.log('\nNúmero enter aleatori entre 1 (inclusiu) i 5 (exclusiu)');
for (i=0; i<10; i++) {
	console.log(getRandomInt(1,5));
}
 
console.log('\nNúmero enter aleatori entre 1 (inclusiu) i 5 (inclusiu)');
for (i=0; i<10; i++) {
	console.log(getRandomIntInclusive(1,5));
}
Podeu veure l’exemple a: http://codepen.io/ioc-daw-m06/pen/jrBeNW.

### 3.6.4. L'objecte Date

L’objecte Date s’utilitza per treballar amb dates i temps. Per instanciar un objecte tipus Date s’utilitza new, i admet diferents arguments:

let data = new Date(); //data del sistema
console.log(data);
let data = new Date(34885453664); //genera un data que representa els mil·lisegons que han passat des de l'1 de gener de 1970
console.log(data);
data = new Date('2016/05/23');
console.log(data);
data = new Date(2016,5,23,12,15,24,220);  //any,mes,dia,hora,minuts,segons,mil·lisegons
console.log(data);
Treballar amb dates no sempre és fàcil i immediat: haurem de tenir en compte el format de data i el fus horari.

Sigui quin sigui el format en què expressem les dates, aquestes es guarden internament com un número que representa els mil·lisegons que han passat des de l’1 de gener de 1970 (00:00:00). Per exemple, des de la data actual (amb precisió de mil·lisegons) fins aquesta data original han passat:

let data = new Date(); //data del sistema
console.log(data.getTime()); //milisegons
console.log('Des de 1970 han passat ' + data.getTime()/1000/3600/24/365 + ' anys aprox');
Podeu veure els exemples a: http://codepen.io/ioc-daw-m06/pen/beqmGN.

Propietats de l'objecte Date
Les propietat de l’objecte Date són:

constructor: retorna la funció que ha creat el prototipus de l’objecte Date.
prototype: permet afegir propietats i mètodes a l’objecte.
Mètodes de l'objecte Date
Hi ha molts mètodes de l’objecte Date. En veurem alguns, en especial aquells que permeten representar les dates en el format usual (dd/mm/aaaa):

getDay(): retorna el dia de la setmana (0-6, començant per diumenge).
getFullYear(): retorna l’any (4 dígits).
getMonth(): retorna el mes (0-11).
getDate(): retorna el dia del mes (1-31).
getHours(): retorna l’hora (0-23).
getMinutes(): retorna els minuts (0-59).
getSeconds(): retorna els segons (0-59).
getMilliseconds(): retorna els mil·lisegons (0-999).
getUTCDate(): retorna el dia del mes (1-31), d’acord amb l’horari UTC universal.
getUTCDay(): retorna el dia de la setmana (0-6, començant per diumenge), d’acord amb l’horari UTC universal.
getUTCFullYear(): retorna l’any (4 dígits), d’acord amb l’horari UTC universal.
getUTCMonth(): retorna el mes (0-11), d’acord amb l’horari UTC universal.
getUTCHours(): retorna l’hora (0-23), d’acord amb l’horari UTC universal.
getUTCMinutes(): retorna els minuts (0-59), d’acord amb l’horari UTC universal.
getUTCSeconds(): retorna els segons (0-59), d’acord amb l’horari UTC universal.
getUTCMilliseconds(): retorna els mil·lisegons (0-999), d’acord amb l’horari UTC universal.
getTime(): retorna el número de mil·lisegons que han transcorregut des de la data fins l’1 de gener de 1970.
now(): retorna el número de mil·lisegons que han transcorregut des de la data del sistema fins l’1 de gener de 1970.
parse(): transforma una cadena de text (representant una data), i retorna el número de mil·lisegons transcorreguts des de la data fins l’1 de gener de 1970.
setFullYear(): especifica el dia de l’any.
setMonth(): especifica el mes.
setDate(): especifica el dia del mes.
setHours(): especifica l’hora.
setMinutes(): especifica els minuts.
setSeconds(): especifica els segons.
setMilliseconds(): especifica els mil·lisegons.
setTime(): especifica una data a partir del número de mil·lisegons abans o després de l’1 de gener de 1970.
setUTCFullYear(): especifica l’any, d’acord amb l’horari UTC universal.
setUTCMonth(): especifica el mes, d’acord amb l’horari UTC universal.
setUTCDate(): especifica el dia del mes, d’acord amb l’horari UTC universal.
setUTCHours(): especifica l’hora, d’acord amb l’horari UTC universal.
setUTCMinutes(): especifica els minuts, d’acord amb l’horari UTC universal.
setUTCSeconds(): especifica els segons, d’acord amb l’horari UTC universal.
setUTCMilliseconds(): especifica els mil·lisegons, d’acord amb l’horari UTC universal.
toDateString(): converteix la part de la data en una cadena llegible.
toLocaleDateString(): converteix la part de la data en una cadena llegible, utilitzant les convencions locals.
toISOString(): converteix la data a cadena, utilitzant la convenció ISO.
toJSON(): converteix la data a cadena amb format JSON.
toTimeString(): converteix la part del timestamp de l’objecte Date a cadena.
toLocaleTimeString(): converteix la part del timestamp de l’objecte Date, utilitzant les convencions locals.
toString(): converteix l’objecte Date a cadena.
toLocaleString(): converteix l’objecte Date a cadena, utilitzant les convencions locals.
Diferents exemples per mostrar com s’utilitzen aquests mètodes són:

let data = new Date();
let array_mes = ['gener', 'febrer', 'març', 'abril', 'maig', 'juny', 'juliol', 'agost', 'setembre', 'octubre', 'novembre', 'desembre'];
let array_dies_setmana = ['diumenge', 'dilluns', 'dimarts', 'dimecres', 'dijous', 'divendres', 'dissabte'];
console.log('Avui és ' + array_dies_setmana[data.getDay()] + ', ' + data.getDate() + ' de ' + array_mes[data.getMonth()] + ' de ' + data.getFullYear());
//Per veure el número de mil·lisegons des de l'origen dels temps (1 de gener de 1970 00:00:00):
let data = new Date();
console.log(data.getTime());
// I també:
console.log(Date.now());
let d1 = Date.parse("23 March 2016"); //parse sap interpretar diferents formats de data, però en anglès.
let d2 = Date.parse("28 May 2016");
console.log(d1);
console.log(d2);
console.log(d1>d2); //Podem comparar les dates per saber quina és la més gran
Per veure la diferència entre utilitzar UTC o no, hem de pensar que aquí a Catalunya estem en el fus horari UTC/GMT +1 hora, però hem de tenir en compte si estem en horari d’estiu o d’hivern. Quan estem a l’estiu s’ha de compensar el fus horari i aleshores és UTC/GMT +2 hora. Per tant, podem veure la diferència entre l’hora local i l’hora absoluta internacional:

let data = new Date();
console.log(data.getHours()); //per ex, 14, hora real d'un rellotge local.
console.log(data.getUTCHours()); //per ex, 12, hora UTC
Podem veure la diferència entre utilitzar les convencions locals o no.

let d = new Date();
//Dia del Treball
d.setDate(1); 
d.setMonth(4); //Representa el mes de maig 
d.setFullYear(2016); 
console.log(d); 
console.log(d.toDateString()); //Sun May 01 2016
console.log(d.toLocaleDateString()); //1/5/2016
 
//Com que toLocaleDateString() retorna una cadena, ja puc utilitzar les funcions de cadena:
let array_data = d.toLocaleDateString().split('/');
console.log(array_data[0]); //dia
console.log(array_data[1]); //mes
console.log(array_data[2]); //any
Utilitzem les convencions locals:

let d = new Date();
console.log(d.toLocaleString()); // 2/5/2016, 14:44:37
console.log(d.toLocaleDateString()); // 2/5/2016
console.log(d.toLocaleTimeString()); // 14:44:37
Podeu veure els exemples a: http://codepen.io/ioc-daw-m06/pen/ezvPmW.

### 3.6.5. L'objecte RegExp

Les expressions regulars estan explicades amb deteniment en la unitat “Esdeveniments. Manejament de formularis”.

Les expressions regulars són objectes de JavaScript que s’utilitzen per descriure un patró de caràcters. Aplicades a les cadenes de text, amb les expressions regulars podem esbrinar si una cadena de text compleix un patró, i realitzar funcions de cerca i reemplaçament.

En una expressió regular distingim entre el patró i els modificadors: /pattern/modificadors;.

let patro = /IOC/i
En aquest cas, la i és un modificador que significa que farem una cerca sense tenir en compte majúscules/minúscules. Hi ha altres modificadors que pots consultar, entre d’altres llocs, al tutorial de la Fundació Mozilla https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions.

Per veure el funcionament bàsic de les expressions regulars veurem els mètodes test i match:

test: mètode que retorna true o false si la cadena de text compleix el patró.
match: mètode de l’objecte String que fa una cerca de la cadena contra un patró, i retorna un array amb els resultats trobats, o el valor primitiu null en cas que no en trobi cap.
let patro1 = /ioc/i
let patro2 = /ioc/
let cad="Curs de JavaScript de l'IOC";
 
console.log(patro1.test(cad));
console.log(patro2.test(cad));
 
let res = cad.match(patro1);
console.log(res.length); //1, una sola ocurrència
console.log(res[0]); //IOC
Dins una expressió regular podem utilitzar brackets per expressar un rang de caràcters, i metacaràcters, que tenen un significat especial. Per exemple, anem a veure una expressió regular per comprovar si una cadena compleix amb el format de data dd/mm/aaaa:

regexp = /^(3[01]|[12][0-9]|0?[1-9])\/(1[0-2]|0?[1-9])\/([0-9]{2})?[0-9]{2}$/;
console.log(regexp.test("01/01/2016")); //true
console.log(regexp.test("2016/01/01")); //false
console.log(regexp.test("01/01/16")); //true
console.log(regexp.test("1/1/16")); //true
console.log(regexp.test("IOC")); //false
Amb el circumflex (^) estem indicant com ha de començar l’expressió.
Amb el dòlar ($) estem indicant com ha d’acabar l’expressió.
Utilitzem la contrabarra (\) per indicar que la barra (/) no és un metacaràcter, sinó un caràcter a tenir en compte.
El dia del mes pot ser: 30 o 31; del 10 al 29; o també del 1 al 9, ficant o no un 0 al davant.
El mes pot ser 1-12, ficant o no un zero al davant.
L’any pot ser de 2 o 4 dígits.
Un altre exemple, en aquest cas per validar un número de targeta de crèdit:

regexp = /^[0-9]{4}(-|\s)[0-9]{4}(-|\s)[0-9]{4}(-|\s)[0-9]{4}$/;
console.log(regexp.test("3782-8224-6310-0067")); //true
console.log(regexp.test("3782 8224 6310 0067")); //true
console.log(regexp.test("3782*8224*6310*0067")); //false
console.log(regexp.test("37828224630006")); //false
Podeu veure els exemples a: http://codepen.io/ioc-daw-m06/pen/WxpavQ.

## 3.7. BOM (Browser Object Model)

El DOM (Document Object Model) està explicat amb més detall a la unitat “Model d’objectes del document”.

L’objectiu del BOM no és només canviar el contingut del document HTML, sinó també realitzar altres manipulacions relacionades amb el navegador i les seves finestres. Per exemple, és possible redimensionar i moure una finestra del navegador, modificar la informació que es mostra a la barra d’estat, moure’s per l’historial d’URLs en les quals navegador ha accedit, gestionar les cookies (galetes), etc.

Quan un client web (el navegador web: Firefox, Chrome, IE) carrega un document HTML, crea uns objectes associats al document, al seu contingut, i altra informació útil. Aquests objectes guarden una jerarquia en què l’objecte window és l’arrel, i d’aquí pengen els altres objectes que podem referenciar (vegeu la següent figura).

![](https://imgur.com/AiY2nvr.png)

Cada document HTML crea els següents objectes:

+ **window**: representa l’arrel de l’arbre del BOM. Una finestra pot tenir subfinestres (per exemple, pop-ups), que seran fills en aquest arbre que representa l’estructura.
+ **location**: conté les propietats de la direcció URL del document.
+ **history**:conté la informació de les direccions URL que s’han visitat en la sessió actual.
+ **document**: conté informació sobre el document actual, com ara el títol, imatges, links, taules, formularis que conté, etc. Per accedir a tota aquesta informació tenim el DOM. Les propietats de l’objecte document poden ser alhora altres objectes (com ara l’objecte cookies).
A més de propietats i mètodes, també hi tenim events associats. És a dir, aquests objectes poden respondre a events disparats per les accions de l’usuari.

### 3.7.1. L'objecte window. Jerarquia d'objectes associats al navegador

En l’arrel de la jerarquia trobem l’objecte window, que representa una finestra oberta en el navegador. En la figura figura figura2.1 es pot veure la jerarquia d’objectes que pengen de window.

En aquesta jerarquia, els descendents d’un objecte es representen mitjançant propietats de l’objecte. Per exemple, una imatge *img1* és un objecte però també és una propietat de l’objecte document, i serà referenciat com a document.img1. Per referenciar una propietat s’han de precisar els seus ascendents. De fet, seria window.document.img1, però window, que és l’arrel, es pot ometre. Alhora aquesta imatge, com a objecte que és, té les seves propietats (típicament width i heigh): document.img1.width.

Un altre exemple: utilitzant la jerarquia podem saber la URL actual de la pàgina que estem visitant: window.location.href (o location.href).

El codi HTML per poder provar els anteriors exemples és:

```html
<!DOCTYPE html>
<html>
    <head>
        <meta http-equiv="content-type" content="text/html; charset=utf-8">
        <title>Objecte window</title>
    </head>
    <body>
        <img src="./muntanya.jpg" name="img1" />
        <script>
            console.log(window.document.img1.width);
            console.log(document.img1.height);
            console.log(window.location.href);
            console.log(location.protocol);
        </script>
    </body>
</html>
```
Evidentment, l’usuari haurà de tenim una imatge muntanya.jpg en la mateixa carpeta que el document HTML.

<strong style="text-decoration:underline;">Propietats de window</strong>


* `defaultStatus`: és el missatge que es visualitza en la barra d’estat del navegador.
* `frames`: és la matriu de la col·lecció de frames que conté una finestra. Per exemple, si volem fer referència al primer frame de la finestra: `window.frames[0]`. `frames.length` és el número de frames que conté una finestra.
* `parent`: ascendent d’una finestra.
* `self`: fa referència a la finestra actual.
status: missatge que mostra l’estat del client web.
* `top`: fa referència a l’arrel de la jerarquia d’objectes.
* `window`: fa referència a la finestra actual.
* `innerWidth`, `innerHeight`: amplada i altura interiors de la finestra.
* `closed`: retorna un boolean indicant si la finestra s’ha tancat o no.
* `screenX`, `screenY`: coordenades de la finestra en relació a la pantalla. Vàlid per als navegadors Google Chrome i IE (per a Firefox utilitzar screenLeft i screenTop).
* `opener`: retorna una referència a la finestra que ha creat la finestra.
* `localStorage`: retorna una referència a l’objecte localStorage que s’utilitza per emmagatzemar dades. Al contrari que les galetes, no té data d’expiració.
document, history, location, navigator, screen: són propietats de window que fan referència als objectes document, history, location, navigator, screen. Recordeu que formen part d’una estructura jeràrquica.
* `sessionStorage`: retorna un objecte storage per emmagatzemar dades en una sessió web.
Les propietats més clares les podem veure en aquest exemple:

```html
<!DOCTYPE html>
<html>
    <head>
        <meta http-equiv="content-type" content="text/html; charset=utf-8">
        <title>Objecte window</title>
    </head>
    <body>
        <script>
            console.log(window.innerWidth + '-' + window.innerHeight); //Pots redimensionar la finestra per veure com canvia aquest valor
            console.log(window.screenX + '-' + window.screenY); //Si mous la finestra de posició per veure com canvia aquest valor
            window.defaultStatus = "informació a la barra d'estat";
            console.log(window.defaultStatus);
            console.log(window.closed);
        </script>
    </body>
</html> 
```

<strong style="text-decoration:underline;">Mètodes de window</strong>

* `alert(missatge)`: crea una finestra de diàleg on es mostra el missatge.
* `confirm(missatge)`: crea una finestra de *confirmació (OK/Cancel)* on es mostra el missatge. Retorna true o false.
* `prompt(missatge, text)`: crea una finestra de diàleg on es mostra el missatge i permet l’edició. El paràmetre “text” és el valor predeterminat. Igual que confirm, conté Acceptar i Cancelar. Si acceptem, el mètode retorna el valor inserit (o el valor per defecte). Si cancelem, retorna null.
* `close()`: només es poden tancar les finestres que també s’han creat amb un script.
* `stop()`: atura la càrrega de la finestra.
* `setTimeout(expressió, msec)`: executa l’expressió que es passa com a argument, un cop han passat msec mil·lisegons. S’utilitza per prorrogar l’execució de l’expressió.
* `clearTimeout(timeoutID)`: restaura el compte enrere iniciat per setTimeout.
* `setInterval(expressió, msec)`: executa l’expressió passada com a argument cada msec mil·lisegons. S’utilitza per executar l’expressió a intervals regulars de temps.
* `open(url, WindowName, params)`: crea una finestra nova, li associa el nom WindowName, i accedeix a la URL que li hem passat. Li passem un conjunt de paràmetres que descriuen les propietats de la finestra. Entre d’altres: toolbar, width, height, left, top, fullscreen, resizable, location, status, scrollbars, menubar.
En el següent exemple utilitzem alguns d’aquests mètodes:

```html
<!DOCTYPE html>
<html>
    <head>
        <meta http-equiv="content-type" content="text/html; charset=utf-8">
        <title>Creació d'una finestra</title>
    </head>
    <body>
        <script>
            let myWindow;
            let titol;
 
            myWindow = window.open("http://ioc.xtec.cat", "", "width=300,height=300, left=300, top=300, resizable=1");
            setTimeout( function(){ myWindow.close(); titol = prompt("Posa el títol de la finestra:","Títol"); }, 2000);
 
            setTimeout(function(){crear_finestra(titol)}, 2000);
 
            function crear_finestra(titol) {
              let opcions = "toolbar=0, location=0, directories=0, status=0,";
            	opcions+= "menubar=0, scrollbars=0, resizable=0, copyhistory=0,";
            	opcions += "width=100,height=100";
 
            	window.open("", titol, opcions);
            }
        </script>
    </body>
</html>
```

### 3.7.2. L'objecte document

Quan un document HTML es carrega en un navegador web, obtenim un objecte document. L’objecte document és el node arrel d’un document HTML, i d’ell pengen tots els altres nodes: nodes d’elements, de text, d’atributs, de comentaris.

Recordeu que el document és part de l’objecte window, i per tant el podem accedir amb window.document.

<strong><u>  Propietats de document</u></strong>

* `location`: conté la URL del document.
* `title`: títol del document HTML.
* `lastModified`: data de l’última modificació.
* `cookie`: cadena de caràcters que conté el cookie associat al recurs representat per l’objecte.
* Les propietats `anchors`, `forms`, `images`, `links` retornen un objecte amb el qual podem accedir a cadascun dels elements (àncores, formularis, imatges, enllaços) presents en el document.

El següent exemple utilitza algunes d’aquestes propietats:

```html
<!DOCTYPE html>
<html>
    <head>
        <meta http-equiv="content-type" content="text/html; charset=utf-8">
        <title>Objecte document. Propietats</title>
    </head>
    <body>
        <a href="https://bcncodes.github.io/webgroup/">Mean Stack1</a><br />
        <img src="bcncodes.github.io/webgroup/images/logo.png" /img>
        <script>
            console.log ("location: " + document.location);
            console.log ("títol: " + document.title);
            console.log ("lastModified: " + document.lastModified);
            console.log(document.links[0].href);
            console.log(document.links.item(0).href);
            console.log(document.images[0].src);
        </script>
    </body>
</html>
```

<strong><u>Mètodes de document</u></strong>  

* `write()`: escriu codi HTML en el document.
* `writeln()`: idèntic a write, però inserta un retorn de carro al final.
* `open(tipus MIME)`: obre un buffer per recollir el que retorna els mètodes write i writeln. Els tipus MIME que es poden utilitzar són: text/html, text/plain, text/jpeg, etc.
* `close()`: tanca el buffer.
* `clear()`:esborra el contingut del document.

```html
<!DOCTYPE html>
<html>
    <head>
        <meta http-equiv="content-type" content="text/html; charset=utf-8">
        <title>Objecte document. Mètodes</title>
        <script type="text/javascript">
          function ReemplacarContingut () {
        		document.open ("text/html");
        		document.write ("<a href=\"http://web.gencat.cat/ca/inici/\">gencat.cat</a><br />");
        		document.write ("<img src=\"http://web.gencat.cat/web/.content/Imatge/marca_home/NG_logo_generalitat_home.png_602392567.png\" /img>");
        		document.close ();
          }
        </script>
    </head>
    <body>
        <a href="https://bcncodes.github.io/webgroup/">Mean Stack1</a><br />
        <img src="bcncodes.github.io/webgroup/images/logo.png" /img><br />
        <button onclick="ReemplacarContingut ();">Reemplaçar el contingut del document</button>
    </body>
</html>
```

### 3.7.3. L'objecte location

L’objecte location conté informació sobre l’actual URL, conté les propietats de la direcció URL del document.

L’objecte location és part de l’objecte window i per tant podem accedir-hi a través de la propietat `window.location`.

<strong><u>Propietats de location</u></strong>

* `hash`: retorna la part de la URL que representa l’àncora (#). Per ex, url#IOC.
* `host`: retorna el hostname i el número de port de la URL.
* `hostname`: retorna el hostname de la URL.
* `href`: retorna la URL sencera.
* `origin`: retorna el protocol, hostname i port de la URL.
* `pathname`: retorna el path de la URL.
* `port`: retorna el número de port de la URL.
* `protocol`: retorna el protocol de la URL.
* `search`: retorna la part de querystring de la URL. Per ex, url?search=Bcncodes.

<strong><u>Mètodes de location</u></strong>

* `assign()`: carrega un nou document.
* `reload()`: recarrega el document actual.
* `replace()`: reemplaça el document actual per un de nou.
  
Si proveu l’anterior exemple com a fitxer HTML 
obtindreu `location.protocol: file`. Si el proveu com a pàgina web que ens serveix un servidor web obtindreu `location.protocol: http`.

Un exemple per veure la major part d’aquestes propietats i mètodes:

```html
<!DOCTYPE html>
<html>
    <head>
        <meta http-equiv="content-type" content="text/html; charset=utf-8">
        <title>Objecte location. Propietats i Mètodes</title>
        <script type="text/javascript">
          function assign_url () {
        		document.location.assign('http://www.gencat.cat');
        	}
        	function reload_url () {
        		document.location.reload();
        	}
        	function replace_url () {
        		document.location.replace('http://www.gencat.cat'); <!-- fixeu-vos que no tenim l'històric de tirar enrere -->
        	}
        	console.log('location.hash: ' + location.hash);
        	console.log('location.hostname: ' + location.hostname);
        	console.log('location.href: ' + location.href);
        	console.log('location.origin: ' + location.origin);
 
        	console.log('location.pathname: ' + location.pathname);
        	console.log('location.port: ' + location.port);
        	console.log('location.protocol: ' + location.protocol);
        	console.log('location.search: ' + location.search);
        </script>
    </head>
    <body>
        <a href="https://bcncodes.github.io/webgroup/">Mean Stack1</a><br />
        <img src="bcncodes.github.io/webgroup/images/logo.png" /img><br />
        <button onclick="assign_url();">Mètode location.assign</button>
        <button onclick="reload_url();">Mètode location.reload</button>
        <button onclick="replace_url();">Mètode location.replace</button>
    </body>
</html>
```

### 3.7.4. L'objecte history

L’objecte history conté les URLs visitades per l’usuari (en el marc d’una finestra del navegador). L’objecte history és part de l’objecte window, i podem accedir-hi a través de la propietat `window.history`.

<strong><u>Propietats de history</u></strong>

La propietat més important de l’objecte history és:

* `length`: retorna el número d’URLs en la llista de l’històric de navegació.

<strong><u>Mètodes de history</u></strong>

* `back()`: carrega la URL prèvia en la llista de l’històric de navegació.
* `forward()`: carrega la següent URL en la llista de l’històric de navegació.
* `go()`: carrega una URL específica en la llista de l’històric de navegació.

Com a exemple, i sempre dins de la mateixa finestra, podeu navegar per les següents URLs, i finalment introduir la URL del codi que es proposa.

https://ca.wikipedia.org/wiki/Manresa
https://ca.wikipedia.org/wiki/Balsareny
https://ca.wikipedia.org/wiki/Navàs
https://ca.wikipedia.org/wiki/Puig-reig
https://ca.wikipedia.org/wiki/Gironella
https://ca.wikipedia.org/wiki/Berga

```html
<!DOCTYPE html>
<html>
    <head>
        <meta http-equiv="content-type" content="text/html; charset=utf-8">
        <title>Objecte history. Propietats i Mètodes</title>
    </head>
    <body>
        <button onclick="console.log('Número elements: ' + history.length);">Número d'elements a la llista</button>
        <button onclick="history.back()">URL anterior</button>
    </body>
</html>
```

### 3.7.5. L'objecte navigator

L’objecte navigator conté informació sobre el navegador web que estem utilitzant.

<strong><u>Propietats de navigator</u></strong>

* `appCodeName`: retorna el codi del navegador, per exemple, Mozilla.
* `appName`: retorna el nom oficial del navegador. Per exemple, en el cas de Mozilla Firefox, retorna netscape.
* `appVersion`: la versió del navegador (potser no coincideix amb la versió real del navegador).
* `cookieEnabled`: retorna true si les galetes estan habilitades.
* `language`: retorna l’idioma del navegador.
* `onLine`: retorna true si el navegador està en línia.
* `platform`: retorna en quina plataforma es va compilar el navegador.
* `product`: retorna el nom del motor del navegador.
* `userAgent`: retorna tota la capçalera user-agent que el navegador envia al servidor en el protocol HTTP. Aquest valor l’utilitza el servidor per identificar el client. En aquesta capçalera sí que podem veure la versió real del nostre navegador (per exemple, Mozilla/5.0 (X11; Ubuntu; Linux i686; rv:22.0) Gecko/20100101 Firefox/22.0).

En el següent exemple es s’utilitzen les principals propietats de l’objecte navigator:

```html
<!DOCTYPE html>
<html>
    <head>
        <meta http-equiv="content-type" content="text/html; charset=utf-8">
        <title>Objecte navigator</title>
    </head>
    <body>
        <script>
            console.log("appCodeName: " + navigator.appCodeName);
            console.log("appName: " + navigator.appName);
            console.log("appVersion: " + navigator.appVersion);
            console.log("cookieEnabled: " + navigator.cookieEnabled);
            console.log("language: " + navigator.language);
            console.log("onLine: " + navigator.onLine);
            console.log("platform: " + navigator.platform);
            console.log("product: " + navigator.product);
            console.log("userAgent: " + navigator.userAgent);
        </script>
    </body>
</html>
```

### 3.7.6. L'objecte screen

L’objecte screen conté informació sobre la pantalla on està obert el navegador del client. Aquesta informació s’extreu a partir de les propietats descrites més avall. En canvi, no té mètodes. No s’ha de confondre l’objecte screen amb l’objecte window, que representa la finestra del navegador.

<strong><u>Propietats de l'objecte screen</u></strong>

Als dissenyadors web sempre els ha preocupat saber quina és la resolució del navegador del client per tal que les pàgines web es vegin bé en els diferents formats de pantalla. Avui en dia, gràcies a frameworks com bootstrap, l’adaptació de la web a diferents formats de pantalla és molt més fàcil.

* `availHeight`: retorna l’altura de la pantalla.
* `height`: retorna l’altura total de la pantalla. La diferència amb availHeight és l’altura de la barra de tasques (depèn del sistema operatiu).
* `availWidth`: retorna l’amplada de la pantalla.
* `width`: retorna l’amplada total de la pantalla.
* `colorDepth`: retorna la resolució de la paleta de colors (en número de bits). Per exemple: 8 significa 256 colors; 24 significa 16 milions de colors.
* `pixelDepth`:retorna la resolució de color (en bits per píxel) de la pantalla.

En el següent exemple s’utilitzen les principals propietats de l’objecte screen que acabem de veure:

```html
<!DOCTYPE html
<html>
    <head>
        <meta http-equiv="content-type" content="text/html; charset=utf-8">
        <title>Objecte screen</title>
    </head>
    <body>
        <script>
            console.log("availHeight: " + screen.availHeight);
            console.log("height: " + screen.height);
            console.log("availWidth: " + screen.availWidth);
            console.log("width: " + screen.width);
            console.log("colorDepth: " + screen.colorDepth);
            console.log("pixelDepth: " + screen.pixelDepth);
        </script>
    </body>
</html>
```