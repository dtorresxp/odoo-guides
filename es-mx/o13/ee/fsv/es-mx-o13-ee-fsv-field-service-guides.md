# O13 - EE - FSV - Servicio en Sitio &nbsp;&nbsp;&nbsp;&nbsp; [![en-uk](/doc/img/en-uk_flag_button_small.png)](/en-uk/o13/ee/fsv/en-uk-o13-ee-fsv-field-service-guides.md) [ ![es-mx](/doc/img/es-mx_flag_button_small.png)](/es-mx/o13/ee/fsv/es-mx-o13-ee-fsv-field-service-guides.md)
#### [_&#x23CE; menu_](/es-mx/o13/ee/es-mx-o13-ee-guides-menu.md)  
### ![fsv](/doc/img/field_service.png)

#### [Control de Servicio en Sitio &nbsp;&nbsp; (O13 - EE - Odoo Mates - xx-xx - 06:12 - Control de Servicio en Sitio)](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=3&end=0&rel=0&nocount)<br>

- [Instalar el app de Servicio](https://youtube.com/embed/AjG16B-DTYY?start=3&end=16)  
  ![apps](/doc/img/apps.png) | o:Apps | f:Buscar... Servicio en sitio | i:ServicioEnSitio | b:Instalar  

- [Ver Tareas](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=17s&end=31s&rel=0)  
  ![apps](/doc/img/apps.png) | o:ServicioEnSitio | f:Buscar... | _(MisTareas)_ &#x2716; | _(ToDo)_ &#x2716; | _(Future)_ &#x2716; |  
  m:Planeación | \[ o:PorUsuario || o:PorProyecto ]  

- [Crear Tarea](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=32s&end=1m18s&rel=0)  
  ![apps](/doc/img/apps.png) | o:ServicioEnSitio | b:Crear | f:Título | f:Cliente &#x25BC; | _a:Capture la descripción de la Tarea en el Correo_ |  
  f:HojaTemplate | \[ &#x25BC; _a:Seleccionar Template_ || ![show_catalog](/doc/img/show_catalog.png) | w:Abrir:HojaTemplate | f:Nombre | b:Guardar ] |  
  f:Proyecto | f:Fecha &#x1F4C5; | f:AsignadoA | b:Guardar  
  
- [Iniciar Servicio](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=1m19s&end=1m36s&rel=0)  
  ![apps](/doc/img/apps.png) | o:ServicioEnSitio | m:MisTareas | _a:Seleccionar Tarea_ | b:Iniciar |  
  _a:Ver el cronómetro avanzando en la esquina superior derecha_  
  
- [Crear Registro de Tareas](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=1m35s&end=4m2s&rel=0)  
  _a:Iniciar Tarea_ | s:Hoja | \[ b:Crear | f:Descripción | f:Duración | b:Guardar ]&#x207F; |  
  &#x23BD;/&#x23BD;/:TareaIniciada | _a:Ver que s:Tiempo muestra el tiempo total registrado_ | s:Hoja |  
  f:PersonaDeContacto | f:TipoDeTarea &#x25BC; \[ Funcional || Técnica ] |  
  f:Comentarios | f:FirmaDelTécnico | f:FirmaDelCliente | b:Guardar |  
  s:Productos | \[ _a:Agregar Productos a la Tarea_ \[ ![add](/doc/img/button_add.png) || ![sub](/doc/img/button_sub.png) ] ]&#x207F;_ |  
  &#x23BD;/&#x23BD;/:TareaIniciada | _a:Ver que s:Productos muestra los totales_ |  
  t:Registro | _a:Ingresar texto en f:Log_ | b:Registrar |  
  t:EnviarMensaje | _a:Ingresar f:TextoDelMensaje para seguidores de i:TareaIniciada_ | b:Enviar |  
  b:Detener | w:Registro | f:Tiempo | f:Descripción | b:Guardar  
  
- [Crear Cotizaciones y Facturas](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=4m7s&end=5m&rel=0)  
  _a:Seleccionar Tarea_ | b:NuevaCotización | \[ o:AgregarAProducto | f:Producto &#x25BC; | f:Cantidad ]&#x207F; | b:Guardar |  
  _a:Ver que s:Cotizaciones muestra el número de Cotizaciones_ | b:Validar |  
  b:CrearFactura | w:Facturación | f:CrearFactura \[ &#x25C9; Normal || Porcentage || Cantidad ] |  
  b:CrearYVerFactura | w:VistaPreviaDeFactura | b:Validar  

<br>

###### Guías Odoo - V2_01 &nbsp; 2019-08-01  
**[_&#x23CE; menu_](/es-mx/o13/ee/es-mx-o13-ee-guides-menu.md)**  
