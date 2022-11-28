# Movie Challenge

## Índice

- [1. Preámbulo](#1-preambulo)
- [2. Resumen del proyecto](#2-resumen-del-proyecto)
- [3. Consideraciones generales](#3-consideraciones-generales)
- [4. Objetivos de aprendizaje](#4-objetivos-de-aprendizaje)
- [5. Criterios de aceptación mínimos del proyecto](#5-criterios-de-aceptacion-minimos-del-proyecto)
- [6. Consideraciones técnicas](#6-consideraciones-tecnicas)
- [7. Pistas, tips y lecturas complementarias](#8-pistas-tips-y-lecturas-complementarias)

---

## 1. Preámbulo

La manera en que vemos películas ha cambiado radicalmente durante los últimos
años debido, en parte, a la aparición de los servicios de
[_streaming_](https://es.wikipedia.org/wiki/Streaming) que nos permiten hacerlo
desde donde estemos y en cualquier momento. El mejor reflejo de este fenómeno es
el éxito de Netflix, HBO y Disney+, etc.

En tiempos en los que una de las principales herramientas para combatir
[la pandemia de Covid-19](https://es.wikipedia.org/wiki/COVID-19) es
[evitar](https://es.wikipedia.org/wiki/Distanciamiento_social) compartir
espacios con muchas personas (como en el cine), ver películas por _streaming_
será una de las pocas maneras de hacerlo (¿o la única?).

Creemos que hay una gran oportunidad de proponer productos/experiencias
innovadoras de todo tipo utilizando datos de películas (directorxs, actorxs,
sagas, secuelas, fechas, etc.). Podríamos pensar en juegos, comunidades,
catálogos, recomendaciones basadas en gustos personales, etc. (sólo por
mencionar algunas ideas obvias).

![Pelis](https://live.staticflickr.com/117/257368762_38bf6fcf9f_h.jpg)

## 2. Resumen del proyecto

La idea de este proyecto es que, usando una API con información de películas,
puedas idear, planear, organizar y desarrollar una aplicación web que aproveche
estos datos y tenga una propuesta de valor atractiva para lxs usuarixs.

Aunque la decisión de qué hacer es enteramente tuya, hay algunas consideraciones
generales que se presentan a continuación. Puedes cumplir esos requisitos en
proyectos muy diferentes, ¡depende de tu creatividad y del entendimiento que
tengas de tus potenciales usuarixs!

## 3. Consideraciones generales

- Este proyecto se debe resolver en equipos de 2 o más personas.
- Debes elegir y sustentar qué problema o necesidad estás resolviendo con el
  producto que estás diseñando y desarrollando.
- Debes utilizar los datos de la API de [OMDB](http://www.omdbapi.com/) (The
  Open Movie Database) con
  [Fetch](https://developer.mozilla.org/es/docs/Web/API/Fetch_API) o cualquier
  otra API que encuentres.
- Piensa en _test driven development_ al momento de programar la solución.
  Tendrás que escribir las pruebas unitarias, aprovecha la oportunidad de
  comenzar haciéndolo antes de escribir la funcionalidad.
- Este proyecto es "agnóstico" a la tecnología que uses, es decir puedes
  desarrollarlo en Vanilla JavaScript o algún _framework_ o biblioteca
  (librería) de tu elección.
- Intenta pensar en un alcance que, considerando su complejidad y la cantidad de
  personas en el equipo, permita terminar el proyecto en 2 semanas.

## 4. Objetivos de aprendizaje

Reflexiona y luego marca los objetivos que has llegado a entender y aplicar en tu proyecto. Piensa en eso al decidir tu estrategia de trabajo.

### HTML

- [ ] **Uso de HTML semántico**

    <details><summary>Links</summary><p>

  - [HTML semántico](https://curriculum.laboratoria.la/es/topics/html/02-html5/02-semantic-html)
  - [Semantics - MDN Web Docs Glossary](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#Semantics_in_HTML)
  </p></details>

### CSS

- [ ] **Uso de selectores de CSS**

    <details><summary>Links</summary><p>

  - [Intro a CSS](https://curriculum.laboratoria.la/es/topics/css/01-css/01-intro-css)
  - [CSS Selectors - MDN](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Selectors)
  </p></details>

- [ ] **Modelo de caja (box model): borde, margen, padding**

    <details><summary>Links</summary><p>

  - [Box Model & Display](https://curriculum.laboratoria.la/es/topics/css/01-css/02-boxmodel-and-display)
  - [The box model - MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
  - [Introduction to the CSS box model - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)
  - [CSS display - MDN](https://developer.mozilla.org/pt-BR/docs/Web/CSS/display)
  - [display - CSS Tricks](https://css-tricks.com/almanac/properties/d/display/)
  </p></details>

- [ ] **Uso de flexbox en CSS**

    <details><summary>Links</summary><p>

  - [A Complete Guide to Flexbox - CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  - [Flexbox Froggy](https://flexboxfroggy.com/#es)
  - [Flexbox - MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
  </p></details>

- [ ] **Uso de CSS Grid Layout**

    <details><summary>Links</summary><p>

  - [A Complete Guide to Grid - CSS Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)
  - [Grids - MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Grids)
  </p></details>

- [ ] **Uso de media queries**

  <details><summary>Links</summary><p>

  - [CSS media queries - MDN](https://developer.mozilla.org/es/docs/CSS/Media_queries)

### Web APIs

- [ ] **Uso de selectores del DOM**

    <details><summary>Links</summary><p>

  - [Manipulación del DOM](https://curriculum.laboratoria.la/es/topics/browser/02-dom/03-1-dom-methods-selection)
  - [Introducción al DOM - MDN](https://developer.mozilla.org/es/docs/Web/API/Document_Object_Model/Introduction)
  - [Localizando elementos DOM usando selectores - MDN](https://developer.mozilla.org/es/docs/Web/API/Document_object_model/Locating_DOM_elements_using_selectors)
  </p></details>

- [ ] **Manejo de eventos del DOM (listeners, propagación, delegación)**

    <details><summary>Links</summary><p>

  - [Introducción a eventos - MDN](https://developer.mozilla.org/es/docs/Learn/JavaScript/Building_blocks/Events)
  - [EventTarget.addEventListener() - MDN](https://developer.mozilla.org/es/docs/Web/API/EventTarget/addEventListener)
  - [EventTarget.removeEventListener() - MDN](https://developer.mozilla.org/es/docs/Web/API/EventTarget/removeEventListener)
  - [El objeto Event](https://developer.mozilla.org/es/docs/Web/API/Event)
  </p></details>

- [ ] **Manipulación dinámica del DOM**

    <details><summary>Links</summary><p>

  - [Introducción al DOM](https://developer.mozilla.org/es/docs/Web/API/Document_Object_Model/Introduction)
  - [Node.appendChild() - MDN](https://developer.mozilla.org/es/docs/Web/API/Node/appendChild)
  - [Document.createElement() - MDN](https://developer.mozilla.org/es/docs/Web/API/Document/createElement)
  - [Document.createTextNode()](https://developer.mozilla.org/es/docs/Web/API/Document/createTextNode)
  - [Element.innerHTML - MDN](https://developer.mozilla.org/es/docs/Web/API/Element/innerHTML)
  - [Node.textContent - MDN](https://developer.mozilla.org/es/docs/Web/API/Node/textContent)
  </p></details>

### JavaScript

- [ ] **Diferenciar entre tipos de datos primitivos y no primitivos**

- [ ] **Arrays (arreglos)**

    <details><summary>Links</summary><p>

  - [Arreglos](https://curriculum.laboratoria.la/es/topics/javascript/04-arrays)
  - [Array - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/)
  - [Array.prototype.sort() - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)
  - [Array.prototype.forEach() - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)
  - [Array.prototype.map() - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
  - [Array.prototype.filter() - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
  - [Array.prototype.reduce() - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce)
  </p></details>

- [ ] **Objetos (key, value)**

    <details><summary>Links</summary><p>

  - [Objetos en JavaScript](https://curriculum.laboratoria.la/es/topics/javascript/05-objects/01-objects)
  </p></details>

- [ ] **Variables (declaración, asignación, ámbito)**

    <details><summary>Links</summary><p>

  - [Valores, tipos de datos y operadores](https://curriculum.laboratoria.la/es/topics/javascript/01-basics/01-values-variables-and-types)
  - [Variables](https://curriculum.laboratoria.la/es/topics/javascript/01-basics/02-variables)
  </p></details>

- [ ] **Uso de condicionales (if-else, switch, operador ternario, lógica booleana)**

    <details><summary>Links</summary><p>

  - [Estructuras condicionales y repetitivas](https://curriculum.laboratoria.la/es/topics/javascript/02-flow-control/01-conditionals-and-loops)
  - [Tomando decisiones en tu código — condicionales - MDN](https://developer.mozilla.org/es/docs/Learn/JavaScript/Building_blocks/conditionals)
  </p></details>

- [ ] **Uso de bucles/ciclos (while, for, for..of)**

    <details><summary>Links</summary><p>

  - [Bucles (Loops)](https://curriculum.laboratoria.la/es/topics/javascript/02-flow-control/02-loops)
  - [Bucles e iteración - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Loops_and_iteration)
  </p></details>

- [ ] **Funciones (params, args, return)**

    <details><summary>Links</summary><p>

  - [Funciones (control de flujo)](https://curriculum.laboratoria.la/es/topics/javascript/02-flow-control/03-functions)
  - [Funciones clásicas](https://curriculum.laboratoria.la/es/topics/javascript/03-functions/01-classic)
  - [Arrow Functions](https://curriculum.laboratoria.la/es/topics/javascript/03-functions/02-arrow)
  - [Funciones — bloques de código reutilizables - MDN](https://developer.mozilla.org/es/docs/Learn/JavaScript/Building_blocks/Functions)
  </p></details>

- [ ] **Pruebas unitarias (unit tests)**

    <details><summary>Links</summary><p>

  - [Empezando con Jest - Documentación oficial](https://jestjs.io/docs/es-ES/getting-started)
  </p></details>

- [ ] **Módulos de ECMAScript (ES Modules)**

    <details><summary>Links</summary><p>

  - [import - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Statements/import)
  - [export - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Statements/export)
  </p></details>

- [ ] **Uso de linter (ESLINT)**

- [ ] **Uso de identificadores descriptivos (Nomenclatura y Semántica)**

- [ ] **Diferenciar entre expresiones (expressions) y sentencias (statements)**

### Angular

- [ ] **Components & templates**

    <details><summary>Links</summary><p>

  - [Angular Components Overview - Documentación oficial (en inglés)](https://angular.io/guide/component-overview)
  - [Introduction to components and templates - Documentación oficial (en inglés)](https://angular.io/guide/architecture-components#introduction-to-components)
  </p></details>

- [ ] **Directivas estructurales (ngIf / ngFor)**

    <details><summary>Links</summary><p>

  - [Writing structural directives - Documentación oficial (en inglés)](https://angular.io/guide/structural-directives)
  </p></details>

- [ ] **@Input | @Output**

    <details><summary>Links</summary><p>

  - [Component interaction - Documentación oficial (en inglés)](https://angular.io/guide/component-interaction#component-interaction)
  </p></details>

- [ ] **Creación y uso de servicios**

    <details><summary>Links</summary><p>

  - [Providing services - Documentación oficial (en inglés)](https://angular.io/guide/architecture-services#providing-services)
  </p></details>

- [ ] **Manejo de rutas**

    <details><summary>Links</summary><p>

  - [In-app navigation: routing to views - Documentación oficial (en inglés)](https://angular.io/guide/router)
  </p></details>

- [ ] **Creación y uso de Observables.**

    <details><summary>Links</summary><p>

  - [Observables in Angular - Documentación oficial (en inglés)](https://angular.io/guide/observables-in-angular)
  </p></details>

- [ ] **Uso de HttpClient**

    <details><summary>Links</summary><p>

  - [Communicating with backend services using HTTP - Documentación oficial (en inglés)](https://angular.io/guide/http)
  </p></details>

- [ ] **Estilos de componentes (ngStyle / ngClass)**

    <details><summary>Links</summary><p>

  - [Template syntax - Documentación oficial (en inglés)](https://angular.io/guide/template-syntax#built-in-directives)
  </p></details>

### React

- [ ] **JSX**

    <details><summary>Links</summary><p>

  - [Presentando JSX - Documentación oficial](https://es.reactjs.org/docs/introducing-jsx.html)
  </p></details>

- [ ] **Componentes y propiedades (props)**

    <details><summary>Links</summary><p>

  - [Componentes y propiedades - Documentación oficial](https://es.reactjs.org/docs/components-and-props.html)
  </p></details>

- [ ] **Manejo de eventos**

    <details><summary>Links</summary><p>

  - [Manejando eventos - Documentación oficial](https://es.reactjs.org/docs/handling-events.html)
  </p></details>

- [ ] **Listas y keys**

    <details><summary>Links</summary><p>

  - [Listas y keys - Documentación oficial](https://es.reactjs.org/docs/lists-and-keys.html)
  </p></details>

- [ ] **Renderizado condicional**

    <details><summary>Links</summary><p>

  - [Renderizado condicional - Documentación oficial](https://es.reactjs.org/docs/conditional-rendering.html)
  </p></details>

- [ ] **Elevación de estado**

    <details><summary>Links</summary><p>

  - [Levantando el estado - Documentación oficial](https://es.reactjs.org/docs/lifting-state-up.html)
  </p></details>

- [ ] **Hooks**

    <details><summary>Links</summary><p>

  - [Presentando Hooks - Documentación oficial](https://es.reactjs.org/docs/hooks-intro.html)
  </p></details>

- [ ] **CSS modules**

    <details><summary>Links</summary><p>

  - [Adding a CSS Modules Stylesheet - Documentación de Create React App (en inglés)](https://create-react-app.dev/docs/adding-a-css-modules-stylesheet/)
  </p></details>

- [ ] **React Router**

    <details><summary>Links</summary><p>

  - [Quick Start - Documentación oficial (en inglés)](https://reactrouter.com/web/guides/quick-start)
  </p></details>

### Vue

- [ ] **Instancia de Vue.js**

    <details><summary>Links</summary><p>

  - [La instancia Vue - Documentación oficial](https://es.vuejs.org/v2/guide/instance.html)
  </p></details>

- [ ] **Datos y métodos**

    <details><summary>Links</summary><p>

  - [Datos y Métodos - Documentación oficial](https://es.vuejs.org/v2/guide/instance.html#Datos-y-Metodos)
  </p></details>

- [ ] **Uso y creación de componentes**

    <details><summary>Links</summary><p>

  - [Conceptos Básicos de Componentes - Documentación oficial](https://es.vuejs.org/v2/guide/components.html)
  </p></details>

- [ ] **Props**

    <details><summary>Links</summary><p>

  - [Pasando datos a componentes secundarios con Props - Documentación oficial](https://es.vuejs.org/v2/guide/components.html#Pasando-datos-a-componentes-secundarios-con-Props)
  </p></details>

- [ ] **Directivas (v-bind | v-model)**

    <details><summary>Links</summary><p>

  - [v-bind - Documentación oficial](https://es.vuejs.org/v2/api/#v-bind)
  - [Binding en Formularios - Documentación oficial](https://es.vuejs.org/v2/guide/forms.html)
  </p></details>

- [ ] **Iteración (v-for)**

    <details><summary>Links</summary><p>

  - [Mapeando una matriz a elementos con v-for - Documentación oficial](https://es.vuejs.org/v2/guide/list.html#Mapeando-una-matriz-a-elementos-con-v-for)
  </p></details>

- [ ] **Eventos (v-on)**

    <details><summary>Links</summary><p>

  - [Manejo de eventos - Documentación oficial](https://es.vuejs.org/v2/guide/events.html)
  </p></details>

- [ ] **Propiedades Computadas y Observadores**

    <details><summary>Links</summary><p>

  - [Propiedades Computadas y Observadores](https://es.vuejs.org/v2/guide/computed.html)
  </p></details>

- [ ] **Routing**

    <details><summary>Links</summary><p>

  - [Getting Started - Documentación oficial de Vue Router](https://router.vuejs.org/guide/#html)
  </p></details>

- [ ] **Clases y Estilos**

    <details><summary>Links</summary><p>

  - [Enlace Clases y Estilos - Documentación oficial](https://es.vuejs.org/v2/guide/class-and-style.html)
  </p></details>

### Control de Versiones (Git y GitHub)

- [ ] **Git: Instalación y configuración**

- [ ] **Git: Control de versiones con git (init, clone, add, commit, status, push, pull, remote)**

- [ ] **Git: Integración de cambios entre ramas (branch, checkout, fetch, merge, reset, rebase, tag)**

- [ ] **GitHub: Creación de cuenta y repos, configuración de llaves SSH**

- [ ] **GitHub: Despliegue con GitHub Pages**

    <details><summary>Links</summary><p>

  - [Sitio oficial de GitHub Pages](https://pages.github.com/)
  </p></details>

- [ ] **GitHub: Colaboración en Github (branches | forks | pull requests | code review | tags)**

### Centrado en el usuario

- [ ] **Diseñar y desarrollar un producto o servicio poniendo a las usuarias en el centro**

### Diseño de producto

- [ ] **Crear prototipos de alta fidelidad que incluyan interacciones**

- [ ] **Seguir los principios básicos de diseño visual**

### Investigación

- [ ] **Planear y ejecutar testeos de usabilidad de prototipos en distintos niveles de fidelidad**

    <details><summary>Links</summary><p>

  - [Intro a testeos usabilidad](https://coda.io/@bootcamp-laboratoria/contenido-ux/test-de-usabilidad-15)
  - [Pruebas con Usuarios 1 — ¿Qué, cuándo y para qué testeamos?](https://eugeniacasabona.medium.com/pruebas-con-usuarios-1-qu%C3%A9-cu%C3%A1ndo-y-para-qu%C3%A9-testeamos-7c3a89b4b5e7)
  </p></details>

## 5. Criterios de aceptación mínimos del proyecto

- Utilizar la API de OMDB mediante _Fetch_ para obtener y mostrar una interfaz
  basada en los datos de cada respuesta.
- Lo que sea que decidas hacer, deberás seleccionar aleatoriamente datos y
  mostrarlos en alguna de las características de tu proyecto. Para esto
  generalmente se usa el método `random` del objeto `Math` en JavaScript.
- Tu solución debe ser _responsive_. Debe adaptarse a pantallas de escritorio,
  tabletas y teléfonos.
- Debes desplegar tu aplicación usando [GitHub Pages](https://pages.github.com/).

## 6. Consideraciones técnicas

- Para poder usar la API de OMDB deberás crear una llave (_key_) de acceso y
  agregarla a cada petición que hagas al servidor (revisar sección _Usage_ de su
  [sitio web](http://www.omdbapi.com/)), la llave la generas en este
  [link](http://www.omdbapi.com/apikey.aspx) llenando el formulario con la
  versión gratuita (_free_) seleccionada y luego revisando tu _email_ para
  activarla y poder usarla.
- Recuerda que GitHub Pages sirve sus páginas con un certificado
  [SSL](https://es.wikipedia.org/wiki/Seguridad_de_la_capa_de_transporte) por lo
  que las peticiones a la OMDB deben incluir `https` en la URL.
- Recuerda que tienes un máximo de 1.000 peticiones diarias a la API de la OMDB
  por cada [IP](https://es.wikipedia.org/wiki/Direcci%C3%B3n_IP), creemos que es
  suficiente, pero te recomendamos hacer un uso responsable de este recurso
  gratuito.
- Para este proyecto necesitas crear una Web App con una librería o framework de JavaScript (React, Angular o Vue) y Firebase.

## Contenido de referencia

- [Fetch](https://developer.mozilla.org/es/docs/Web/API/Fetch_API)
- [Math.random](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Math/random)

Trata de divertirte. ¡a empezar esta aventura 🎬!

## 7. Pistas, tips y lecturas complementarias

### Frameworks / libraries

- [React](https://reactjs.org/)
- [Angular](https://angular.io/)
- [Vue](https://es.vuejs.org/index.html)
