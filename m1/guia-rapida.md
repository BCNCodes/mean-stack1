### Conceptos HTML

* Elementos de bloque vs elementos inline
* Uso de semánticos:
  * nav
  * main
  * section
  * article
  * header
  * summary
  * details
  * figure
  * aside
  * figcaption
  * footer
  * mark
  * time

### Conceptos CSS
 * Regla CSS: Selector-Propiedad-Valor
 * Introducción al DOM:
 ![DOM](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/DOM-model.svg/989px-DOM-model.svg.png)
 
 * Selector de tipo: body, p, h1
 * Selector de clase: .menu{}, .menu-item{}
 * Selector de id: #item1{}
 * Selector de atributo: img[title], img[title="riv"]{}
 * Selectores de descendientes: p destaca{ }
 * Selectores de hijos p>destaca{}
 * Selectores de hermano adyacente p+h1{}
 * Selectores de hermano general p~h1{}
 * Agrupamiento de selectores: h1, h2, h3, h6{}
 * Pseudo-clase: a:visited{}
 * Pseudo-elemento: div::after{}

### A List of DOM Properties and Methods

Here is a list of some more [DOM Properties](https://developer.mozilla.org/en-US/docs/Web/API/Element) and [DOM Methods](https://developer.mozilla.org/en-US/docs/Web/API/Element#Methods) for you to refer to

| **Property / Method** | **Description** |
|-----------------------|-----------------|
| `element.attributes` | Returns a NamedNodeMap of an element's attributes
| `element.childNodes` | Returns a collection of an element's child nodes (including text and comment nodes)
| `element.children` | Returns a collection of an element's child element (excluding text and comment nodes)
| `element.classList` | Returns an array with the class name(s) of an element
| `element.className`	| Sets or returns the value of the class attribute of an element
| `element.clientHeight` | Returns the height of an element, including padding
| `element.clientLeft` | Returns the width of the left border of an element
| `element.clientTop` | Returns the width of the top border of an element
| `element.clientWidth` | Returns the width of an element, including padding
| `element.contains()` | Returns true if a node is a descendant of a node, othwerwise false
| `element.contentEditable` | Sets or returns whether the content of an element is editable or not
| `element.firstChild` | Returns the first child node of an element
| `element.firstElementChild` | Returns the first child element of an element
| `element.focus()` | Gives focus to an element
| `element.getAttribute()` | Returns the specified attribute value of an element node
| `element.getAttributeNode()` | Returns the specified attribute node
| `element.getElementsByClassName()` |Returns a collection of all child elements with the specified class name
| `element.getElementsByTagName()` | Returns a collection of all child elements with the specified tag name
| `element.getFeature()`| Returns an object which implements the APIs of a specified feature
| `element.hasAttribute()` | Returns true if an element has the specified attribute, otherwise false
| `element.hasAttributes()` | Returns true if an element has any attributes, otherwise false
| `element.hasChildNodes()` | Returns true if an element has any child nodes, otherwise false
| `element.id` | Sets or returns the value of the id attribute of an element
| `element.isEqualNode()` | Checks if two elements are equal
| `element.isSameNode()` | Checks if two elements are the same node
| `element.lastChild` | Returns the last child node of an element
| `element.lastElementChild` | Returns the last child element of an element
| `element.nextSibling` | Returns the next node at the same node tree level
| `element.nextElementSibling` | Returns the next element at the same node tree level
| `element.nodeName` | Returns the name of a node
| `element.nodeValue` | Sets or returns the value of a node
| `element.offsetHeight` | Returns the height of an element, including padding, border and scrollbar
| `element.offsetWidth` | Returns the width of an element, including padding, border and scrollbar
| `element.offsetLeft` | Returns the horizontal offset position of an element
| `element.offsetParent` | Returns the offset container of an element
| `element.offsetTop` | Returns the vertical offset position of an element
| `element.parentNode` | Returns the parent node of an element
| `element.parentElement` | Returns the parent element node of an element
| `element.previousSibling` | Returns the previous node at the same node tree level
| `element.previousElementSibling` | Returns the previous element at the same node tree level
| `element.querySelector()` | Returns the first child element that matches a specified CSS selector(s) of an element
| `element.querySelectorAll()` | Returns all child elements that matches a specified CSS selector(s) of an element
| `element.removeAttribute()` | Removes a specified attribute from an element
| `element.removeAttributeNode()` | Removes a specified attribute node, and returns the removed node
| `element.removeChild()` | Removes a child node from an element
| `element.replaceChild()` | Replaces a child node in an element
| `element.removeEventListener()` | Removes an event handler that has been attached with the addEventListener() method
| `element.scrollHeight` | Returns the entire height of an element, including padding
| `element.scrollLeft` | Sets or returns the number of pixels an element's content is scrolled horizontally
| `element.scrollTop` | Sets or returns the number of pixels an element's content is scrolled vertically
| `element.scrollWidth` | Returns the entire width of an element, including padding
| `element.setAttribute()` | Sets or changes the specified attribute, to the specified value
| `element.setAttributeNode()` | Sets or changes the specified attribute node
| `element.style` | Sets or returns the value of the style attribute of an element
| `element.tabIndex` | Sets or returns the value of the tabindex attribute of an | element
| `element.tagName` | Returns the tag name of an element
| `element.textContent` | Sets or returns the textual content of a node and its | descendants
| `element.title` | Sets or returns the value of the title attribute of an element
| `element.toString()` | Converts an element to a string
| `nodelist.item()` | Returns the node at the specified index in a NodeList
| `nodelist.length` | Returns the number of nodes in a NodeList





### Enlaces:
+ Aplicacions de productivitat:
  * [Trello](https://trello.com): aplicación de programación tareas  en proyecto (Kanban)
  * [SLACK](https://slack.com/intl/es-es/): herramienta comunicación de equipos
  * [Visual Studio Code](https://code.visualstudio.com/): editor de texto para programar
  * [Git](https://git-scm.com/): herramienta de control de versiones distribuida
  * [Giphy](https://giphy.com/): herramienta para generar .gif
  * [Postimage](https://postimg.cc): herramienta almacenamiento de imágenes que después se pueden referenciar en nuestros proyectos
  * [imgur](https://imgur.com): almacenamiento de imágenes
  * [Codepen](https://codepen.io): herramienta para generar aplicaciones HTML-CSS-JS
+ [Primera Web](http://info.cern.ch/)
+ Recursos MDN html:
  * [Aprende HTML](https://developer.mozilla.org/es/docs/Learn)
  * [Referències HTML](https://developer.mozilla.org/kab/docs/Web/HTML)
  * [Planificació d'una Web simple](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure#Enter_HTML5_structural_elements#Planning_a_simple_website)
+ [W3C Validator](https://validator.w3.org/#validate_by_input )
+ [HTML5Doctor](http://html5doctor.com/element-index/)
+ [W3CSchools](https://www.w3schools.com/)

* Aplicación para móvil equivalencias medidas: Introspect (Android y Apple)
* [Fuentes y Tipografías](https://lenguajecss.com/p/css/propiedades/fuentes-y-tipografias): Buena página para entender cómo funcionan las fuentes en css.
* [Plates](https://flukeout.github.io/): juego para aprender selectores CSS
* [cheat-sheet emmet](https://docs.emmet.io/cheat-sheet/): Guía de atajos para CSS y HTML
* [Centrado de elementos con CSS](http://laboratorio.pablofv.com/front-end/centrar-elementos-con-css/#centro42)
* [Advanced Styling CSS Forms](https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/Advanced_styling_for_HTML_forms);
* [Wufoo](https://www.wufoo.com/gallery/templates/): Plantillas Formularios
* [https://htmlreference.io/forms/](https://htmlreference.io/forms/): Referencia rápida de widgets de formularios
* [The Accessibility of Styled Form Controls]https://github.com/scottaohara/a11y_styled_form_controls: Información y ejemplo de restyling de widgets de formulario sin alterar la accesibilidad.
