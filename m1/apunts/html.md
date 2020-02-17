[HTML5](#1-introducció-html5)

- [1. Introducció HTML5](#1-introducci%C3%B3-html5)
  - [1.1. Estructura del document amb HTML5](#11-estructura-del-document-amb-html5)
  - [1.2. Capçalera del document](#12-cap%C3%A7alera-del-document)
- [2. Etiquetes i Atributs](#2-etiquetes-i-atributs)
  - [2.1. Etiquetes del cos del document](#21-etiquetes-del-cos-del-document)
    - [2.1.1. Tipus d'elements](#211-tipus-delements)
  - [2.2. Atributs genèrics](#22-atributs-gen%C3%A8rics)
    - [2.2.1. Atributs globals](#221-atributs-globals)
    - [2.2.2. Atributs de llenguatge](#222-atributs-de-llenguatge)
    - [2.2.3. Atributs d'esdeveniment ('event')](#223-atributs-desdeveniment-event)
  - [2.3. Etiquetes de text](#23-etiquetes-de-text)
    - [2.3.1. Paràgrafs](#231-par%C3%A0grafs)
    - [2.3.2. Els encapçalaments](#232-els-encap%C3%A7alaments)
    - [2.3.3. Èmfasi](#233-%C3%A8mfasi)
    - [2.3.4. Citacions](#234-citacions)
    - [2.3.5. Abreviatures](#235-abreviatures)
    - [2.3.6. Text preformatat](#236-text-preformatat)
    - [2.3.7. Codi de programació](#237-codi-de-programaci%C3%B3)
  - [2.4. Etiquetes sense atributs semàntics](#24-etiquetes-sense-atributs-sem%C3%A0ntics)
  - [2.5. Etiquetes estructurals](#25-etiquetes-estructurals)
  - [2.6. Enllaços](#26-enlla%C3%A7os)
    - [2.6.1. Enllaços a pàgines externes](#261-enlla%C3%A7os-a-p%C3%A0gines-externes)
    - [2.6.2. Enllaços a pàgines locals](#262-enlla%C3%A7os-a-p%C3%A0gines-locals)
    - [2.6.3. Àncores](#263-%C3%A0ncores)
  - [2.7. Imatges](#27-imatges)
  - [2.8. Panell de dibuix o llenç](#28-panell-de-dibuix-o-llen%C3%A7)
  - [2.9. Àudio](#29-%C3%A0udio)
  - [2.10. Vídeo](#210-v%C3%ADdeo)
  - [2.11. Llistes](#211-llistes)
    - [2.11.1. Llistes ordenades](#2111-llistes-ordenades)
    - [2.11.2. Llistes desordenades](#2112-llistes-desordenades)
    - [2.11.3. Llistes de definició](#2113-llistes-de-definici%C3%B3)
    - [2.11.4. Enniuament de llistes](#2114-enniuament-de-llistes)
  - [2.12. Taules](#212-taules)
    - [2.12.1. Grups de columnes](#2121-grups-de-columnes)
    - [2.12.2. Expansió de files i columnes](#2122-expansi%C3%B3-de-files-i-columnes)
  - [2.13. Formularis](#213-formularis)
    - [2.13.1. Propietats d'un formulari](#2131-propietats-dun-formulari)
    - [2.13.2. Associació de text i controls](#2132-associaci%C3%B3-de-text-i-controls)
    - [2.13.3. Atributs comuns dels controls d'un formulari](#2133-atributs-comuns-dels-controls-dun-formulari)
    - [2.13.4. Camps de text](#2134-camps-de-text)
    - [2.13.5. Camps de contrasenya](#2135-camps-de-contrasenya)
    - [2.13.6. Camp de correu](#2136-camp-de-correu)
    - [2.13.7. Camp d'URL](#2137-camp-durl)
    - [2.13.8. Camp numèric](#2138-camp-num%C3%A8ric)
    - [2.13.9. Camp de rang](#2139-camp-de-rang)
    - [2.13.10. Camps de data o horaris](#21310-camps-de-data-o-horaris)
    - [2.13.11. Camps de colors](#21311-camps-de-colors)
    - [2.13.12. Camp de cerca](#21312-camp-de-cerca)
    - [2.13.13. Botons d'opció](#21313-botons-dopci%C3%B3)
    - [2.13.14. Caselles de verificació](#21314-caselles-de-verificaci%C3%B3)
    - [2.13.15. Llistes de selecció](#21315-llistes-de-selecci%C3%B3)
    - [2.13.16. Llista de dades: `<datalist>`](#21316-llista-de-dades-datalist)
    - [2.13.17. Generador de claus: `<keygen>`](#21317-generador-de-claus-keygen)
    - [2.13.18. Sortida de resultats: `<output>`](#21318-sortida-de-resultats-output)
    - [2.13.19. Àrees de text](#21319-%C3%A0rees-de-text)
    - [2.13.20. Botons](#21320-botons)
    - [2.13.21. Controls ocults](#21321-controls-ocults)
  - [2.14. Marcs flotans](#214-marcs-flotans)
  - [2.15. Mapes](#215-mapes)
    - [2.15.1. Mapes gestionats des del client](#2151-mapes-gestionats-des-del-client)
    - [2.15.2. Mapes gestionats des del servidor](#2152-mapes-gestionats-des-del-servidor)
  - [2.16. Objectes](#216-objectes)
  - [2.17. Tipus MIME](#217-tipus-mime)
  - [2.18. Connectors](#218-connectors)
- [3. Organització de codificació i estructuració dels portals](#3-organitzaci%C3%B3-de-codificaci%C3%B3-i-estructuraci%C3%B3-dels-portals)
  - [3.1. Llegibilitat i organització del codi](#31-llegibilitat-i-organitzaci%C3%B3-del-codi)
  - [3.2. Organització dels directoris](#32-organitzaci%C3%B3-dels-directoris)
- [4. Eines d'anàlisi i desenvolupament](#4-eines-dan%C3%A0lisi-i-desenvolupament)
  - [4.1. Eines de desenvolupament dels navegadors](#41-eines-de-desenvolupament-dels-navegadors)
  - [4.2. Instal·lació de *plug-ins* al navegador](#42-installaci%C3%B3-de-plug-ins-al-navegador)

# 1. Introducció HTML5

Les pàgines web contenen informació, normalment procedent del servidor, en format text. Aquest text no solament incorpora els continguts sinó que inclou també **marques** que indiquen com presentar o distribuir aquesta informació dins les finestres del navegador. Per aquest motiu fem servir els anomenats **llenguatges de marques** per a la web. El llenguatge de marques més usat en el món web és el llenguatge HTML (**HyperText Markup Language**).

La web actual es basa en l’estàndard HTML5. L’anterior versió de l’HTML, l’HTML 4.01, és de l’any 1999 i l’àmbit del web ha evolucionat molt des de llavors. L’HTML5 incorpora moltes funcionalitats que en aquell moment no es van tenir en compte: àudios, vídeos, eines de dibuix, validació de formularis, etiquetatge semàntic i molt més.

HTML5 va incorporant noves funcionalitats, a vegades forçades pels mateixos fabricants i els desenvolupadors de navegadors. Per aquest motiu no tots els navegadors implementen totes les funcionalitats a l’instant en què un desenvolupador s’avança; és a dir, les etiquetes que fem servir no sempre es comporten igual segons el navegador amb què obrim els documents.

Un parell de webs que ens informen de l’estat d’implementació d’aquestes funcionalitats en els diferents navegadors són:

[http://html5test.com/](http://html5test.com/)
[http://caniuse.com/](http://caniuse.com/)

Un dels avanços més grans ha estat l’afegiment de noves etiquetes que ajuden a fer la web més eficaç alhora que comprensible, gràcies a l’anomenat **etiquetatge semàntic** (semantic markup) . Si abans es feia servir una etiqueta genèrica com `<div>` per contenir elements molt diversos, ara tenim diverses etiquetes molt més específiques com `<nav>`, `<article>`, `<section>` o `<footer>` entre d’altres, que farien una funció similar però que en anomenar-se d’aquesta manera indiquen la funció que compleixen dins d’un document web. Això no solament ajuda a fer el codi dels documents web més comprensible, sinó alhora ajuda els cercadors d’Internet que facin ús d’aquestes etiquetes per poder filtrar millor les cerques i, per extensió, accedir millor al contingut.

## 1.1. Estructura del document amb HTML5

Qualsevol pàgina (o document) HTML és una colecció d'etiquetes descriptives o *tags* que, excepte alguns casos, s'obren i tanquen. Les etiquetes s'utilitzen per descriure contingut específic tal com imatges, paràgrafs, capçaleres, peus de pàgines i molt més.

El document html comença amb la declaració del tipus de document:  **`<!DOCTYPE html>`**. Aquesta etiqueta es opcional i no cal tancar-la.

Desprès de la declaració, cal incloure l'element arrel **`<html>`**:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Títol de la web</title>
  </head>
  <body>
     <!-- Aquí hi va el contingut de la web -->
  </body>
</html>
```

Tot document HTML té dues seccions principals: la capçalera, indicada mitjançant l’etiqueta **`<head>`**, i el cos del document, marcat amb l’etiqueta **`<body>`**.

## 1.2. Capçalera del document

Consultar: [What’s in the head? Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

La capçalera conté elements que faciliten informació diversa de la pàgina, com ara el títol, l’enllaç amb altres fitxers relacionats amb el document (fulls d’estils, codi JavaScript…) i metainformació del document, entre d’altres.

Una capçalera mínima seria la següent:

```html
<head>
   <meta charset="utf-8" />
   <title>La meva pàgina web</title>
</head>
```

L'etiqueta **`<meta>`** serveix per establir metainformació del document (informació no visible) i té diferents funcions, en aquest cas diem que el nostre document està codificat amb UTF-8.

**charset i codificació del document**
UTF-8 representa la codificació per defecte a HTML5. Es recomana posar-ho sempre per evitar problemes de visualització del document.

Dins de la codificació de l'UTF-8 es fa necesari "escapar" alguns caràcters que podrien interpretar-se de forma incorrecta. Per això s'han de substituir pels equivalents codificats:

" is replaced with \&quot;
& is replaced with \&amp;
< is replaced with \&lt;
\> is replaced with \&gt;


Altres `<meta>` importants per al posicionament SEO de la pàgina són: 

* **`name`** especifica quin tipus de meta element és; la informació que conté.
* **`content`** especifica el contingut.

Ex:

```html
<meta name="author" content="Chris Mills">
<meta name="description" content="The MDN Web Docs Learning Area aims to provide
complete beginners to the Web with all they need to know to get
started with developing web sites and applications.">
```

* **favicon** (*favorite icon*). Icone que es mostra amb el títol de la pàgina o al directori de favorits (*bookmarks*). Requereix una imatge emmagamatzemada al mateix directori del document i afegir la següent línia a la capçalera:
  

```html
<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
```


L'etiqueta **`<title>`** ens serveix per posar el títol de la nostra web. El navegador mostra el contingut d’aquesta marca com a títol de la finestra o de la pestanya on es mostra el document, com es pot veure a la següent figura:

![imatge capçalera](https://i.imgur.com/XdbxBF9.png)

El títol del document també serà la proposta de enllaç a favorits.

* **`<link>`** i **`<script>`**
Dins de HTML5 es fan servir per referenciar arxius de CSS i javascript, respectivament.

```html

<link rel=“stylesheet” href=“estil.css”>


<script src=“funcions.js”></script>
```

# 2. Etiquetes i Atributs

Les etiquetes de HTML serveixen per estructurar tota la informació que ha de contenir l’aplicació. A més a més de les etiquetes que conformen l’estructura d’un document, tenim disponibles una col·lecció d’etiquetes que ens permetran ordenar la informació que tenim al cos de la web, la qual cosa donarà un significat semàntic a cada porció d’informació.

Com a regla general podríem dir que les etiquetes tenen atributs i que segueixen la següent nomenclatura:

  ```html
  <nom_etiqueta nom_atribut_1="valor_atribut"...nom_atribut_N="valor_atribut">Contingut de l'element o etiqueta </nom_etiqueta>
  ```

## 2.1. Etiquetes del cos del document

Per dissenyar la part visible d’un document o plana web, partirem del concepte cos del document (marcat amb l’etiqueta `<body>`) on hem d’incloure tot el contingut de la web, és a dir, la informació que volem que vegi l’usuari final de l’aplicació web, tot i que poden existir minoritàriament elements ocults a l’usuari dins del cos. A l’interior del `<body>` o cos, disposarem de diferents elements que, amb els seus atributs, ens permetran aconseguir aquest objectiu.

```html
    <!doctype html>
    <html>
        <head>
            <meta charset="UTF-8">
            <title>.:: Exemple de document web ::.</title>
        </head>
        <body>
        <!-- Aquí disposarem de les etiquetes i atributs visibles a la web -->
        
        </body>
    </html>
```

### 2.1.1. Tipus d'elements

Els elements HTML5 descendents de l’element `<body>` es poden classificar en dos tipus: els **elements de bloc** (block elements) i els **elements de línia** (inline elements).

<p style="background-color:rgb(230,230,230); padding: 5px" >Els <strong>elements de bloc</strong>, com per exemple els títols, els paràgrafs, les llistes o les taules, els articles, les seccions, etc. són grans estructures que poden contenir altres elements de bloc, elements de línia, o text.</p>

Normalment, el navegador els mostra com a blocs independents i separa un bloc d’un altre amb un salt de línia. Per aquest motiu, si posem a una pàgina un element en bloc, aquest tendeix a expandir-se el màxim permès per la finestra i provoca un salt de línia. Heu de tenir en compte que aquest comportament és modificable, ja que podem forçar la grandària dels elements principalment des de CSS.

<p style="background-color:rgb(230,230,230); padding: 5px" >Els <strong>elements de línia</strong>, com per exemple els enllaços, les citacions o les imatges, són petites estructures que representen o descriuen petits trossos de text o dades. Poden contenir només text o altres elements de línia..</p>

Normalment, el navegador mostra els elements de línia un al costat de l’altre, dins de l’element de bloc que els conté, o al seu defecte dins del document que representa l’etiqueta `<body>`. Podríem dir que un element de línia ocupa l’espai d’allò que conté, però no s’expandeix més enllà.

Si ho comparem amb un processador de textos, podem pensar en un paràgraf com un element de bloc i una paraula emfatitzada, per exemple en negreta, com un element de línia.

## 2.2. Atributs genèrics

Les etiquetes poden tenir atributs que acaben de definir l’element. Hi ha una sèrie d’atributs comuns a la majoria d’elements:

* Atributs globals
* Atributs de llenguatge
* Atributs d’esdeveniment (event)

### 2.2.1. Atributs globals

Els atributs globals són atributs genèrics. Són principalment els següents:

**id**: identifica l’element. No hi poden haver dos elements en un mateix document amb el mateix id.
**class**: serveix per associar un element a una classe. Més d’un element pot ser anomenat amb la mateixa classe. Ens és molt útil a l’hora de definir els estils d’una pàgina, ja que podem especificar característiques comunes a tots els elements que pertanyin a la mateixa classe.
**style**: s’usa per definir l’estil de l’element (normalment farem servir CSS per definir els estils d'un component).
**title**: s’usa per posar un text amb una informació breu de l’element. Molts navegadors mostren aquest text quan es passa per damunt de l’element.

Demo: Tenim un paràgraf que volem identificar amb la cadena descripció, que pertany a la classe important i que volem que en passar-hi per sobre ens aparegui un text amb la frase Aquest paràgraf és molt important.

<p id="descripcio" class="important" title="Aquest paràgraf és molt important"> Si passeu per sobre, us n'adonareu del contingut del títol del paràgraf!</p>

### 2.2.2. Atributs de llenguatge

Els atributs de llenguatge ens especifiquen diferents característiques de la llengua del text contingut a l’element. Són els següents:

**lang**: especifica la llengua del text contingut a l’element.
**dir**: especifica la direcció de lectura de la llengua del text contingut a l’element.
Per saber quins són els codis associats a cada llenguatge podem visitar w3schools

Per establir l’idioma en el qual està escrit tot el document, s’acostuma a posar en l’atribut **lang** de l’etiqueta `<html>`:

Si al document HTML volem indicar que està escrit en català farem el següent:

```html
<html lang="ca">
...
</html> 
```

Igualment amb l’atribut **dir**, podem assignar-li tres possibles valors: **ltr**, **rtl** i **auto**, indicant si l’escriptura és d’esquerra a dreta, de dreta a esquerra o si deixem que el propi navegador detecti de quin tipus és respectivament.

<html dir="ltr">
...
</html>

### 2.2.3. Atributs d'esdeveniment ('event')

Els atributs d’esdeveniment són atributs que associen una acció que es realitzarà quan es produeixi una determinada interacció de l’usuari cap a l’element que té aquest atribut. Aquests atributs són molt útils quan s’usen en combinació amb el llenguatge de programació JavaScript.

La quantitat d’esdeveniments disponibles és força elevada, i des de la versió HTML5 han augmentat significativament. Podem fer-ne una classificació en 8 grups:

**Finestra** (**window events**): relacionats amb tot allò que té a veure amb la finestra. Per exemple quan carreguem un document a la finestra del navegador o quan redimensionem la finestra, entre d’altres.
**Formulari** (**form events**): relacionats amb tots els camps que formin part d’un formulari. Per exemple quan entrem a un camp d’un formulari per començar a escriure o seleccionar/modificar un camp.
**Teclat** (**keyboard events**): relacionats amb el teclat. Per exemple quan cliquem a una tecla o l’alliberem, entre d’altres.
**Ratolí** (**mouse events**): relacionats amb el ratolí. Per exemple, moure’l, passar per sobre d’un element, clicar-lo, etc.
**Portapapers** (**clipboard events**): quan copiem, retallem o enganxem.
**Mèdia** (**media events**): relacionats amb tot el que té a veure amb imatges, vídeo o àudio.
**Tàctils** (**touch events**): tenen a veure amb la interacció d’un usuari amb pantalles tàctils, ja siguin per mòbil, tauleta o qualsevol tipus de pantalles tàctils.
**Miscel·lània** (**altres**): aquesta classificació agrupa aquells esdeveniments que no tenen cabuda a cap dels anteriors, per exemple quan es produeix un **error en carregar un arxiu extern al document**, si aquest hi fa referència.

Alguns dels més importants són els següents:

*onclick*: l’acció es produirà quan es faci un clic amb el ratolí damunt de l’element.
*ondblclick*: l’acció es produirà quan es faci doble clic amb el ratolí.
*onmousedown*: l’acció es produirà quan es premi el botó del ratolí.
*onmouseup*: l’acció es produirà quan es deixi de prémer el botó del ratolí.
*onmouseover*: l’acció es produirà quan estiguem amb el ratolí fora d’un element i el moguem de manera que passem a estar damunt de l’element.
*onmousemove*: l’acció es produirà quan es mogui el ratolí per damunt de l’element.
*onmouseout*: l’acció es produirà quan estiguem amb el ratolí damunt d’un element i el moguem de manera que deixem d’estar-hi al damunt.
onkeypress: l’acció es produirà quan es premi una tecla i es deixi anar damunt de l’element.
*onkeydown*: l’acció es produirà quan es premi una tecla damunt de l’element.
*onkeyup*: l’acció es produirà quan es deixi anar una tecla damunt de l’element.
*ondrag*: l’acció es produirà quan un element sigui arrossegat.
*ondragend*: quan un element hagi finalitzat el procés d’arrossegament.
*ondragstart*: quan un element comenci el procés d’arrossegament.
*ondrop*: quan un element arrossegat sigui alliberat.
*onload*: quan hagi finalitzat la càrrega d’una pàgina.
etc.

Per veure un llistat ordenat segons els tipus i quantitat d’esdeveniments disponibles podeu visitar w3schools

Exemple de esdeveniment *onclick*: 

`<p onclick="obreFinestra()">Aquest és un paràgraf que ens permet obrir una finestra</p>`

Hem d’interpretar que quan es faci un clic damunt d’aquest paràgraf, s’executarà una funció que, segons el seu nom, provocarà l’obertura d’una finestra.

## 2.3. Etiquetes de text

Marcar el text del document vol dir diferenciar les parts d’aquest text per tal de denotar-ne la major o menor importància, aclarir si una part de text és una citació, si hi volem fer més o menys èmfasi…

A continuació es detalla un resum de les etiquetes de text més importants:

Etiquetes corresponents a elements de bloc:

```html
<h1>, <h2>, <h3>, <h4>, <h5>, <h6>: encapçalaments. El número denota el nivell de l’encapçalament, és a dir <h1> és l’encapçalament de primer nivell i <h6> l’encapçalament d’últim nivell.
<p>: paràgraf.
<br />: salt de línia.
<hr />: línia separadora.
<blockquote>: citació de tipus bloc.
<pre>: text preformatat.
<div>: capa. Es tracta d’una etiqueta de tipus bloc sense significat semàntic que ens servirà per agrupar text i/o d’altres elements.
<header>: encapçalament, no lligat a cap format i amb una clara orientació semàntica.
<aside>: element de bloc, que es posiciona al voltant normalment d’un altre.
<footer>: posicionat normalment al final de les pàgines.
<article>: determina que el contingut és un article, independentment dels elements continguts.
<section>: marca una secció.
Etiquetes corresponents a elements de línia:
<em>: text amb èmfasi.
<strong>: text amb molt èmfasi.
<q>: citació de tipus línia.
<cite>: font de la citació.
<abbr>: abreviació.
<code>: codi de programació.
<samp>: sortida d’un programa.
<kbd>: text introduït per un usuari.
<var>: variable o paràmetre d’un programa.
<span>: etiqueta de tipus línia sense significat semàntic que ens servirà per agrupar text i/o d’altres elements.
```

### 2.3.1. Paràgrafs

Entenem per paràgraf un conjunt de frases que estan relacionades entre si. Els paràgrafs són elements de tipus bloc i l’etiqueta que s’usa és l’etiqueta **`<p>`**.

Si, per exemple, tenim un paràgraf que ens explica què és el llenguatge HTML5, el marquem de la manera següent:

```html
<p>HTML5 (acrònim Hyper Text Markup Language versió 5) és el llenguatge d'etiquetes que fem servir a l'actualitat per l'elaboració de pàgines web, interpretables pels navegadors.</p>
```

### 2.3.2. Els encapçalaments

Els llenguatges d’etiquetes (X)HTML ens permeten crear sis nivells d’encapçalament amb les etiquetes `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>` i `<h6>`. Tots aquests elements són de tipus bloc. L’objectiu del seus ús és la classificació dels continguts en títol o subtítols, o simplement la creació de diferents nivells de titulars.

A continuació veiem un fragment d’un document HTML5 en què ens expliquen diverses característiques d’aquest llenguatge d’etiquetes. Fixem-nos en les etiquetes d’encapçalament:

<iframe height="265" style="width: 100%;" scrolling="no" title="capçaleres i pàragrafs" src="http://codepen.io/rglepe/embed/gEbOmr/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">  See the Pen <a href='https://codepen.io/rglepe/pen/gEbOmr/'>capçaleres i pàragrafs</a> by Raul Garcia  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

### 2.3.3. Èmfasi

Quan volem posar èmfasi a una part de text perquè volem destacar-ne la importància, tenim a la nostra disposició dues etiquetes. L’etiqueta `<em>` serveix per donar èmfasi i l’etiqueta `<strong>` per donar molt d’èmfasi.

Al següent paràgraf volem destacar algunes paraules, amb lletra negreta:

<iframe height="265" style="width: 100%;" scrolling="no" title="èmfasi" src="http://codepen.io/rglepe/embed/JzorVZ/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/JzorVZ/'>èmfasi</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

### 2.3.4. Citacions

Quan volem fer referència a un text que no hem escrit nosaltres hem de fer servir les citacions. Tenim tres etiquetes diferents per descriure-les: `<blockquote>`, `<q>` i `<cite>`. El seu ús el podeu veure a la següent llista:

`<blockquote>`, si la citació és tot un paràgraf.
`<q>`, si la citació és enmig d’un element de bloc (per exemple, dins d’un paràgraf).
`<cite>`, ens serveix per marcar l’origen de la citació (l’autor de la citació, el títol…).
Posem un exemple d’ús d’aquestes etiquetes. Imaginem que estem fent un lloc web on volem posar una citació de l’escriptor Manuel de Pedrolo:

https://codepen.io/rglepe/pen/drPZPa/

<iframe height="265" style="width: 100%;" scrolling="no" title="citacions" src="http://codepen.io/rglepe/embed/drPZPa/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">   See the Pen <a href='https://codepen.io/rglepe/pen/drPZPa/'>citacions</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Cal destacar que dins l’etiqueta `<blockquote>` no podem escriure text directament sinó que hem d’afegir una altra etiqueta de bloc (`<p>`, `<div>`…).

### 2.3.5. Abreviatures

Si en un text trobem una abreviatura també tenim l’etiqueta adequada per assenyalar-la que és `<abbr>`. Posem un exemple d’ús:

<iframe height="265" style="width: 100%;" scrolling="no" title="abreviatures" src="http://codepen.io/rglepe/embed/pYvdwd/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true"> See the Pen <a href='https://codepen.io/rglepe/pen/pYvdwd/'>abreviatures</a> by Raul Garcia (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

### 2.3.6. Text preformatat

Si volem posar un fragment de text tal com està escrit en el fitxer de text HTML, hem d’usar l’etiqueta `<pre>` que ens indica que aquell fragment de text està preformatat. Aquesta etiqueta fa que tot allò que hi estigui contingut aparegui exactament igual en el navegador. És a dir, es respecten els espais, els salts de línia, etc.

Vegem, com a exemple, una estructura de directoris “dibuixada” mitjançant caràcters. El codi és el següent:

<iframe height="265" style="width: 100%;" scrolling="no" title="text preformatat" src="http://codepen.io/rglepe/embed/rRaYYr/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/rRaYYr/'>text preformatat</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

### 2.3.7. Codi de programació

Si en una pàgina web volem incloure codi de programació, tenim diverses etiquetes que ens ajuden a formatar aquest codi. A continuació s’exposen aquestes etiquetes i l’ús que tenen:

`<code>`: ens serveix per marcar codi de programació en si.
`<samp>`: serveix per posar el text obtingut en la sortida d’un programa.
`<kbd>`: s’usa per dir a l’usuari què ha de teclejar.
`<var>`: serveix per marcar variables o paràmetres de programes.
Tots aquests elements són elements de línia.

En les línies de codi següents, que són un exemple de codificació amb JavaScript, podem veure com es poden usar les etiquetes descrites:

<iframe height="265" style="width: 100%;" scrolling="no" title="codi programació" src="http://codepen.io/rglepe/embed/oVgoqK/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/oVgoqK/'>codi programació</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

## 2.4. Etiquetes sense atributs semàntics

Hi ha dues etiquetes que no tenen un significat semàntic concret. Això ens serveix per delimitar un tros de text o dades que no s’adeqüen a cap de les etiquetes existents.

Per crear un element de bloc genèric usem l’etiqueta **`<div>`** i per crear un element de línia genèric usem l’etiqueta **`<span>`**.

L’etiqueta **`<div>`** ha estat, i és, especialment útil a vegades per maquetar o fer el layout d’un document, és a dir, crear àrees d’agrupacions de contingut per donar-li estructura a un document o bé una estètica concreta amb l’ajuda de CSS a tota l’agrupació.

Actualment `<div>` és fa servir moltíssim, però altres etiquetes d’HTML5 han substituït part del seu ús, amb funcions similars a la que afegeixen una orientació semàntica al contingut. Aquestes etiquetes les veurem detalladament en altres apartats, però un exemple il·lustratiu seria per exemple l’etiqueta `<footer>`, que serveix per crear el peu del document, ja que és un element bloc com el `<div>`, però ens informa alhora que la ubicació d’aquest bloc és a la part inferior de la pàgina.

També heu de pensar que pels cercadors de contingut (Google, Yahoo, etc.) aquesta informació semàntica és molt útil per filtrar contingut.

En l’exemple següent observem l’ús de l’etiqueta <div> per a la creació de diverses capes ubicades a diferents àrees del document visible per l’usuari: la capçalera, la barra lateral, el cos de la web i el peu de pàgina.

```html
<div id="capcalera">
<!--  contingut de la capçalera  (logo, títol, navegació interna...)-->
</div>
 
<div id="lateral">
<!-- contingut del menú lateral (enllaços d'interès, informació...) -->
</div>
 
<div id="contingut">
<!-- contingut (el contingut de la pàgina) -->
</div>
 
<div id="peu">
<!--  contingut del peu de pàgina  (informació sobre drets d'autoria, crèdits, aspectes 
legals)-->
</div>
```

Heu de pensar que gràcies a aquesta estructura, un cop haguem incorporat l’ús de CSS, podrem maquetar la pàgina web al nostre gust, però és molt aconsellable no assignar noms als id’s que indiquin una posició exacta, ja que actualment les pàgines modifiquen les posicions dels blocs en funció de la pantalla amb la qual les consultem, és a dir, no és el mateix un disseny per veure amb mòbil, o amb una tauleta, o amb un ordinador; és el que s’anomena disseny adaptatiu o responsive web design (RWD) en anglès.

## 2.5. Etiquetes estructurals

Moltes pàgines web disposen d’una estructura similar o tenen àrees molt diferenciades: tenen una **capçalera**, un **menú de navegació**, un **cos** on va el gruix de la informació, **articles**, **seccions** amb informació concreta i un **peu de pàgina**. Així doncs, quan maquetem una web podem dividir-la en diferents seccions. A més, moltes webs estan conformades principalment d’articles com, per exemple, els blogs, els diaris o portals d’informació.

HTML5 inclou diverses etiquetes que solucionen aquest problema. Les veiem llistades a continuació:

* **`<main>`**: contingut principal del document. Aquest contingut ha de ser exclusiu del document, no s'hauria de repetir a la resta del document.
* **`<section>`**: secció genèrica del document que agrupa contingut similar.
* **`<header>`**: capçalera d’un document o secció.
* **`<footer>`**: peu d’un document o secció.
* **`<nav>`**: un bloc de navegació.
* **`<article>`**: especifica un article: una notícia, article d’un blog… Se suposa que pot ser distribuït de manera independent, per exemple per a la sindicació de continguts.
* **`<aside>`**: relacionat amb una àrea que envolta altre contingut d’un mateix element contenidor.

A continuació es pot veure un exemple de maquetació d’una web amb dues columnes, capçalera, peu de pàgina, barra de navegació i uns quants articles.

Vegem primer com es podria fer amb HTML5 i divs:
```html
<!DOCTYPE html>
<head>
   <title>Títol de la web</title>
   <meta charset=utf-8">
</head>
<body>
   <div id="cap">
    ...
   </div>
   <div id="menu">
   ...
   </div>
   <div id="lateral">
   ...
   </div>
   <div id="cos">
      <div id="article1">
      ...
      </div>
      <div id="article2">
      ...
      </div>
    </div>
    <div id="peu">
      ...
    </div>
</body>
</html>
```

Vegem ara com podríem codificar aquest mateix document usant algunes les etiquetes estructurals d’HTML5:

```html
<!DOCTYPE html>
<head>
   <meta charset=utf-8">
   <title>Títol de la web</title>
</head>
<body>
   <header>
   ...
   </header>
   <nav>
   ...
   </nav>
   <aside>
   ...
   </aside>
   <section>
      <article>
      ...
      </article>
      <article>
      ...
      </article>
   </section>
   <footer>
   ...
   </footer> 
</body>
</html>
```

## 2.6. Enllaços

L’etiqueta que té HTML per crear hiperenllaços és l’etiqueta `<a>`. Els elements `<a>` són elements de línia, ja que podem posar enllaços envoltats de text.

Per indicar quin és el destí del nostre enllaç usem l’atribut ***href***. També és convenient usar l’atribut genèric de tipus global ***title*** per posar una breu descripció de l’enllaç.

### 2.6.1. Enllaços a pàgines externes

Si volem fer un enllaç a una pàgina externa a la nostra aplicació web hem de saber l’URL complet del document al qual volem fer l’enllaç.

Imaginem que volem fer un enllaç a un article que es pot trobar a l’URL *http://www.creativebloq.com/web-design/10-top-html5-resources-413919*, però que el text que volem que aparegui en el navegador és simplement “Recursos HTML5”. El codi que hem d’introduir és el següent:

```html

<p><a href="http://www.creativebloq.com/web-design/10-top-html5-resources-413919" title="Article HTML 5">Recursos HTML5
5</a></p>
```

La majoria de navegadors ens mostraran l’enllaç anterior de color blau i subratllat. A més, quan ens hi posem a sobre apareixerà el text que haguem posat en l’atribut title.

### 2.6.2. Enllaços a pàgines locals

Si l’enllaç que volem fer està dirigit a un document HTML local, és a dir, a un document que pertany a la mateixa aplicació web, posem, com a valor de l’atribut href, el camí relatiu al fitxer al qual volem fer l’enllaç.

Com a exemple, imaginem que estem codificant un fitxer de nom index.html, que és la pàgina d’inici del portal o aplicació, en el qual tenim un menú amb diferents enllaços que van a les diferents seccions del lloc web. Aquí teniu el fragment de codi del fitxer index.html:

<iframe height="265" style="width: 100%;" scrolling="no" title="enllaços" src="http://codepen.io/rglepe/embed/BbyxPV/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">   See the Pen <a href='https://codepen.io/rglepe/pen/BbyxPV/'>enllaços</a> by Raul Garcia (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

En aquest exemple estem suposant que els fitxers de l’aplicació estan organitzats amb la següent estructura de directoris:

<pre>
|--web
    |--seccions
    |    |--fotos.html
    |    |--activitats.html
    |    |--projectes.html
    |
    |--index.html
    |--contacte.html
</pre>

### 2.6.3. Àncores

Alguns documents HTML són molt extensos i ens pot interessar navegar dins la mateixa pàgina. Per poder fer això hem de fer servir l’atribut global id de les etiquetes per forçar els punts on volem anar, i posteriorment crear enllaços que hi apuntin, que posicionaran la pàgina en el lloc concret quan hi cliquem.

Els punts on volem anar s’anomenen **àncores**. Si, per exemple, volem fer una àncora a un element `<h2>` hem d’escriure el codi següent:

`<h2 id="seccio1">Secció 1</h2>`

Un cop tenim feta l’àncora, hi podem enllaçar des de qualsevol punt del text fent un enllaç a l’àncora. Els enllaços a àncores es caracteritzen perquè el destí es denota amb el valor de l’atribut id de l’element al qual volem enllaçar precedit del caràcter #. Si volem enllaçar a l’àncora creada en l’exemple anterior, escriurem el codi següent:

`<a href="#seccio1" title="Secció 1">Anar a la secció 1</a>`

Imaginem ara un text molt llarg amb diferents seccions. Per tenir una bona navegabilitat podem crear un petit índex a l’inici del document que tingui enllaços cap a les diferents parts del document. A més, també podem fer enllaços que ens condueixin a l’inici del document:

```html
<h1 id="dalt">Seccions</h1>
 
<div id="menu"> 
   <a href="#seccio1" title="Secció 1">Anar a la secció 1</a> 
   <a href="#seccio2" title="Secció 2">Anar a la secció 2</a> 
   <a href="#seccio3" title="Secció 3">Anar a la secció 3</a>
</div>
 
<h2 id="seccio1">Secció 1</h2>
<p>...</p>
<p><a href="#dalt" title="A dalt">Anar a dalt</a></p>
 
<h2 id="seccio2">Secció 2</h2>
<p>...</p>
<p><a href="#dalt" title="A dalt">Anar a dalt</a></p>
 
<h2 id="seccio3">Secció 3</h2>
<p>...</p>
<p><a href="#dalt" title="A dalt">Anar a dalt</a></p>
Si el que volem és enllaçar a una àncora des d’un altre document podem fer el següent:

<a href="seccions.html#seccio1" title="Secció 1">Anar a la secció 1</a>
```

## 2.7. Imatges

Les imatges són un recurs molt utilitzat en el desenvolupament web. A part de fer més atractiva la nostra aplicació, ens permeten donar informació d’una manera visual.

Tot i això, hem de vigilar de no abusar de posar massa imatges: hem d’anar amb cura tant amb el nombre d’imatges, com amb el pes i mida d’aquestes imatges.

El pes d’aquestes imatges pot fer que la navegació per la nostra aplicació sigui massa lenta, ja que s’ha de descarregar al navegador per tal que sigui visible. Per aquest motiu es recomana:

* Fer servir imatges comprimides amb JPEG, PNG, GIF, etc. per tal de reduir els temps de descàrrega.
* Ajustar la grandària de les imatges per tal que s’ajusti a la pàgina prèviament a introduir-les a la maquetació, i evitar fer servir els seus atributs (`width` o `height`) per reduir-ne la grandària.

L’etiqueta que ens serveix per inserir una imatge és l’etiqueta `<img>`. Es tracta d’un element de línia que no té etiqueta de tancament: es tanca en ella mateixa.

L’atribut **`src`** ens servirà per dir on està ubicada la imatge: podem posar un URL extern o el camí del fitxer, si disposem de la imatge localment. També usarem l’atribut `alt`, que ens servirà per posar un text alternatiu, en el cas que el navegador no pogués mostrar o accedir a la nostra imatge. Aquest atribut també és útil pels screen readers, és a dir, software llegeix les planes web i les textualitza per tal de ser escoltades per persones amb dèficit visual.

Si, per exemple, volem inserir una imatge que tenim al directori de nom imatges que es diu logo.png i, si no es pot visualitzar aquesta imatge, volem que surti el text “Logo de la web”, hem d’escriure el codi següent:

```html
<img src="imatges/logo.png" alt="Logo de la web" />
```

En el cas que vulguem que una imatge sigui un enllaç, haurem d’enviar correctament les etiquetes `<a>` i `<img>`. Per exemple, si volem incorporar el logotip del W3C per destacar que la nostra pàgina ha passat el nivell de conformitat d’accessibilitat AA i, a més, volem enllaçar aquesta imatge cap al validador en línia que ens ofereix el W3C (i així mostrar que realment el nostre document és vàlid),

```html
<a href="http://www.w3.org/WAI/WCAG2AA-Conformance" title="Explanation of WCAG 2.0 Level Double-A Conformance">
 <img height="32" width="88" 
 src="http://www.w3.org/WAI/wcag2AA"
 alt="Level Double-A conformance, 
 W3C WAI Web Content Accessibility Guidelines 2.0">
</a>
```


## 2.8. Panell de dibuix o llenç

HTML5 incorpora una etiqueta que ha revolucionat el món web: es tracta de l’etiqueta `<canvas>`. Aquesta etiqueta defineix un panell de dibuix o llenç. Si la combinem amb l’ús del llenguatge de programació JavaScript, es poden aconseguir efectes fascinants, tant dibuixant com animant. 

Vegem un exemple, usant una mica de JavaScript:

<iframe height="400" style="width: 100%;" scrolling="no" title="canvas" src="http://codepen.io/rglepe/embed/ywyENy/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true"> See the Pen <a href='https://codepen.io/rglepe/pen/ywyENy/'>canvas</a> by Raul Garcia (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

## 2.9. Àudio

Per reproduir so usarem l’etiqueta `<audio>`, que permet la reproducció de fitxers de so, i que tenim disponible exclusivament a HTML5. Els atributs més rellevants són:

`autoplay`: si l’activem posant autoplay=“autoplay”, el so començarà a sonar un cop el fitxer s’hagi carregat.
`controls`: si l’activem posant controls=“controls”, es mostraran uns controladors a l’usuari (per engegar l’àudio, pausar-lo, canviar el volum…)
`loop`: si l’activem posant loop=“loop”, un cop acabat de reproduir el so, tornarà a començar.
`src`: especifica on és el fitxer d’àudio que volem reproduir. Si volem que el navegador tingui diverses alternatives, és millor usar l’etiqueta `<source>`, que anirà dins de l’etiqueta `<audio>`.
L’etiqueta `<source>` s’insereix dins l’etiqueta `<audio>` i ens serveix per donar diverses alternatives de format de fitxer al navegador, ja que no tots els navegadors suporten tots els formats. Així, si el navegador no suporta un format d’àudio, en podrà escollir un altre. A la següent taula es mostren les compatibilitats per diversos navegadors i formats d’àudio.

Taula de compatibilitats navegadors i formats d’àudio

Navegador|	MP3|	Wav|	Ogg|
---|---|---|---|
Firefox|	Suportat|	Suportat|	Suportat
Chrome|	Suportat|	Suportat|	Suportat|
Opera|	Suportat|	Suportat|	Suportat|
Safari|	Suportat|	Suportat|	No suportat|
Internet Explorer|	Suportat|	No suportat|	No suportat

Per convertir formats d’àudio i fins i tot manipular àudio, existeix programari exclusiu. Un dels més estesos és Audacity.

Imaginem que volem reproduir un enregistrament d’àudio en una web en format .ogg. Per si el navegador de l’usuari no pot reproduir ”.ogg”, volem oferir també el format ”.mp3” . A més, volem que l’enregistrament es reprodueixi indefinidament i volem que l’usuari disposi dels controls per pausar o posar en marxa l’àudio. Si els fitxers són enregistrament_audio.ogg i enregistrament_audio.mp3, el codi seria el següent:

<iframe height="265" style="width: 100%;" scrolling="no" title="audio" src="http://codepen.io/rglepe/embed/rRaKKm/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">   See the Pen <a href='https://codepen.io/rglepe/pen/rRaKKm/'>audio</a> by Raul Garcia (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

En aquest cas, el navegador intentaria reproduir el fitxer enregistrament_audio.ogg i si no pogués reproduiria enregistrament_audio.mp3. Si no suportés aquesta etiqueta donaria el missatge d’error a l’usuari.

Igualment l’etiqueta `<audio>` es pot combinar amb codi JavaScript per tenir un millor control i donar-li molts més usos, per exemple a l’hora de fer llistes de reproducció o jocs.

## 2.10. Vídeo

De la mateixa manera que amb l’àudio, tenim l’etiqueta `<video>`, per reproduir vídeo en HTML5. Els atributs més rellevants són:

`autoplay`: si l’activem posant autoplay=“autoplay”, el vídeo es començarà a reproduir un cop s’hagi carregat.
`controls`: si l’activem posant controls=“controls”, es mostraran uns controladors a l’usuari (per començar a reproduir el vídeo, pausar-lo, canviar el volum…)
`loop`: si l’activem posant loop=“loop”, un cop acabat de reproduir el vídeo, tornarà a començar.
`src`: especifica on és el fitxer de vídeo que volem reproduir. Si volem que el navegador tingui diverses alternatives, és millor usar l’etiqueta `<source>`, que anirà dins de l’etiqueta `<video>`.
`height` i `witdh`: especifiquen respectivament l’alçada i l’amplada en píxels del reproductor de vídeo.
`muted`: si l’activem posant `muted=“muted”`, el vídeo no tindrà so.
`poster`: serveix per posar la URL d’una imatge mentre el vídeo es descarrega o fins que l’usuari premi el botó d’inici de reproducció.

L’etiqueta `<source>` actua igual que en l’etiqueta `<audio>`: s’insereix dins l’etiqueta `<video>` per tal de donar diverses alternatives de format al navegador, ja que no tots els navegadors són capaços de reproduir tots els formats de vídeo disponibles. A la taula Taula2.2 teniu una llista de compatibilitats:

Taula de compatibilitats navegadors i formats de vídeo:

Navegador|	MP4|	WebM|	Ogg|
---|---|---|---|
Firefox|	Darreres versions|	Suportat|	Suportat
Chrome|	Suportat|	Suportat|	Suportat
Opera|	Darreres versions|	Suportat|	Suportat
Safari|	Suportat|	No suportat|	No suportat|
Internet Explorer|	Suportat|	No suportat|	No suportat

Vegem un exemple d’inserció d’un vídeo amb aquesta etiqueta:

<iframe height="265" style="width: 100%;" scrolling="no" title="video" src="http://codepen.io/rglepe/embed/OqPEdL/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/OqPEdL/'>video</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

## 2.11. Llistes

Les llistes són el recurs que ens serveix per fer una enumeració. Hi ha tres tipus de llista: les llistes ordenades, les llistes desordenades i les llistes de definició.

Tot i que inicialment, les llistes ordenades `<ol>` i desordenades `<ul>` són molt diferenciades, des de CSS podem modificar l’estètica i arribar a obtenir el mateix aspecte.

### 2.11.1. Llistes ordenades
Les llistes ordenades són les llistes en què necessitem que els elements estiguin numerats. Per marcar l’inici i el final de la llista usem l’etiqueta `<ol>` (ordered list) i per marcar cada element de la llista usem l’etiqueta `<li>` (list item).

Imaginem que estem fent una recepta de cuina i volem enumerar els passos que hem de seguir. El codi seria el següent:

<iframe height="265" style="width: 100%;" scrolling="no" title="llista-ordenada" src="http://codepen.io/rglepe/embed/ywyErg/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/ywyErg/'>llista-ordenada</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

### 2.11.2. Llistes desordenades

Les llistes desordenades són les llistes en què no necessitem que els elements estiguin numerats, és a dir, no cal tenir en compte l’ordre de l’enumeració. Per marcar l’inici i el final de la llista usem l’etiqueta `<ul>` (unordered list) i per marcar cada element de la llista usem l’etiqueta `<li>` (list item).

Si, per exemple, volem llistar tots els ingredients necessaris per fer una truita a la francesa, ho codifiquem de la manera següent:

<iframe height="265" style="width: 100%;" scrolling="no" title="llista-desordenada" src="http://codepen.io/rglepe/embed/Wmbyqw/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/Wmbyqw/'>llista-desordenada</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

### 2.11.3. Llistes de definició

Les llistes de definició es caracteritzen per ser una enumeració de definicions de termes. Per tant, els ítems de les llistes de definició estan formats per dos elements: el terme i la definició d’aquest terme. Per marcar l’inici i el final de la llista usem l’etiqueta `<dl>` (definition list); per a cadascun dels termes s’usa l’etiqueta `<dt>` (definition term), i per a cadascuna de les definicions s’usa l’etiqueta `<dd>` (definition description).

Si per exemple volguéssim definir els termes HTML, CSS i JavaScript, podem usar aquest tipus de llistes, que es visualitzen com mostra la figura Figure16.16.

<iframe height="265" style="width: 100%;" scrolling="no" title="llista-definició" src="http://codepen.io/rglepe/embed/vPEroM/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/vPEroM/'>llista-definició</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

### 2.11.4. Enniuament de llistes

Si volem fer llistes complexes, és a dir, inserir llistes dins d’altres llistes, també podem fer-ho. Només hem de vigilar d’obrir i tancar les etiquetes correctament: si volem encapsular una llista, ja sigui numerada o no numerada. Aquesta llista ha de ser dins d’un ítem (`<li>`) de la llista mare.

Com a exemple, podem pensar els passos per la realització d’un disseny web de l’entorn client:

```html
<h1>Fases en la realització d'un disseny web.</h1>
 <ol>
 <li>Realització de l'esbós.</li>
 <li>Realització del prototip.
  <ol>
   <li>Escollir eines de disseny.
    <ul>
     <li>Eina de creació tipogràfica</li>
     <li>Eina de creació de l'esquema de colors</li>
     <li>Eina de dibuix</li>
    </ul>
   </li>
   <li>Creació de la guia d'estil.</li>
  </ol>  
 </li>
 <li>Realització del layout.
  <ul>
   <li>Elecció llenguatges.</li>
   <li>Proves a diferents navegadors.</li>
   <li>Proves a diferents resolucions.</li>
  </ul>
 </li>
 <li>Entrega de les plantilles al client.</li>
</ol>
```

## 2.12. Taules

Les taules són un recurs que ens permet mostrar informació tabulada en files i columnes.

Antigament molts llocs web feien servir les taules per maquetar la seva estructura, és a dir, si per exemple, la web té un menú lateral i un cos, es codifica una taula de dues columnes i es posa el contingut de la web en les cel·les d’aquesta taula. Actualment no és treballa així, i hem d’evitar aquesta pràctica, ja que complica el codi innecessàriament, i dóna poca flexibilitat a l’hora de redistribuir columnes en dissenys per mòbils o tauletes, és a dir, no es pot fer una web adaptativa.

Per maquetar actualment hem de fer ús dels elements `<div>` conjuntament amb fulls d’estils CSS, o elements estructurals i semàntics com ja hem vist a apartats anteriors. Podem usar etiquetes com ara, `<header>`, `<footer>`, `<section>`, `<aside>`, etc.

L’ús de taules té molta utilitat quan és per presentar informació tal com ho faríem amb full de càlcul; taules que acompanyen informació estadística, llistes de resultats, llistats comparatius, enumeració tabulada, etc.

Hem de restringir, doncs, l’ús de les taules a la informació tabular. A continuació, enumerem les etiquetes bàsiques per fer taules:

`<table>`: estableix on comença i on acaba una taula. Els seus atributs són:
`summary`: petit resum del propòsit de la taula.
`width`: amplada de la taula.
`border`: indica la mida de la vora de la taula.
`cellpadding`: indica l’espai entre les vores de la cel·la fins al contingut de la cel·la.
`cellspacing`: indica l’espai entre cel·les.
`<caption>`: títol associat a la taula.
`<tr>`: estableix on comencen i acaben cadascuna de les files d’una taula. Els seus atributs són:
`align`: alineació horitzontal.
`valign`: alineació vertical.
`<td>`: estableix on comencen i acaben cadascuna de les cel·les d’una fila. Els seus atributs són:
`rowspan`: nombre de files d’expansió.
`colspan`: nombre de columnes d’expansió.
`<th>`: cel·la de capçalera. Té els mateixos atributs que l’etiqueta <td>.
`<thead>`: ens permet agrupar les diferents files de la taula que formen la capçalera d’aquesta taula. Els seus atributs són:
`align`: alineació horitzontal.
`valign`: alineació vertical.
`<tfoot>`: ens permet agrupar les diferents files de la taula que en formen el peu. Té els mateixos atributs que l’etiqueta `<thead>`.
`<tbody>`: ens permet fer diferents agrupacions de files de la taula. Té els mateixos atributs que l’etiqueta `<thead>`.
Per crear una taula, hem de marcar l’inici i el final amb l’etiqueta `<table>`. Dins d’aquest element hem de posar tants elements `<tr>` com files tingui la taula. Finalment, dins de cada element `<tr>` hem de posar tants elements `<td>` com columnes tingui la taula. Si les cel·les són cel·les de capçalera, és a dir, tenen certa rellevància, en lloc de posar l’etiqueta `<td>` posem l’etiqueta `<th>`.

### 2.12.1. Grups de columnes

Igual que podem fer agrupacions de files d’una taula, també es poden agrupar les columnes d’una taula usant les etiquetes `<colgroup>` i `<col>`. Podeu trobar més informació de com fer-ho a `http://www.w3.org/TR/html401/struct/tables.html#h-11.2.4`

De vegades voldrem agrupar les files en grups, per denotar quines files formen la capçalera de la taula, quines el peu i si hi ha diferents agrupacions en les files que conformen el cos de la taula. Per tal de fer això, usem les etiquetes `<thead>`, `<tfoot>` i `<tbody>`, respectivament.

Imaginem que volem fer una taula de 7 files i 2 columnes. La primera fila és la capçalera de la taula; les cinc següents conformen el cos de la taula, i l’última és el peu. Tindrem el codi següent:

<iframe height="265" style="width: 100%;" scrolling="no" title="taula simple" src="http://codepen.io/rglepe/embed/aMzjZj/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/aMzjZj/'>taula simple</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Observem que, en el codi, la fila que fa de peu de taula es pot escriure abans que les que fan de cos, ja que el navegador ja sap que és el peu, atès que està marcat amb l’etiqueta `<tfoot>`.

### 2.12.2. Expansió de files i columnes

Les taules simples ens permeten fer una quadrícula de x files i y columnes, però ens podem trobar amb la necessitat de voler fusionar cel·les tan horitzontalment com verticalment. Per aconseguir aquest objectiu l’etiqueta `<td>` disposa de dos atributs: `colspan` i `rowspan`.

L’atribut `colspan` serveix per fusionar dues o més cel·les horitzontalment. L’atribut es posa a la cel·la que ha d’ocupar més d’una columna i se li dóna com a valor el nombre de columnes que ha d’ocupar.

L’atribut `rowspan` serveix per fusionar dues o més cel·les verticalment. L’atribut es posa a la cel·la que ha d’ocupar més d’una fila i se li dóna com a valor el nombre de files que ha d’ocupar.

Veiem el següent exemple amb un horari escolar:

<iframe height="265" style="width: 100%;" scrolling="no" title="taula complexa" src="http://codepen.io/rglepe/embed/YgPjpo/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/YgPjpo/'>taula complexa</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

## 2.13. Formularis

Els formularis web ens serveixen per interactuar amb l’usuari i perquè aquest usuari ens pugui transmetre informació. Aquesta informació es pot processar de diferents maneres, segons les necessitats de l’aplicació web.

Tècnicament, un formulari no és altra cosa que un fragment de codi HTML que conté uns elements característics anomenats controls o camps. Tenim diversos tipus de control: camps de text, camps de contrasenya, botons d’opció (radio buttons), caselles de verificació (checkbox), camps per introduir fitxers, llistes de selecció, àrees de text i botons. En la següent figura es pot veure un exemple de formulari amb part d’aquests controls:

![formulari-bàsic](https://imgur.com/d17wjSF.jpg)

El tipus d’elements que es mostren a la figura es corresponen amb:

1. Camps de tipus text
2. Camps de tipus password
3. Camp de tipus email
4. Llista de selecció
5. Botons d’opcions
6. Camp de tipus file
7. Caselles de verificació
8. Àrea de text
9. Botons de tipus submit i reset de formulari

Cadascun dels controls d’un formulari ha de tenir l’atribut name, amb el qual s’identifica la dada que es vol enviar.

Posem un exemple: tenim un camp de text l’objectiu del qual és que l’usuari introdueixi el seu nom i suposem que l’usuari introdueix “Pau”. Si el valor de l’atribut name del camp de text és nom (name=“nom”), la informació que s’enviarà és nom=Pau. Fixem-nos en el codi d’aquest formulari:

<iframe height="265" style="width: 100%;" scrolling="no" title="formulari" src="http://codepen.io/rglepe/embed/moJVpw/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">  See the Pen <a href='https://codepen.io/rglepe/pen/moJVpw/'>formulari</a> by Raul Garcia  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Des de l’aparició d’HTML5 el número de tipus de camps es va incrementar significativament, tot i que no tots els navegadors els suporten tots. Per veure el seu comportament disposem de planes informatives, on s’indica el tipus de camp i la versió a partir de la qual el navegador l’ha va integrar si és el cas.

[http://html5test.com/](http://html5test.com/)
[http://caniuse.com/](http://caniuse.com/)

### 2.13.1. Propietats d'un formulari

Tota agrupació de camps d’un formulari va emmarcada dins l’etiqueta `<form>`. Hem de tenir en compte que podem disposar de més d’un formulari per pàgina i que cada formulari tindrà els seus camps i que a l’hora d’enviar igualment cada formulari indicarà qui serà qui processi la informació. L’etiqueta `<form>` té diferents atributs, que ens serveixen per dir com volem trametre la informació que omple l’usuari. A continuació s’enumeren cadascun d’aquests atributs:

* `action`: el valor d’aquest atribut és el destí on ha d’anar a parar la informació que l’usuari ha posat en el formulari. Normalment és un URL amb l’script o programa que ha de processar les dades del formulari, però també podem fer que la informació es dirigeixi a una adreça de correu electrònic.
* `name`: indica el nom que té el formulari, i n’és una referència unívoca.
* `method`: ens permet dir de quina manera enviem la informació. Tenim dues possibilitats:
  * si el valor de l’atribut és **get** enviem la informació juntament amb l’URL de destí, i d’aquesta manera és visible a la barra de navegació. 
  * si el valor de l’atribut method és **post**, la informació s’envia dins de la capçalera HTTP que fa la petició.

A continuació es mostra un formulari amb dos camps de text que demanen a l’usuari el seu nom i clau d’accés, i un botó per enviar les dades. Suposem que al servidor hi ha un script fet amb llenguatge PHP anomenat processa.php, que és qui rep les dades i les gestiona. Suposem primer que el mètode d’enviament és de tipus `get`:

```html
<form name="formulariacces" action="processa.php" method="get">
 <div>
  <label for="id_nom">Escriu el teu nom: </label>
  <input type="text" name="nom" id="id_nom"/>
 </div>
 <div>
  <label for="id_clau">Escriu la teva clau: </label>
  <input type="password" name="clau" id="id_clau" />
 </div>
 <div>
  <input type="submit" value="Envia les dades" />
 </div>
</form>
```

Si l’usuari entra de nom Sara i de contrasenya secreta, quan premi el botó per enviar el formulari anirem a parar a l’URL següent: http://elquesigui.org/processa.php?nom=Sara&clau=secreta.

Suposem que canviem el mètode d’enviar les dades pel mètode de tipus post:

```html
<form action="processa.php" method="post">
...
</form>
```

L’URL que veuríem seria http://elquesigui.org/processa.php, però les dades s’haurien enviat igualment dins la capçalera HTTP.

<p >

**Capçalera HTTP**

Per tal de veure les capçaleres HTTP quan s’usa el mètode POST, podríem usar un analitzador de xarxes, com pot ser el programa **Postman**. Un exemple de capçalera HTTP amb POST fent la captura amb aquest programa ens retornaria el següent:

```
POST /processa.php HTTP/1.1
Host: localhost
User-Agent: Mozilla/5.0 (X11; U; Linux i686; ca; rv:1.8.1.12) Gecko/20080129 Iceweasel/2.0.0.12 (Debian-2.0.0.12-1)
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Accept-Language: ca,es;q=0.8,en-us;q=0.5,en;q=0.3
Accept-Encoding: gzip,deflate
Accept-Charset: ISO-8859-1,utf-8;q=0.7,*;q=0.7
Keep-Alive: 300
Connection: keep-alive
Referer: http://localhost/formulari_complet.html
Content-Type: application/x-www-form-urlencoded
Content-Length: 28
nom=Sara&clau=secreta
```

* **enctype**: aquest atribut ens indica el tipus de contingut que enviem amb el formulari (quan el mètode és de tipus `post`). Per defecte, el valor és **application/x-www-form-urlencoded**. Si el formulari ens permet enviar un fitxer hem de canviar aquest valor per ***multipart/form-data***.

### 2.13.2. Associació de text i controls

*Accessibilitat*
L’etiqueta `<label>` està pensada fonamentalment per tal que la nostra web sigui accessible. Amb aquesta etiqueta els lectors de web per a persones cegues llegeixen el formulari en l’ordre correcte, associant cada text amb el seu control. També serveix perquè en fer clic damunt del text contingut en l’etiqueta `<label>` el control associat rebi el focus.

L’etiqueta `<label>` ens serveix per associar els elements de text explicatius dels controls amb els controls corresponents. L’atribut `for` de l’etiqueta `<label>` ens permet posar l’identificador (atribut `id`) del control al qual volem associar l’etiqueta.

Per dir que el text Escriu el teu nom està associat al control amb identificador nom escriurem el següent:

<iframe height="265" style="width: 100%;" scrolling="no" title="label" src="http://codepen.io/rglepe/embed/rRVvbB/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/rRVvbB/'>label</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

### 2.13.3. Atributs comuns dels controls d'un formulari

Hi ha uns quants atributs, a part del globals, que podem assignar a cadascun dels controls d’un formulari. Els més destacables són els següents:

En un formulari, podem saltar de control en control sense necessitat d’usar el ratolí o pulsació tàctil, prement la tecla del tabulador.

* `tabindex`: indica la posició en l’ordre de tabulació.
* `disabled`: si l’establim (`disabled=“disabled”`), el control queda deshabilitat.
* `autocomplete`: si aquest atribut està activat, amb el valor on, el navegador intentarà autocompletar el camp. Per desactivar-lo, el valor és off.
* `autofocus`: si activem aquest atribut (`autofocus=“autofocus”`), quan es carregui la pàgina, el control amb aquest atribut tindrà el focus.
* `pattern`: permet posar una expressió regular que haurà de complir el text introduït per l’usuari.
* `placeholder`: mostra el text que posem com a valor en el control. Aquest text desapareixerà només rebre el focus.

### 2.13.4. Camps de text

Els camps de text són els camps en què l’usuari pot introduir un text relativament curt, en cas que sigui llarg es recomana fer servir una altra etiqueta i tipus anomenat `<textarea>`, que veurem en un altre apartat. Per crear un camp de text usem l’etiqueta:

```html

<input type=“text” />
```

A més, tenim els atributs següents:

* `name`: nom del control.
* `value`: valor per defecte del camp de text.
* `readonly`: si l’establim (readonly=“readonly”), el control és de només lectura, no s’hi pot escriure.
* `maxlength`: nombre màxim de caràcters que permetrem escriure en el control.
* `size`: mida del control.
 
Seguint l’exemple de l’associació de text i controls, que hem vist amb anterioritat, hem afegit al camp que mesuri l’espai que ocuparien 30 caràcters però que hi permetem que se n’escriguin fins a 100. Això seria:

```html
<label for="identificadornom">Escriu el teu nom:</label>
<input type="text" name="nom" size="30" maxlength="100" id="identificadornom">
```

### 2.13.5. Camps de contrasenya

Els camps de contrasenya són els camps en què l’usuari pot introduir una contrasenya, ja que el text que s’introdueix queda “camuflat” amb asteriscos o punts. Per crear un camp de contrasenya usem l’etiqueta:

```html
<input type=“password” /> 
```

i els mateixos atributs que utilitzem per als camps de text. Un exemple de camp de contrasenya seria el següent:

<iframe height="265" style="width: 100%;" scrolling="no" title="contrasenya" src="http://codepen.io/rglepe/embed/eXNKzN/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/eXNKzN/'>contrasenya</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

### 2.13.6. Camp de correu

Abans d’HTML5 no existia aquest tipus d’entrada i fèiem servir el tipus text controlant amb JavaScript el valor introduït. L’etiqueta email serveix per escriure una adreça de correu electrònic. Si el navegador detecta que el que ha escrit l’usuari és invàlid, mostrarà un error. Vegem el codi en un exemple:

```html
<label for="mail">E-mail:</label> 
<input type="email" id="email" name="email" />
```

Com hem dit abans, fent servir l’atribut `pattern` a una etiqueta de tipus `text`, podríem arribar a fer el mateix fent ús d’una expressió regular.

### 2.13.7. Camp d'URL

url: serveix per escriure un URL. Si el navegador detecta que no compleix el patró correcte per a un URL mostrarà un error. Vegem un exemple:

```html
<label for="enllac">URL:</label> 
<input type="url" id="enllac" name="enllac" />
```

### 2.13.8. Camp numèric

`number`: serveix per escriure un nombre. A més, podrem fer restriccions del nombre introduït a partir dels següents atributs:

+ `min`: mínim valor permès.
+ `max`: màxim valor permès.
+ `step`: especifica quins nombres permetem segons el salt indicat. Per exemple, si `step=“2”`, els nombres permesos seran: -2, 0, 2, 4, 6…
+ `value`: especifica el nombre per defecte que apareixerà al control.

Vegem un exemple d’aquest control:

```html
<label for="nota">Nota de l'examen:</label> 
<input type="number" id="nota" name="nota" min="0" max="10" />
```

### 2.13.9. Camp de rang

`range`: és una barra de desplaçament que simula un nombre en un rang. Per tal d’establir el rang disposem dels mateixos atributs que el tipus number: `min`, `max` i `step`.

<iframe height="265" style="width: 100%;" scrolling="no" title="range" src="http://codepen.io/rglepe/embed/droKVZ/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/droKVZ/'>range</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

### 2.13.10. Camps de data o horaris

`date`, `month`, `week`, `time`, `datetime` i `datetime-local`: aquests tipus ens serveixen per poder seleccionar una data/hora, tot i que el seu comportament no és el mateix segons el navegador que fem servir, ja que aquests tipus encara no són plenament integrats en tots els navegadors.

Vegem un exemple:

<iframe height="265" style="width: 100%;" scrolling="no" title="data" src="http://codepen.io/rglepe/embed/oVXyEo/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/oVXyEo/'>data</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Si volguéssim fer servir altres tipus com ara `month`, `time`, etc, hauríem de substituir l’atribut type de l’etiqueta input pel valor corresponent.

### 2.13.11. Camps de colors

El camp de tipus color serveix per a camps que han de contenir un color. El codi seria:

<iframe height="265" style="width: 100%;" scrolling="no" title="color" src="http://codepen.io/rglepe/embed/RdPJyB/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/RdPJyB/'>color</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

### 2.13.12. Camp de cerca

Serveix per a camps de cerca i cal fer servir el valor search per l’atribut type de la etiqueta input. El seu comportament és molt semblant a un camp de tipus text. El codi seria:

```html
<label for="cerca">Cerca:</label> 
<input type="search" id="cerca" name="cerca" />
```

### 2.13.13. Botons d'opció

Els botons d’opció ens permeten triar una i només una de les opcions que se’ns ofereixen. Per crear un botó d’opció usem l’etiqueta 

```html
<input type=“radio” />. 
```

A més, tenim els atributs següents:

`name`: nom del control. És molt important fer servir el mateix nom per agrupar botons d’opcions que pertanyen a la mateixa selecció, de forma que exclusivament un sigui seleccionable alhora.
`checked`: determina si el control està seleccionat.
`value`: si està seleccionat, estableix quin valor es tramet.
`size`: determina la mida del control en píxels.

Habitualment, no només posem un botó d’opció sinó que en posem diversos d’associats entre si. Per exemple, si demanem el sexe de la persona, tenim dos botons d’opció, un per senyalar que és dona i l’altre per senyalar que és home.

El codi d’aquest exemple seria el següent:

<iframe height="265" style="width: 100%;" scrolling="no" title="radiobutton" src="http://codepen.io/rglepe/embed/OqVEBq/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/OqVEBq/'>radiobutton</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Fixem-nos que per tal que el formulari sàpiga que aquests botons d’opció estan relacionats, donem el mateix valor a l’atribut name.

Vegem un altre exemple, en què apareixen tres botons d’opció:

```html
 <h2>Fes la selecció de franja d'edat</h2>
 <input type="radio" name="edat" id="edat_menor" value="menor"/>
 <label for="edat_menor">Menys de 18 anys </label>
 <input type="radio" name="edat" id="edat_major" value="major" checked="checked"/>
 <label for="edat_major">De 18 a 65 anys </label>
 <input type="radio" name="edat" id="edat_jubilat" value="jubilat"/>
 <label for="edat_jubilat">Més de 65 anys</label>
```

Observem que els tres controls tenen el mateix valor en el camp `name` (edat). Així, quan trametem el formulari, ens arriba una de les tres possibilitats següents: `edat=menor` o bé `edat=major` o bé `edat=jubilat`. També observem que hi ha una selecció marcada per defecte amb l’atribut `checked` assignat al valor `checked`.

### 2.13.14. Caselles de verificació

Les caselles de verificació ens permeten triar una opció o més de diverses possibilitats. Per crear una casella de verificació usem l’etiqueta 

```html
<input type=“checkbox” />. 
```

A més, tenim els mateixos atributs que amb els botons d’opció.

En aquest cas l’atribut name no ha de ser el mateix ja que es pot prémer una o més d’una de les caselles de verificació. Fixem-nos en l’exemple i com es mostra en el navegador:

<iframe height="265" style="width: 100%;" scrolling="no" title="checkbox" src="http://codepen.io/rglepe/embed/eXNKwv/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/eXNKwv/'>checkbox</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

En aquest cas, si preméssim les caselles Programació HTML i Programació CSS s’enviaria: `coneixaments=html&coneixaments=css`, a la plana processa.php del servidor, per tal que la processés.

### 2.13.15. Llistes de selecció

Les llistes de selecció tenen dos formats: les llistes de selecció **simple**, que ens deixen escollir una única opció d’un llistat de possibilitats i les llistes de selecció **múltiple**, que ens deixen escollir més d’una opció (prement la tecla <kbd>Ctrl</kbd> mentre seleccionem les diverses opcions).

La funció de la llista de selecció simple és similar als botons d’opció (només es pot triar una opció), mentre que la funció de la llista de selecció múltiple és similar a les caselles de verificació (podem triar més d’una opció). Malgrat això, el format de presentació i el funcionament del control és diferent.

Per crear una llista de selecció usem dues etiquetes:

L’etiqueta `<select>` ens serveix per dir on comença i s’acaba la llista de selecció. Tenim els atributs següents:

+ `name`: nom del control.
+ `size`: nombre d’opcions visibles.
+ `multiple`: si l’establim (`<select multiple=“multiple”>`) farà que aquesta llista sigui una llista de selecció múltiple.
Per a cadascuna de les opcions usem l’etiqueta `<option>`. Aquesta etiqueta està continguda dins de l’etiqueta `<select>` que al seu torn conté el text de l’opció que s’ha de seleccionar. Té els atributs següents:
  + `value`: determina el valor que s’envia si se selecciona aquesta opció.
  + `selected`: si l’establim (`selected=“selected”`) aquesta opció està seleccionada per defecte. Hem de tenir en compte que si la llista és de selecció simple, només haurem de tenir una opció amb aquest atribut, mentre que si és de selecció múltiple podem posar-lo en més d’una opció.
   
Un exemple de llista d’opció és el següent:

<iframe height="265" style="width: 100%;" scrolling="no" title="Option List" src="http://codepen.io/rglepe/embed/bZdjpd/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/bZdjpd/'>Option List</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

En aquest cas, es permet que l’usuari marqui diverses opcions. Si per exemple, marca que ha visitat les poblacions Sant Salvador i Segur de Calafell, s’envia `municipi=Sant+Salvador&municipi=Segur+de+Calafell`. L

Si volem fer seleccions classificant les diferents opcions de la llista en grups posant-los un títol descriptiu, podem usar l’etiqueta `<optgroup>`, com es veu en l’exemple següent:

```html
<h2>Selecciona estació destí </h2>
<select name="estacio" id="estacio" size="11">
 <optgroup label="Barcelona">
  <option value="Sans"selected="selected">Barcelona Sants</option>
  <option value="Passeig Gracia" >Barcelona Passeig de Gràcia</option>
  <option value="Franca">Barcelona Estació de França</option>
  <option value="Clot">Barcelona El Clot</option>
 </optgroup>
 <optgroup label="Terrassa">
  <option value="Terrassa Centre">Terrassa Centre</option>
  <option value="Terrassa Est">Terrassa Est</option>
 </optgroup>
</select>
```

El contingut de l’atribut `label` de l’element `<optgroup>` es mostra com un títol descriptiu, però no es pot seleccionar.

### 2.13.16. Llista de dades: `<datalist>`

L’etiqueta `<datalist>` és una llista de dades que podem associar a diferents tipus de camp `<input>`, i que pot funcionar igualment a tall de suggeriment. Quan l’usuari vol introduir un valor en un camp, l’ajudarem a completar-ho amb valors llistats dins del `<datalist>`, tot i que pot escollir de propis. A més a més, podem canviar/ajudar allò que introdueix l’usuari pel valor correcte. Això pot ser molt útil per a codis en els quals l’usuari en sap la descripció, però no el codi.

És imprescindible que establim l’atribut `id` de l’etiqueta `<datalist>` per tal de poder associar la llista de dades amb el control `<input>`. En el control `<input>` tindrem l’atribut list, on haurem de posar l’ id de l’element `<datalist>`.
Dins de l’element `<datalist>` tindrem diversos elements `<option>` amb els següents atributs:
+ `label`: allò que escriurà l’usuari
+ `value`: valor amb el qual substituirem allò que escriu l’usuari

Vegem un exemple: suposem que volem que l’usuari de la nostra aplicació web hagi d’escriure el codi d’un aeroport. Normalment els usuaris saben les ciutats o la zona on hi ha l’aeroport, però no saben el codi. Podríem ajudar-lo mitjançant un `<datalist>`:

<iframe height="265" style="width: 100%;" scrolling="no" title="DataList" src="http://codepen.io/rglepe/embed/VRLBMR/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/VRLBMR/'>DataList</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Com hem apuntat abans, la llista de dades pot fer-se servir amb altres tipus d’inputs, com ara range, color, time, datatime-local, date, week o moth, tot i que això depèn del navegador on les visualitzem, ja que no tots tenen aquests tipus d’inputs i cal consultar-ho amb anterioritat a algun portal com ara [](www.html5test.com) o [](www.caniuse.com).

A mode d’exemple, amb el següent codi podem veure un `<input type=“time”>` amb una llista de selecció.

```html
<label>Escull una hora:</label>
<input type="time" list="hores" />
<datalist id="hores">
  <option label="Mitjanit">00:00</option>
  <option label="Matinada">06:00</option>
  <option label="Migdia">12:00</option>
  <option>18:00</option>
</datalist>
```

### 2.13.17. Generador de claus: `<keygen>`

La seguretat a la xarxa és un factor que cada cop ha esdevingut més important atesa la immensa quantitat de traspàs de dades sensibles a través de la xarxa. És per això que HTML5 incorpora una etiqueta que fa que l’enviament de dades sigui més segur. L’etiqueta s’anomena `<keygen>` i si l’usem es generen un parell de claus per tal de comunicar-se amb el servidor web a qui se li vol enviar la informació.

D’aquest parell de claus, la clau privada s’emmagatzema en el client i la pública s’envia al servidor.

Vegem com s’usa aquesta etiqueta:

```html
<form action="accio.php" method="get">
   <label for="usuari">Usuari:</label>
   <input type="text" name="usuari" id="usuari" />
   <label for="enc">Encriptació:</label>
   <keygen name="enc" id="enc" />
   <input type="submit" value="Envia dades" />
</form>
```

### 2.13.18. Sortida de resultats: `<output>`

L’etiqueta `<output>` serveix per mostrar els resultats d’alguna operació feta generalment amb Javascript.

Tot i que haurem d’usar una mica de JavaScript per tal de veure’n la utilitat. Com a exemple, suposem que l’usuari entra un preu sense IVA i l’IVA a aplicar i volem que es vagi recalculant el preu amb IVA si canviem els valors. El codi seria el següent:

<iframe height="265" style="width: 100%;" scrolling="no" title="output" src="http://codepen.io/rglepe/embed/ywNqRP/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/ywNqRP/'>output</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

### 2.13.19. Àrees de text

Les àrees de text permeten que l’usuari de l’aplicació web enviï una porció de text més gran que amb els camps de text. L’etiqueta que ens permet inserir una àrea de text és `<textarea>`. Els atributs que podem usar amb aquesta etiqueta són els següents:

+ `name`: nom del control.
+ `cols`: amplada, en caràcters.
+ `rows`: alçada, en nombre de línies.
+ `readonly`: si l’establim (`readonly=“readonly”`), el control és de només lectura, no s’hi pot escriure.

Vegem un exemple de control d’àrea de text en què deixem a l’usuari cinc files i trenta columnes visibles per escriure. El text que està entre les etiquetes d’inici i fi és el text que surt per defecte a l’àrea de text:

```html
<textarea name="comentari" id="comentari" cols="30" rows="5">Escriu aquí els teus comentaris</textarea>
```

Resultat:
<textarea name="comentari" id="comentari" cols="30" rows="5">Escriu aquí els teus comentaris</textarea>

### 2.13.20. Botons

Els botons d’un formulari ens serveixen per fer accions quan els premem. Tenim tres tipus de botons:

* **Botó d’enviament de formulari**: quan es prem aquest botó el formulari es tramet. És a dir, les dades són enviades al destí que hem posat en l’atribut action de l’element `<form>`. Per inserir un botó d’aquest tipus usem l’etiqueta `<input type=“submit” />`. Disposem, a més, de l’atribut `value`, que ens indica el text que apareix en el botó.
* **Botó de restabliment del formulari**: quan es prem aquest botó el formulari torna a posar-se en l’estat inicial. És a dir, s’esborra tot allò que ha escrit l’usuari i es posen les dades per defecte del formulari. Per inserir un botó d’aquest tipus usem l’etiqueta `<input type=“reset” />`. Amb l’atribut value podem indicar el text que apareix al botó.
* **Botó genèric**: podem inserir botons en els quals podem afegir noves funcions mitjançat codi de programació. Per poder fer això usem l’etiqueta `<button>`. El valor que ens apareix al botó és allò que posem entre l’inici i el final de l’etiqueta. Podem posar tant text com imatges. Aquest control té els atributs següents:
    * `type`: defineix quin tipus de botó és. Pot prendre els valors següents: 
      * `submit` (amb la mateixa funció que els botons d’enviament de formulari), 
      * `reset` (amb la mateixa funció que els botons de restabliment de formulari) o 
      * `button` (botó genèric).
    * `name`: nom del control
    * `value`: valor que es tramet quan premem el botó.
  
Posem com a exemple els botons de restabliment de formulari i el d’enviament de formulari:

<iframe height="265" style="width: 100%;" scrolling="no" title="buttons" src="http://codepen.io/rglepe/embed/zbvKOJ/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/zbvKOJ/'>buttons</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Fixem-nos que l’etiqueta `<button>` no es tanca en ella mateix i per tant podem inserir qualsevol cosa dins del botó com, per exemple, una imatge o el text que ha d’aparèixer:

```html
<button><img src="envia.png" alt="Enviament de dades" /></button>
```

### 2.13.21. Controls ocults

En alguns casos ens pot interessar tenir en un formulari un control amb un valor concret, però que no sigui ni visible ni directament modificable per l’usuari final. Per inserir un control d’aquest tipus s’usa l’etiqueta `<input type=“hidden” />`. Els atributs que s’usen amb aquest control són els següents:

`name`: nom del control.
`value`: valor que es tramet.
Per exemple, si volem enviar `seccio=segona`, hem d’escriure el codi següent:

```html
<input type="hidden" name="seccio" value="segona" />
```

## 2.14. Marcs flotans

En ocasions ens interessa introduir contingut dins d’una pàgina d’una altra pàgina. En aquests casos el que fem servir són els marcs flotants amb l’ús de l’etiqueta `<iframe>`, indicant amb l’atribut `src` l’origen del contingut a mostrar dins del marc creat.

Un exemple de codificació per mostrar el contingut dins d’una pàgina seria el següent:

<iframe height="265" style="width: 100%;" scrolling="no" title="buttons" src="https://ca.wikipedia.org/wiki/Llenguatge_de_marques" frameborder="no" allowtransparency="true" allowfullscreen="true" name="marcflotant_a">
</iframe>
<p><a href="http://www.w3c.es/" target="marcflotant_a">Mostrar portal W3C</a></p>

 <p>Quan cliquem a l'enllaç obrim la pàgina principal del portal www.w3c.es a l'interior del marc flotant.</p>

A l’etiqueta `<iframe>` hem afegit l’atribut `width` i `height` per donar-li una amplada i alçada respectivament al marc flotant, i també hem fet ús de l’atribut `name` per posar-li un nom i posteriorment fer-ho servir a l’etiqueta `<a>`. Això ens permet indicar-li amb l’atribut `target` de l’enllaç, quin marc flotant serà el destí de l’enllaç quan cliquem, és a dir, posarà el contingut que marca l’enllaç a dins del marc flotant. A la figura Figure36 veiem el resultat del codi anterior.

## 2.15. Mapes

La combinació de l’etiqueta `<a>` amb l’etiqueta `<img>` ens permet fer que una imatge sigui alhora un enllaç. Però si el que volem és que segons el punt d’una imatge on premem ens porti a un enllaç o a un altre, haurem de recórrer a un altre recurs: **els mapes sensibles** (imatges que presenten múltiples enllaços segons la zona on se situï el cursor).

Hi ha dos tipus de mapes, els mapes gestionats des del client i els mapes gestionats des del servidor.

### 2.15.1. Mapes gestionats des del client

La primera tasca que cal fer quan confeccionem un mapa sensible gestionat des del client és dividir la imatge en zones. Per tal de fer això hem de delimitar aquestes zones establint-ne les coordenades.

<p style="background-color:rgba(200,200,200,0.5)"> <strong>Eines de confecció de mapes</strong> Confeccionar un mapa “a mà” i obtenir les coordenades necessàries pot arribar a ser molt laboriós. Existeixen diversos programes que ens poden ajudar en aquesta tasca. Podem posar com a exemples el programa <b>kimagemapeditor</b> o el connector <b>imagemap</b> del programa de tractament d’imatges GIMP.</p>

Hi ha diversos programes de dibuix que ens permeten veure les coordenades de cada punt de la imatge. També tenim eines específiques per a la creació de mapes d’imatges que ofereixen aquesta possibilitat.

Si volem utilitzar mapes sensibles, hem de fer dues actuacions: declarar el mapa i assignar-lo a una imatge. Vegem com podem fer aquests dos passos:

1. La declaració d’un mapa es fa amb una etiqueta `<map>` i diverses etiquetes `<area>` seguint la sintaxi següent:

    ```html
    <map name="nom_mapa">
    <area shape="..." coords="..." href="..." alt="..." />
    ...
    </map>
    ```

    A l’etiqueta `<map>` hi establim el nom del mapa i a les etiquetes `<area>` hi definim cadascuna de les zones del mapa. Els atributs per fer-ho són els següents:

    + `shape`: defineix la forma de la zona, que pot ser **rectangular** (`rect`), **circular** (`circ`) o **poligonal** (`poly`).
    + `coords`: defineix les coordenades de la zona, seguint la normativa següent:
    + Si es tracta d’un rectantgle (`rect`), cal indicar les coordenades de l’extrem superior esquerre: `x1` i `y1`; i les de l’extrem inferior dret: `x2` i `y2` .
    + Si es tracta d’un cercle (`circ`), cal indicar les coordenades del centre del cercle: x i y; i el radi (`r`) d’aquest cercle.
    + Si es tracta d’un polígon (`poly`), cal indicar les coordenades `x1`, `y1`, `x2`, `y2`, `x3`, `y3`… on cada parella `xi, yi` defineix un vèrtex del polígon. La darrera parella s’uneix a la primera per tancar el polígon.
    + `href`: defineix l’enllaç on s’anirà si l’usuari prem sobre la zona.
    + `nohref`: si l’establim (nohref= ””) indiquem que la zona no té cap enllaç definit.
    + `alt`: incorpora el text que es presenta si no es pot presentar la imatge.

2. L’assignació d’un mapa a una imatge es fa amb l’atribut usemap de l’etiqueta `<img>`. La sintaxi és la següent: `<img src="cami_imatge" usemap="#nom_mapa" />`
    El nom del mapa sempre ha d’anar precedit del símbol # i ha de coincidir amb l’atribut name de l’etiqueta `<map>`.

Imaginem que tenim la imatge que es veu en la següent figura i volem que en prémer sobre qualsevol de les quatre figures es faci una consulta a la Viquipèdia que correspongui a cadascuna d’elles. El codi complet seria el següent:

<iframe height="265" style="width: 100%;" scrolling="no" title="maps" src="http://codepen.io/rglepe/embed/PLPWMZ/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/PLPWMZ/'>maps</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

### 2.15.2. Mapes gestionats des del servidor

L’objectiu dels mapes gestionats des del servidor és enviar al servidor les coordenades del punt on s’ha premut. En el servidor hi haurà un programa que sap com s’han de gestionar aquestes coordenades (per exemple, enviar a una altra pàgina segons on s’hagi premut). Per tal de fer això hem d’usar l’atribut ismap=“ismap” de l’etiqueta `<img>`. Per exemple:

```html
<a href="mapaservcoord.html"><img src="imatges/linux.png" alt="linux" ismap="ismap" /></a>
```

Això fa que si premem les coordenades 5,15 de la imatge anem a la pàgina mapaservcoord.html?5,15. La pàgina de destinació pot agafar la part de l’URL que conté les coordenades i gestionar-les com convingui.

## 2.16. Objectes

Altres etiquetes HTML5 per a objectes concrets

HTML5 incorpora etiquetes pròpies per inserir objectes de diversos tipus. Per exemple tenim l’etiqueta `<audio>` per a inserir so o l’etiqueta `<video>` per a inserir vídeos. Tot i això, HTML5 continua conservant l’etiqueta genèrica `<object>` que ja existia a HTML4, amb l’objectiu d’englobar qualsevol tipus d’objecte.

L’etiqueta `<object>` neix per oferir una solució universal a la inclusió de qualsevol tipus de fitxers en els documents HTML, de manera que els navegadors rebin la informació necessària per tractar l’objecte (fitxer incrustat en el document).

Com a regla general, l’etiqueta `<object>` serveix per definir un objecte o component extern al navegador que s’encarrega de reproduir l’objecte (so, animació, vídeo, connectors, documents…). Per aconseguir una reproducció correcta, l’etiqueta `<object>` ha de permetre declarar l’objecte, la seva ubicació i el seu tipus, i unes etiquetes optatives especials, `<params>`, permeten acabar de definir els valors o paràmetres que aquest necessiti.

La sintaxi genèrica és la següent:

```html
<object atribut1="valor1" atribut2="valor2" ... atributN="valorN">
   <param name="nom" value="valor">
   <param name="nom" value="valor">
   ...
</object>
```

Un atribut bàsic en la declaració d’un objecte és l’atribut `type` que permet indicar al navegador el tipus d’objecte que ha de carregar. El navegador ha d’utilitzar aquesta informació per esbrinar si disposa d’alguna aplicació adequada per reproduir l’objecte, i n’ha d’avortar la càrrega si no en disposa.

De tot això es dedueix que hi ha dos punts importants perquè un objecte es pugui reproduir correctament:

+ El tipus d’objecte ha d’estar ben identificat en el document HTML. Per a això, cal utilitzar els tipus MIME.
+ El navegador ha de tenir instal·lada alguna aplicació adequada per tal de reproduir l’objecte. Les aplicacions que possibiliten aquesta funció s’anomenen connectors (en anglès, plugins).

L’etiqueta `<object>` disposa dels següents atributs:

+ `data`: nom del fitxer per reproduir amb la seva ubicació.
+ `type`: cadena amb el tipus MIME adequat a l’objecte.
+ `width`: amplada en píxels del control.
+ `height`: alçada en píxels del control.

Per exemple, si volem reproduir un arxiu de música, hem de fer el següent:

```html
<object data="musica.mp3" type="audio/mpeg">
   <p>Aquest objecte no ha pogut ser reproduït.</p>
</object>
En nombre de paràmetres, depèn de quin objecte vulguem encastar, en podrem posar uns o uns altres.
```

## 2.17. Tipus MIME

**MIME** és l’acrònim anglès de **Multipurpose Internet Mail Extensions** (extensions multipropòsit de correu d’Internet). Es tracta d’un estàndard que especifica com un programa (inicialment, de correu o navegador web) ha de transferir arxius multimèdia (vídeo, so i, per extensió, qualsevol arxiu que no estigui codificat en US-ASCII).

L’estàndard MIME adjunta un fitxer de capçalera a cada fitxer, que especifica el tipus i el subtipus del contingut del fitxer principal. Gràcies a aquesta informació, tant el servidor com el navegador poden gestionar i presentar correctament les dades.

En la utilització diària d’Internet, ens beneficiem dels tipus MIME. Cada vegada que sol·licitem una pàgina d’Internet, s’obre un diàleg entre el nostre navegador i el servidor que proporciona la pàgina. El nostre navegador demana la pàgina i el servidor, abans d’enviar-la, confirma que existeix i comprova el tipus de dades que conté. Això darrer es fa mitjançant el tipus MIME que correspongui.

La gestió del tipus MIME en el web té lloc en tres punts ben diferenciats:

1. En el servidor, que ha de ser capaç de gestionar diversos tipus MIME i tenir-los activats.

2. En la pàgina web, en què l’autor pot fer referència a tipus MIME, tot i que és merament consultiu. Els enllaços a arxius externs (fulls d’estils, scripts de JavaScript, objectes incrustats…) es feien servir en versions anteriors a HTML5 indicant el tipus de l’arxiu enllaçat amb l’atribut type. A continuació posem alguns exemples, tot i que si no l’indiquem als dos primers casos, el navegador ja dóna per defecte un comportament adequat:

+ Enllaços a fulls d’estils:

```html
<link rel="stylesheet" type="text/css" href="estils.css" />
<!-- A les darreres versions de navegadors funciona igualment aquesta altre definició-->
<link rel="stylesheet" href="estils.css" />
```

+ Crida a scripts JavaScript:
  
```html
<script type="text/javascript" src="codi.js"></script>
<!-- A les darreres versions de navegadors funciona igualment aquesta altre definició-->
<script src="codi.js"></script>
```

+ Definició d’objectes:

```html
<object data="musica.mp3" type="audio/mpeg">
   <p>Text alternatiu</p>
</object>
```

3. En el navegador del client, que ha d’estar capacitat per interpretar els tipus MIME que el servidor li envia i, fins i tot, ha de poder informar el servidor dels tipus MIME que pot acceptar.

<span style= "align: center"> ![Logotip d'IANA](https://www.iana.org/_img/2013.1/iana-logo-header.svg)</span>


L’organisme que s’encarrega de registrar els tipus MIME és l’IANA, acrònim anglès d’Internet Assigned Numbers Authority (Agència d’Assignació de Números d’Internet). A la seva pàgina web podem trobar la llista completa de tipus/subtipus MIME.

Per permetre aquesta funció, el navegador ha de tenir instal·lades les aplicacions adequades als diferents tipus MIME que interessi gestionar. Són els anomenats connectors (plugins) del navegador.

Actualment, els tipus MIME s’agrupen en vuit categories, i cada tipus MIME s’identifica pel nom compost: categoria/tipus. De vegades, es parla de tipus/subtipus. Les vuit categories són les següents: application, audio, image, message, model, multipart, text i video. Cadascuna està formada per un conjunt més o menys gran de tipus MIME, i cadascun dels tipus acostuma a dur associades una extensió d’arxius o més d’una.

Taula Recull de tipus MIME i extensions de fitxers associades

Tipus/Subtipus MIME|	Extensions de fitxers|	Tipus/Subtipus MIME|Extensions de fitxers|
---|---|---|---|
image/png|	.png|	video/x-msvideo|	.avi|
image/gif|	.gif|	application/pdf|	.pdf|
image/jpeg|	.jpg, .jpeg, .jpe|	application/postscript|	.ai, .eps, .ps|
image/tiff|	.tif, .tiff|	application/rtf|	.rtf|
audio/x-wav|	.wav|	application/gzip|	.gz|
audio/x-midi|	.mid|	application/x-tar|	.tar|
text/plain|	.txt|	application/zip|	.zip|
text/richtext|	.rtf, .rtx|	application/x-java-vm|	.class|
video/mpeg|	.mpeg, .mpg, .mpe|	application/x-java-archive|	.jar|

## 2.18. Connectors

Per reproduir fitxers encastats dins les pàgines web com a objectes genèrics, els navegadors necessiten tenir instal·lat el connector adequat.

Els connectors (**plugins**) són aplicacions informàtiques que interactuen amb una altra aplicació per afegir-hi una funció o utilitat específica.

És a dir, si en un document web s’hi ha incrustat un objecte (`<object>`) que fa referència a un document d’un cert tipus MIME, el navegador que l’hagi de reproduir ha de disposar d’un connector adequat per a aquell tipus MIME. Per exemple moltes vegades trobem que certs navegadors necessiten de la instal·lació d’un pluging específic per reproduir objectes de tipus Flash d’Adobe.

El fet que el sistema operatiu disposi d’una aplicació que pugui reproduir un determinat arxiu (corresponent a un tipus MIME) no és garantia que els navegadors instal·lats en aquell sistema tinguin instal·lat el connector corresponent.

Els navegadors, en rebre pàgines web que contenen tipus MIME no suportats, haurien d’oferir a l’usuari, tal com recomana el W3C, la possibilitat d’instal·lar-los d’una manera senzilla.

Si es vol saber els connectors que es tenen instal·lats al navegador Chrome s’ha d’escriure [chrome://extensions/](chrome://extensions/) a la barra de navegació. El navegador ens mostra un document HTML amb la informació corresponent de tots els connectors instal·lats.

Exemples d'incorporació d'objectes genèrics en una pàgina web
A continuació es mostren diversos exemples de com podem incrustar alguns tipus de mitjans multimèdia a la nostra web. En tots els exemples, si no es pot accedir al mitjà, es mostra un text que ofereix la possibilitat de baixar el fitxer directament.

+ Inserció d’un fitxer PDF d’extensió .pdf.

```html
 <object data="https://www.w3.org/WAI/ER/tests/xhtml/testfiles/resources/pdf/dummy.pdf" type="application/pdf" width="100%" height="100%">
 <p>Sembla que no tens un connector per veure el contingut del fitxer PDF.
 Baixa-te'l de: <a href="[dummy.pdf](https://www.w3.org/WAI/ER/tests/xhtml/testfiles/resources/pdf/dummy.pdf)">Fes click i es descarregarà</a></p>
 </object>
```

![](https://imgur.com/pNMWq4J.png)


+ Inserció d’un vídeo en format .mpg:

```html
<object data="http://distribution.bbb3d.renderfarming.net/video/mp4/bbb_sunflower_1080p_30fps_stereo_abl.mp4" type="video/mp4" width="500" height="500">
     No es pot accedir al vídeo. Baixa-te'l d'<a href="media/EntrevistaStallman.mpg">aquí</a>
</object>
```

+ Inserció d’un fitxer àudio en format .mp3:

<iframe height="265" style="width: 100%;" scrolling="no" title="mime-type-audio" src="http://codepen.io/rglepe/embed/drYVoO/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/drYVoO/'>mime-type-audio</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

+ Inserció d’un format .swf (aplicació Flash):

```html
<object type="application/x-shockwave-flash" data="http://www.example.com/baner.swf" width="400" 
height="400">
   <param name="src" value="http://www.example.com/baner.swf" />
</object>
```

# 3. Organització de codificació i estructuració dels portals

Hi ha dos aspectes fonamentals dins del desenvolupament de portals: la **llegibilitat** i la **organització del codi**, és a dir, com organitzem d’una banda el codi dins d’un document, i de l’altra l’organització dels diferents fitxers que componen el portal (l’arbre de directoris del portal). Per aquest motiu podríem dir que es necessita una organització interna al document, lligada a la llegibilitat del codi, i una d’externa, lligada a com es disposen els documents dins del directori arrel del portal.

## 3.1. Llegibilitat i organització del codi

La llegibilitat del codi font fa referència a la claredat amb la qual escrivim el codi, en el sentit que un ésser humà sigui capaç d’entendre’l de manera fàcil i ràpida, és a dir, la seva estructura i els elements que aquest conté simplement fent un cop d’ull.

És fonamental que el codi font (X)HTML que generem sigui fàcilment comprensible. Hem de pensar que normalment no treballarem sols i fer que allò que hem desenvolupat sigui llegible, pot ajudar a aquells que treballin amb el nostre document a entendre què hem fet i per què. Fins i tot, suposant que el document creat només serà modificat per nosaltres, la llegibilitat també és fonamental per recordar tot allò que hem fet.

Entendrem per organització del codi font l’estructuració de l’aplicació web en diversos fitxers així com la classificació d’aquests fitxers en els directoris que calgui.

Hi ha diverses tècniques per tal que el codi sigui llegible i estigui ben organitzat. Les més rellevants són els comentaris, el sagnat del codi, l’ús de noms clarificadors relacionats amb la funció que realitza una part de codi i l’organització dels fitxers.

<span style="text-decoration:underline">
<em>Comentaris</em></span>

En un document (X)HTML podem posar anotacions que no són visibles als usuaris que mirin la web amb el navegador (excepte si examinen el codi font), però que són útils per al desenvolupador web.

La sintaxi dels comentaris amb (X)HTML és la següent:
`<!-- comentari -->`

És molt important comentar el codi font, sobretot si es tracta d’un document molt llarg.

Imaginem que tenim una pàgina web amb una capçalera, un menú per navegar, seccions centrals amb 3 articles i un peu de pàgina. Podríem posar els següents comentaris per denotar on comencen cadascuna d’aquestes seccions del nostre document:

```html
    <!doctype html>
        <html>
            <head>
                <meta charset=utf-8">
                <title>Títol de la pàgina web</title>
            </head>
            <body>
                <!-- Capçalera -->
                ...
                <!-- Menú de navegació -->
                ...
                <!-- Secció d'articles -->
                ...
                <!-- Article 1 -->
                ...
                <!-- Article 2 -->
                ...
                <!-- Article 3 -->
                ...
                <!-- Peu de pàgina -->
                ...
            </body>
        </html>
```

<span style="text-decoration:underline">*Sagnat del codi o tabulació*</span>

El codi HTML està farcit d’etiquetes que s’obren i es tanquen. Al navegador web que interpretarà aquest codi no li cal que hi hagi ni salts de pàgina ni tabuladors per poder interpretar-lo, però els éssers humans necessitem que el codi estigui organitzat amb salts de línia i sagnats per tal de llegir-lo d’una manera còmoda.

Una tècnica per tal de sagnar el codi és que tot el contingut que hi ha entre una etiqueta d’inici i la seva etiqueta de tancament corresponent estigui sagnat. Aquest sagnat es fa sempre, excepte si el contingut és text, ja que això provocaria massa sagnats. Posem un exemple on es veu com l’etiqueta `<p>` queda sagnada respecte l’etiqueta `<div>` i, en canvi, el text contingut en el paràgraf no el sagnem:

 ```html
 <div>
     <p>Això és el contingut d'un paràgraf</p>
 </div>
 ```
Si els elements són de línia, tampoc s’acostuma a sagnar el codi. Posem un altre exemple:

Existeixen principalment dos “Tipus d’elements”; els elements de línia (que ocupen exclusivament espai a la línia on són inserits) i els elements de bloc, que per defecte ocupen tot l’ample del document visualitzat.

```html
   <div>
      <p>Això és el contingut d'un paràgraf, ara fem un <a href="http://elquesigui.org"> enllaç extern</a> i continuem escrivint...</p>
   </div>
```

Una altra ajuda per fer més fàcil la nostra tasca de diferenciar codi ve donada pels editors HTML, que acoloreixen el codi segons els elements que formen els documents. El que fan és reconèixer el codi i fins i tot el poden arribar a tabular automàticament si està ben etiquetat, o fer-nos suggeriments a mesura que l’escrivim.

## 3.2. Organització dels directoris

<span style="text-decoration:underline">*L'arbre de directoris als portals/apps*</span>

Pràcticament la totalitat d’aplicacions web contenen un nombre elevat de fitxers de diferents tipus i extensions com ara: .html, fulls d’estil amb extensió .css, fitxers amb codi JavaScript amb extensió .js, imatges, vídeos… Si tenim tots aquests fitxers barrejats, la nostra aplicació web tindrà una organització caòtica. Hem d’organitzar la nostra aplicació en directoris. Un exemple per una aplicació no gaire gran seria l’arbre de directoris següent:

```
  |--web
  |   |--imatges
  |   |    |--img1.png
  |   |    |--img2.jpg
  |   |    |--img3.gif
  |   |    |...
  |   |--videos
  |   |    |--video1.mpg
  |   |    |--video2.mpg
  |   |    |...
  |   |--audios
  |   |    |--audio1.ogg
  |   |    |--audio2.mp3
  |   |    |...
  |   |--javascript
  |   |    |--llibreria1.js
  |   |    |--codificacio.js
  |   |--css
  |   |    |--estil1.css
  |   |    |--estil2.css  
  |   |    |...
  |   |--pagines
  |   |    |--quisom.html
  |   |    |--seccio1.html 
  |   |    |--seccio2.html   
  |   |    |--contacte.html   
  |   |    |...
  |   |--index.html
  |   |...
  |
```

Com podeu observar, és molt recomanable que cada cop que creem una aplicació web creem també un directori principal o arrel, on desarem tots els nostres fitxers o arbre de directoris. En el cas de l’exemple l’hem anomenat web. En aquest directori podem posar el fitxer principal .html (a l’exemple index.html) i crear els directoris que ens calguin per posar els fitxers multimèdia (imatges, àudios i vídeos), els estils de l’aplicació, la carpeta pels fitxers de JavaScript o la carpeta que conté la resta de pàgines HTML que no siguin l’índex principal.

<span style="text-decoration:underline">*Nomenament dels fitxers*</span>

Per tal d’anomenar els fitxers del nostre portal, hem de seguir igualment algunes regles d’obligat compliment o opcionals però que unifiquin criteris comuns a tot el portal.

* No feu servir espais en blanc per anomenar els fitxers. Per exemple: “la meva plana.html” no seria correcte però sí “la_meva_plana.html”.
* No feu servir lletres accentuades, apòstrofs o lletres que estiguin lligades a llengües concretes (la ñ en castellà o la ç o l·l en català són un exemple).
* Penseu que els fitxers segons els sistemes operatius són case sensitive, és a dir, distingeixen entre majúscules i minúscules. És molt millor posar tots els noms en minúscula, per unificar criteris.
* Feu servir noms breus pels noms dels fitxers de com a màxim 12 caràcters com a regla general.
* Feu servir noms que donin una idea de la informació que conté la pàgina o document. Per exemple: contacte.html, home.html, serveis.html són un bon exemple, però no pagina1.html o lamevaplana.html.
* És recomanable que el fitxer d’inici de les aplicacions tingui el nom index.html. Això fa que l’usuari no hagi d’escriure el nom del fitxer per accedir-hi.

Es pot configurar el servidor web per tal que en lloc d’ index.html el fitxer d’inici tingui un altre nom.

# 4. Eines d'anàlisi i desenvolupament

Una vegada vist com s’estructura una pàgina web i com s’organitzen els fitxers dins d’un portal o aplicació, és important saber com treballen els desenvolupadors d’interfícies web, quines són les eines habituals de treball al marge dels editors HTML, per tal de manegar el nostre codi.

L’objectiu d’aquestes eines és veure el funcionament i codificació de les nostres pàgines directament al navegador on les obrim i modificar-les en viu sense efecte sobre els fitxers originals, però amb l’objectiu d’orientar-nos a l’hora de fer canvis.

Tenim bàsicament dues opcions:

- Mitjançant les eines de desenvolupament dels mateixos navegadors.
- Afegint funcionalitats de tercers, mitjançant connectors (plug-ins), al nostre navegador.

## 4.1. Eines de desenvolupament dels navegadors

Cada navegador té les seves pròpies eines de desenvolupament, a les quals podem accedir bé pel menú o bé per abreviació de teclat. Tenint en compte els principals navegadors, podeu consultar la següent taula de resum:


|Abreviació| teclat|
|---|---|	
Chrome o Chromium|	F12|
|Firefox|	Ctrl + Majúscules + I|
Internet Explorer|	F12
Opera(*)	|Ctrl + Majúscules + I
<em>(*) Opera anomena a aquestes eines Opera Dragonfly</em>

## 4.2. Instal·lació de *plug-ins* al navegador

Consultar la [chrome web store](https://chrome.google.com/webstore/category/ext/11-web-development?hl=es) per obtenir eines per desenvolupadors.
