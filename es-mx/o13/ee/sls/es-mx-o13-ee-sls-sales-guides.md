# O13 - EE - SLS - Ventas &nbsp;&nbsp;&nbsp;&nbsp; [![en-uk](/doc/img/en-uk_flag_button_small.png)](/en-uk/o13/ee/sls/en-uk-o13-ee-sls-sales-guides.md) [ ![es-mx](/doc/img/es-mx_flag_button_small.png)](/es-mx/o13/ee/sls/es-mx-o13-ee-sls-sales-guides.md)
#### [_&#x23CE; menu_](/es-mx/o13/ee/es-mx-o13-ee-guides-menu.md)  
### ![sls](/doc/img/sale.png)

#### [Configurador de Productos &nbsp;&nbsp; (O13 - EE - Odoo Mates - xx-in - 01:27)](https://youtube.com/embed/W9Ncu2mwqHQ?autoplay=1&start=0&end=0&rel=0)
![apps](/doc/img/apps.png) | o:Ventas | m:Productos | o:Productos | b:Editar | o:ConfigureAProducto | w:ConfigureAProducto |  
f:Producto &#x2BC6; | _a:Seleccionar producto_ | \[ _a:Seleccionar características optionales_ |  
b:Add | w:Configure \]&#x207F; | b:Confirmar | d:LowStockWarning | b:Ok | w:Cotizaciones | b:Guardar  

<br>

#### Cupones & Promociones

#### [Cupon de Ventas y Programas de Promoción &nbsp;&nbsp; (O13 - EE - Odoo Mates - xx-in - 06:55)](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=0&end=0&rel=0&nocount)

- [Configuración](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=0&end=31&rel=0)  
  ![apps](/doc/img/apps.png) | o:Apps | f:Buscar... coupon | ![filter](/doc/img/filter.png) _(apps) &#x2716; |  
  _a:Instalar módulos_ \[ Cupones & Promociones || Cupón de Venta || Venta Cupón Entrega || Gratis Entrega with Cupón \] |  
  ![apps](/doc/img/apps.png) | o:Ventas | m:Configuración | o:Configuración | i:Precio | f:CuponesYPromociones &#x1F5F9; |  
  \[ &#x1F872; Promoción Programas || Cupón Programas \]  

- [Cupón de Descuento](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=31&end=127&rel=0)  
  ![apps](/doc/img/apps.png) | o:Ventas | m:Productos | o:Programas de Cupones | \[ b:Crear || b:Editar \] |  
  f:NombreDelPrograma | i:Condiciones | i:Validéz | i:Bonos: Descuento | b:Guardar | b:GenerarCupón |  
  w:NúmeroDeCuponesAGenerar | f:TipoDeGeneración | f:NúmeroDeCupones | b:GenerarCupones |  
  w:CupónNombre | s:Cupones | _a:Seleccionar cupón_ | _a:Copiar número de cupón válido_ |  
  ![apps](/doc/img/apps.png) | o:Ventas | m:Órdenes | o:Cotizaciones | b:Crear | _a:Ingresar datos de la Cotización_ | b:Guardar | b:Confirmar |  
  b:AplicarCupón | w:IngresarCódigoDeCupón | f:Cupón | _a:Pegar número de cupón válido_ | b:Aplicar Cupón |  
  w:NúmeroDeCotización | _a:Verificar que aparezca el descuento como una nueva partida negativa_  

- [Cupón de Producto Gratis](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=127&end=228&rel=0)  
  _a:Crear Programa de Promoción como se indicó anteriormente, con Bonos: Gratis Producto_ | _a:Copiar número de cupón válido_ |  
  d:Los productos bonificados deben aparecer en las líneas de la orden de venta para aplicar el descuento |  
  _a:Abrir Cotización_ | _a:Agregar el producto gratuito_ | b:Guardar |  
  b:Aplicar Cupón | w:IngresarCódigoDeCupón | f:Cupón | _a:Pegar número de cupón válido_ | b:Aplicar Cupón |  
  _a:Verificar que aparezca el descuento como una nueva partida negativa_  

- [Promoción Paga tres y Llévate uno completamente gratis](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=228&end=320&rel=0)  
  ![apps](/doc/img/apps.png) | o:Ventas | m:Productos | o:ProgramasDePromoción | \[ b:Crear || b:Editar \] |  
  i:Condiciones | _a:Generar Programa con datos de f:BasadoEnProductos_ |  
  f:NombreDeCampo &#x2BC6; | f:Operador &#x2BC6; | f:TextoDeLaRegla | _a:Verificar que sea algo así como i:nombre contiene xxx_ |  
  \[ _a:Usar ![add](/doc/img/button_add.png) para agregar más condiciones_ | _a:Agregar regla como se indica anteriormente_ ]&#x207F; \] |  
  _a:Configurar Validéz y Bonos_ | b:Guardar |  
  ![apps](/doc/img/apps.png) | o:Ventas | m:Órdenes | o:Cotizaciones | b:Crear | _a:Ingresar Cotización_ | b:Guardar |  
  b:ActualizarPromociones | _a:Verificar Orden_ | b:Confirmar  

- [Promoción de descuento del 10%](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=320&end=0&rel=0)  
  ![apps](/doc/img/apps.png) | o:Ventas | m:Productos | o:ProgramasDePromoción | \[ b:Crear || b:Editar \] |  
  _a:Crear programa como se indica anteriormente, con f:BasadoOnProductos_ |  
  f:NombreDeCampo &#x2BC6; | f:Operador &#x2BC6; | f:TextoDeLaRegla | _a:Verificar que sea algo así como i:Puede ser Vendido es verdadero_ |  
  ![apps](/doc/img/apps.png) | o:Ventas | m:Órdenes | o:Cotizaciones | b:Crear | _a:Ingresar Cotización_ | b:Guardar |  
  b:Actualizar Promociones | _a:Verificar Orden_ | b:Confirmar   

<br>

###### Guías Odoo - v4_02 &nbsp; 2019-08-05  
**[_&#x23CE; menu_](/es-mx/o13/ee/es-mx-o13-ee-guides-menu.md)**  
