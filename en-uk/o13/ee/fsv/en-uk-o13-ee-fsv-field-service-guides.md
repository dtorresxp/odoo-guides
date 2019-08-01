# O13 - EE - FSV - Field Service &nbsp;&nbsp;&nbsp;&nbsp; [![en-uk](/doc/img/en-uk_flag_button_small.png)](/en-uk/o13/ee/fsv/en-uk-o13-ee-fsv-field-service-guides.md) [ ![es-mx](/doc/img/es-mx_flag_button_small.png)](/es-mx/o13/ee/fsv/es-mx-o13-ee-fsv-field-service-guides.md)
#### [_&#x23CE; menu_](/en-uk/o13/ee/en-uk-o13-ee-guides-menu.md)  
### ![fsv](/doc/img/field-service.png)

#### [Field Service Management (O13 - EE - Odoo Mates - xx-xx - 06:12 - Control de Servicio en Sitio)](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=3&end=0&rel=0&nocount)<br>

- [Install Presence module (Instalar módulo de Asistencias)](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=3s&end=16s&rel=0)  
  ![apps](/doc/img/apps.png) | o:Apps | f:Search... field service | i:FieldService | b:Install  

- [View Tasks (Ver Tareas)](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=17s&end=31s&rel=0)  
  ![apps](/doc/img/apps.png) | o:FieldService | f:Search... | _(MyTasks)_ &#x2716; | _(ToDo)_ &#x2716; | _(Future)_ &#x2716; | m:Planning | \[ o:ByUser || o:ByProject ]  

- [Create Task (Crear Tarea)](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=32s&end=1m18s&rel=0)  
  ![apps](/doc/img/apps.png) | o:FieldService | b:Create | f:Title | f:Customer &#x25BC; | _a:Type eMail with Task description_  
  f:WorksheetTemplate | \[ &#x25BC; _a:Select Template_ || ![show_catalog](/doc/img/show_catalog.png) | w:Open:WorksheetTemplate | f:Name | b:Save ]  
  | f:Project | f:Date &#x1F4C5; | f:AssignedTo | b:Save  
  
- [Start Service (Iniciar Servicio)](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=1m19s&end=1m36s&rel=0)  
  ![apps](/doc/img/apps.png) | o:FieldService | m:MyTasks | _a:Select Task_ | b:Start | _a:See started Timer in upper-right corner_  
  
- [Creating Worksheet (Crear Registro de Tareas)](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=1m35s&end=4m2s&rel=0)  
  _a:Start Task_ | s:Worksheet | \[ b:Create | f:Description | f:Duration | b:Save ]&#x207F;  
  &#x23BD;/&#x23BD;/:StartedTask | _a:See s:Time showing total registered time_ | s:Worksheet  
  f:ContactPerson | f:InterventionType &#x25BC; \[ Functional || Technical ]  
  f:Comments | f:WorkerSignature | f:CustomerSignature | b:Save  
  s:Products | \[ _a:Add products to task \[ + || - ] ]&#x207F;_ | &#x23BD;/&#x23BD;/:StartedTask | _a:See s:Products showing Totals_  
  t:LogNote | _a:Enter f:Log text_ | b:Log  
  t:SendMessage | _a:Enter f:MessageText for followers of i:StartedTask_ | b:Send  
  b:Stop | w:Log | f:Time | f:Description | b:Save  
  
- [Creating Quotations & Invoices (Crear Cotizaciones y Facturas)](https://youtube.com/embed/AjG16B-DTYY?autoplay=1&start=4m7s&end=5m&rel=0)  
  _a:Select Task_ | b:NewQuotation | \[ o:AddAProduct | f:Product &#x25BC; | f:Quantity ]&#x207F; | b:Save  
  _a:See s:Quotations showing number of quotations_ | b:Validate  
  b:CreateInvoice | w:Invoicing | f:CreateInvoice \[ &#x25C9; Regular || Percentage || Ammount ]  
  b:CreateAndViewInvoice | w:InvoicePreview | b:Validate  

<br>

###### Odoo Guides - V2_01 &nbsp; 2019-07-31  
**[_&#x23CE; menu_](/en-uk/o13/ee/en-uk-o13-ee-guides-menu.md)**  
