# Guias Odoo
Ligas a videos y guias en _&#x03C8;Code_ para Odoo.

![Ligas a videos y guias en _&#x03C8;Code_ para Odoo](/doc/img/logo_odoo_guides_mini.jpg)

# Guides

# ![o13](/doc/img/odoo13.png)
- [Edicion de la Comunidad](/es-mx/o13/ce/es-mx-o13-ce-guides_menu.md)
- [Edicion Empresarial](/es-mx/o13/ee/es-mx-o13-ee-guides_menu.md)

<br>

# Objetivos del Proyecto _&#x03C8;Code_ Project objectives

?Bienvenid@s al proyecto _&#x03C8;Code_!<br>

Nuestra intenciones apoyar el soporte, uso, capacitacion y certificacion en Odoo.<br><br>
Creamos un pseudo lenguaje simple llamado _&#x03C8;Code_, para ayudar a la gente a trabajar lo mis pronto posible, basindonos en la t¨¦cnica "qu¨¦-donde" del _Knowledgeware_.  La idea es integrar las nuevas tecnicas de capacitacion mediante videos con algo mis simple que los pesados manuales de sistema, pero retomando todas las ventajas de indexamiento, b¨²squeda y eficiencia de la capacitacion tradicional.  Nuestro objetivo es tomar lo mejor de ambos mundos, privilegiando el "junto con", sobre el "en vez de".

Es un esfuerzo comunitario, dise?ado para reducir la brecha entre los gurus y los que estan comenzando a aprender Odoo.  A pesar del gran esfuerzo que Odoo ha estado haciendo en estos ultimos a?os para documentar su sistema, creemos que el volumen de desarrollo y la llegada de nuevar versiones cada a?o (y eso sin mencionar todas las localizaciones en cada idioma), requiere un enfoque totalmente nuevo.

Creemos que los videos son una forma muy bonita pero muy ineficiente de capacitacion.  Sin pretender forzar a los _milenials_, realmente esperamos que los _centenials_ retomen la idea de leer... como lo hicieron las generaciones precedentes por mucho tiempo.  Mientras alguien no invente una interfaz como la de la pelicula Matrix, que nos permita aprender cualquier cosa en un par de segundos, necesitamos una forma mis ripida para localizar el procedimiento correcto y resolver un problema.

Estamos convencidos de que el exito de una empresa de servicios de Odoo a largo plazo depende de la velocidad con que puedan mover su informacion de donde esti, a donde se necesita.

Como hizo _Euclides_ hace como 2,300 anos, nosotros no procucimos videos, sino que seleccionamos los mejores y redactamos el _&#x03C8;Code_ correspondiente en forma de _guias_ de procedimientos.  Como una ventaja extra, las ligas de nuestras guias apuntan directamente al inicio y fin del procedimiento dentro del video.

Queremos respetar los derechos de los creadores de contenidos.  Todos nuestras ligas a videos incluyen el nombre y direccion del creador original, para cumplir con las politicas del _juego limpio_.

Nosotros recibiremos, contestaremos, verificaremos y por supuesto que agradeceremos mucho cualquier guia que nos hagan llegar.  La vamos a incluir aqui, para apoyar nuestra comunidad de Odoo lo mejor que podamos.<br><br>

Gracias.

<br>

# Estructura del Repositorio

Para facilitar su uso, todos nuestros archivos se pueden accesar mediante ligas en menus.  No se necesita entrar a cada carpeta para buscar informacion.  En estos tiempos, hay varias versiones activas de Odoo, mismo que viene en dos formas: _CE_ (Edicion de la Comunidad) y _EE_ (Edicion Empresarial), asi que nuestros menus estin organizados por version y por edicion.

Este archivo README es la base del proyecto y contiene nuestros objetivos, explicaciones tecnicas y nuestra informacion de contacto.

El irbol de carpetas esti ordenado por _version_ / _edicion_ / _modulo_ / _guia_.
Conforme el proyecto vaya creciendo, se podri agregar un _menu_ antes de _guia_, pero todos los archivos que correspondan a un mismo modulo se alojarin dentro de la carpeta del modulo.

Si no puedes encontrar lo que buscas en ningun _menu_, o si encuentras algun error en nuestro _&#x03C8;Code_, por favor no dudes en enviarnos un correo mencionando tu preocupacion de manera razonable... de preferencia con una liga a un video donde se explique mejor el tema.  Te ofrecemos darle una mayor prioridad a tus sugerencias, con el fin de atender mejor a nuestra comunidad.

<br>

# Explicacion bisica del _&#x03C8;Code_

Esta es una explicacion bisica sobre el _&#x03C8;Code_.  Su unico proposito es indicarte los pasos necesarios en un orden correcto y ayudarte a encontrar el objeto en pantalla donde cada paso debe ser realizado:

- Guias
  - Cada guia consta de una liga a un video, seguida del _&#x03C8;Code_ de su procedimiento
  - Cada liga incluye:  
    - Nombre del video
    - Numero de version de Odoo  
    - Edicion de Odoo (CE or EE)  
    - Creador Origina  
    - Idioma (n/v=no voz)  
    - Duracion del video  
  - Cuando un video contiene varios procedimientos, se mostrarin en forma de lista debajo de la liga al video completo
  - Cada procedimiento tendri su propia liga, pero solo apuntari al procedimiento indicado dentro del video
  - Despues de cada liga al procedimiento, seguiri su _&#x03C8;Code_
- Pasos
  - El elemento fundamental de una guia de _&#x03C8;Code_ es el _PASO_, una tarea aislada a realizar dentro de la pantalla.  
  - Cada paso se separa de los demis mediante una _BARRA VERTICAL_ |  
  - Los pasos relacionados normalmente aparecen en el mismo _RENGL?N_, a menos que no quepan y se necesiten separar en varios renglones  
  - Algunos pasos van agrupados logicamente, encerrados entre _CORCHETES_.  Si son mutuamente exclusivos (opciones), aparecen separados por _DOS BARRAS VERTICALES_ || (uno de los simbolos de OR).  Si las tareas del grupo se pueden repetir, un superindice lo indica a la derecha del corchete que se cierra: \[ \]&#x207F;  
  - Existen varios _ICONOS_ semejantes a los que Odoo muestra en pantalla
    - ![apps](/doc/img/apps.png)&nbsp;&nbsp;representa el icono de cuadritos de _APPS_ en la parte superior izquierda de la ventana de Odoo, en la barra de navegacion (_navbar_)  
	- &#x23BD;/&#x23BD;/&nbsp;&nbsp;representa la lista de accessos directos a los modulos y elementos que el usuario haya abierto previemente en Odoo, que aparece debajo de la navbar
	- Los campos de tipo fecha tienen el caracter &#x25BC; a su derecha y permiten abrir el objeto &#x1F4C5; para seleccionarla ficilmente  
    - Los demis simbolos son los mismos que Odoo muestra en la pantalla
	- Algunos pasos son precedidos por una letra y dos puntos, lo cual indica el tipo de elemento (objeto) que deberis buscar en pantalla para realizar la tarea
    - _**_a:_**_ &nbsp;significa _ACTION_ _(ACCI?N)_ y es el unico elemento que no se refiere a un solo paso.  Corresponde a una tarea compleja de varios pasos que se indican como si fuera uno solo, para facilitar la lectura de la guia, usualmente porque ya fueron explicados previamente o porque se explican en otra guia
	- **_i:_** &nbsp;&nbsp;significa _ITEM_ _(ELEMENTO)_ y representa a cualquier objeto que no este en esta lista
    - Los otros tipos de elemento usados en pantalla son: _**b:** Button (Boton), **d:** Dialog (Cuadro de Diilogo), **f:** Field (Campo), **l:** Link (Hipervinculo), **m:** Menu (Menu), **o:** Option (Opcion), **s:** SmartButton (Boton Inteligente), **t:** Tab (Pesta?a), **v:** View (Vista) y **w:** Window (Ventana)_.
    - A continuacion se muestra la lista completa de simbolos que se utilizan en las guias y su significado.

####
[***Sync***]: # (homepCodeBrief_spa)  
[***Sync***]: # (es-mx-o13-ce-guides_menu)  
[***Sync***]: # (es-mx-o13-ee-guides_menu)  

| Icono | Significado | Icono | Significado | 
| :---: | :--- | :---: | :--- |
| paso | paso | &#x2026; row &#x2026; | agrupacion logica de pasos |
| \| | separador de pasos | \[ x \| y ] | grupo de pasos |
| _(etiqueta)_ | etiqueta | &nbsp;\[ x \| y \]&#x207F; | pasos repetibles n-veces |
| &#x23BD;/&#x23BD;/ | historial de ventana | \[ x \|\| y ] | pasos optativos |
| ![apps](/doc/img/apps.png) | icono de apps en _barranav_ | &#x2630; | icono de menu de la app |
| &#x2807; | icono de menu de la lista | &#x2716; | quitar etiqueta / cerrar |
| &#x1F5F9; | opcion marcada con palomita | &#x2610; | opcion desmarcada |
| &#x25C9; | encendido | &#x2B58; | apagado |
| &#x25BC; | abrir combo y seleccionar opcion | **&#x2B73;** | descargar |
| &#x21C4; | tabla dinimica: intercambiar ejes | &#x2725; | tabla dinimica: expandir todo |
| &#x1F41E; | opciones del desarrollador | ![warning](/doc/img/warning.png) | alerta |
| &#x1F6E0; | abrir Odoo studio | &#x1F557; | actividades |
| &#x1F5ED; | conversaciones | &#x1F50D; | busqueda avanzada |
| &#x1F4C5; | calendario | &#x2B50; | favoritos |
| ![presence_yes](/doc/img/presence_yes.png) \|\| ![presence_no](/doc/img/presence_no.png) | presente \|\| ausente | &#x1F870; \|\| &#x1F872; | retroceder \|\| avanzar |
| ![add](/doc/img/button_add.png) \|\| ![sub](/doc/img/button_sub.png) | agregar \|\| eliminar | ![trashcan](/doc/img/trashcan.png) \|\| ![cancel](/doc/img/cancel.png) | cancelar |
| ![active](/doc/img/active.png) \|\| ![inactive](/doc/img/inactive.png) | activo \|\| inactivo | ![phone_receiver](/doc/img/phone_receiver.png) | confirmar |
| ![view_kanban](/doc/img/view_kanban.png) | vista kanban | ![view_list](/doc/img/view_list.png) | vista de lista |
| ![view_activity](/doc/img/view_activity.png) | vista de actividades | ![view_map](/doc/img/view_map.png) & ![map_location](/doc/img/map_location.png)| vista de mapa y localizacion |
| ![show_catalog](/doc/img/show_catalog.png) | mostrar catilogo | ![filter](/doc/img/filter.png) | filtrar |
| _**a:** Accion_ | accion (varios pasos) | **b:** Button | boton |
| **d:** Dialogo | alerta o cuadro de diilogo | **f:** Field | campo de captura |
| **i:** Item | elemento en pantalla | **l:** Liga | hipervinculo |
| **m:** Menu | menu | **o:** Opcion | opcion |
| **s:** SmartButton | boton inteligente | **t:** Tab | pesta?a |
| **v:** View | vista | **w:** Window | window |

<br>

# El Enfoque _Que-Donde_
![Ligas a videos y guias en _&#x03C8;Code_ aprovechar Odoo](/doc/img/logo_odoo_guides_mini.jpg)

Es parte de la teoria de _knowledgeware_.  En el contexto de las interfaces de usuario, se refiere a que la capacitacion puede reducirse a explicar unicamente _que_ hacer y _donde_ hacerlo.  Esto implica que el usuario ya conoce _por que_ debe hacerlo, por lo cual no necesita ser parte de la explicacion.  Esto minimiza el tiempo, informacion y esfuerzo necesarios para adquirir nuevo conocimiento.

En esta era _hiper-gamificada_, muchas interfaces de sistemas son designadas como si fueran video juegos, donde uno tiene que _descubrir_ por si mismo donde y como debe usar los elementos de la pantalla para realizar sus tareas, ya que el estilo _minimalista_ requiere el uso de interfaces _sencillas_.

Esto es muy comun e incluso entendible en la industria de los celulares, pero recientemente se comenzo a hacer lo mismo en los sistemas empresariales usados en computadoras de escritorio y portitiles.  En estos dias es muy raro encontrar un _dise?ador_ que este pidiendo retroalimentacion y corrigiendo los problemas que tienen los usuarios al utilizar su sistema en el dia a dia.

Es muy costoso capacitar usuarios en un nuevo sistema con una interfaz que parece video juego, donde tienen que _descubrir_ donde estan las cosas.  El porcenaje de uso (y peor aun, de uso _correcto_) de los sistemas en la actualiadad es muy bajo, porque las interfaces tienden a ser confusas y cambiar mucho entre plataformas, marcas e incluso versiones.  Es sabido que muchos usuarios nativos de Windows-8 que se burlaban de sus compa?eros de trabajo (principalmente aquellos que conocian Windows desde antes de la version 7), terminaron quejindose de lo mismo cuando fueron forzados a _actualizarse_ a Windows-10.

De cualquier modo, esta tecnica es muy util para ayudar a la gente que mis o menos sabe _que_ necesita hacer.  Les explica como hacerlo con las instrucciones minimas indispensables sobre _donde_ realizar las cosas en pantalla y sobre todo, haciendolo en el _orden_ correcto.

<br>

# Aportaciones de _&#x03C8;Code_

| id | Nombre | Grupo | Pais | Guias |
| :---: | :--- | :---: | :---: | :---: |
| [@oldyguy](mailto:pcode@appti.mx) | $og | appti | MX | all |

#### Notas para las Aportaciones:
  - A veces una guia debe ir en varios menus.  Para asegurarnos de que se sincronizan todas cada vez que hay una actualizacion, se debe agregar el siguiente comentario inmediatamente despues del renglon con la liga:
    _\[\*\*\*Sync\*\*\*\] # \(ll-cc-o[08..13]-[ce]e-[iddelmodulo]-[nombredelarchivo])_
  - Todas las referencias al _&#x03C8;Code_ como nombre de archivo, deben ser convertidas a _pCode_ debido a las limitaciones del codigo ASCII
  - Se debe agregar _&nocount_ al final de la liga a un video con multiples procedimientos, para eliminarlo de la cuenta total de guias
  - Para agregar una nueva traduccion, se debe usar el nombre de 5-caracteres formado por _ii-cc_, tomindolos de las siguientes listas oficiales:
    - __ii__: Codigo de idioma: [ISO 639-1  two-letter](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)
    - __cc__: Codigo de pais: &nbsp;&nbsp; [ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2)
	- Los iconos de las bandeas deben ser de (250x150) pixeles en estilo _fly breeze_, tomindolos de [_aqui_](https://amazon.com)


<br><br>
#### Guis Odoo - v6_01 &nbsp; 2019-07-31
 
