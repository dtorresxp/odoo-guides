# O13 - EE - FSV - Servicio en Sitio &nbsp;&nbsp;&nbsp;&nbsp; [![en-uk](/doc/img/en-uk_flag_button_small.png)](/en-uk/o13/ee/fsv/en-uk-o13-ee-fsv-field-service-guides.md) [ ![es-mx](/doc/img/es-mx_flag_button_small.png)](/es-mx/o13/ee/fsv/es-mx-o13-ee-fsv-field-service-guides.md)
#### [_&#x23CE; menu_](/es-mx/o13/ee/es-mx-o13-ee-guides-menu.md)  
### ![fsv](/doc/img/field_service.png)

#### [Control de Servicio en Sitio &nbsp;&nbsp; (O13 - EE - Odoo Mates - xx-xx - 06:12 - Control de Servicio en Sitio)](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=3&end=0&rel=0&nocount)<br>

- [Instalar el app de Servicio](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=3s&end=16s&rel=0)  
  ![apps](/doc/img/apps.png) | o:Apps | f:Buscar... field service | i:FieldService | b:Instalar  

- [Ver Tareas](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=17s&end=31s&rel=0)  
  ![apps](/doc/img/apps.png) | o:FieldService | f:Buscar... | _(MyTareas)_ &#x2716; | _(ToDo)_ &#x2716; | _(Future)_ &#x2716; | m:Planning | \[ o:ByUser || o:ByProject ]  

- [Crear Tarea](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=32s&end=1m18s&rel=0)  
  ![apps](/doc/img/apps.png) | o:FieldService | b:Crear | f:Título | f:Cliente &#x25BC; | _a:Tipo eMail with Tarea description_  
  f:WorksheetTemplate | \[ &#x25BC; _a:Seleccionar Template_ || ![show_catalog](/doc/img/show_catalog.png) | w:Abrir:WorksheetTemplate | f:Name | b:Guardar ]  
  | f:Project | f:Date &#x1F4C5; | f:AssignedTo | b:Guardar  
  
- [Iniciar Servicio](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=1m19s&end=1m36s&rel=0)  
  ![apps](/doc/img/apps.png) | o:FieldService | m:MyTareas | _a:Seleccionar Tarea_ | b:Iniciar | _a:See started Timer in upper-right corner_  
  
- [Crear Registro de Tareas](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=1m35s&end=4m2s&rel=0)  
  _a:Iniciar Tarea_ | s:Worksheet | \[ b:Crear | f:Descripción | f:Duration | b:Guardar ]&#x207F;  
  &#x23BD;/&#x23BD;/:IniciaredTarea | _a:See s:Time showing total registered time_ | s:Worksheet  
  f:ContactPerson | f:InterventionTipo &#x25BC; \[ Functional || Technical ]  
  f:Comments | f:WorkerSignature | f:ClienteSignature | b:Guardar  
  s:Products | \[ _a:Add products to task \[ + || - ] ]&#x207F;_ | &#x23BD;/&#x23BD;/:IniciaredTarea | _a:See s:Products showing Totals_  
  t:LogNote | _a:Enter f:Log text_ | b:Log  
  t:EnviarMensaje | _a:Enter f:MensajeText for followers of i:IniciaredTarea_ | b:Enviar  
  b:Stop | w:Log | f:Time | f:Descripción | b:Guardar  
  
- [Crear Cotizaciones y Facturas](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=4m7s&end=5m&rel=0)  
  _a:Seleccionar Tarea_ | b:NewCotización | \[ o:AddAProduct | f:Product &#x25BC; | f:Quantity ]&#x207F; | b:Guardar  
  _a:See s:Cotizaciones showing number of quotations_ | b:Validar  
  b:CrearFactura | w:Facturación | f:CrearFactura \[ &#x25C9; Regular || Percentage || Ammount ]  
  b:CrearAndVerFactura | w:FacturaPreview | b:Validar  

<br>

###### Guías Odoo - V2_01 &nbsp; 2019-07-31  
**[_&#x23CE; menu_](/es-mx/o13/ee/es-mx-o13-ee-guides-menu.md)**  
