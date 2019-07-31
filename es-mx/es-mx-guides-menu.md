# Guías Odoo
Ligas a videos y guías en _&#x03C8;Code_ para Odoo.

![Ligas a videos y guías en _&#x03C8;Code_ para Odoo](/doc/img/logo_odoo_guides_mini.jpg) &nbsp;&nbsp;&nbsp; ![en-uk](/doc/img/flag_en-uk.jpg)](/en-uk/en-uk-guides-menu.md) &nbsp; ![es-mx](/doc/img/flag_es-mx.jpg)](/es-mx/es-mx-guides-menu.md)

# Guides

# ![o13](/doc/img/odoo13.png)
- [Edición de la Comunidad](/es-mx/o13/ce/es-mx-o13-ce-guides_menu.md)
- [Edición Empresarial](/es-mx/o13/ee/es-mx-o13-ee-guides_menu.md)

<br>

# Objetivos del Proyecto _&#x03C8;

¡Bienvenid@s al proyecto _&#x03C8;Code_!<br>

Nuestra intenciones apoyar el soporte, uso, capacitación y certificación en Odoo.<br><br>
Creamos un pseudo lenguaje simple llamado _&#x03C8;Code_, para ayudar a la gente a trabajar lo más pronto posible, basándonos en la técnica "qué-dónde" del _Knowledgeware_.  La idea es integrar las nuevas técnicas de capacitación mediante videos con algo más simple que los pesados manuales de sistema, pero retomando todas las ventajas de indexamiento, búsqueda y eficiencia de la capacitación tradicional.  Nuestro objetivo es tomar lo mejor de ambos mundos, privilegiando el "junto con", sobre el "en vez de".

Es un esfuerzo comunitario, diseñado para reducir la brecha entre los gurús y los que están comenzando a aprender Odoo.  A pesar del gran esfuerzo que Odoo ha estado haciendo en estos últimos años para documentar su sistema, creemos que el volúmen de desarrollo y la llegada de nuevar versiones cada año (y eso sin mencionar todas las localizaciones en cada idioma), requiere un enfoque totalmente nuevo.

Creemos que los videos son una forma muy bonita pero muy ineficiente de capacitación.  Sin pretender forzar a los _milenials_, realmente esperamos que los _centenials_ retomen la idea de leer... como lo hicieron las generaciones precedentes por mucho tiempo.  Mientras alguien no invente una interfaz como la de la película Matrix, que nos permita aprender cualquier cosa en un par de segundos, necesitamos una forma más rápida para localizar el procedimiento correcto y resolver un problema.

Estamos convencidos de que el éxito de una empresa de servicios de Odoo a largo plazo depende de la velocidad con que puedan mover su información de donde está, a donde se necesita.

Como hizo _Euclides_ hace como 2,300 años, nosotros no procucimos videos, sino que seleccionamos los mejores y redactamos el _&#x03C8;Code_ correspondiente en forma de _guías_ de procedimientos.  Como una ventaja extra, las ligas de nuestras guías apuntan directamente al inicio y fin del procedimiento dentro del video.

Queremos respetar los derechos de los creadores de contenidos.  Todos nuestras ligas a videos incluyen el nombre y dirección del creador original, para cumplir con las políticas del _juego limpio_.

Nosotros recibiremos, contestaremos, verificaremos y por supuesto que agradeceremos mucho cualquier guía que nos hagan llegar.  La vamos a incluir aquí, para apoyar nuestra comunidad de Odoo lo mejor que podamos.<br><br>

Gracias.

<br>

# Estructura del Repositorio

Para facilitar su uso, todos nuestros archivos se pueden accesar mediante ligas en menús.  No se necesita entrar a cada carpeta para buscar información.  En estos tiempos, hay varias versiones activas de Odoo, mismo que viene en dos formas: _CE_ (Edición de la Comunidad) y _EE_ (Edición Empresarial), así que nuestros menús están organizados por versión y por edición.

Este archivo README es la base del proyecto y contiene nuestros objetivos, explicaciones técnicas y nuestra información de contacto.

El árbol de carpetas está ordenado por _versión_ / _edición_ / _módulo_ / _guía_.
Conforme el proyecto vaya creciendo, se podrá agregar un _menú_ antes de _guía_, pero todos los archivos que correspondan a un mismo módulo se alojarán dentro de la carpeta del módulo.

Si no puedes encontrar lo que buscas en ningún _menú_, o si encuentras algún error en nuestro _&#x03C8;Code_, por favor no dudes en enviarnos un correo mencionando tu preocupación de manera razonable... de preferencia con una liga a un video donde se explique mejor el tema.  Te ofrecemos darle una mayor prioridad a tus sugerencias, con el fin de atender mejor a nuestra comunidad.

<br>

# Explicación básica del _&#x03C8;Code_

Esta es una explicación básica sobre el _&#x03C8;Code_.  Su único propósito es indicarte los pasos necesarios en un orden correcto y ayudarte a encontrar el objeto en pantalla donde cada paso debe ser realizado:

- Guías
  - Cada guía consta de una liga a un video, seguida del _&#x03C8;Code_ de su procedimiento
  - Cada liga incluye:  
    - Nombre del video
    - Número de versión de Odoo  
    - Edición de Odoo (CE or EE)  
    - Creador Origina  
    - Idioma (n/v=no voz)  
    - Duración del video  
  - Cuando un video contiene varios procedimientos, se mostrarán en forma de lista debajo de la liga al video completo
  - Cada procedimiento tendrá su propia liga, pero sólo apuntará al procedimiento indicado dentro del video
  - Después de cada liga al procedimiento, seguirá su _&#x03C8;Code_
- Pasos
  - El elemento fundamental de una guía de _&#x03C8;Code_ es el _PASO_, una tarea aislada a realizar dentro de la pantalla.  
  - Cada paso se separa de los demás mediante una _BARRA VERTICAL_ |  
  - Los pasos relacionados normalmente aparecen en el mismo _RENGLÓN_, a menos que no quepan y se necesiten separar en varios renglones  
  - Algunos pasos van agrupados lógicamente, encerrados entre _CORCHETES_.  Si son mutuamente exclusivos (opciones), aparecen separados por _DOS BARRAS VERTICALES_ || (uno de los símbolos de OR).  Si las tareas del grupo se pueden repetir, un superíndice lo indica a la derecha del corchete que se cierra: \[ \]&#x207F;  
  - Existen varios _ICONOS_ semejantes a los que Odoo muestra en pantalla
    - ![apps](/doc/img/apps.png)&nbsp;&nbsp;representa el icono de cuadritos de _APPS_ en la parte superior izquierda de la ventana de Odoo, en la barra de navegación (_navbar_)  
	- &#x23BD;/&#x23BD;/&nbsp;&nbsp;representa la lista de accessos directos a los módulos y elementos que el usuario haya abierto previemente en Odoo, que aparece debajo de la navbar
	- Los campos de tipo fecha tienen el caracter &#x25BC; a su derecha y permiten abrir el objeto &#x1F4C5; para seleccionarla fácilmente  
    - Los demás símbolos son los mismos que Odoo muestra en la pantalla
	- Algunos pasos son precedidos por una letra y dos puntos, lo cual indica el tipo de elemento (objeto) que deberás buscar en pantalla para realizar la tarea
    - _**_a:_**_ &nbsp;significa _ACTION_ _(ACCIÓN)_ y es el único elemento que no se refiere a un solo paso.  Corresponde a una tarea compleja de varios pasos que se indican como si fuera uno solo, para facilitar la lectura de la guía, usualmente porque ya fueron explicados previamente o porque se explican en otra guía
	- **_i:_** &nbsp;&nbsp;significa _ITEM_ _(ELEMENTO)_ y representa a cualquier objeto que no esté en esta lista
    - Los otros tipos de elemento usados en pantalla son: _**b:** Botón (Button), **d:** Cuadro de Diálogo (Dialog), **f:** Campo (Field), **l:** Hipervínculo (Link), **m:** Menú (Menu), **o:** Opción (Option), **s:** Botón Inteligente (SmartButton), **t:** Pestaña (Tab), **v:** Vista (View) y **w:** Ventana (Window)_.
    - A continuación se muestra la lista completa de símbolos que se utilizan en las guías y su significado.

####
[***Sync***]: # (homepCodeBrief_spa)  
[***Sync***]: # (es-mx-o13-ce-guides_menu)  
[***Sync***]: # (es-mx-o13-ee-guides_menu)  

| Icono | Significado | Icono | Significado | 
| :---: | :--- | :---: | :--- |
| paso | paso | &#x2026; row &#x2026; | agrupación lógica de pasos |
| \| | separador de pasos | \[ x \| y ] | grupo de pasos |
| _(etiqueta)_ | etiqueta | &nbsp;\[ x \| y \]&#x207F; | pasos repetibles n-veces |
| &#x23BD;/&#x23BD;/ | historial de ventana | \[ x \|\| y ] | pasos optativos |
| ![apps](/doc/img/apps.png) | icono de apps en _barranav_ | &#x2630; | icono de menú de la app |
| &#x2807; | icono de menú de la lista | &#x2716; | quitar etiqueta / cerrar |
| &#x1F5F9; | opción marcada con palomita | &#x2610; | opción desmarcada |
| &#x25C9; | encendido | &#x2B58; | apagado |
| &#x25BC; | abrir combo y seleccionar opción | **&#x2B73;** | descargar |
| &#x21C4; | tabla dinámica: intercambiar ejes | &#x2725; | tabla dinámica: expandir todo |
| &#x1F41E; | opciones del desarrollador | ![warning](/doc/img/warning.png) | alerta |
| &#x1F6E0; | abrir Odoo studio | &#x1F557; | actividades |
| &#x1F5ED; | conversaciones | &#x1F50D; | búsqueda avanzada |
| &#x1F4C5; | calendario | &#x2B50; | favoritos |
| ![presence_yes](/doc/img/presence_yes.png) \|\| ![presence_no](/doc/img/presence_no.png) | presente \|\| ausente | &#x1F870; \|\| &#x1F872; | retroceder \|\| avanzar |
| ![add](/doc/img/button_add.png) \|\| ![sub](/doc/img/button_sub.png) | agregar \|\| eliminar | ![trashcan](/doc/img/trashcan.png) \|\| ![cancel](/doc/img/cancel.png) | cancelar |
| ![active](/doc/img/active.png) \|\| ![inactive](/doc/img/inactive.png) | activo \|\| inactivo | ![phone_receiver](/doc/img/phone_receiver.png) | confirmar |
| ![view_kanban](/doc/img/view_kanban.png) | vista kanban | ![view_list](/doc/img/view_list.png) | vista de lista |
| ![view_activity](/doc/img/view_activity.png) | vista de actividades | ![view_map](/doc/img/view_map.png) & ![map_location](/doc/img/map_location.png)| vista de mapa y localización |
| ![show_catalog](/doc/img/show_catalog.png) | mostrar catálogo | ![filter](/doc/img/filter.png) | filtrar |
| _**a:** Acción_ | acción (varios pasos) | **b:** Button | botón |
| **d:** Dialogo | alerta o cuadro de diálogo | **f:** Field | campo de captura |
| **i:** Item | elemento en pantalla | **l:** Liga | hipervínculo |
| **m:** Menu | menu | **o:** Opción | opción |
| **s:** SmartButton | botón inteligente | **t:** Tab | pestaña |
| **v:** View | vista | **w:** Window | window |

<br>

# El Enfoque _Qué-Dónde_
![Ligas a videos y guías en _&#x03C8;Code_ aprovechar Odoo](/doc/img/logo_odoo_guides_mini.jpg)

Es parte de la teoría de _knowledgeware_.  En el contexto de las interfaces de usuario, se refiere a que la capacitación puede reducirse a explicar únicamente _qué_ hacer y _dónde_ hacerlo.  Esto implica que el usuario ya conoce _por qué_ debe hacerlo, por lo cual no necesita ser parte de la explicación.  Esto minimiza el tiempo, información y esfuerzo necesarios para adquirir nuevo conocimiento.

En esta era _hiper-gamificada_, muchas interfaces de sistemas son designadas como si fueran video juegos, donde uno tiene que _descubrir_ por sí mismo dónde y cómo debe usar los elementos de la pantalla para realizar sus tareas, ya que el estilo _minimalista_ requiere el uso de interfaces _sencillas_.

Esto es muy común e incluso entendible en la industria de los celulares, pero recientemente se comenzó a hacer lo mismo en los sistemas empresariales usados en computadoras de escritorio y portátiles.  En estos días es muy raro encontrar un _diseñador_ que esté pidiendo retroalimentación y corrigiendo los problemas que tienen los usuarios al utilizar su sistema en el día a día.

Es muy costoso capacitar usuarios en un nuevo sistema con una interfaz que parece video juego, donde tienen que _descubrir_ dónde estan las cosas.  El porcenaje de uso (y peór aun, de uso _correcto_) de los sistemas en la actualiadad es muy bajo, porque las interfaces tienden a ser confusas y cambiar mucho entre plataformas, marcas e incluso versiones.  Es sabido que muchos usuarios nativos de Windows-8 que se burlaban de sus compañeros de trabajo (principalmente aquellos que conocían Windows desde antes de la versión 7), terminaron quejándose de lo mismo cuando fueron forzados a _actualizarse_ a Windows-10.

De cualquier modo, esta técnica es muy útil para ayudar a la gente que más o menos sabe _qué_ necesita hacer.  Les explica cómo hacerlo con las instrucciones mínimas indispensables sobre _dónde_ realizar las cosas en pantalla y sobre todo, haciéndolo en el _órden_ correcto.

<br>

# Aportaciones de _&#x03C8;Code_

| id | Nombre | Grupo | País | Guías |
| :---: | :--- | :---: | :---: | :---: |
| [@oldyguy](mailto:pcode@appti.mx) | $og | appti | MX | all |

#### Notas para las Aportaciones:
  - A veces una guía debe ir en varios menús.  Para asegurarnos de que se sincronizan todas cada vez que hay una actualización, se debe agregar el siguiente comentario inmediatamente después del renglón con la liga:
    _\[\*\*\*Sync\*\*\*\] # \(ll-cc-o[08..13]-[ce]e-[iddelmódulo]-[nombredelarchivo])_
  - Todas las referencias al _&#x03C8;Code_ como nombre de archivo, deben ser convertidas a _pCode_ debido a las limitaciones del código ASCII
  - Se debe agregar _&nocount_ al final de la liga a un video con múltiples procedimientos, para eliminarlo de la cuenta total de guías
  - Para agregar una nueva traducción, se debe usar el nombre de 5-caracteres formado por _ii-cc_, tomándolos de las siguientes listas oficiales:
    - __ii__: Código de idioma: [ISO 639-1  two-letter](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)
    - __cc__: Código de país: &nbsp;&nbsp; [ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2)
    - Los iconos de las banderas deben ser de (250x150) pixeles en estilo _fly breeze_, tomándolos de [_aquí_](https://amazon.com)


<br><br>
#### Guías Odoo - v6_01 &nbsp; 2019-07-31
 
