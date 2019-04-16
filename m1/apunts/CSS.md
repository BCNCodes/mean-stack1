- [1. El llenguatge de fulls d'estil CSS](#1-el-llenguatge-de-fulls-destil-css)
  - [1.1. Història i orígens del CSS](#11-hist%C3%B2ria-i-or%C3%ADgens-del-css)
  - [1.2. El CSS](#12-el-css)
  - [1.3. Ubicació dels estils](#13-ubicaci%C3%B3-dels-estils)
  - [1.4. Sintaxi bàsica de CSS](#14-sintaxi-b%C3%A0sica-de-css)
  - [1.5. Les directives (regles @)](#15-les-directives-regles)
  - [1.6. Comentaris](#16-comentaris)
  - [1.7. Cascada i herència](#17-cascada-i-her%C3%A8ncia)
    - [1.7.1. Cascada](#171-cascada)
    - [1.7.2. Herència](#172-her%C3%A8ncia)
- [2. Regles CSS](#2-regles-css)
  - [2.1. Selectors](#21-selectors)
    - [2.1.1. Selectors de tipus](#211-selectors-de-tipus)
    - [2.1.2. Selectors de classe](#212-selectors-de-classe)
    - [2.1.3. Selectors d'identificador](#213-selectors-didentificador)
    - [2.1.4. Selectors d'atribut](#214-selectors-datribut)
    - [2.1.5. Selector universal](#215-selector-universal)
    - [2.1.6. Selectors de descendents](#216-selectors-de-descendents)
    - [2.1.7. Selectors de fills](#217-selectors-de-fills)
    - [2.1.8. Selectors de germans adjacents](#218-selectors-de-germans-adjacents)
    - [2.1.9. Selector general de germans](#219-selector-general-de-germans)
    - [2.1.10. Agrupament de selectors](#2110-agrupament-de-selectors)
  - [2.2. Pseudoclasses i pseudoelements](#22-pseudoclasses-i-pseudoelements)
    - [2.2.1. Pseudoclasses](#221-pseudoclasses)
    - [2.2.2. Pseudoelements](#222-pseudoelements)
  - [2.3. Propietats bàsiques de format](#23-propietats-b%C3%A0siques-de-format)
    - [2.3.1. Mesures](#231-mesures)
    - [2.3.2. Colors](#232-colors)
    - [2.3.3. Colors amb transparència RGBA o HSLA](#233-colors-amb-transpar%C3%A8ncia-rgba-o-hsla)
    - [2.3.4. Fonts](#234-fonts)
    - [2.3.5. Aspecte del text](#235-aspecte-del-text)
    - [2.3.6. Color i fons](#236-color-i-fons)
  - [2.4. El model de caixa](#24-el-model-de-caixa)
    - [2.4.1. Mar­ges](#241-mar%C2%ADges)
    - [2.4.2. Far­ci­ment](#242-far%C2%ADci%C2%ADment)
    - [2.4.3. Vores](#243-vores)
  - [2.5. El format visual dels elements d'un document](#25-el-format-visual-dels-elements-dun-document)
  - [2.6. Efectes CSS](#26-efectes-css)
    - [2.6.1. Transformacions 2D](#261-transformacions-2d)
    - [2.6.2. Transicions](#262-transicions)
    - [2.6.3. Animacions](#263-animacions)
    - [2.6.4. Transitions vs. Animations!](#264-transitions-vs-animations)
  - [2.7. Gradients](#27-gradients)
    - [2.7.1. Gradient Lineal](#271-gradient-lineal)
    - [2.7.2. Gradient Radial](#272-gradient-radial)
  - [2.8. Columnes](#28-columnes)
  - [2.9. FlexBox](#29-flexbox)
    - [2.9.1. Vocabulari Flexbox](#291-vocabulari-flexbox)
    - [2.9.2. Flex Container](#292-flex-container)
    - [2.9.3. `flex-direction`](#293-flex-direction)
    - [2.9.4. `flex-wrap`](#294-flex-wrap)
    - [2.9.5. `flex-flow`](#295-flex-flow)
    - [2.9.6. `justify-content`](#296-justify-content)
    - [2.9.7. `align-items`](#297-align-items)
    - [2.9.8. `align-content`](#298-align-content)
  - [2.10. Flex items](#210-flex-items)
    - [2.10.1. `order`](#2101-order)
    - [2.10.2. `flex-grow` and `flex-shrink`](#2102-flex-grow-and-flex-shrink)
    - [2.10.3. `flex-basis`](#2103-flex-basis)
    - [2.10.4. `flex`](#2104-flex)
    - [2.10.5. `align-self`](#2105-align-self)
    - [2.10.6. Play around with flexbox](#2106-play-around-with-flexbox)
    - [2.10.7. Help the Froggy](#2107-help-the-froggy)
  - [2.11. CSS Grid](#211-css-grid)
    - [2.11.1. Conceptes](#2111-conceptes)
    - [2.11.2. Grid amb files i columnes](#2112-grid-amb-files-i-columnes)
    - [2.11.3. fr: Unitat fracció restant](#2113-fr-unitat-fracci%C3%B3-restant)
    - [2.11.4. Files i columnes repetitives](#2114-files-i-columnes-repetitives)
    - [2.11.5. Grid per àrees](#2115-grid-per-%C3%A0rees)
    - [2.11.6. Grid amb buits](#2116-grid-amb-buits)
    - [2.11.7. Posició en el grid](#2117-posici%C3%B3-en-el-grid)
    - [2.11.8. Ajust automàtic de cel·les](#2118-ajust-autom%C3%A0tic-de-celles)
    - [2.11.9. Propietats per a ítems fills](#2119-propietats-per-a-%C3%ADtems-fills)
  - [2.12. Media Queries](#212-media-queries)
    - [2.12.1. Media types](#2121-media-types)
    - [2.12.2. Media features](#2122-media-features)
  - [2.13. Exemples pràctics amb CSS](#213-exemples-pr%C3%A0ctics-amb-css)
    - [2.13.1. Fer menús amb llistes](#2131-fer-men%C3%BAs-amb-llistes)
    - [2.13.2. Maquetació de webs](#2132-maquetaci%C3%B3-de-webs)
    - [2.13.3. Simulació de marcs amb CSS](#2133-simulaci%C3%B3-de-marcs-amb-css)

# 1. El llenguatge de fulls d'estil CSS

En els orígens del web i en les seves primeres versions, el llenguatge de marques HTML era un llenguatge fàcil d’aprendre i molt reduït quant a les marques i l’estructura. Tot va canviar quan van aparèixer els primers navegadors que eren capaços de representar recursos gràfics per afegir a la informació textual.

D’aquesta manera, el nombre de llocs web va començar a créixer i, amb ell, el nombre de marques que l’especificació HTML preveia. L’objectiu era construir llocs web cada vegada més atractius i, per a això, l’HTML havia d’incloure noves marques destinades a aconseguir efectes visuals.

Per tal d’evitar que  fos el responsable de la part estètica i visual de la web, es van idear els fulls d’estil, és a dir, es va dissenyar el llenguatge CSS (Cascading Style Sheets).

## 1.1. Història i orígens del CSS

El que ara coneixem com a CSS va aparèixer quan l’W3C va rebre 9 propostes diferents per a fulls d’estil, de les quals en va seleccionar dues: Cascading HTML Style Sheets (CHSS), proposta per Håkon Wium Lie el 1994 i Stream-based Style Sheet Proposal (SSP). D’aquí van néixer les Cascading Style Sheets (CSS), la primera versió de les quals, anomenada CSS level 1, va ser proposada com a estàndard a finals de l’any 1996.

El maig de l’any 1998 es va publicar l’estàndard CSS Level 2. Deu anys més tard, el 2008, se’n va fer una revisió i es va publicar el CSS Level 2 Revision 1, conegut com a CSS2.1.

Actualment s’ està treballant amb el CSS3. En aquest cas l’especificació està dividida en mòduls, alguns dels quals ja han esdevingut estàndards i en d’altres encara s’hi està treballant, és a dir, per una part tenim estàndards i per una altra una tecnologia en continu desenvolupament.

Finalment hem de tenir en compte que una vegada tenim un nou estàndard, aquest no és immediatament assolit per tots els navegadors alhora, i és molt útil recórrer a pàgines com  caniuse.com per veure si determinades característiques ja han sigut implementades, per quins navegadors i en quina versió d’aquests navegadors.

<figure>
<img src="../imagenes/CSS3-modulos.png">
<figcaption style="font-size:0.75em">Los módulos definidos en CSS3 ya están listos para ir evolucionando y creciendo de forma independiente. Fuente: Wikipedia</figcaption>
</figure>

## 1.2. El CSS

Usar fulls d’estil ens proporciona els avantatges següents:

+ Possibilitat de mantenir el codi.
+ En el camp de disseny, el CSS és més potent que les marques de disseny que ofereix .
+ El CSS és un llenguatge senzill.
+ Es poden especificar diferents fulls d’estil per a un sol documen. Per exemple, podem tenir l’estil per a la pàgina web quan es visita amb el navegador i l’estil per a quan volem imprimir aquesta pàgina.
+ Els fulls d’estil es poden reutilitzar des de diferents document.

El gran inconvenient dels fulls d’estil és que no tots els navegadors es comporten de la mateixa manera davant del mateix full d’estil. Això es deu al fet que alguns navegadors no compleixen els estàndards establerts i, amb això, obliguen el programador a codificar diferents fulls d’estil (un per a cada navegador). Tot i això, en els últims anys els navegadors cada cop s’acosten més a complir els estàndards proposats.

## 1.3. Ubicació dels estils

El CSS ens defineix quin aspecte han de tenir els element. És per això que hem d’associar d’alguna manera aquestes propietats als elements.

Podem ubicar les propietats CSS en diferents localitzacions:

+ A l’**etiqueta**: afegint les propietats CSS directament a l’element usant l’atribut style. Posem un exemple: suposem que volem que un determinat paràgraf estigui centrat amb lletra vermella. Hem de tenir en compte que aquesta forma d’incloure codificació CSS s’ha de fer servir puntualment, o per fer proves, però no permet reutilitzar el codi en diverses etiquetes.

El codi és el següent:

```html

<p style="text-align:center; color:red">Paràgraf centrat vermell</p>
```

+ A la **capçalera del document*: podem posar les diferents propietats CSS dins de l’element `<style>` que està ubicat dins de l’element <head>. Per exemple, si volem que tots els paràgrafs estiguin centrats i amb lletra vermella, el codi és el següent:

```html

<!doctype html>
<html>
<head>
<meta charset="UTF-8" lang="ca">
<title>Document HTML</title>
<style>
p {
text-align:center;
color:red
}
</style>
</head>
<body>
<p>Paràgraf centrat vermell</p>
<p>Paràgraf centrat vermell</p>
<p>Paràgraf centrat vermell</p>
</body>
</html>
```

L’avantatge de l’ús d’incloure CSS a la capçalera, és que el codi CSS es pot reaprofitar a dins de tot el document i permet que diverses etiquetes comparteixin les característiques estètiques que codifiquem.

+ En un **document extern**: posem totes les propietats dins d’un document amb extensió .css i des del documen enllacem aquest full d’estil amb l’ajuda de l’etiqueta `<link>`, filla de l’element `<head>`. Si volem tenir tots els paràgrafs centrats amb lletra vermella, el documen és:

```html
<!doctype html>
<head>
<meta charset="UTF-8" lang="ca">
<link rel="stylesheet" href="estils.css" />
</head>
<body>
<p>Paràgraf centrat vermell</p>
</body>
</html>

```
El fitxer estils.css té el contingut següent:

```html
p {
text-align:center;
color:red;
}
```

L’avantatge d’usar documents externs per establir les propietats CSS és que podem reutilitzar un mateix full d’estil per a diferents document.

## 1.4. Sintaxi bàsica de CSS

Un full d’estil és un conjunt de **regles** que defineixen l’estètica final dels document que l’usen. Cadascuna d’aquestes regles està formada per un **selector** i per un conjunt de **declaracions**.

Una declaració està formada per una **propietat** amb el seu **valor** associat.

    h1 {color: rgb(0,240,100); }

<table style="text-align:center";>
<th colspan=8 style="background-color: rgb(0,240,100)">Normes d'estil</th>
<tr style="border: rgb(0,240,100) 3px solid; font-weight:bold;"><td>h1</td><td>{</td><td>color</td><td>:</td><td>rgb(0,240,100)</td><td>;</td><td>...</td><td>}</td></tr>
<tr><td style="background-color: rgb(0,240,100)" rowspan=3>Selector</td><td rowspan=2></td><td style="background-color: rgb(0,240,100)">Propietat</td><td></td><td style="background-color: rgb(0,240,100)">Valor</td><td></td><td colspan=2  >Propietat: Valor...</td></tr>
<tr><td colspan=3>Declaració</td><td colspan=3>Declaració...</td></tr>
<tr><td colspan=7>Bloc de Declaració</td></tr>
</table>

## 1.5. Les directives (regles @)

Hi ha un conjunt de regles especials que s’anomenen regles arrova o *at-rules* en anglès. Aquestes regles es caracteritzen perquè comencen pel caràcter @.

Enumerem a continuació quines són aquestes regles i com s’utilitzen:

+ **`@import`**: serveix per incloure al nostre full d’estil fulls d’estil externs. Si, per exemple, volem incloure en el nostre full d’estil totes les propietats que hi ha en el document mesestils.css, hem d’escriure la línia següent:

    `@import "mesestils.css";`

+ **`@media`**: serveix per diferenciar per quin mitjà s’ofereixen les propietats que conté aquesta regla. La sintaxi genèrica és la següent:

    ```css
    @media mitjà{
    propietats
    }
    ```

    on mitjà pot ser print (per imprimir) o screen (per mostrar per pantalla), entre d’altres.

    Imaginem, per exemple, que volem que, quan imprimim el documen, la lletra tingui una mida de 10pt, però que, quan es miri per pantalla, tingui una mida de 12pt. També volem que en ambdós casos l’alçada de la línia sigui d’1.2. En el nostre full d’estil hem d’introduir el codi següent:

    ```css
    @media print {
    body{ font-size: 10pt }
    }
    @media screen {
    body { font-size: 12pt }
    }
    @media screen, print {
    body { line-height: 1.2 }
    }
    ```

    Avui en dia amb l’augment dels diferents tipus de dispositius representa que tenim moltes mides de pantalles diferents (smartsphones, tablets, ordinadors, etc.), aquesta regla ha estat molt útil per aplicar diferents regles CSS de forma condicional, és a dir, aplicar regles diferents CSS, segons el tipus de pantalla o la seva orientació. Aquest tipus de programació se l’ha anomenat **Disseny Adaptatiu** (en anglès *Responsive Web Design* o RWD), i a la combinació de la regla `@media` amb les condicions que podem afegir, se l’ha anomenat ***media-queries***.

+ **`@font-face`**: especifica una font no inclosa en el navegador que l’usuari es descarregarà.
Vegem un exemple:

    ```css
    @font-face {
    font-family: DeliciousRoman;
    src: url("Delicious-Roman.otf");
    }
    p {
    font-family: DeliciousRoman, Helvetica, Arial, sans-serif;
    }
    ```

    En aquest exemple, en la regla `@font-face` estem definit una font. Per tal de definir-la li posem un nom: això es fa amb la propietat `font-family` i en aquest cas hem triat el nom DeliciousRoman. A més, és imprescindible especificar on es troba aquesta font, per tal que el navegador la pugui descarregar i usar, i això es fa amb la propietat src. Veiem que en aquest exemple la font és *Delicious-Roman.otf*.

    Un cop definida la font, podem usar-la en qualsevol regla. Veiem com a l’exemple una regla que ens defineix que tots els paràgrafs (`selector p`) usaran com a font DeliciousRoman. Si aquesta font no estigués disponible, s’usaria la font *Helvètica*, si aquesta tampoc la tingués l’usuari, s’usaria la font *Arial*. Finalment, si no es disposés de cap d’aquestes fonts, s’usaria *sans-serif*.

+ **`@charset`**: especifica quin és el joc de caràcters que farem servir dins del fitxer CSS.
  
    ```css

    @charset "UTF-8"; /* activa el joc de caràcters pel full d'estil a Unicode UTF-8 */
    @charset 'iso-8859-15'; /* activa el joc de caràcters pel full d'estil Latin-9 (Llengües de l'oest d'Europa, amb el símbol de l'euro) */
    ```

+ **`@supports`**: dóna la possibilitat d’especificar una o diverses condicions, que en cas de complir-se posaran en marxa les regles CSS a aplicar. La nomenclatura bàsica és la següent:

    ```css
    @supports (display:flex) {
    section { display: flex }
    ...
    }
    ```

    Al codi anterior ens diu que si existeix per la propietat `display` el valor `flex`, apliqui a tots els elements HTML de tipus `section` d’aquesta propietat.
  
+ **`@page`**: es fa servir per modificar propietats CSS, a l’hora d’imprimir un document, però s'ha de tenir en compte que pot actuar sobre un nombre de propietats CSS limitat.

## 1.6. Comentaris

Com en tot llenguatge, la llegibilitat és imprescindible si treballen en grup. És per això que CSS ofereix una manera de comentar els fulls d’estil.

Si en un full d’estil volem posar comentaris destinats a l’aclariment del codi CSS, hem de fer servir la sintaxi següent:

`/* comentaris */`

Posem un exemple:

```css
/* Estil per a totes les capçaleres del document */
h1 {
   text-align: center; /* Text centrat per destacar la importància*/
   color: red;         /* Color de lletra vermella per emfatitzar el text */  
}
```

## 1.7. Cascada i herència

Dues de les característiques que fan que els fulls d’estil tinguin una gran potència és la **cascada** i l’**herència**.

La **cascada** es refereix a la possible combinació de diferents fulls d’estil. L’**herència** fa referència a la capacitat que tenen els elements del documen d’heretar propietats dels seus elements antecessors.

### 1.7.1. Cascada

Les sigles CSS volen dir *Cascading Style Sheets* (‘Fulls d’estil en cascada’). Però, què vol dir cascada en aquest àmbit? Doncs vol dir que podem combinar diferents fulls d’estil i que les propietats de tots ells es van acumulant. Això ens és molt útil quan pensem en llocs web grans, on podem tenir un full d’estil bàsic i anar incorporant-hi altres fulls d’estil, segons les nostres necessitats.

Ara caldria preguntar-nos: si podem combinar diferents fulls d’estil, pot donar-se el cas que hi hagi propietats que es contradiguin? Si es dóna aquest cas, com se soluciona? Quina propietat té prioritat? Per solucionar aquest problema hi ha establerta la jerarquia següent, en ordre de prevalença:

1. **Propietats establertes per l’autor de la web**: les propietats que estableix l’autor es poden ubicar en diferents llocs i, segons aquesta ubicació, la propietat té més o menys prioritat. La jerarquia és la següent, per ordre de quina preval sobre les altres:
   
    + Propietats establertes en l’atribut `style` d’un element o `Inline style`.
    + Propietats establertes en l’element `<style>` del documen, o Internal Style Sheet.
    + Propietats establertes en un **full d’estil extern**, o External Style Sheet.
 
    D’aquesta manera podem dir que l’ordre de prioritat ve marcat per la proximitat amb l’element que l’afecta, sent la més prioritària Inline Style i la menys External Style Sheet.

2. **Propietats establertes per l’usuari**: els navegadors permeten a l’usuari establir diferents propietats d’estil: mida de la lletra, colors…

3. **Propietats establertes pel navegador**: els navegadors tenen un estil predeterminat per a cadascun dels element. Si no s’ha establert cap propietat en els ítems anteriors, les propietats del navegador són les que prevalen.

Posem un exemple que mostri la jerarquia d’estils dins de les propietats que defineix l’autor del web. Imaginem que tenim els següents fitxers:

El fitxer index.html:

```html
<!doctype html >
<html lang="ca">
<head>
...
<link rel="stylesheet" href="estils.css" />
<style>
   p {
      color: red;
   }
</style>
</head>
<body>
   <h1>Encapçalament</h1>
   <p style="color: blue">Un paràgraf</p>
   <p>Un altre paràgraf</p>
</body>
</html>
```

El fitxer estils.css:

```css
p {
   color: green;
}
h1 {
   color: violet;
}
```

En l’exemple anterior, podríem pensar que les tres declaracions que apareixen estan en contradicció: el full d’estil estils.css té una regla que ens diu que tots els paràgrafs tindran la lletra de color verd; l’element `<style>` del document **index.html** ens diu que tots els paràgrafs d’aquest document seran de color vermell, i l’etiqueta `style` del primer paràgraf del document index.html ens diu que aquest paràgraf serà de color blau. La pregunta és: de quin color seran aquests paràgrafs i per què?

La resposta correcta és que el primer paràgraf serà de color blau perquè l’atribut style és la ubicació amb més alta jerarquia mentre que el segon paràgraf serà de color vermell ja que no té cap atribut style, però la regla que apareix dins l’element `<style>` preval damunt la regla que apareix en el document **estils.css**.

Per últim, s’ha de fer notar que el color de lletra de l’encapçalament `<h1>` serà violeta, tal com està establert al fitxer estils.css, ja que és l’única regla que tenim que faci referència a l’etiqueta `<h1>`.

Posem un altre exemple per mostrar la poca prevalença de les propietats establertes pel navegador. Imaginem el següent fitxe:

```html
<!doctype html >
<html lang="ca">
<head>
...
</head>
<body>
   <p>Un paràgraf amb una <strong>paraula molt emfatitzada</strong></p>
</body>
</html>
```

Si mirem aquest fitxer amb la majoria de navegadors, ens adonarem que la cadena paraula molt emfatitzada apareix en negreta. Això es deu al fet que, en absència de la definició de cap estil per part de l’autor de la web, el navegador decideix que per emfatitzar molt una cadena la posarà en lletra negreta.

Modifiquem el codi anterior, afegint un estil per a l’etiqueta `<strong>`:

```html
<!doctype html>
<html lang="ca">
<head>
...
<style>
   strong {
      font-weight: normal;
      color:red;
   }
</style>
</head>
<body>
   <p>Un paràgraf amb una <strong>paraula molt emfatitzada</strong></p>
</body>
</html>
```

Si ara visualitzéssim la web, ens adonaríem que la cadena paraula molt emfatitzada ja no apareix en negreta, a causa de la declaració `font-weight: normal` i a més apareix de color vermell gràcies a la declaració `color:red`. Això ens mostra que les propietats establertes per l’autor prevalen per sobre de les propietats establertes pel navegador.

En el cas de la prevalença entre les propietats establertes per l’autor de la web i les propietats establertes per l’usuari, hi ha la possibilitat d’invertir l’ordre posant la cadena **`!important`** després de la declaració.

Aquest fet ens pot servir perquè la pàgina sigui més accessible, ja que si, per exemple, un usuari té problemes de visió, li permetem que pugui fer la lletra més gran, tot i que l’aplicació estigui pensada per ser visualitzada amb una lletra més petita.

Imaginem doncs que dissenyem una web on volem que la font sigui petita, però que volem permetre que l’usuari la canviï, si així ho desitja, mitjançant la configuració apropiada del seu navegador. Per fer-ho, codificarem la següent regla CSS:
```css
body{
   font-size: small !important;
}
```

Finalment, es podria donar el cas que ens trobem dues regles en el mateix nivell de jerarquia. Com se soluciona aquest “empat”? Doncs bé, si ens trobem en el cas que les propietats “empaten”, l’última propietat escrita és la que “guanya”. Per exemple, fixeu-vos en el codi següent en un full d’estil extern (i suposant que no hi ha més regles que se superposin en el fitxer HTML des d’on es cridi aquest full d’estil):

```css
p{
  color:red;
}
...
p{
  color:green;
}
...
```

En aquest cas la lletra dels paràgrafs serà sempre de color verd, ja que és l’última regla escrita en el document CSS. La regla on diu que el color de lletra dels paràgrafs serà de color vermell queda completament invalidada.

Moltes vegades, com que no marquem cap propietat per CSS sobre elements, i atès que el navegador porta per defecte algunes propietats ja establertes, aquestes s’apliquen per defecte. Si no volem que això sigui així, és molt habitual que els desenvolupadors facin servir un full d’estil extern on “inicialitzen” totes les propietats preestablertes pel navegador. Un exemple d’això el podem trobar a l’anomenat **reset css** de  meyerweb.com.

A l’annex trobareu el fitxer reset.css agafat de la web meyerweb.com

El codi que faríem servir per afegir aquest reset css, l’afegiríem com un document extern abans (a l’exemple reset.css) que la resta de fitxers CSS externs que féssim servir (a l’exemple estilspropis.css). Tal com indica l’exemple següent:

```html
<!doctype html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Exemple de document amb reset CSS </title>
	<link rel="stylesheet" href="css/reset.css" />
	<link rel="stylesheet" href="css/estilspropis.css" />
	<!-- En podem afegir d'altres -->
</head>
Cos del document
<body></body>
</html>
```

### 1.7.2. Herència

Tots els elements d’una pàgin, amb l’excepció de l’element arrel `<html>`, estan continguts en un altre element.

Quan parlem d’herència ens referim al fet que tot element hereta les propietats dels seus elements antecessors. Malgrat tot, hem de tenir en compte el següent:

+ No totes les propietats s’hereten. Aquesta característica està descrita en l’especificació de CSS corresponent.
+ Si volem forçar l’herència en una propietat, podem introduir-hi el valor inherit.
+ Si posem un valor a una propietat, aquest valor preval sobre el valor heretat.
+ Els elements hereten el valor computat, no el valor especificat. És a dir, si una propietat té per valor un valor relatiu (per exemple, un percentatge), el valor heretat és el resultat calculat.
Posem un exemple per veure l’herència de CSS en acció, considerem el següent codi:

```html
<! DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3c.org/TR/xhtml1/
DTD/xhtml1-strict.dtd " >
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="ca" lang="ca">
<head>
...
<style>
   body{
      font-size: small;
   } 
   p {
      color: gray;
   }
   strong {
      font-style: italic;
   }
</style>
</head>
<body>
   <p>Un paràgraf amb una <strong>text molt emfatitzat</strong></p>
</body>
</html>
```

Fixem-nos que l’element `<strong>` és a dins de l’element `<p>`, que està contingut a l’element `<body>`. Això vol dir que la cadena text molt emfatitzat tindrà les següents propietats: evidentment estarà en cursiva perquè així ho especifica la propietat `font-style`: italic de tots els elements `<strong>`, però a més, com que aquest element `<strong>` és a dins de l’element `<p>` i el color de lletra de tots els paràgrafs és el gris, tal com diu la propietat color: gray, la cadena també serà de color gris. És més, com que l’element `<p>` és a dins de l’element `<body>`, `<strong>` també hereta la declaració `font-size: small`. En resum, la cadena text molt emfatitzat tindrà lletra petita, serà de color gris i estarà en cursiva.

# 2. Regles CSS

Per tal de donar forma estètica a una web, necessitem moltes funcionalitats diferents: colors, fonts, posicionament dels elements… A partir de la codificació de regles CSS, amb els seus selectors i propietats, podem aconseguir els nostres objectius.

L’especificació CSS estableix més selectors i propietats que les que es presenten en aquests materials. Trobareu un llistat complet a l’Annex “Referències ràpides” del material web d’aquesta unitat.

Com que en l’actualitat l’estàndard que fem servir és CSS3, i aquest està en contínua transformació, ens trobem que no tots els navegadors han adoptat algunes de les propietats, o si ho han fet, moltes vegades necessiten un prefix abans de la propietat, per tal que funcionin correctament. Aquests prefixos el farem servir, quan així sigui necessari, als codis exemples d’aquesta unitat i són:

-moz-: prefix per al navegador Firefox.
-ms-: prefix per al navegador Internet Explorer.
-webkit-: prefix per als navegadors Chrome i Safari.
-o-: prefix per al navegador Opera.

## 2.1. Selectors

Un selector és la part de la regla CSS que identifica l’element o elements del documen dels quals volem definir propietats.

Hi ha diferents tipus de selectors: des dels més simples, on només és posa la marc a la qual volem modificar l’estètica, fins a combinacions complexes d’aquests selectors.

### 2.1.1. Selectors de tipus
Els selectors de tipus són els selectors més simples: es tracta únicament d’especificar l’etiquet. Afecten a tots els element amb aquella etiqueta.

La sintaxi genèrica és la següent:

```css
etiqueta {
   declaracions
}
```

Imaginem que volem que tots els encapçalaments de primer ordre, amb marca `<h1>`, siguin de color blau. El codi és el següent:

```css
h1 {
   color: blue;
}
```

Però, i si no volem modificar l’aparença de tots els elements d’un mateix tipus? Per aconseguir això hem d’usar altres tipus de selectors, com ara els selectors de classes o els selectors d’identificadors.

### 2.1.2. Selectors de classe

Els selectors de classe serveixen per associar propietats a tots els elements que tinguin l’atribut class d’igual valor. Si en el documen tenim:

`<etiqueta class="nomclasse">...</etiqueta>`

podem introduir la regla següent amb un selector de classe:

```css
etiqueta.nomclasse {
   declaracions
}
```

Això fa que a tots els elements etiqueta que tinguin l’atribut class amb valor nomclasse se’ls apliquin les propietats especificades.

També podem definir un selector de classe més genèric, que no depengui de l’etiqueta de l’element. És a dir, podem definir la regla següent:

```css
.nomclasse {
   declaracions
}
```

Aquesta regla fa que qualsevol element amb l’atribut class amb valor nomclasse compleixi les declaracions especificades.

Posem un exemple: volem que tots els paràgrafs siguin de color verd, excepte els de classe destacat, que són de color vermell. El codi CSS és el següent:

```css
p {
   color: green;
}
 
p.destacat {
   color: red;
}
```

Qualsevol paràgraf amb etiqueta `<p>` tindrà el color de lletra verd, però si introduïm un paràgraf amb classe destacat, `<p class=“destacat”>`, la lletra d’aquest paràgraf serà de color vermell.

Si el que volem és que qualsevol element amb `class=“destacat”` tingui la lletra vermella, hem d’escriure el codi següent:

```css
.destacat {
   color: red;
}
```

Això implica que més d’un element, o fins i tot elements de diferent tipus, poden compartir el mateix nom de classe.

### 2.1.3. Selectors d'identificador

Els selectors d’identificador serveixen per associar unes propietats a l’element que té un determinat identificador. L’identificador d’un elemen es declara amb l’atribut id de l’element. Hem de tenir en compte que en un documen no hi pot haver dos elements amb el mateix identificador. Si en el documen tenim:

`<etiqueta id="nomidentificador">...</etiqueta>`

podem escriure la regla següent amb un selector d’identificador:

```css
etiqueta#nomidentificador {
   declaracions
}
```

Podem introduir la mateixa regla prescindint de quin element porti l’identificador, és a dir, podem especificar:

```css
#nomidentificador {
   declaracions
}
```

Si, per exemple, volem que el paràgraf amb identificador principal,`<p id=“principal”>`, estiguin centrats haurem d’escriure:

```css
p#principal {
   text-align: center;
}
```

Si no ens importa l’etiqueta, és a dir, si volem que l’element amb identificador principal, sigui quin sigui l’element, estigui centrat haurem d’escriure:

```css
#principal {
   text-align: center;
}
```

### 2.1.4. Selectors d'atribut

Els selectors d’atribut serveixen per aplicar les propietats de la regla als elements que tenen un atribut concret. El selector següent:

```css
tag[atribut] {
   declaracions
}
```

afecta tots els element amb la següent sintaxi:

`<etiqueta atribut="valor">...</etiqueta>`

Per exemple, si volem que hi hagi un marge dret de 2em en tots els elements `<img>` que tinguin establert l’atribut title, hem d’escriure el següent:

```css
img[title] {
   margin-right: 2em;
}
```

Els elements afectats per aquesta regla seran similars al següent:

`<img src="imatges/river.png" alt="River" title="riv" />`

En canvi, si tinguéssim un element com el següent:

`<img src="imatges/river.png" alt="River" />`

no es veuria afectat per la regla, ja que no disposa de l’atribut `title`.

Els selectors d’atribut permeten diverses variants. Una d’aquestes variants és que podem jugar amb el valor de l’atribut. Per exemple, si volem establir un marge dret de 4em en totes les imatges que tenen establert l’atribut title i que, a més, aquest atribut té per valor river, la regla CSS hauria de ser la següent:

```css
img[title="river"] {
   margin-right: 4em;
}
```

En aquest cas l’element

`<img src="imatges/river.png" alt="River" title="river" />`

seguiria veient-se afectat, però un element com el següent:

`<img src="imatges/river.png" alt="River" title="riv" />`

no tindria el marge dret a 4em ja que no compliria allò que diu el selector: el valor de title és riv, no river.

També podem filtrar per més d’un atribut. Per exemple, imaginem que ara volem seleccionar tots els elements `<img>` que tenen l’atribut title i que són de classe preferent, com el següent element:

```html
<img src="imatges/river.png" alt="River" title="riv" class="preferent" />
```

La regla CSS seria:

```css
img[title][class="preferent"] { 
   margin-right: 6em; 
}
```

Finalment, podem filtrar segons una part del valor de l’atribut. Disposem de dues fórmules per fer-ho:

`[atribut~=“valor”]`: s’usa per seleccionar els elements que tenen com a atribut una llista de paraules separades per espais, una de les quals és exactament valor.
`[atribut|=valor]`: s’usa per seleccionar els elements que tenen com a atribut una llista de paraules separades per guions, començant per valor.
Posem un exemple per a cada cas:

```css
img[alt~="Riu"] {
   border: solid;
}

 
p[lang|="en"] {
   font-family: "Times New Roman", serif;
}
```

La primera regla selecciona les imatges en les quals l’atribut alt té per valor una cadena que conté la paraula Riu, com per exemple alt=“Riu Muntanyes”. La segona regla selecciona els paràgrafs que tenen com a valor de l’atribut lang, paraules que comencen amb en, com en-US o en-cockney.

CSS3 afegeix tres nous selectors d’atribut. Vegem-los:

element`[atribut^=“text”]`: selecciona elements amb aquest atribut, el valor del qual comença per text.
element`[atribut$=“text”]`: selecciona elements amb aquest atribut, el valor del qual acaba amb text.
element`[atribut*=“text”]`: selecciona elements amb aquest atribut, el valor del qual conté text.

### 2.1.5. Selector universal

El selector * s’anomena selector universal i afecta tots els elements del document. La sintaxi és la següent:

```css
* {
   declaracions
}
```

Per exemple, la següent norma:

```css
* {
   font-size: 12px;
}
```

faria que tot el text del document tingués una mida de 12px, independentment de l’etiqueta que l’envolti.

### 2.1.6. Selectors de descendents

Diem que un element és descendent d’un altre quan aquest element està contingut en l’altre, no importa a quin nivell. Per tant, un selector de descendents ens permet seleccionar tots els elements que estan continguts en un altre. La sintaxi genèrica és la següent:

```css
etiqueta etiqueta_descendent { 
   declaracions
}
```

Per exemple, si volem posar en blau tots els elements `<em>` continguts en un paràgraf hem d’escriure:

```css
p em {
   color: blue;
}
```

Aquesta regla afectaria tant al text èmfasi com al text paraula del següent cod, ja que els dos elements `<em>` són descendents d’un element `<p>`:

```html
<p>Paràgraf amb una paraula amb <em>èmfasi</em>. Aquesta altra <span><em>paraula</em></span> és a dins d'un &lt;span&gt; que conté un &lt;em&gt;</p>
```

Podem posar més nivells i barrejar altres tipus de selectors. Imaginem un exemple més complex: volem posar amb lletra vermella tots els elements de classe destaca que estiguin continguts en paràgrafs que alhora estan continguts en elements `<div>`:

```css
div p .destaca {
   color: red;
}
```

A quin tipus d’element afectaria aquesta regla? Vegem-ne un exemple:

```html
<div>
   <p> Aquesta <span class="destaca">paraula</span> l'hem de destacar.</p>
</div>
```

En aquest cas el text paraula apareixeria en vermell, ja que l’element `<span>` és un element de classe destaca descendent d’un element `<p>` que és descendent d’un element `<div>`.

### 2.1.7. Selectors de fills

Un element és fill d’un altre si és descendent de primer nivell.

Per exemple, en el següent codi HTML:
```html
<p><span class="destaca">Els orígens dels <em>fulls d'estil</em></span> es remunten als anys 90.</p> 
L’element <em> és fill de l’element <span>, però no és fill de l’element <p>.
```

Els selectors de fills ens permeten seleccionar els fills d’un determinat element. El símbol que hem d’usar és >:

```css
etiqueta > etiqueta_filla {
   declaracions
}
```

Per exemple, suposem que tenim les regles següents en el nostre document CSS:

```css
body > p {
   font-weight: bold;
}

div ol > li p {
   text-decoration: underline;
}
```

La primera línia de l’exemple fa que tots els paràgrafs que són fills de `<body>` estiguin en lletra negreta.

La segona regla és una mica més complexa: el selector afecta tots els elements `<p>` que són descendents d’un element `<li>`, on l’element `<li>` ha de ser fill d’un element `<ol>` que, alhora, ha de ser descendent d’un element `<div>`.

En un exemple quedaria:

<iframe height="265" style="width: 100%;" scrolling="no" title="selectors-css-fills" src="http://codepen.io/rglepe/embed/PLGXMY/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/PLGXMY/'>selectors-css-fills</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

En aquest exemple, veiem com el primer paràgraf està en negreta perquè es fill de `<body>`. En canvi, el segon paràgraf no està en negreta ja que, tot i ser descendent de `<body>`, no n’és fill directe.

En el cas de les llistes veiem que només apareixen subratllats aquells paràgrafs descendents dels elements `<li>` que són fills directes d’un `<ol>`. Veiem també que el text que no està en un paràgraf no està subratllat ja que la regla només afecta els paràgrafs descendents de `<li>`. Finalment, podem observar que tots aquells paràgrafs descendents de la llista no numerada tampoc estan subratllats, ja que tot i ser descendents d’un element `<li>`, aquest no és fill d’un element `<ol>`, sinó que és fill d’un element `<ul>`.

### 2.1.8. Selectors de germans adjacents

Els selectors de germans adjacents ens permeten, donat un element, atorgar propietats al seu germà immediatament posterior. El símbol usat és el +:

```css
etiqueta + etiqueta_adjacent {
   declaracions
}
```

Per exemple, si al següent exemple volguéssim reduir l’espai vertical que hi ha entre l’`<h1>` i l’`<h2>` que el segueix immediatament definiriem la regla següent:

```css
h1 + h2 { 
   margin-top: -5mm;
}
```

<iframe height="265" style="width: 100%;" scrolling="no" title="selectors-css-germans" src="http://codepen.io/rglepe/embed/jJMdMB/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/jJMdMB/'>selectors-css-germans</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

S'observa que l'encapçalament `<h1>` i l'encapçalament `<h2>` (germà adjacent) estan més junts. El segon element `<h2>` és a la distància per defecte, ja que, tot i ser un germà de l’element `<h1>` (estan al mateix nivell), no és un germà adjacent d’aquest element.

Complicant una mica la regla anterior, podem fer que la regla només s’apliqui si l’element `<h1>` és de la classe obert (`class=“obert”`):

```css
h1.obert + h2 { 
   margin-top: -5mm;
}
```

### 2.1.9. Selector general de germans

A la versió actual de CSS (CSS3) disposem del selector selector general de germans, representat amb el símbol ~, que permet seleccionar tots els germans d’un element, siguin adjacents o no.

Vegem un exemple:

```html
<h1>...</h1>
<p>...</p>
<div>
   <p>...</p>
</div>
<p>...</p>
```
La regla css seria:
```css
h1 ~ p {
   color: gray;
}
```

En aquest cas, el text del primer i del tercer paràgrafs que apareixen en el cod serien de color gris. El segon paràgraf no ho seria perquè no és germà d’un element `<h1>`.

### 2.1.10. Agrupament de selectors

Si diversos selectors tenen les mateixes propietats, podem agrupar-los separant els selectors per una coma. La sintaxi és la següent:

```css
selector1, selector2, selector3 {
   declaracions
}
```

Per exemple, les regles següents:

```css
h1 { 
   font-family: sans-serif;
   color: orange; 
}
 
h2 { 
   font-family: sans-serif; 
   color: orange;
}
 
h3 { 
   font-family: sans-serif; 
   color: orange; 
}
```

són equivalents a la regla següent, on hem agrupat els tres selectors:

```css
h1, h2, h3 { 
   font-family: sans-serif; 
   color: orange; 
}
```

Posem un altre exemple, on no coincideixin totes les declaracions. Imaginem que tenim les següents regles:

```css
h1 { 
   font-size: 20px;
   font-family: sans-serif;
   color: orange; 
}
 
h2 { 
   font-size: 18px;
   font-family: sans-serif; 
   color: orange;
}
 
h3 { 
   font-size: 16px;
   font-family: sans-serif; 
   color: orange; 
}
```

Podem observar que la primera declaració és diferent per a cadascuna de les regles, però la resta de declaracions són iguals. Podríem obtenir els mateixos resultats codificant el següent:

```css
h1 { 
   font-size: 20px;
}
 
h2 { 
   font-size: 18px;
}
 
h3 { 
   font-size: 16px;
}
 
h1, h2, h3 { 
   font-family: sans-serif; 
   color: orange; 
}
```

## 2.2. Pseudoclasses i pseudoelements

Les pseudoclasses i els pseudoelements serveixen per afegir alguns efectes addicionals a alguns selectors. La seva sintaxi genèrica és:

```css
selector:pseudo_classe {
   declaracions
}

selector::pseudoelement {
   declaracions
}
```

### 2.2.1. Pseudoclasses

A continuació enumerem les **pseudoclasses** existents amb la seva descripció i alguns exemples:

* `:first-child`: selecciona un element que és el primer fill d’un altre element. Per exemple:

   ```css
   /* Els paràgrafs fills de div.nota tindran un sagnat d'1em */
   div.nota > p {
      text-indent: 1em;
   }

   /* El primer paràgraf fill dels elements div.nota tindrà un sagnat de 2em */
   div.nota > p:first-child {
      text-indent: 2em;
   ```

   ```html
   <p> Paràgraf exterior al &lt;div&gt;</p>
   <div class="nota">
      <p>Primer paràgraf fill de &lt;div&gt;</p>
      <p>Segon paràgraf  fill de &lt;div&gt;</p>
   </div>
   </body>
   ```

* `:link`: permet definir l’estil dels enllaços de la nostra pàgina, quan encara no s’han visitat.
  
* `:visited`: permet definir l’estil dels enllaços de la nostra pàgina, quan ja s’han visitat.
  
Aquestes dues pseudoclasses ens permeten modificar el comportament per defecte dels enllaços, és a dir, substituir el color blau i subratllat pels enllaços no visitats (link) i el color lila i subratllat pels enllaços visitats (visited), per altres colors i format de text.

* `:active`: permet definir l’estil dels elements quan s’activen (quan premem el ratolí damunt seu).
* `:hover`: permet definir l’estil dels elements quan passem per damunt seu.
És molt comú fer servir aquestes dues pseudoclasses, en combinació amb link i visited, per donar major dinamisme als enllaços, tot i que active i hover es fan servir també per altres tipus d’elements.
* `:focus`: permet definir l’estil dels elements quan reben el focus.

Exemple de les pseudoclasses anteriors:

<iframe height="265" style="width: 100%;" scrolling="no" title="pseudoclasses" src="http://codepen.io/rglepe/embed/NJRmoq/?height=265&theme-id=0&default-tab=css,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/NJRmoq/'>pseudoclasses</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

* `:lang`: permet definir les propietats segons l’idioma.
  
Per exemple, si volem establir que els paràgrafs que tenen l’atribut lang amb valor ca (`<p lang=“ca”>…</p>`) estiguin amb lletra vermella, hem de definir-ho amb la regla següent:

```css
p:lang(ca) {
   color: red;
}
```

* `:last-child`: selecciona els elements indicats, però amb la condició que siguin l’últim fill del seu element pare.
* `:nth-child(nombre)`: selecciona els elements indicats, però amb la condició que sigui el fill n-èsim del seu element pare.
* `:nth-last-child(nombre)`: funciona com la pseudoclasse anterior, però els fills es comencen a comptar pel final.
* `:nth-of-type(nombre)`: selecciona els elements indicats, però amb la condició que sigui el fill n-èsim d’aquest tipus. Com a valor, a més de posar nombres, podem posar ‘odd’ que recuperarà tots els fills en posició senar o ‘even’ que recuperarà tots els fills en posició parell.
* `:nth-last-of-type(numero)`: funciona com la pseudoclasse anterior, però els fills es comencen a comptar pel final.
* `:empty`: selecciona l’element, però amb la condició que aquest no tingui fills (ni altres elements ni text).

### 2.2.2. Pseudoelements

A continuació s'enumeren els pseudoelements disponibles:

* `::first-line`: permet definir l’estil de la primera línia de l’element.
* `::first-letter`: permet posar propietats d’estil a la primera lletra de l’element.
* `::after`: permet introduir contingut al final de l’element. Haurem d’afegir la propietat content amb el valor desitjat.
* `::before`: permet introduir contingut a l’inici de l’element. Haurem d’afegir la propietat content amb el valor desitjat.
* `::selection`, afecta allò que l’usuari ha seleccionat amb el ratolí.

A continuació s'exposa un exemple on participen tots aquests pseudoelements:

<iframe height="265" style="width: 100%;" scrolling="no" title="pseudoelements" src="http://codepen.io/rglepe/embed/pYNgEo/?height=265&theme-id=0&default-tab=css,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/pYNgEo/'>pseudoelements</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

## 2.3. Propietats bàsiques de format

Per tal de definir les declaracions d’una regla tenim disponibles un seguit de propietats que ens permeten modificar l’aparença dels elements: grandària, colors, tipografia…

### 2.3.1. Mesures

Algunes de les propietats que podem establir en el full d’estil tenen com a valor una unitat de mesura que ens indica la mida de la propietat (mides de lletra, amplades, marges…). Aquestes unitats de mesura poden ser unitats relatives o absolutes:

<p style="background-color:rgba(200,200,200,0.6); font-family:arial; font-size: 0.75em"> La unitat de mesura <strong> "em"</strong><br><br>
Una de les unitats de mesura més usades, és la mesura em. 1em és equivalent a la mida de la font actual. Per tant, 2em és dues vegades la mida de la font actual.
Per exemple, si un element es mostra amb una mida de 10pt, llavors 2em equival a una mida de 24pt.
</p>

Les unitats relatives les podem mesurar de molt diverses maneres:

* **`em`**: relativa a la mida del tipus de lletra usat. Hem de tenir en compte que aquesta unitat té com a referència el seu contenidor.
  
* **`rem`**: relativa a la mida del tipus de lletra general, és a dir, té com a referència la unitat que fa servir l’element arrel (root), i no l’element contenidor.
* **`px` (pixels)**: possiblement és la mesura més popular i té a veure amb la resolució que ofereixen les pantalles que mostren l’HTML.
* **`%`**: unitat percentual.
**`ex`**: relativa a l’alçada de la lletra x. Canvia si es canvia la font que fem servir.
**`ch`**: similar a l’anterior, però és relativa al caràcter numèric 0.

També disposem d’unitats relatives al viewport, és a dir, a l’amplitud de la finestra del navegador:

* **`vw` (viewport width)**: 1vw equival a (1/100) de l’amplada de la finestra, és a dir, 1%. Per reflectir un valor del 15% hauríem de posar 15vw.
* **`vh` (viewport height)**: el mateix funcionament que l’anterior però respecte a l’alçada (height).
* **`vmin`**: el funcionament és molt similar als anteriors, però hi ha una avaluació prèvia de quin eix, x o y, és menor i selecciona com a referent l’eix que ho sigui.
* **`vmax`**: idèntic a l’anterior, però agafant com a referent l’eix que sigui més gran dels dos.

Les unitats absolutes es poden mesurar amb centímetres, amb mil·límetres , amb polzades o amb punts:
* **`cm`**: centímetres.
* **`mm`**: mil·límetres.
* **`in`**: polzades (inches).
* **`pt`** (punts): és una mesura física, i equival a 1/72 part d’una polzada.
* **`pc`** (piques): és molt semblant a l’anterior 1pc equival a 12pt.

Un altre factor a tenir en compte és que els navegadors per defecte tenen un valor habitual de font de 16px, per aquest motiu 1em = 16px = 0.17in = 12pt = 1pc = 4.2mm = 0.42cm

Quant a les unitats relatives, hem de destacar que una distància definida en px no canvia si l’usuari canvia la mida del text en el seu navegador o si l’usuari canvia la mida de la finestra del navegador, però sí que canvia si l’usuari canvia la resolució de la pantalla. En canvi, una distància definida en em o en percentatge és proporcional a la mida de la font establerta pel navegador. Per tant, si l’usuari canvia la mida del text en el seu navegador, la mesura augmenta o disminueix proporcionalment.

### 2.3.2. Colors

Algunes propietats tenen com a valor un color (color de la lletra, color de fons…). Els colors es poden expressar amb paraules clau, RGB, Hexadecimal o HSL.

* Les **paraules clau** expressen el color que volem mostrar en anglès, de manera que és molt senzill de recordar: red és vermell, green és verd, blue és blau… L’inconvenient d’usar paraules clau per fer referència a un color és que estem limitats a usar un nombre determinat de colors (165 colors, en aquest [enllaç](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value#Color_keywords) trobem la llista complerta).

* Amb **RGB** es pot obtenir tota la gamma de colors, és a dir, es fa ús dels tres components de color bàsics (Red Green Blue). RGB permet especificar quina tonalitat es vol de cadascun dels colors bàsics: el vermell, el verd i el blau. Per a cada color bàsic es pot donar un valor comprès entre 0 i 255. Aquest valor s'el pot especificar en base decimal o en base hexadecimal.
  Per exemple, el color vermell tindrà el valor màxim de vermell i 0 per al verd i el blau.
Si el volem escriure amb base decimal haurem de posar:`rgb(255,0,0)`. Amb aquesta expressió diem que volem 255 de vermell, 0 de verd i 0 de blau.

* Si el volem expressar amb valor **hexadecimal** haurem d’escriure:`#FF0000`. Amb aquesta expressió estem dient, que volem FF de vermell (el nombre FF en hexadecimal és el nombre 255 en decimal), 00 de verd i 00 de blau. Així doncs, si expressem el color en hexadecimal, els dos primers dígits corresponen al vermell, els dos següents al verd i els dos últims al blau.
CSS ens dóna la possibilitat de simplificar l’escriptura si els dos caràcters d’un component de color són iguals, i deixar exclusivament 1 per cada parell, és a dir, el color #FF0000 es pot simplificar per #F00, o en altre exemple és que el color #AACC66 es pot simplificar per #AC6
Dos colors molt comuns són el blanc i el negre. El blanc (white), és la suma dels tres colors bàsics, per tant el podem expressar com #ffffff o bé com rgb(255, 255, 255). En canvi, el negre és l’absència dels colors bàsics, per tant és #000000 o bé rgb(0, 0, 0).

Un petit resum orientatiu amb els colors bàsics ([Basic Colors](https://www.w3.org/TR/css-color-3/))

![](https://imgur.com/rK0PEvo.png)

* Des de CSS3 es compte amb els colors **hsl** (hue, saturation, lightness) més intuitius i fàcils d'utilitzar.
  * **Hue** ( tonalitat ) el tipus de color (com vermell, blau o groc). Es representa com una roda de colors. Cada grau d'angle és un color. Els valors possibles van de 0 a 360° (encara que per a algunes aplicacions es normalitzen del 0 al 100%). Cada valor correspon a un color. Exemples: 0 és vermell, 60 és groc, 120 és verd, blau és 240 i de nou vermell és 360º.
  *  **Saturation** (saturació). Es representa com la distància a l'eix de brillantor negra-blanca. Els valors possibles van del 0 al 100%. A aquest paràmetre, també se'l sol anomenar "puresa" per l'analogia amb la puresa d'excitació i la puresa colorimètrica de la colorimetria. Com menor sigui la saturació d'un color, major tonalitat grisenca hi haurà i més descolorit estarà. Per això, és útil definir la insaturació com la inversa qualitativa de la saturació.
  *  **lightness** (luminància). Es representa la luminositat d'un color en percentatges. Pot agafar valors entre 100% (blanc) i 0% (absència de color o negre).

### 2.3.3. Colors amb transparència RGBA o HSLA

Els navegadors més importants suporten una altra manera d’establir el color, l‘rgba (hsla), que accepta un quart paràmetre a més més dels tres colors bàsics. Aquest quart paràmetre és l’anomenat canal alfa, que determina la transparència del color i pot agafar valors compresos entre el 0.0 (transparència total) i l’1.0 (opacitat total). Per exemple, per posar un vermell mitjanament transparent escriuríem:`rgba(255,0,0,0.5)`

### 2.3.4. Fonts

El llenguatge CSS ens permet descriure les fonts del text contingut a cadascun dels elements HTML.

Les propietats de què disposem per descriure les fonts del nostre document són les següents:

* `font-family`: canvia el tipus de font. Es poden posar diversos tipus, separats per una coma, de manera que si el navegador no disposa del primer tipus, usa el segon, si no té el segon, usa el tercer i així consecutivament.
Hem de tenir en compte que podem establir com a valor una de les famílies genèriques existents. Si usem una família genèrica, ens assegurem que el navegador posi almenys una font similar a la que nosaltres volem. Les famílies genèriques són:

  * `serif`: els caràcters tenen petits acabats en els seus extrems.
  * `sans-serif`: els caràcters no tenen petits acabats en els seus extrems.
  * `monospace`: tots els caràcters tenen la mateixa amplada.

  Podeu veure la diferència entre aquestes grans famílies a la 

  Figura Exemple de font de la família serif

  ![Serif](https://upload.wikimedia.org/wikipedia/commons/thumb/2/26/Serif_and_sans-serif_03.svg/200px-Serif_and_sans-serif_03.svg.png)

  Figura Exemple de font de la família sans-serif

  ![sans-serif](https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Serif_and_sans-serif_01.svg/200px-Serif_and_sans-serif_01.svg.png)

  Figura Exemple de font de la família monospace

  ![monospace](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e1/Monospace_font.svg/200px-Monospace_font.svg.png)

  Vegem un exemple:

  ```css
  body{ 
     font-family: Gill, Helvetica, sans-serif; 
  }
  ```

  En aquest cas tots els elements descendents de `<body>` heretaran aquesta propietat. El navegador intentarà usar la font Gill. Si no la té, intentarà usar l‘Helvetica. Finalment, si tampoc la té, usarà una font de la família genèrica sans-serif.

* `font-style`: permet posar la lletra en cursiva. Si volem que la lletra estigui en cursiva establirem el valor a italic. Si volem treure la lletra cursiva, posarem el valor normal. Vegem un exemple:

   ```css
   h1, h2, h3 { 
      font-style: italic; 
   } 
   
   h1 em { 
   font-style: normal; 
   }
   ```

   Amb aquestes regles estem aconseguint que tot el text inclòs en les etiquetes `<h1>`, `<h2>` i `<h3>` estigui en lletra cursiva, excepte els elements `<em>` descendents d’`<h1>`, que no ho estaran.

* `font-variant`: serveix per establir el valor small-caps. Si volem anul·lar aquest valor, haurem d’establir el valor normal. D’altra banda, small-caps converteix els caràcters que estan en minúscules a majúscules, però amb una tipografia més petita. Vegem-ne un exemple:

   ```css
   h3 { 
      font-variant: small-caps;
   }
   ```

* `font-weight`: serveix per posar la lletra en negreta. Per posar-la usarem el valor bold i per treure-la usarem el valor normal. Un exemple seria el següent:

   ```css
   p { 
      font-weight: normal 
   }
   
   h1 { 
      font-weight: bold 
   }
   ```

   Existeixen altres valors relatius anomenats `bolder` o `lighter`, aquests el que fan és enfosquir o aclarir la font en funció del seu element pare, respectivament.

* `font-size`: aquesta propietat ens permet definir la mida de la lletra. La podrem establir tant en unitats relatives com en unitats absolutes, tot i que, normalment, és més recomanable usar unitats relatives. Vegem un exemple:

   ```css
   p {
      font-size: 16px;
   }

   @media print {
      p {
         font-size: 12pt;
      }
   }
   ```

   En aquest exemple estem distingint la mida dels paràgrafs: quan es mostrin per pantalla tindran una mida de 16px, quan s’imprimeixin tindran una mida de 12pt.

* `font`: aquesta propietat és un resum de les propietats anteriors (propietat *short-hand*). Si establim aquesta propietat, podem posar els valors de les propietats anteriors separats per un espai en blanc. Vegem-ne diversos exemples:
  
<iframe height="265" style="width: 100%;" scrolling="no" title="font-css" src="http://codepen.io/rglepe/embed/aMpORa/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/aMpORa/'>font-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

### 2.3.5. Aspecte del text

CSS disposa de diverses propietats per definir com es mostrarà el text del nostre document. Vegem-les:

El sagnat és la introducció d’espai en blanc al començament d’una línia de text.

* `text-indent`: aquesta propietat ens permet establir el sagnat en alguna de les unitats de mesura existents. Aquesta unitat pot ser tant positiva com negativa. Per exemple, vegem diferents regles per tal de comparar text sense sagnat, amb sagnat positiu i amb sagnat negatiu, respectivament:

   ```css
   p#par1 { 
      text-indent: 0em; 
   }
   
   p#par2 { 
      text-indent: 1em; 
   }
   
   p#par3 { 
      text-indent: -1em; 
   }
   ``` 

* `text-align`: amb aquesta propietat podrem establir el tipus d’alineació. Els valors disponibles són: `center` pel text centrat, `left` pel text alineat a l’esquerra, `right` pel text alineat a la dreta i `justify` si volem el text justificat. Vegem un exemple de text centrat:
  
  ```css
  p{ 
    background-color: #11ffa1;
  }
  p#esquerra{
    text-align: left;
	}
	p#dreta{
		text-align: right;
	}
	p#centrat{
		text-align: center;
	}
	p#justificat{
		text-align: justify;
	}
   ```

* `text-decoration`: ens permet posar una línia a sota per subratllar el text (`underline`), a sobre (`overline`) o ratllant el text (`line-through`). També ens permet fer que el text parpallegi mitjançant el valor `blink`. Vegem-ne un exemple:

   ```css  
   p#par1 { 
      text-decoration: none;
   }
   
   p#par2 { 
      text-decoration: underline;
   }
   
   p#par3 { 
      text-decoration: overline;
   }
   
   p#par4 { 
      text-decoration: line-through;
   }
   
   p#par5 { 
      text-decoration: blink;
   }
   ```

* `letter-spacing`: incrementa la distància entre lletres. Com a valor usarem qualsevol unitat de mesura. Un exemple seria:

   ```css
   blockquote { 
      letter-spacing: 0.1em; 
   }
   ```

* `line-height`: estableix l’alçada o espai entre cadascuna de les línies, respecte la seva base (baseline). Per exemple:

   ```css
   p { 
      line-height: 2em; 
   }
   ```

* `word-spacing`: incrementa la distància entre paraules. Per exemple:

   ```css  
   h1 { 
      word-spacing: 1em; 
   }
   ```

* `text-transform`: converteix les lletres a majúscules posant el valor uppercase; a minúscules posant el valor lowercase, o posa la primera lletra de cada paraula en majúscula i la resta en minúscula posant el valor capitalize. Si volem anul·lar aquesta propietat, hem de posar el valor none. Vegem-ne dos exemples:

   ```css

   h1 { 
      text-transform: uppercase; 
   }
   
   .titol { 
      text-transform: capitalize; 
   }
   ```

* `white-space`: defineix com s’han de tractar els espais en blanc que continguin l’element, ja siguin per salts de línia, tabulacions o espais en blanc directament. Els valors que pot assumir són: normal, pre, nowrap, pre-wrap i pre-line. A continuació tenim una taula per aclarir el seu funcionament.

Valor|	Espais en blanc|	Salt de línia| Ajust de línia (Text wrapping)|
---|---|---|---|
normal|	no es respecten|	no es respecten|	Sí|
pre|	es respecten|	es respecten|	No
nowrap|	no es respecten|	no es respecten|	No
pre-wrap|	es respecten|	es respecten|	Sí
pre-line|	es respecten|	no es respecten|	Sí

Veiem un exemple on hem afegit salts de línia i tabulacions, per veure les diferències:

<iframe height="265" style="width: 100%;" scrolling="no" title="white-space-css" src="http://codepen.io/rglepe/embed/eXgpBP/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/eXgpBP/'>white-space-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

CSS3 afegeix diverses propietats que ens permeten donar més efectes al text contingut als elements. Enumerem-ne algunes:

* `text-shadow`: permet posar una ombra al text. Aquesta propietat té quatre valors separats per espais, els dos primers obligatoris:
  * `ombra horitzontal`: unitat de mesura amb la posició horitzontal de l’ombra.
  * `ombra vertical`: unitat de mesura amb la posició vertical de l’ombra.
  * `borrositat`: unitat de mesura que denota a partir d’on la vora es fa borrosa.
   * `color`: color de l’ombra.

<iframe height="265" style="width: 100%;" scrolling="no" title="text-shadow-css" src="http://codepen.io/rglepe/embed/zbNvJg/?height=265&theme-id=0&default-tab=result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/zbNvJg/'>text-shadow-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

* `word-wrap`: si en un text tenim una paraula molt llarga que no cap a l’element contenidor, aquesta propietat ens permet fer que la paraula es pugui tallar en diferents línies. Els valors d’aquesta propietat són:
  * `normal`: la paraula sobrepassa els límits de l’element i no es pot tallar en línies.
  * `break-word`: permetem que la paraula es talli en més d’una línia.
  
Vegem alguns exemples:

CSS

```css
p.tall {
   word-wrap: break-word;
}
```

HTML
```html
<p class="tall">Text amb una paraula llaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaarga.</p>
<p>Text amb una paraula llaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaarga.</p>
```

* `text-overflow`: aquesta propietat ens serveix per especificar com s’ha de comportar el navegador quan el text queda tallat. Tenim tres valors possibles:
  * `clip`: el text queda tallat
  * `ellipsis`: es posen punts suspensius
  * `una cadena de text`: es posa aquest text

Vegem alguns exemples:

HTML
```html
<p class="desbordament desbordament1">Text amb una paraula llaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaarga.</p>
<p class="desbordament desbordament2">Text amb una paraula llaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaarga.</p>
```
CSS

```css
p.desbordament {
   overflow: hidden;
}
 
p.desbordament1 {
   text-overflow: clip;
}
 
p.desbordament2 { 
   text-overflow: ellipsis;
}
```

### 2.3.6. Color i fons

El CSS ens permet posar colors i imatges a la nostra web, tant pel que fa a la lletra com pel que fa al color o imatge de fons de cada element. Vegem quines propietats ens permeten fer-ho:

* `color`: permet canviar el color de lletra. Vegem, per exemple, dues maneres per establir que el text inclòs en els elements `<em>` serà de color vermell:
  
   ```css  
   em { 
      color: red; 
   }
   
   em { 
      color: rgb(255,0,0); 
   }
   ```

* `background-color`: permet canviar el color de fons de l’element o elements. Per exemple, per posar de color vermell el color de fons dels elements `<h1>`, posaríem:

   ```css
   h1 { 
      background-color: #FF0000; 
   } 
   ```

* `background-image`: permet posar una imatge com a fons de l’element o elements. Si volem que no hi hagi cap imatge, s’estableix el valor `none`. Per defecte, quan posem una imatge com a fons d’un element, aquesta es repeteix tan horitzontalment com verticalment al llarg de l’amplada i alçada de l’element.
Per a posar una imatge de fons de tot el document, per exemple, el selector hauria de ser l’element `<body>`:

   ```css
   body {
      background-image: url("fons.png");
   }
   ```

* `background-attachment`: aquesta propietat s’ha de fer servir juntament amb la propietat background-image i serveix per establir si la imatge de fons ha de quedar fixa o no. Si volem que quan pugem i baixem pel document la imatge resti immòbil, el valor haurà de ser fixed. Si, al contrari, volem que la imatge acompanyi al text quan pugem i baixem pel document, el valor serà scroll. Vegem-ne un exemple:
   ```css
   body { 
      background-image: url("fons.png"); 
      background-attachment: fixed; 
   }
   ```

* `background-repeat`: aquesta propietat s’ha de fer servir juntament amb la propietat background-image i serveix per establir si volem que la imatge de fons es repeteixi (repeat) o no (no-repeat). A més, si volem que es repeteixi només horitzontalment, posarem el valor repeat-x i si volem que només es repeteixi verticalment posarem repeat-y. Vegem-ne un exemple:
   ```css
   body { 
      background: white url("fons.png"); 
      background-repeat: repeat-y; 
   }
   ```
* `background-position`: aquesta propietat s’ha de fer servir juntament amb la propietat background-image i serveix per especificar la posició on es dibuixarà la imatge de fons. Aquesta propietat s’acostuma a usar en conjunció amb la declaració background-repeat: no-repeat;. Com a valor d’aquesta propietat es donen dues paraules clau separades per un espai en blanc. La primera paraula clau correspon a l’eix de les X i pot ser left si volem la imatge alineada a l’esquerra; center si volem la imatge centrada, o right si la volem alineada a la dreta. La segona paraula clau correspon a l’eix de les Y i pot ser top si volem la imatge a dalt de l’element, center si la volem centrada verticalment o bottom si la volem a baix de l’element. En lloc d’aquestes paraules clau es poden posar percentatges que corresponguin al posicionament X-Y de la imatge dins de l’element.
Suposem que volem tenir una imatge a l’extrem superior dret com a fons d’un document. Vegem com establiríem la propietat background-position usant paraules clau o percentatges:

   ```css
      body { 
         background-image: url("fons.png"); 
         background-repeat: no-repeat; 
           /* usant paraules clau */
      }
      
      body { 
         background-image: url("fons.png"); 
         background-repeat: no-repeat; 
         background-position: 100% 0%; /* usant percentatges */
      }
   ```

* `background`: aquesta propietat és un resum de les propietats anteriors (*short-hand*). Si establim aquesta propietat, podem posar els valors de les propietats anteriors separats per un espai en blanc. Vegem-ne diversos exemples:
  
   ```css  
   body { 
      background: red; 
   } 
   
   p { 
      background: gray url("fons.png") no-repeat fixed left top; 
   }
   ```

   Aquest exemple ens diu el següent: el color de fons del document serà vermell. A més, el color de fons dels paràgrafs serà gris amb una única imatge de fons de nom fons.png que estarà situada a l’extrem superior esquerre del paràgraf i que estarà fixada.

Vegem un altre exemple:

```css
p {
   background: #AFABFF url(imatges/firefox.png) no-repeat center 5%;
}
```

CSS3 ens permet jugar a posar múltiples imatges de fons. Imagineu que voleu posar una imatge de tipus patró (pattern) a un document, de forma que es repeteixi com a fons, i alhora voleu posar una altra imatge única de fons a la part superior dreta amb un logotip, com si fons una marca d’aigua. El codi podria ser aquest:

<iframe height="265" style="width: 100%;" scrolling="no" title="background-css" src="http://codepen.io/rglepe/embed/XGpXXJ/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/XGpXXJ/'>background-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Amb CSS3 també podem tenir més control respecte la imatge de fons a partir de les següents propietats:

* `background-size`: permet establir la mida de la imatge de fons. Com a valor podem posar la mida de la imatge en unitats o en percentatges. També podem posar el valor `cover` que escala la imatge per tal que ocupi tot l’element o el valor `contain`, que escala la imatge a la màxima mida visible.

   Vegem-ne uns exemples:

   CSS
   ```css
   p {
      border: 2px #8246D2 solid;
      padding: 25px;
      width: 25%;
      margin-right: 50px;
      float: left;
      background-image: url(imatges/linux.png);
      background-repeat: no-repeat;
   }
   
   p.fons1 {
      background-size: 25px 50px; 
   }
   
   p.fons2 {
      background-size: 50px 50px; 
   }
   
   p.fons3 {
      background-size: cover; 
   }
   
   p.fons4 {
      background-size: contain; 
   }
   ```
   HTML
   ```html
   <p class="fons1">Imatge de fons de 25px d'amplada i 50px d'alçada</p>
   <p class="fons2">Imatge de fons de 50px d'amplada i alçada</p>
   <p class="fons3">Imatge de fons que cobreix tot l'element.</p>  
   <p class="fons4">Imatge de fons el màxim de gran per tal de poder-la veure sencera.</p>
   ```

* `background-origin`: propietat que permet especificar on es posarà la imatge. Els valors poden ser `border-box` per col·locar la imatge a la vora; `padding-box` per col·locar la imatge al farciment de l’element, o `content-box` per col·locar la imatge com a fons del contingut de l’element.

Vegem-ne uns exemples:

<iframe height="265" style="width: 100%;" scrolling="no" title="background-origin-css" src="http://codepen.io/rglepe/embed/YgNYBa/?height=265&theme-id=0&default-tab=css,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/YgNYBa/'>background-origin-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

## 2.4. El model de caixa

Hi ha diverses propietats, com els marges o les vores de cada element, que hem d’establir a partir de l’anomenat model de caixa. Per entendre aquest model hem de pensar cada element del document com si fos una caixa. De cadascuna d’aquestes caixes podem distingir els components següents:

* El contingut (en anglès, **content**) de l’element: text o altres elements.
* El farciment (en anglès, **padding**): espai entre el contingut i la vora de la caixa.
* La vora (en anglès, **border**): vora que delimita la caixa.
* El marge (en anglès, **margin**): espai entre la vora de la caixa i la resta d’elements.

   ![model-box](https://www.w3.org/TR/CSS2/images/boxdim.png)

Per tal d’establir i configurar cadascun dels components d’una caixa, el llenguatge CSS ens ofereix les propietats pertinents.

A banda d’aquest model de caixa, que és l’estàndard que fan servir la majoria de navegadors, Internet Explorer disposa del seu propi, en el qual l’amplada (width) no coincideix amb el contingut (content), sinó que és la suma del contingut + farciment + la vora.

Com a resum podríem establir que, per tal de saber l’amplada total d’una caixa, tenim el model estàndard del W3C i el model de IE, i el càlcul queda de la següent manera:

**Model W3C**

amplada total = margin-left + border-left + padding-left + width + padding-right + border-right + margin-right

Per altra banda, CSS3 ens permet modificar el model de caixa respecte al seu comportament per defecte. Això ho podem fer amb la propietat `box-sizing`. A aquesta propietat li podem assignar tres valors diferents: `content-box`, `padding-box` i `border-box`, per tal que la propietat width computi tenint en compte únicament el contingut (context-box), el contingut + el farciment (padding-box) o la totalitat dels tres (border-box). El valor més habitual és aquest darrer.

A l’exemple següent veiem el model de caixa clàssic (per defecte) i el que modifiquem mitjançant la propietat box-sizing. aquesta propietat ens indica que al primer paràgraf, hem de sumar tant el contingut (200px), com el farciment, com les vores per obtenir l’amplada total:

<iframe height="265" style="width: 100%;" scrolling="no" title="model-box" src="http://codepen.io/rglepe/embed/YgNeom/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/YgNeom/'>model-box</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

**propietats de la vora**

`border-top-left-radius`, `border-top-right-radius`, `border-bottom-left-radius`, `border-bottom-right-radius`: aquestes propietats ens permeten fer vores arrodonides. Com a valor es posa un nombre que correspon al radi de la vora corresponent.
`border-radius`: la funcionalitat d’aquesta propietat és la mateixa que la de les propietats anteriors, però la mida establerta afecta les quatre cantonades de la caixa.

Vegem-ne un exemple:

<iframe height="265" style="width: 100%;" scrolling="no" title="round-border" src="http://codepen.io/rglepe/embed/XGpEXP/?height=265&theme-id=0&default-tab=css,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/XGpEXP/'>round-border</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

* `box-shadow`: per­met posar una ombra a la caixa. Aquesta pro­pi­e­tat pren 6 valors sepa­rats per espais, els dos pri­mers obli­ga­to­ris. Aquests valors són els següents:
  
   * **ombra horit­zon­tal**: uni­tat de mesura que indica la posi­ció de l’ombra horit­zon­tal.
   * **ombra ver­ti­cal**: uni­tat de mesura que indica la posi­ció de l’ombra ver­ti­cal.
   * **bor­ro­si­tat**: uni­tat de mesura que denota a par­tir d’on la vora es fa bor­rosa.
   * **mida**: la mida de l’ombra
   * **color**: el color de l’ombra
   * **inset**: si posem aquesta paraula clau, l’ombra de la caixa serà interna.

Vegem alguns exem­ples d’ombres:

<iframe height="265" style="width: 100%;" scrolling="no" title="box-shadow-css" src="http://codepen.io/rglepe/embed/qvRoPe/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/qvRoPe/'>box-shadow-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Una altra pro­pi­e­tat molt interes­sant ens ser­veix per­què l’usu­ari pugui redi­men­si­o­nar una caixa:

* `resize`: Per­met redi­men­si­o­nar la caixa. Té els següents valors:
  * `horizontal`: la caixa es pot redi­men­si­o­nar horit­zon­tal­ment.
  * `vertical`: la caixa es pot redi­men­si­o­nar ver­ti­cal­ment.
  * `both`: la caixa es pot redi­men­si­o­nar tant horit­zon­tal­ment com ver­ti­cal­ment.
  * `none`: la caixa no es pot redi­men­si­o­nar.

Per exem­ple,

```css
p {
   resize: both;
}
```

### 2.4.1. Mar­ges

Per esta­blir els mar­ges d’un ele­ment tenim les següents pro­pi­e­tats:

`margin-top`, `margin-right`, `margin-bottom` i `margin-left`: aques­tes pro­pi­e­tats ens ser­vi­ran per esta­blir cadas­cun dels mar­ges de la caixa (supe­rior, dret, infe­rior i esquerre, res­pec­ti­va­ment). 

Vegem-ne un exem­ple:
```css
p { 
   margin-top: 1em; 
   margin-right: 2em; 
   margin-bottom: 3em; 
   margin-left: 4em; 
} 
```

* `margin`: Aquesta pro­pi­e­tat ser­veix per resu­mir totes les pro­pi­e­tats margin-*. Es poden intro­duir d’un a qua­tre valors sepa­rats per espai:
  
  * 1 valor: la mesura intro­du­ïda afecta els qua­tre mar­ges.
  * 2 valors: el pri­mer valor espe­ci­fica els mar­ges supe­rior i infe­rior i el segon valor espe­ci­fica els mar­ges esquerre i dret.
  * 3 valors: el pri­mer valor espe­ci­fica el marge supe­rior, el segon valor espe­ci­fica els mar­ges esquerre i dret i el ter­cer valor espe­ci­fica el marge infe­rior.
  * 4 valors: el pri­mer valor espe­ci­fica el marge supe­rior, el segon valor espe­ci­fica els marge dret, el ter­cer valor espe­ci­fica el marge infe­rior i el quart valor espe­ci­fica el marge esquerre.

Vegem-ne alguns exem­ples:

<iframe height="265" style="width: 100%;" scrolling="no" title="margin-css" src="http://codepen.io/rglepe/embed/ZPepOZ/?height=265&theme-id=0&default-tab=css,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/ZPepOZ/'>margin-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>


Hem de tenir en compte que l’àrea que ocupa el margin no se li pot asso­ciar cap color de fons amb cap pro­pi­e­tat de la mateixa caixa. Per tal de crear l’efecte que el fons és d’un color, o fins i tot una imatge, hem de posar aquesta caixa dins d’una altra, i posar-li a aquesta última color.

### 2.4.2. Far­ci­ment

Per esta­blir els mar­ges d’un ele­ment tenim les següents pro­pi­e­tats:

`padding-top`, `padding-right`, `padding-bottom` i `padding-left`: aques­tes pro­pi­e­tats ens ser­vi­ran per esta­blir cadas­cun dels far­ci­ments de la caixa (supe­rior, dret, infe­rior i esquerre, res­pec­ti­va­ment). Vegem-ne un exem­ple:

```css
body { 
   padding-top: 1em; 
   padding-right: 2em; 
   padding-bottom: 1em; 
   padding-left: 2em; 
}
```

`padding`: pro­pi­e­tat *short-hand* que resumeix totes les pro­pi­e­tats padding-*. Podem posar 1, 2, 3 o 4 valors, tal com es fa a la pro­pi­e­tat margin. Vegem-ne alguns exem­ples:

```css
p#par1 {
   padding:2em;
}
 
p#par2 {
   padding:5em 2em;
}
```

En aquest cas, el parà­graf amb iden­ti­fi­ca­dor par1 tin­drà un far­ci­ment de 2em pels qua­tre cos­tats. El parà­graf amb iden­ti­fi­ca­dor par2 tin­drà un far­ci­ment supe­rior i infe­rior de 5em i un far­ci­ment tant a la dreta com a l’esquerra de 2em.

### 2.4.3. Vores

Per esta­blir les vores d’un ele­ment tenim les següents pro­pi­e­tats:

* `border-top-width`, `border-right-width`, `border-bottom-width` i `border-left-width`: aques­tes pro­pi­e­tats espe­ci­fi­quen el gruix de cadas­cuna de les vores supe­rior, dreta, infe­rior i esquerra, res­pec­ti­va­ment. Com a valors podem posar `thin` per a una vora prima, `medium` per a una vora mit­jana o `thick` si volem una vora grui­xuda. Si volem tenir un major con­trol del gruix de les vores, podem usar també una uni­tat de mesura com a valor de la pro­pi­e­tat. Vegem-ne un exem­ple:

   ```css
   h1 { 
      border-top-width: thin; 
      border-right-width: thick; 
      border-bottom-width: medium; 
      border-left-width: thick; 
   }
   ```

* `border-width`: pro­pi­e­tat *short-hand* que ser­veix per agrupar les pro­pi­e­tats border-*- width. Podem posar 1, 2, 3 o 4 valors, tal com es fa a la pro­pi­e­tat margin. Vegem l’exem­ple ante­rior resu­mit en una sola pro­pi­e­tat:

   ```css
   h1 {
      border-width: thin thick medium;
   }
   ```

* `border-top-color`, `border-right-color`, `border-bottom-color` i `border-left-color`: amb aques­tes pro­pi­e­tats podem espe­ci­fi­car el color de cadas­cuna de les vores supe­rior, dreta, infe­rior i esquerra, res­pec­ti­va­ment. Vegem-ne un exem­ple:

   ```css
   p { 
      border-top-color: black; 
      border-right-color: red; 
      border-bottom-color: green; 
      border-left-color: blue; 
   }
   ```

* `border-color`: aquesta pro­pi­e­tat resu­meix totes les pro­pi­e­tats border-*-color. Podem posar 1, 2, 3 o 4 valors, tal com es fa a la pro­pi­e­tat margin. Vegem, per exem­ple, com podríem esta­blir que totes les vores siguin del mateix color:

   ```css
   p { 
      border-color: gray; 
   } 
   ```

   En aquest cas estem fent que tots els parà­grafs tin­guin una vora de color gris.

* `border-top-style`, `border-right-style`, `border-bottom-style` i `border-left-style`: aques­tes pro­pi­e­tats defi­nei­xen els estils de cadas­cuna de les vores supe­rior, dreta, infe­rior i esquerra, res­pec­ti­va­ment. Tenim diver­sos estils dis­po­ni­bles, enu­me­rem-los:
  * `none` o `hidden`: no té vora.
  * `dotted`: la vora és pun­te­jada.
  * `dashed`: la vora són petits guio­nets.
  * `solid`: la vora és una línia con­tí­nua.
  * `double`: la vora són dues línies con­tí­nues.
  * `groove`: la vora es mos­tra enfon­sada, com si esti­gués per sota del nivell de la super­fí­cie de la pan­ta­lla.
  * `ridge`: la vora es mos­tra sor­tida, com si esti­gués per sobre del nivell de la super­fí­cie de la pan­ta­lla.
  * `inset`: la vora està enfon­sada i fa que l’ele­ment que té la vora sem­bli que esti­gui per sota del nivell de la super­fí­cie de la pan­ta­lla.
  * `outset`: la vora està enfon­sada i fa que l’ele­ment que té la vora sem­bli que esti­gui per sobre del nivell de la super­fí­cie de la pan­ta­lla.
   
   Vegem un exem­ple:

<iframe height="265" style="width: 100%;" scrolling="no" title="border-css" src="http://codepen.io/rglepe/embed/gEmrMZ/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/gEmrMZ/'>border-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

* `border-style`: Aquesta pro­pi­e­tat resu­meix totes les pro­pi­e­tats border-*-style. Podem posar 1, 2, 3 o 4 valors, tal com es fa a la pro­pi­e­tat margin. Vegem-ne un exem­ple:

<iframe height="265" style="width: 100%;" scrolling="no" title="border-style-css" src="http://codepen.io/rglepe/embed/KEWNyz/?height=265&theme-id=0&default-tab=css,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/KEWNyz/'>border-style-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

   En aquest exem­ple veiem que l’ele­ment amb iden­ti­fi­ca­dor caixa tin­drà una vora supe­rior i infe­rior amb una línia con­tí­nua. A dreta i esquerra de l’ele­ment tin­drà una línia pun­te­jada. Les dues regles següents volen simu­lar que els ele­ments `<span>` de classe boto sem­blin botons: en el seu estat nor­mal sem­bla­ran un botó sense pré­mer, però quan hi pas­sem per sobre sem­bla­ran un botó pre­mut.

* `border-top`, `border-right`, `border-bottom` i `border-left`: aques­tes pro­pi­e­tats ens ser­vei­xen per posar el gruix, l’estil i el color de la vora, però de manera que només afecti la vora supe­rior, de la dreta, infe­rior i de l’esquerra, res­pec­ti­va­ment. Els tres valor ani­ran sepa­rats per un espai en blanc. Vegem-ne un exem­ple:
  
   ```css
   h1 { 
      border-top: thick solid red; 
      border-right: thick dotted green; 
      border-bottom: thick solid yellow; 
      border-left: thick dotted blue; 
   }
   ```

* `border`: aquesta pro­pi­e­tat és un resum de totes les pro­pi­e­tats ante­ri­ors. Allò que es posi en aquesta pro­pi­e­tat afec­tarà les qua­tre vores de la caixa. Vegem-ne un exem­ple:

   ```css
   p.tipus1{
      border: black medium solid;
   }

   p.tipus2{
      border: red 10px dashed;
   }
   
   p.tipus3{
      border: gray 1px dotted;
   }
   ```

## 2.5. El format visual dels elements d'un document

El format visual dels elements d’un document ens defineix com són les caixes (és a dir, els elements HTML vistos com a caixes) en el document i el comportament d’aquestes caixes envers la resta de caixes de la pàgina.

Veurem a continuació quines propietats ens ajuden a definir aquest format:

* `display`: aquesta propietat ens ajuda a establir el tipus de caixa que defineix l’element. Pot tenir els següents valors:
  * `block`: l’element serà un element de bloc. És a dir, generarà un salt de línia en finalitzar el text de l’element, i tendeix a ocupar l’amplada màxima possible dins del seu contenidor, sempre que no es modifiqui la propietat width per escurçar-ho.
  * `inline`: l’element serà un element de línia. És a dir, no generarà un salt de línia en finalitzar el text de l’element, i ocuparà exclusivament l’espai del que conté, si aquest no és alterat amb una altra propietat.
  * `list-item`: l’element es comportarà com un element d’una llista. Per tant, per defecte, tindrà un petit símbol davant del text de l’element.
  * `none`: l’element amb aquesta propietat no genera cap caixa, no és visible ni ocupa espai en el document. És el cas d’elements com `<script>`, `<input type=“hidden”>`, etc.
  * `run-in`: fa que la caixa sigui de bloc o de línia segons el context.
  * `table`, `inline-table`, `table-row-group`, `table-column`, `table-column-group`, `table-header-group`, `table-footer-group`, `table-row`, `table-cell` i `table-caption`: l’element es comporta com els corresponents elements d’una taula.
Tenint presents aquests valors podem deduir que en els navegadors, els paràgrafs, és a dir els elements `<p>`, tenen per defecte el valor `block`; el text emfatitzat, és a dir els elements `<em>`, tenen per defecte el valor inline, i els ítems d’una llista, és a dir els elements `<li>`, tenen per defecte el valor `list-item`.

Vegem com podem invisibilitzar les imatges:

```css
img { 
   display: none; 
}
```

Vegem un altre exemple: imaginem que volem mostrar un text amb 3 columnes. Podríem fer-ho de la següent manera:

<iframe height="265" style="width: 100%;" scrolling="no" title="display-css" src="http://codepen.io/rglepe/embed/ZPeLVq/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/ZPeLVq/'>display-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

* `position`: amb aquesta pro­pi­e­tat podem defi­nir la posi­ció de la caixa envers la resta de cai­xes del docu­ment, o res­pecte al mateix docu­ment o fines­tra. Es poden posar els següents valors:
  * `static`: l’ele­ment es posi­ci­ona en l’ordre que toca, tal com apa­reix al docu­ment. Aquest és el valor per defecte.
  * `relative`: l’ele­ment es posi­ci­ona rela­ti­va­ment a la posi­ció que li per­to­ca­ria. A més, l’espai que hau­ria d’ocu­par no es col·lapsa.
  * `absolute`: l’ele­ment es posi­ci­ona rela­ti­va­ment a la caixa con­te­ni­dora. L’espai que hau­ria d’ocu­par es col·lapsa.
  * `fixed`: l’ele­ment es posi­ci­ona rela­ti­va­ment a la caixa con­te­ni­dora, però es queda fixat en des­pla­çar-nos pel docu­ment.
Aquesta pro­pi­e­tat no té sen­tit si no la com­bi­nem amb les pro­pi­e­tats següents:

  * `top`, `right`, `bottom` i `left`: amb aques­tes pro­pi­e­tats podem posi­ci­o­nar la caixa amb un des­pla­ça­ment supe­rior, cap a la dreta, infe­rior i cap a l’esquerra, res­pec­ti­va­ment.
  * `width` i `height`: amb aques­tes pro­pi­e­tats podrem indi­car les mides de la caixa, amplada i alçada, res­pec­ti­va­ment.
  
Vegem un exem­ple que com­bina les pro­pi­e­tats de posi­ci­o­na­ment ante­ri­ors:

<iframe height="265" style="width: 100%;" scrolling="no" title="position-css" src="http://codepen.io/rglepe/embed/eXvvZa/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/eXvvZa/'>position-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

* `min-width`, `min-height`, `max-width` i `max-height`: ser­vei­xen per deter­mi­nar les dimen­si­ons míni­mes i màxi­mes que poden pren­dre les cai­xes, sigui quina sigui la mida de la fines­tra del nave­ga­dor.
* `float`: aquesta pro­pi­e­tat fa que la caixa quedi flo­tant a l’esquerra (si esta­blim el valor `left`) o a la dreta (si esta­blim el valor `right`). Per exem­ple, si volem que les imat­ges ens que­din com un objecte flo­tant, escriu­ríem la següent regla:

   ```css  
   img { 
      float: right; 
   }
   ```

Vegem un exem­ple més com­plet:

<iframe height="265" style="width: 100%;" scrolling="no" title="float-css" src="http://codepen.io/rglepe/embed/aMJJQm/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/aMJJQm/'>float-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

* `clear`: aquesta pro­pi­e­tat ser­veix per desac­ti­var els ele­ments flo­tants al vol­tant de l’ele­ment que tin­gui aquesta pro­pi­e­tat. Segons el valor que posem, eli­mi­na­rem els ele­ments flo­tants a la part esquerra amb el valor `left`, els de la part dreta amb el valor `right` o a amb­dós cos­tats amb el valor `both`. Per anul·lar aquesta pro­pi­e­tat usa­rem el valor `none`.
Vegem un exem­ple: ima­gi­neu que en un docu­ment volem que les imat­ges que­din flo­tant a l’esquerra. Ara bé ima­gi­nem que en un parà­graf con­cret no volem que la imatge quedi flo­tant. Ho podríem codi­fi­car de la següent manera:

<iframe height="265" style="width: 100%;" scrolling="no" title="clear-css" src="http://codepen.io/rglepe/embed/pYeVmM/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/pYeVmM/'>clear-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

* `z-index`: esta­bleix la pro­fun­di­tat d’una caixa en l’eix de les Z. El valor és un nom­bre que defi­neix aquesta pro­fun­di­tat. Com més petit sigui el valor més al fons se situ­arà la caixa.

<iframe height="265" style="width: 100%;" scrolling="no" title="z-index-css" src="http://codepen.io/rglepe/embed/moWvQo/?height=265&theme-id=0&default-tab=css,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/moWvQo/'>z-index-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

* `overflow`: indica què fer quan el con­tin­gut mesura més que la caixa. Els pos­si­bles valors són:
  * `visible`: el con­tin­gut es veu sobre­pas­sant la taula.
  * `hidden`: el con­tin­gut sobrant no es veu.
  * `scroll`: apa­reix una barra de des­pla­ça­ment.
  * `auto`: apa­reix una barra de des­pla­ça­ment només si és neces­sà­ria.
  
Vegem un exem­ple on es mos­tren els dife­rents com­por­ta­ments d’aquesta pro­pi­e­tat segons el valor que espe­ci­fi­quem:

<iframe height="265" style="width: 100%;" scrolling="no" title="overflow-css" src="http://codepen.io/rglepe/embed/EMWrMo/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/EMWrMo/'>overflow-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

## 2.6. Efectes CSS

Les animacions i transformacions a un lloc web són eines poderoses per cridar l'atenció dels usuaris.

### 2.6.1. Transformacions 2D

La propietat `transform` permet modificar l'espai de coordenades del model de format visual CSS. Amb el seu ús, els elements poden ser traslladats, rotats, escalats o sesgats d'acord als valors establerts. Aquesta propietat no interromp el flux normal del document.

Tot i que la majoria dels navegadors tenen implementades les transformacions 2D, encara s'ha de posar un prefix a la propietat tal com veureu als exemples (consulteu l’apartat [2. Regles CSS](#2-regles-css) per tenir més detalls dels prefixos).

* `translate(x,y)`: tras­lla­dem l’ele­ment x uni­tats a la dreta i y uni­tats cap avall. Si x és nega­tiu es tras­lla­darà cap a l’esquerra i si y és nega­tiu es tras­lla­darà cap a dalt.
* `rotate(angle)`: rotem l’ele­ment segons l‘angle espe­ci­fi­cat.
* `scale(x,y)`: modi­fi­quem la mida de l’ele­ment, l’amplada es mul­ti­plica pel fac­tor x i l’alçada pel fac­tor y.
* `skew(angleX, angleY)`: deforma l’ele­ment en angleX res­pecte l’eix de les X i en angleY res­pecte l’eix de les Y.
* `matrix(scaleX(),skewY(),skewX(),scaleY(),translateX(),translateY()`: s’aplica una trans­for­ma­ció mate­mà­tica a par­tir del sis valors.
  
<iframe height="265" style="width: 100%;" scrolling="no" title="transformacions-css" src="http://codepen.io/rglepe/embed/KEmbZx/?height=265&theme-id=0&default-tab=css,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/KEmbZx/'>transformacions-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Si es volen establir diverses propietats `transform` en el mateix element amb diferents funcions de transformació, la segona sobreescriurà a l'anterior. Per evitar-ho, es poden emprar transformacions múltiples separant-les mitjançant un espai:

```css
div {
  transform: rotate(5deg) scale(2,2) translate(20px, 40px);
}
```

### 2.6.2. Transicions

Les transicions són efectes que permeten que un element passi de tenir un estil a tenir-ne un altre. Per aconseguir aquests efectes tenim les següents propietats:

* `transition-property`: especifica la propietat CSS respecte la qual s’aplica la transició.
* `transition-duration`: el temps que dura la transició.
* `transition-timing-function`: especifica la corba de velocitat de la transició. Pot tenir els següents valors:
  * `linear`: tota la transició es dóna a la mateixa velocitat.
  ease: l’inici de la transició serà lent, després serà ràpid i acabarà lentament.
  * `ease-in`: l’inici de la transició serà lent.
  * `ease-out`: el final de la transició serà lent.
  * `ease-in-out`: l’inici i el final de la transició seran lents.
* `cubic-bezier(p1x,p1y,p2x,p2y)`: ens per­met defi­nir les velo­ci­tats de la tran­si­ció a par­tir de les coor­de­na­des de dos punts que con­fi­gu­ren una corba de Bézier.
* `transition-delay`: espe­ci­fica des­prés de quant temps comen­çarà la tran­si­ció.
* `transition`: és una pro­pi­e­tat resum de les ante­ri­ors. El seu valor són els valors sepa­rats per espais de `transistion-property`, `transition-duration`, `transition-timing-function` i `transition-delay`.

Una transició s’executa quan una propietat canvia. Una manera de provocar aquest canvi es pot fer usant la pseudoclasse `:hover`. Vegem-ne alguns exemples:

<iframe height="265" style="width: 100%;" scrolling="no" title="transitions-css" src="http://codepen.io/rglepe/embed/ZPJdWb/?height=265&theme-id=0&default-tab=css,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/ZPJdWb/'>transitions-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Es poden aplicar tantes transicions com es vulguin. Per eixemple, per canviar el color de fons i el color de lletra gradualment:

<iframe height="265" style="width: 100%;" scrolling="no" title="multiple-transition-css" src="http://codepen.io/rglepe/embed/NJaWEP/?height=265&theme-id=0&default-tab=css,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/NJaWEP/'>multiple-transition-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

### 2.6.3. Animacions

CSS3 incorpora animacions amb les quals podrem fer que els nostres elements canviïn les seves propietats en un espai de temps.

El primer que s'ha de fer es declarar una **regla @** anomenada `@keyframes`. Amb aquesta regla es defineix des de quina propietat partim i fins a quina propietat volem anar, a més a més dels estats intermigs.

```css
@keyframes canvicolorfons{
0% {background-color: red;}
25% {background-color: yellow;}
50% {background-color: blue;}
100% {background-color: green;}
}
```
Amb aquesta regla aconseguim que inicialment el color de fons estigui en vermell, després del 25% del temps que dura un cicle de l’animació, el fons haurà transicionat fins al color groc, quan estiguem a la meitat del temps el fons serà de color blau i finalment el color de fons transicionarà fins al color verd.

Ara volem que un element es mogui d’esquerra a dreta de la pantalla i, a més, a mida que es mou l’element, aquest roti. Establirem la següent regla:

```css
@keyframes mou{
0% {margin-left: 0; }
25% {margin-left: 25%; transform: rotate(120deg);}
50% {margin-left: 50%; transform: rotate(240deg);}
100% {margin-left: 75%; transform: rotate(360deg);}
}
```
Un cop tenim l’animació definida l’hem d’aplicar. Per tal d’aplicar-la i especificar alguna configuració de l’animació, podem usar les següents propietats:

* `animation-name`: el nom de l’apli­ca­ció que volem apli­car. Ha de coin­ci­dir amb el nom d’alguna regla `@keyframes` defi­nida.
* `animation-duration`: espe­ci­fica el temps que triga una ani­ma­ció en com­ple­tar un cicle.
* `animation-timing-function`: espe­ci­fica la corba de velo­ci­tat de la tran­si­ció. Pot tenir els següents valors: `linear`, `ease`, `ease-in`, `ease-out`, `ease-in-out` i `cubic-bezier(p1x,p1y,p2x,p2y)`.
* `animation-delay`: espe­ci­fica quant temps ha de pas­sar abans que l’ani­ma­ció comenci.
* `animation-iteration-count`: espe­ci­fica quants cops es pro­duirà l’ani­ma­ció. Si volem que es repe­teixi infi­ni­ta­ment, podem posar el valor `infinite`. També admet `initial` i `inherit`.
* `animation-direction`: amb aquesta pro­pi­e­tat podem fer que quan es repe­teixi un cicle l’ani­ma­ció es faci en sen­tit con­trari. Pot tenir dos valors:
* `normal`: l’ani­ma­ció sem­pre es repe­teix en l’ordre esta­blert.
* `alternate`: l’ani­ma­ció es pro­du­eix en ordre invers en els cicles parells.
* `animation-play-state`: espe­ci­fica en quin estat està l’ani­ma­ció. Pot tenir dos valors:
  * `running`: l’ani­ma­ció està fun­ci­o­nant.
  * `paused`: l’ani­ma­ció està pau­sada.

- `animation-fill-mode`: Especifica si els estils de la animació restaran visibles abans o desprès de que l'animació acabi. Els valors són:
	- `backwards`: before the animation (during the animation delay), the styles of the initial keyframe (0%) are applied to the element.
	- `forwards`: After the animation is finished, the styles defined in the final keyframe (100%) are retained by the element.
	- `both`: The animation will follow the rules for both forwards and backwards, extending the animation properties before and after the animation.
	- `normal` (default): The animation does not apply any styles to the element, before or after the animation.

* `animation`: és la pro­pi­e­tat resum de totes les ante­ri­ors. La sin­taxi és la següent:

   ```css
   animation: name duration timing-function delay iteration-count direction;
   ```

Aplicant-ho al nostre exemple:

```css
.canvicolor {
-moz-animation: canvicolorfons 5s linear 0s infinite alternate;
-webkit-animation: canvicolorfons 5s linear 0s infinite alternate;
animation: canvicolorfons 5s linear 0s infinite alternate;
}
 
.canviposicio {
width: 25px;
-moz-animation: mou 5s linear 0s infinite alternate;
-webkit-animation: mou 5s linear 0s infinite alternate;
animation: mou 5s linear 0s infinite alternate;
}
```

En cadascuna de les regles anteriors hem establert quina animació hem d’usar, canvicolorfons i mou, respectivament. En tots dos casos fem que un cicle d’animació duri 5 segons, que la velocitat de l’animació sigui constant durant tot el cicle, que es facin infinits cicles i que l’animació vagi anant cap endavant i cap endarrere alternativament.

<iframe height="265" style="width: 100%;" scrolling="no" title="animations-css" src="http://codepen.io/rglepe/embed/moByGe/?height=265&theme-id=0&default-tab=css,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/moByGe/'>animations-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

### 2.6.4. Transitions vs. Animations!
<img src="https://imgur.com/SBmugNV.png" style="width:48%; margin:0 2% 20px 0;">
<img src="https://imgur.com/otdn06s.png" style="width:48%;margin:0 0 20px 2%;">

|  | Transicions | Animacions |
|------| --------|-----
| **Inici** | Requereix un esdeveniment que engegui la transició, CSS o JavaScript.  | No necessita de esdeveniments externs, encara que pot respondre a ells. Corren automàticament quan es carrega la pàgina.
| **Definició de punts intermedis** | Solsament inici i final | Pot incloure tants punts intermedis com es vulguin (keyframes).
| *CSS Iteració** | No canvia les propietats CSS. | Pot canviar els valors dins del seu *keyframe*.
| **Looping** | No està disenyat per looping | No n'hi han problemes per looping.

## 2.7. Gradients

Si es vol afegir transicions entre 2 o més colors, ex: per posar un estil concret a diferents àrees de les pàgines web. Es pot fer mitjançant codificació entre diferents colors, siguin lineals o radials.

### 2.7.1. Gradient Lineal

En aquest cas hem d’indicar en quina direcció volem que es faci la transició de colors, i igualment indicar-li un origen i un final, mitjançant l’elecció de les paraules `top`/`right`/`bottom`/`left` o bé un angle.

Sintaxi: ```linear-gradient(sentit, color1, color2, …, colorN);```


### 2.7.2. Gradient Radial

L’ús d’aquest gradient parteix del centre de l’àrea afectada, per iniciar els canvis de colors marcats. El seu funcionament és molt similar al del gradient lineal, on també l’indiquem els colors per on ha de passar mitjançant paràmetres que segueixen la següent sintaxi:

Sintaxi: ````radial-gradient(shape size at position, color1, color2,…., colorN)````;

Exemple de ambdòs casos a continuació:

<iframe height="265" style="width: 100%;" scrolling="no" title="gradient-css" src="http://codepen.io/rglepe/embed/ZPXVmx/?height=265&theme-id=0&default-tab=css,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/ZPXVmx/'>gradient-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

## 2.8. Columnes

El text d’un element es distribueix en una única columna. CSS3 incorpora una propietat per fer que el text d’un element es pugui distribuir en més d’una columna. Aquesta característica es pot aconseguir a partir de les següents propietats:

`column-count`: nombre màxim de columnes de l’element.
`column-width`: suggereix l’amplada de les columnes. El navegador s’encarrega de calcular quantes columnes amb aquesta amplada poden entrar.
`columns`: propietat resum per a les dues propietats anteriors. L’ordre dels valors és el següent: `column-width` `column-count`.
`column-gap`: determina l’espai entre columnes.
Entre les columnes hi ha una línia de la qual podem establir els atributs:

`column-rule-color`: color de la línia.
`column-rule-style`: estil de la línia. Pot prendre els següents valors: none, hidden, dotted, dashed, solid, double, groove, ridge, inset o outset.
`column-rule-width`: el gruix de la línia.
`column-rule`: propietat resum de les anteriors propietats. L’ordre dels valors és el següent: `column-rule-width` `column-rule-style` `column-rule-color`.

Imaginem que volem maquetar el text dels paràgrafs en tres columnes, amb una separació de 50px entre elles i una línia puntejada que les separi. Establiríem la següent regla:

```css
p {
column-count: 3;
column-rule: 5px dotted #458FD1;
-moz-column-count: 3;
-moz-column-gap: 50px;
-moz-column-rule: 5px dotted #458FD1;
-webkit-column-count: 3;
-webkit-column-gap: 50px;
-webkit-column-rule: 5px dotted #458FD1;
}
```

## 2.9. FlexBox

[Flexible Box](https://developer.mozilla.org/ca/docs/Web/CSS/CSS_Flexible_Box_Layout/Utilitzar_model_flexible_caixes_CSS) és un mode de disseny  que preveu la disposició dels elements en una pàgina de tal manera que els elements es comporten d'una forma predictible quan el disseny de la pàgina s'ha d'adaptar a diferents mides de pantalla i a diferents dispositius de visualització.

Els elements (items*) dins d'un contenidor flex (*flex container*) modifiquen la seva amplada i alçada (s'expandeixen o s'encogeixen) emplenant l'espai disponible. 

L'algoritme de **Flexbox** és agnòstic pel que fa a la direcció dels seus elements, de manera oposada al *layout* de `block` —que té un biaix vertical—, o el *layout* `inline` —que el té horitzontal. 

És especialment apropiat per components d'aplicació així com per *layouts* a petita escala, mentre que el Grid layout* (següent tema) està orientat als layouts d'una escala major.

### 2.9.1. Vocabulari Flexbox

 **`Flexbox`** és un mòdule complert i inclou un conjunt de propietats, algunes de les quals s'han de definir a nivell del contenidor (`flex-container`) i altres a nivell dels fills (`flex items`).

Al contrari que el model basat en blocs i línies, la disposició flex es basa en `flex-flow directions`. A la següent figura s'aclara aquesta idea:

https://developer.mozilla.org/files/3739/flex_terms.png

![](https://developer.mozilla.org/files/3739/flex_terms.png)

Bàsicament, els items* es disposen seguint l'eix principal *main axis* (des del *main-start* al *main-end*) o l'eix curt (*cross axis*) (des del *cross-start* al *cross-end*).

- ***main axis***: L'eix principal de un contenidor flex és l'eix primari al llarg del qual es despleguen els items* flex. No és necesari que sigui l'eix horitzontal.
- ***main-start* | *main-end*** - Els items* flex es situen dins del contenidor començant des del *main-start* fins al *main-end*.
- ***main size*** - la propietat, ja sigui l'ample (*width*) o l'alçada (*height*), d'un *item* que es situa a la dimensió principal.
- ***cross axis*** - L'eix perpendicular a l'eix principal. La seva direcció depèn de l'eix principal.
- ***cross-start* | *cross-end*** - Les línies flex s'emplenen amb  items* i es situen al contenidor començant per la part *cross-start* fins al *cross-end*.
- ***cross size*** - L'ample o alçada d'un *item* flex, qualsevol que es situi a la dimensió creuada (*cross dimension*), és el *item's cross size*.

### 2.9.2. Flex Container

Contenidor dels items* `flex` . Es defineix mitjançant el valor `flex` o `inline-flex` de la propietat `display`. Habilita un context flex als seus fills directs.

```htmlmixed=
.container {
  display: flex; /* or inline-flex */
}
```

### 2.9.3. `flex-direction`

![flexdirection](https://imgur.com/MYhwj7a.png)

Estableix el **main-axis**, sobre el que es disposen els *flex items* en row* (horizontal)  o column* (vertical).

  - *row** (default): esquerra a dreta a ltr; dreta a esquerra a rtl
  - *row-reverse**: esquerra a dreta a rtl; dreta a esquerra a ltr
  - *column**: el mateix que row* però de dalt cap a baix
  - *column-reverse**: mateix que row-reverse* però de baix cap a dalt

```htmlmixed=
.container {
  flex-direction: row | row-reverse | column | column-reverse;
}
```

### 2.9.4. `flex-wrap`

Els *flex items* encaixen, per defecte, a una línia. Es pot variar amb els següents valors:

- **nowrap** (default): tots els* flex items* es disposen en una línia.
- **wrap**: els *flex items* es disposen en varies línies de dalt a baix.
- **wrap-reverse**: *flex items* es disposen de baix a dalt.

```htmlmixed=
.container{
  flex-wrap: nowrap | wrap | wrap-reverse;
}
```
Al següent exemple es mostren les diferents opcions del `flex-wrap`:

<iframe height="265" style="width: 100%;" scrolling="no" title="Flex Wrap Example" src="http://codepen.io/rglepe/embed/JzpmQV/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/JzpmQV/'>Flex Wrap Example</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

### 2.9.5. `flex-flow`

*shorthand* per les propietats  `flex-direction` i `flex-wrap` junts defineixen els eixos  which together define the flex container's main and cross axes. The default is *row nowrap**.

```htmlmixed=
flex-flow: <‘flex-direction’> || <‘flex-wrap’>
```

### 2.9.6. `justify-content`

Defineix l'alineament al llarg de l'eix principal **main axis**. Ajuda a distribuir l'espai lliure que deixen els **flex items** quan no modifiquen la seva mida o quan han adquirit la màxima mida. A mès permet control·lar l'alineament quan els items* desborden la línia.

```htmlmixed=
.container {
  justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly;
}
```

<img src="https://imgur.com/bnr2hop.png"
alt="" style="width:65%; float:right; margin-left:10px">

- **flex-star** (per defecte): els items* s'agrupen cap l'inici de línia
- **flex-end**: els items* s'agrupen cap al final de línia
- **center**: els items* es centren a la línia
- **space-between**: els items* es distribueixen simètricament. Sense deixar espais als principi i final de línia.
- **space-around**: els items* es distribueixen simètricament peró es deixa espai al voltant d'ells. Visualment sembla que no tinguin el mateix espai, però els items* dels extrems nomès tenen una unitat d'espai i els d'interior porten dos.
- **space-evenly**: els items* es distribuieixen de manera que l'espai es el mateix entre qualsevol parell de items*.

### 2.9.7. `align-items`

Defineix el comportament per defecte dels **flex items** amb relació al eix curt o **cross axis**. És la versió de  `justify-content` per el **cross-axis** (perpendicular to the main-axis).

```htmlmixed=
.container {
  align-items: flex-start | flex-end | center | baseline | stretch;
}
```

<img src="https://imgur.com/72iHOxI.png" alt="" style="width:65%; float:right; margin-left:10px">

- **stretch** (default): stretch to fill the container (still respect min-width/max-width)
- **flex-start**: cross-start margin edge of the items is placed on the cross-start line
- **flex-end**: cross-end margin edge of the items is placed on the cross-end line
- **center**: items are centered in the cross-axis
- **baseline**: items are aligned such as their baselines align


### 2.9.8. `align-content`

This aligns a **flex container's lines** within when there is extra space in the **cross-axis**, similar to how justify-content aligns individual items within the main-axis.

```htmlmixed=
.container {
  align-content: flex-start | flex-end | center | space-between | space-around | stretch;
}
```
<img src="https://imgur.com/BoQ5jOG.png" alt="" style="width:65%; float:right; margin-left:10px">

- **stretch** (default): lines stretch to take up the remaining space
- **flex-start**: lines packed to the start of the container
- **flex-end**: lines packed to the end of the container
- **center**: lines packed to the center of the container
- **space-between**: lines evenly distributed; the first line is at the start of the container while the last one is at the end
- **space-around**: lines evenly distributed with equal space around each line

<br><br><br><br>


## 2.10. Flex items

Same way there are properties for the **flex-container**, we have some for **flex items**.
:::info
Text that is directly contained inside a **flex container** is automatically wrapped in an **anonymous flex item**. However, an anonymous flex item that contains only white space is not rendered, as if it were designated `display: none`.
:::

### 2.10.1. `order`

The `order` property allows for reordering the **flex items** within a container. Simply put, with the `order` property you can move a flex-item from one position to another. Just like you would do with “sortable” lists.

By default, flex items are laid out in the source order. However, the order property controls the order in which they appear in the flex container.

```htmlmixed=
.item {
  order: <integer>; /* default is 0 */
}
```

![](https://imgur.com/xxF4cMz.png)


### 2.10.2. `flex-grow` and `flex-shrink`

![](https://imgur.com/NQKl7k8.png)


The beauty of **flex items** is being “flexible”. The `flex-grow` and `flex-shrink` properties allow us to play around this ‘flexibility’ even more.

This defines the ability for a flex item to grow if necessary. It accepts a unitless value that serves as a proportion. It dictates what amount of the available space inside the flex container the item should take up.

If all items have `flex-grow` set to 1, the remaining space in the container will be distributed equally to all children. If one of the children has a value of 2, the remaining space would take up twice as much space as the others (or it will try to, at least). The same way, `flex-shrink` property control how much a **flex-item** should "shrink" if there is no extra space.

```htmlmixed=
.item {
  flex-grow: <number>; /* default 0 */
  flex-shrink: <number>; /* default 1 */
}
```

:::info
Negative numbers are invalid.
:::


### 2.10.3. `flex-basis`

This defines the default size of an element before the remaining space is distributed. It can be a **length** (e.g. 20%, 5rem, etc.) or a **keyword**.

We can use the following keywords:

- **`auto`**. Means "look at my width or height property".
- **`content`**. Means size it based on the item's content (this keyword isn't well supported yet, so it's hard to test and harder to know what its brethren max-content, min-content, and fit-content do).

```htmlmixed=
.item {
  flex-basis: <length> | auto; /* default auto */
}
```

If set to `0`, the extra space around content isn't factored in. If set to `auto`, the extra space is distributed based on its `flex-grow` value.

![](https://imgur.com/tRcsaB3.png)

### 2.10.4. `flex`

This is the shorthand for `flex-grow`, `flex-shrink` and `flex-basis` combined. The second and third parameters (`flex-shrink` and `flex-basis`) are optional. The default is **`0 1 auto`**.

```htmlmixed=
.item {
  flex: none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]
}
```

:::info
It is recommended that you use this shorthand property rather than set the individual properties. The short hand sets the other values intelligently.
:::

### 2.10.5. `align-self`

This allows the default alignment (or the one specified by `align-items`) to be overridden for individual **flex items**.

The available values are the same as `align-items`,

```htmlmixed=
.item {
  align-self: auto | flex-start | flex-end | center | baseline | stretch;
}
```

### 2.10.6. Play around with flexbox

Check the following **CodePen** and play a bit with different properties of **flex containers** and **flex items**. It will help you a lot to better understand all the properties :wink:

<iframe height="265" style="width: 100%;" scrolling="no" title="Flexbox playground" src="http://codepen.io/rglepe/embed/xBjoXm/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/xBjoXm/'>Flexbox playground</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>


### 2.10.7. Help the Froggy

[Flexbox Froggy](http://flexboxfroggy.com/) is a game where you must help Froggy and friends by writing CSS code!

![](https://imgur.com/w9vOsi3.png)

## 2.11. CSS Grid

El sistema *flexbox* és una gran millora respecte al posicionament *float* o bloc/línia. No obstant això, per a web compleixes es necessita un sistema que simplifiqui la creació dels *layout* o estructures de les seves pàgines.

Molts *frameworks* i llibreries utilitzen un sistema grid* on defineixen una quadrícula determinada, i modificant els noms de les classes dels elements HTML, s'els pot donar-li grandària, posició o col·locació.

Grid CSS** neix d'aquesta necessitat, i recull els avantatges d'aquest sistema, afegint-li nombroses millores i característiques que permeten crear ràpidament quadrícules senzilles i potents de forma pràcticament instantània.

### 2.11.1. Conceptes

![](https://imgur.com/bGcfrXL.png)

**Contenidor**: Existeix un element pare que és el contenidor que definirà la quadrícula o reixeta.
**Ítem**: Cadascun dels fills que conté la quadrícula (element contenidor).
**Cel·la** (*grid cell*): Cadascun dels quadradets (unitat mínima) de la quadrícula.
**Area** (*grid area*): Regió o conjunt de cel·les de la quadrícula.
**Banda** (*grid track*): Banda horitzontal o vertical de cel·les de la quadrícula.
**Línia** (*grid line*): Separador horitzontal o vertical de les cel·les de la quadrícula.

Fem servir el següent escenari:

```html
<div class="grid"> <!-- contenidor -->
  <div class="a">Item 1</div> <!-- cadascun dels ítems del grid -->
  <div class="b">Item 2</div>
  <div class="c">Item 3</div>
  <div class="d">Item 4</div>
</div>
```

Per activar la quadrícula grid* cal utilitzar sobre l'element contenidor la propietat `display` i especificar el valor `grid` o `inline-grid`. Aquest valor influeix en com es comportarà la quadrícula amb el contingut exterior. El primer d'ells permet que la quadrícula aparegui damunt/sota el contingut exterior (en bloc) i el segon d'ells permet que la quadrícula aparegui a l'esquerra/dreta (en línia) del contingut exterior.

Una vegada triat un d'aquests dos valors, i establerta la propietat `display` a l'element contenidor, hi ha diverses formes de configurar la nostra quadrícula grid*. Comencem amb les propietats que s'apliquen a l'element contenidor (pare).

### 2.11.2. Grid amb files i columnes

És possible crear quadrícules amb una grandària explícita. Per a això, només hem d'usar les propietats CSS: `grid-template-columns` i `grid-template-rows`, que serveixen per indicar les dimensions de cada cel·la de la quadrícula, diferenciant entre columnes i files. A l'exemple:

```css
.grid {
  display: grid;
  grid-template-columns: 50px 300px;
  grid-template-rows: 200px 75px;
}
```
Tindrem una quadricula amb **2 columnes** (*la primera amb 50px d'ample i la segona amb 300px d'ample*) i amb **2 files** (*la primera amb 200px d'alt i la segona amb 75px d'alt*). Ara, depenent del nombre d'ítems (*elements fills*) que tingui el contenidor grid**, tindrem una quadrícula de 2x2 elements (*4 ítems*), 2x3 elements (*6 ítems*), 2x4 elements (*8 ítems*) i així successivament. Si el nombre d'ítems és imparell, l'última cel·la de la quadrícula es quedarà buida.

![](https://imgur.com/KVu9VOU.png)

### 2.11.3. fr: Unitat fracció restant

En aquest exemple he utilitzat **píxels** com a unitats de les cel·les de la quadrícula, no obstant això, també podem utilitzar altres unitats (i fins i tot combinar-les) com a percentatges, la paraula clau **auto** (que obté la grandària restant) o la unitat especial **fr** (*fraction*), que simbolitza una **fracció d'espai restant** en el *grid**. Vegem un codi d'exemple en acció:

```css
.grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 2fr 1fr;
}
```
Es crea una quadrícula de *2x2*, on la grandària d'ample de la quadrícula es divideix en **dues columnes** (mateixa grandària d'ample per a cadascuna), i la grandària d'alt de la quadrícula es divideix en **dues files**, on la primera ocuparà el doble (2 *fr) que la segona (1 *fr):

![](https://imgur.com/NtKAc7T.png)

D'aquesta forma, podem tenir un millor control de l'espai restant de la quadrícula, i com utilitzar-ho.

### 2.11.4. Files i columnes repetitives

En alguns casos, en les propietats grid-template-columns i grid-template-rows podem necessitar indicar les mateixes quantitats un nombre alt de vegades, resultant repetitiu i molest. Es pot utilitzar l'expressió ***repeat()*** per indicar repetició de valors, indicant el nombre de vegades que es repeteixen i la grandària en qüestió.

L'expressió a utilitzar seria la següent: `repeat([núm de vegades], [valor o valors])`:

```css
.grid {
  display: grid;
  grid-template-columns: 100px repeat(2, 50px) 200px;
  grid-template-rows: repeat(2, 50px 100px);
}
```

Assumint que tinguèssim un contenidor grid amb 8 ítems fills (o més), l'exemple anterior crearia una quadrícula amb **4 columnes** (*la primera de 100px d'ample, la segona i tercera de 50px d'ample i la quarta de 200px d'ample*). D'altra banda, tindria **2 files** (*la primera de 50px d'alt, i la segona de 100px d'alt*). En el cas de tenir més ítems fills, el patró se seguiria repetint.

L'exemple anterior seria equivalent al codi CSS següent:

```css
.grid {
  display: grid;
  grid-template-columns: 100px 50px 50px 200px;
  grid-template-rows: 50px 100px 50px 100px;;
}
```

### 2.11.5. Grid per àrees

Mitjançant els *grids CSS* és possible indicar el nom i posició concreta de cada àrea d'una quadrícula. Per a això utilitzarem la propietat `grid-template-areas`, on hem d'especificar l'ordre de les àrees en la quadrícula. Posteriorment, en cada ítem fill, utilitzem la propietat `grid-area` per indicar el nom de l'àrea del que es tracta:

D'aquesta forma, és molt senzill crear una quadrícula altament personalitzada en amb prou feines unes quantes línies de CSS, amb molta flexibilitat en la disposició i posició de cada àrea:

<iframe height="265" style="width: 100%;" scrolling="no" title="templates-grid-css" src="http://codepen.io/rglepe/embed/PLBdgJ/?height=265&theme-id=0&default-tab=css,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/PLBdgJ/'>templates-grid-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Aplicant aquest codi, aconseguiríem una quadrícula on:

El *Item 1*, la capçalera (*head*), ocuparia tota la part superior.
El *Item 2*, el menú (*menu*), ocuparia l'àrea esquerra del grid, sota la capçalera.
El *Item 3*, el contingut (*main*), ocuparia l'àrea dreta del grid, sota la capçalera.
El *Item 4*, el peu de quadrícula (*foot*), ocuparia tota la zona inferior del grid.

En la propietat `grid-template-areas`, en lloc d'indicar el nom de l'àrea a col·locar, també podem indicar una paraula clau especial:

* La paraula clau **none**: Indica que no es col·locarà cap cel·la en aquesta posició.
* Un o més punts(**.**): Indica que es col·locarà una cel·la buida en aquesta posició.

### 2.11.6. Grid amb buits

Per defecte, la quadrícula té totes les seves cel·les pegades a les seves cel·les contigües. Encara que seria possible donar-li un **marge** a les cel·les dins del contenidor, existeix una forma més apropiada, que evita els problemes clàssics dels models de caixa: els buits (*gutters*).

Per especificar els buits (espai entre cel·les) podem utilitzar les propietats:
*  `grid-column-gap`: Estableix la mida dels buits entre columnes (línies verticals).
*  `grid-row-gap`: Estableix la mida dels buits entre files (línies horitzontals).

Prenguem l'exemple anterior com a base. En ell, li indiquem aquestes propietats per col·locar buits entre les cel·les de la quadrícula. El codi a afegir a l'exemple anterior seria el següent:

```css
.grid {
  grid-column-gap: 100px;
  grid-row-gap: 10px;
}
```

Amb això, obtindríem un resultat com el següent, indicant buits entre columnes de 100px i buits entre files de 10px.

![](https://imgur.com/2Ysd5pb.png)

* *short-hand*: Existeix una propietat de drecera per a les propietats `grid-column-gap` i `grid-row-gap`, permetent-nos la possibilitat de no haver d'indicar-les per separat.

La propietat en qüestió seria **`grid-gap`** i s'utilitzaria de la següent forma:

```css
.grid {
  /* grid-gap: <row-gap> <column-gap> */
  grid-gap: 20px 80px;

  /* grid-gap: <row-column-gap> */
  grid-gap: 40px;
  /* Equivalent a grid-gap: 40px 40px; */
}
```

### 2.11.7. Posició en el grid

Existeixen una sèrie de propietats que es poden utilitzar per col·locar els ítems dins de la quadrícula. Amb elles podem distribuir els elements d'una forma molt senzilla i còmoda. Aquestes propietats són: `justify-items` i `align-items`, de manera equivalent a **flexbox**:

* **`justify-items`:**	`start | end | center | stretch`	Distribueix els elements en l'eix horitzontal.
* **`align-items`:**	`start | end | center | stretch`	Distribueix els elements en l'eix vertical.

Aquestes propietats s'apliquen sobre l'element contenidor pare, però afecten als ítems fills, per la qual cosa actuen sobre la distribució de cadascun dels fills. En el cas que vulguem que un dels ítems fills tinguin una distribució diferent a la resta, apliquem la propietat `justify-self` o `align-self` sobre l'ítem fill en qüestió, sobreescrivint la seva distribució.

Aquestes propietats funcionen exactament igual que les seves anàlogues `justify-items` o `align-items`, només que en lloc d'indicar-se en l'element pare contenidor, es fa sobre un element fill. Les propietats sobre ítems fills les veurem més endavant.

També podem utilitzar les propietats `justify-content` o `align-content` per modificar la distribució de tot el contingut en el seu conjunt, i no només dels ítems per separat:

* **`justify-content:`**	`start | end | center | stretch | space-around | space-between | space-evenly`
* **`align-content:`**	`start | end | center | stretch | space-around | space-between | space-evenly`
  
D'aquesta forma, podem controlar pràcticament tots els aspectes de posicionament de la quadrícula directament des dels estils CSS del seu contenidor pare:

![](https://imgur.com/4ElWLs7.gif)

### 2.11.8. Ajust automàtic de cel·les

És possible utilitzar les propietats `grid-auto-columns` i `grid-auto-rows` per donar-li una grandària automàtica a les cel·les de la quadrícula. Per a això, només cal especificar la grandària desitjada en cadascuna de les propietats. A més, també podem utilitzar `grid-auto-flow` per indicar el flux d'elements en la quadrícula, i especificar per on s'aniran afegint. Les propietats són les següents:

* **`grid-auto-columns`:**	*`mida`*	Indica la grandària automàtica d'ample que tindran les columnes.
* **`grid-auto-rows`:**	*`mida`*	Indica la grandària automàtica d'alt que tindran les files.
* **`grid-auto-flow`:**	*`row | column |dense`*. Utilitza un algorisme de autoposicionament (intenta emplenar buits).
Un exemple de com s'inseririen els elements en una quadrícula de 2x2 utilitzant grid-auto-flow per columnes o per files:

![](https://imgur.com/RQiTaqK.png)

*short-hand*: `grid` serveix de drecera per a la majoria de propietats CSS relatives a quadrícules. El seu esquema d'utilització seria el següent, al costat d'alguns exemples:

```css
.grid {
  /* grid: <grid-template> <grid-auto-flow> <grid-auto-rows> / <grid-auto-columns> */

  grid: 100px 20px;
  grid: 200px repeat(2, 100px) 300px;
  grid: row;
  grid: column dense;
  grid: row 200px;
  grid: row 400px / 150px;
}
```
### 2.11.9. Propietats per a ítems fills

Fins ara, excepte algunes excepcions com `justify-self`, `align-self` o `grid-area`, hem vist propietats CSS que s'apliquen solament al contenidor pare d'una quadrícula. A continuació, anem a veure certes propietats que en el seu lloc, s'apliquen a cada ítem fill de la quadrícula, per alterar o canviar el comportament específic d'aquest element, que no es comporta com la majoria.

Algunes de les propietats vistes fins ara són les següents:

* `justify-self`:	Altera la justificació de l'ítem fill en l'eix horitzontal.
* `align-self`:	Altera l'alineació de l'ítem fill en l'eix vertical.
* `grid-area`:	Indica un nom a l'àrea especificada, per a la seva utilització amb grid-template-areas.

No obstant això, existeixen algunes propietats més, referents en aquest cas, a la posició dels fills de la quadrícula on va a començar o acabar una fila o columna. Les propietats són les següents:

* `grid-column-start`:	Indica que columna començarà l'ítem de la quadrícula.
* `grid-column-end`:	Indica que columna acabarà l'ítem de la quadrícula.
* `grid-row-start`:	Indica que fila començarà l'ítem de la quadrícula.
* `grid-row-end`:	Indica que fila acabarà l'ítem de la quadrícula.
Amb aquestes propietats, podem indicar el següent codi CSS sobre el primer ítem d'una quadrícula de 4 ítems:

```css
.grid {
  display:grid;
}
.a {
  grid-column-start: 1;
  grid-row-end: 2;
}
```

D'aquesta forma, tenim una quadrícula de 4 elements, en el qual indiquem la posició de l'ítem 1 (element HTML amb classe .a): començant en la columna 1 i acabant en l'inici de la columna 2:

Grid CSS: grid-column-start y grid-column-end

Aquest seria el funcionament normal. On es veu la utilitat d'aquestes propietats, és si variem els valors de manera que prenguin posicions diferents, com per exemple, si indiquem que l'ítem 1 ha de començar en la columna 1, però acabar en la columna 3 (ocupant la hipotètica primera i segona cel·la):

Grid CSS: grid-column-start y grid-column-end

En aquest nou exemple, comencem el primer ítem en la columna 2 i ho acabem al principi de la columna 3, per la qual cosa la cel·la romandrà en la posició de la segona columna. A més, afegim la propietat grid-row-start que fa el mateix que fins ara, però amb les files. En aquest cas, li indiquem que comenci en la fila 3, per la qual cosa l'ítem 1 es desplaça a una nova fila de la quadrícula, deixant en l'anterior l'ítem 4:

Grid CSS: grid-column-start y grid-column-end

També és possible utilitzar la paraula clau `span` seguida d'un nombre, que indica que abasti fins a aquesta columna o cel·la.

Drecera: grid-column i grid-row
El mòdul grid de CSS proporciona les propietats de drecera grid-column i grid-row on se'ns permet escriure en un format abreujat les propietats anteriors. La seva sintaxi seria la següent:

.grid {
  display: grid;
}

.a {
  /* grid-column: <grid-column-start> <grid-column-end> */
  /* grid-row: <grid-row-start> <grid-row-end> */
  grid-column: acte;
  grid-column: 4 / 6;
  grid-column: *span 3;
  grid-column: *span 3 / 6;
}

## 2.12. Media Queries

Un dels avanços més importants que va possibilitar CSS3, va ser la capacitat de donar una resposta condicional en funció de la mida del navegador, i aplicar diferents regles quan variem aquesta mida. Una de les eines que fem servir per tal de fer-ho són les media queries.

Les media queries es fan servir conjuntament amb altres tècniques per realitzar el que s’anomena disseny adaptatiu per a la web o RWD (Resposive Web Design), és a dir, variar diferents aspectes de disseny i regles CSS perquè s’adaptin a diferents dispositius, ja siguin smartphones, tablets, pantalles d’escriptori, etc.

La declaració de les media queries la podem fer o bé dins del mateix document HTML o en diferents documents associats al document HTML.

Dins del document HTML:

```css
  <style>
    @media screen and (min-width: 1200px){
    }
  </style>
```

Associant un document extern:

```html
    <link rel="stylesheet" media="screen and (min-width: 1200px)" href="estil_gran.css" />
```

En ambdós exemples veiem dues seccions importants: la que a l’exemple diu screen, que es refereix a les media type o tipus de mitjà, i la que ens parla de la grandària mínima amb l’atribut `min-width`, anomenada media features o característiques del mitjà.

### 2.12.1. Media types

El tipus de mitjans poden ser molt variats, i ens descriuen per quin mitjà volem aplicar les regles CSS que escollim. El llistat de mitjans és el següent:

* `all`: per qualsevol dispositiu.
* `braile`: per dispositius tàctils de Braile.
* `embossed`: per impressores de Braile paginades.
* `handheld`: per dispositius de mà o amb poca amplada de banda.
* `print`: el fem servir per impressores
* `projection`: el fem servir per projectors
* `screen`: per qualsevol pantalla.
* `speech`: per dispositius que sintetitzen veu.
* `tty`: per dispositius amb un joc de caràcters limitat, com ara terminals.
* `tv`: el fem servir per televisors.

### 2.12.2. Media features

Les media features, es referencien a característiques del mitjà com ara la resolució, l’orientació o l’amplada del dispositiu o del navegador entre d’altres, i la seva utilitat fer-les servir com a condicions per aplicar unes regles CSS o unes altres.

* `width` i `height`: dimensions de l’àrea de visualització, és a dir, la que el dispositiu renderitza. Admet valors fixos o relatius.
* `device-width` i `device-height`: amplada i alçada del dispositiu de sortida.
* `aspect-ratio`: relació entre amplada i l’alçada del dispositiu.
* `device-aspect-ratio`: igual a l’anterior però referit a la resolució de la pantalla.
* `color`: número de bits per cada component de color.
* `color-index`: nombre d’entrades a la taula de color del dispositiu.
`orientation`: podem fer servir dos valors `landscape` (horitzontal) o `portrait` (vertical).
`monochrome`: nombre de bits per pixel a la memòria del quadre de vídeo monocromàtic.
`resolution`: resolució del dispositiu expressat en dpi (punt per polzada) o dpcm (punts per centímetre)
`device-pixel-ratio`: densitat de pixel, és a dir, punts per pixel. Els valors habituals són 1.5 o 2 en dispositius amb pantalles de retina.
Totes les media features admeten el prefix `max-` o `min-`, a excepció de orientation.

Vegem-ho amb un exemple pràctic: imaginem que tenim un div identificat pel id contenidor que conté dos quadres de color, identificats per quadre1 i quadre2. Volem que aquests quadres estiguin a mà esquerra i dreta respectivament flotant dins del contenidor, de forma que si escurcem l’amplada del navegador per sota de 600px, els dos quadres es mantinguin en aquestes posicions. Però també volem que passada una amplada mínima de 600px no es desplacin més, ja que quedarien molt apartats entre ells. Les codificacions per fer-ho són:

```HTML

<div id="contenidor">
  <div id="quadre1"></div>
  <div id="quadre2"></div>
</div>
```

```css:

#quadre1 {
  width: 100px;
  height: 100px;
  background-color: coral;
  margin: 10px;
  float: left;
}
#quadre2 {
  width: 100px;
  height: 100px;
  background-color: coral;
  margin: 10px;
  float: right;			
}
@media all and (min-width:600px){
  #contenidor{
   width:600px; /*Forcem que el div contenidor no superi mai una amplada de 600px quan el navegador la supera*/
  }
}
```

Per sobre de 600px d’amplada del navegador el quadre contenidor no supera els 600px, tal com es mostra a la figura Figure40:

Figura Funcionament de les media queries

## 2.13. Exemples pràctics amb CSS

L’art del CSS no és saber-se totes les propietats que hi ha de memòria sinó saber-les combinar adequadament per aconseguir els efectes desitjats. Hi ha centenars de tècniques per a problemes comuns.

Casos típics on és necessari dominar les propietats CSS són fer menús a partir de llistes o maquetar webs sense usar taules.

### 2.13.1. Fer menús amb llistes

Gairebé tot web disposa d’un menú de navegació que ens permet anar enllaçant amb les diferents seccions del lloc. Una manera molt elegant de fer aquests menús és pensar-los com una llista amb ítems (i subítems, si s’escau). El problema que tenim és que les llistes són “lletges”.

Vegem com podem fer un més “bonic” a partir d’una llista. Es tracta d’un menú vertical que té l’aspecte que es mostra a continuació:

<iframe height="265" style="width: 100%;" scrolling="no" title="menu-facil-css" src="http://codepen.io/rglepe/embed/MxZjwK/?height=265&theme-id=0&default-tab=css,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rglepe/pen/MxZjwK/'>menu-facil-css</a> by Raul Garcia
  (<a href='https://codepen.io/rglepe'>@rglepe</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Figura Menú fet amb una llista

El codi (X)HTML és molt simple. Es tracta simplement d’una llista desordenada:

Si estiguéssim usant (X)HTML5 en lloc d’usar `<div id=“menu”` usaríem l’etiqueta `<nav>`.

```html
<div id="menu">
   <ul>
      <li><a href="index.html">Inici</a></li>
      <li><a href="seccio1.html">Secció 1</a></li>
      <li><a href="sexxio2.html">Secció 2</a></li>
   </ul>
</div>
```

A continuació combinarem diverses de les regles CSS existents per tal d’aconseguir que aquesta simple llista desordenada acabi essent un menú atractiu i accessible per a l’usuari.

Primer de tot, hem de dir a la llista que no volem pics a cada ítem, i això ho podem aconseguir aplicant una propietat específica de llistes que es diu list-style-type. A més, traiem marges i farciments i hi posem una vora:

```css
#menu ul {
   list-style-type: none ;
   margin: 0;
   padding: 0;
   border: thick solid #D68EFF;
}
```
A cada ítem de la llista hi canviem el color de fons:

```css
#menu ul li {
   background-color: #B20298;
}
```

Ara definim l’estil dels enllaços: canviem el color de la lletra, traiem el subratllat, fem que les lletres siguin sempre majúscules i hi posem una mica de farciment. Hem de destacar que la declaració `display: block` serveix perquè l’enllaç passi a ser un element de bloc (per defecte, és un element de línia) i així poder prémer l’enllaç en tot el bloc, no només on hi ha les lletres de l’enllaç:

```css
#menu ul li a {
   color: white;
   text-decoration: none;
   text-transform: uppercase;
   display: block;
   padding: 0.2em 0.2em 0.2em 0.4em;
}
```

Finalment, definim quina estètica han de tenir els enllaços quan hi passem per damunt. En aquest cas, els canviem el color de lletra i de fons, i hi fem aparèixer una vora a l’esquerra:

```css
#menu ul li a:hover {
   background: #CC4ABD;
   border-left: 0.3em solid #58014B;
   color: #58014B;
}
```

### 2.13.2. Maquetació de webs

La maquetació que ens proposem fer és la d’un lloc web típic (*The holly grial web*), amb una capçalera, dos barres laterals: una per al menú i l'altre per informació adicional, el cos de la pàgina amb el contingut del lloc i un peu de pàgina. El resultat desitjat el podeu observar en la següent figura:

![holly-grail](https://imgur.com/qNPH6De.png)

Usarem les etiquetes HTML5 estructurals (<header>, <nav>, <footer>…) en lloc d’usar etiquetes <div> amb identificadors.

```html
<body>
   <div id="contenidor">
      <header>
         <h1>Títol de la web</h1>
         <h2>Subtítol de la web</h2>
      <header>
      <main>
         <article>
            <h3>Inici</h3>
            <p>..</p>
         </article>
         <nav>
            <ul>
               <li><a href="index.html">Inici</a></li>
               <li><a href="seccio1.html">Secció 1</a></li>
               <li><a href="seccio2.html">Secció 2</a></li>
            </ul>
         </nav>
         <aside>
         </aside>
      </main>
      <footer id="peu">
         <p>Peu de página </p>
      </footer>
   </div>
</body>
```

Ara definim les regles pertinents per aconseguir els nostres objectius.

En la marca `<body>` definim totes les propietats genèriques: color de fons, color de lletra i tipus de lletra. A més, posem el text centrat (perquè Internet Explorer entengui que volem el contingut centrat) i traiem qualsevol tipus de marge.

```css
body {
   text-align: center ;
   background-color:#FFC7FC;
   color: #58014B;
   font: small sans-serif;
   margin: 0;
}
```
Al `<div>` amb identificador contenidor hem de dir-li que no ocupi tota la pàgina (li diem que n’ocupi només un 80%), que quedi centrat (això s’aconsegueix posant els marges esquerre i dret amb valor auto) i que el fons sigui blanc. A més, fem que tot el text del web estigui alineat a l’esquerra.

```css
#contenidor{
   width: 80%;
   margin: 0px auto;
   text-align: left;
   background-color:white;
}
```

La capçalera i el peu de pàgina tenen propietats comunes: tenen la mateixa imatge de fons, el color de lletra és blanc i en negreta, i el text està centrat.

```css
#cap, #peu{
   background-image: url("imatges/banner-web.png");
   text-align:center;
   font-weight: bold;
   color:white;
}
```

Especifiquem també les propietats que només afecten la capçalera: volem que els títols que contingui no tinguin marges:

```css
#cap h1, #cap h2{ 
   margin:0; 
}
```

Posem, a més, les mides per defecte que han de tenir tots els encapçalaments `<h1>` i `<h2>` de la pàgina:

```css
h1 { 
   font-size: 5em; 
}
 
h2 { 
   font-size: 4em; 
}
```

Per al peu de pàgina també tenim propietats específiques: la lletra ha de ser petita i fem que no pugui tenir cap element flotant. Així, la barra lateral, que és un element flotant, mai no es posarà per damunt del peu de pàgina.

```css
#peu {
   font-size: small;
   clear: both;
}
```

Ara definim la barra lateral: és un element flotant a l’esquerra i té una amplada del 15% de la pàgina:

```css
#lateral {
   width: 15%;
   float: left;
}
```

Per maquetar el cos del web diem que el marge esquerre és d’un 15%, que és just l’espai que ocupa la barra lateral. A més, posem una mica de farciment a l’esquerra, perquè el text del cos no quedi enganxat al menú.

```css
#cos {
   margin-left: 15% ;
   padding-left: 1em ;
}
```

Amb totes aquestes regles hem aconseguit el nostre objectiu: tenim una web bonica, ben estructurada, amb un codi (X)HTML senzill i sense fer ús de taules.

### 2.13.3. Simulació de marcs amb CSS

L’ús de marcs no és gens aconsellable. A partir d’un ús intel·ligent de les propietats CSS podem simular marcs sense usar-los. Vegem com.

L’exemple mostrarà una web amb una capçalera i un peu de pàgina, un menú lateral esquerre i una part central de la web amb el contingut de cada secció. Suposarem que el contingut de cada secció no és molt llarg, de manera que posarem el contingut de totes les seccions en el mateix document HTML. Si ho preferíssim, podríem crear diverses pàgines repetint la mateixa estructura que aquí es presenta.

El codi del cos del document seria el següent:

```html
<body>
<div id="contenidor">
   <div id="cap">
      <h1>Títol de la web</h1>
      <h2>Subtítol de la web</h2>
   </div>
   <div id="lateral">
      <div id="menu">
         <ul>
            <li><a href="#inici">Inici</a></li>
            <li><a href="#seccio1">Secció 1</a></li>
            <li><a href="#seccio2">Secció 2</a></li>
         </ul>
      </div>
   </div>
   <div id="cos">
      <div id="inici">
         <h3>Inici</h3>
         <p>...</p>
         <p>...</p>
         <p>...</p>
      </div>
      <div id="seccio1">
         <h3>Secció 1</h3>
         <p>...</p>
         <p>...</p>
         <p>...</p>
      </div>
      <div id="seccio2">
         <h3>Secció 2</h3>
         <p>...</p>
         <p>...</p>
         <p>...</p>
      </div>
   </div>  
   <div id="peu">
      <p>Peu de pàgina </p>
   </div>
</div>
</body>
```

Per tal de simular els marcs hem de fer que les capes cap, lateral, cos i peu estiguin fixades i que si el contingut de cada secció, que s’anirà mostrant a la capa cos, no hi cap, ens aparegui una barra de desplaçament. Aquests objectius els aconseguirem amb una combinació de les propietats position: fixed i overflow:auto.

Primer posicionarem la capa contenidor per tal que no ocupi la totalitat de la finestra. Tindrà una amplada del 80%, amb un marge del 10% per cada costat.

```css
/* Contenidor que ho engloba tot (capçalera, columnes i peu) */

#contenidor{
   /* El contingut de la web ocuparà el 80% d'amplada de la finestra*/
   width: 80%;
   /* Centrem el contenidor */
   margin: 0px auto;
   /* Text alineat a l'esquerra */
   text-align: left;
   /* Fons de color blanc */
   background-color:white;
}
```

Ara posicionarem cadascuna de les capes principals:

```css
#cap {
   /* Posició fixada*/
   position: fixed;
   /* Posició de la capçalera: la posem a dalt de tot */
   top: 0;
   /* Mides de la capçalera */
   width: 80%;
   height: 25%;
   /* Si el text sobrepassa l'alçada de la capçalera quedarà ocult */
   overflow:hidden;
}
 
#peu {
   /* Posició fixada*/
   position: fixed;
   /* Posició del peu de pàgina */
   top: 90%;
   /* Mides del peu de pàgina */
   width: 80%;
   /* Si el text sobrepassa el peu de pàgina quedarà ocult */
   overflow:hidden;
}
 
#lateral {
   /* Posició fixada*/
   position: fixed;
   /* Posició de la columna esquerra, coincideix amb l'alçada de la capçalera */
   top: 25%;
   /* Mides de la columna esquerra */
   width: 12%;
   height: 65%;
   /* Si el text sobrepassa l'alçada de la columna quedarà ocult */
   overflow:hidden;
   /* Color de fons */
   background-color:white;
}
 
#cos {
   /* Posició fixada*/
   position: fixed;
   /* Posició del cos, coincideix amb l'alçada de la capçalera */
   top: 25%;
   /* Posicionem a 10% (marg esquerre del contenidor) + 12% (amplada columna esquerra)*/
   left: 22%;   
   /* Establim marge i farciment */
   margin-left: 0%;
   padding-left: 1%;
   /* Mides del cos. */ 
   /* L'amplada: 67% + 1% (padding) + 12% (columna esquerra) = 80% (amplada total del contenidor) */
   width: 67%;
   height: 65%;   
   /* Si el text sobrepassa l'alçada del cos de la web quedarà ocult */
   overflow:hidden;
   /* Color de fons */
   background-color:white;
}
```

Finalment, hem de fer que els `<div>` que siguin fills de la capa cos ocupin tota l’alçada de la capa cos i si el text és molt llarg ens aparegui una barra de desplaçament. Això ho aconseguirem amb la següent regla:

```css
#cos>div{
   /* Els <div> de dins el cos ocuparan tota l'alçada possible */
   height: 100%;
   /* Si el text sobrepassa l'alçada del <div> apareixerà una barra de desplaçament */
   overflow: auto;
}
```

Tot plegat es mostra al següent exemple:

