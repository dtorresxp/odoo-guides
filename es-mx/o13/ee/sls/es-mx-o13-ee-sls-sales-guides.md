# O13 - EE - SLS - Ventas &nbsp;&nbsp;&nbsp;&nbsp; [![en-uk](/doc/img/en-uk_flag_button_small.png)](/en-uk/o13/ee/sls/en-uk-o13-ee-sls-sales-guides.md) [ ![es-mx](/doc/img/es-mx_flag_button_small.png)](/es-mx/o13/ee/sls/es-mx-o13-ee-sls-sales-guides.md)
#### [_&#x23CE; menu_](/es-mx/o13/ee/es-mx-o13-ee-guides-menu.md)  
### ![sls](/doc/img/sale.png)

#### [Configurador de Productos &nbsp;&nbsp; (O13 - EE - Odoo Mates - xx-xx - 01:27)](https://youtube.com/embed/W9Ncu2mwqHQ?autoplay=1&start=0&end=0&rel=0)
![apps](/doc/img/apps.png) | o:Sales | m:Products | o:Products | b:Editar | o:ConfigureAProduct | w:ConfigureAProduct | f:Product &#x25BC; | _a:Seleccionar product_  
\[ _a:Seleccionar optional features_ | b:Add | w:Configure \]&#x207F; | b:Confirm | d:LowStockWarning | b:Ok | w:Cotizaciones | b:Guardar  

<br>

#### Cupones & Promociones

#### [Cupon de Ventas y Programas de Promoción &nbsp;&nbsp; (O13 - EE - Odoo Mates - xx-xx - 06:55)](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=0&end=0&rel=0&nocount)

- [Configuración](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=0&end=31&rel=0)  
![apps](/doc/img/apps.png) | o:Apps | f:Buscar... coupon | _(apps) &#x2716;  
_a:Instalar modules_ \[ Coupons & Promotions || Sale Coupon || Sale Coupon Delivery || Free Delivery with Coupon \]  
![apps](/doc/img/apps.png) | o:Sales | m:Configuration | o:Configuración | i:Pricing | f:Coupons&Promotions &#x1F5F9;  
\[ &#x1F872; Promotion Programs || Coupon Programs \]

- [Cupón de Descuento](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=31&end=2m7s&rel=0)  
![apps](/doc/img/apps.png) | o:Sales | m:Products | o:Coupon Programs | \[ b:Crear || b:Editar \]  
f:ProgramName | i:Conditions | i:Validity | i:Rewards: Discount | b:Guardar | b:Generate Coupon  
w:NumberoOfCouponsToGenerate | f:Generation Tipo | f:NumberOfCoupons | b:Generate Coupons  
w:CouponName | s:Coupons | _a:Seleccionar coupon_ | _a:Copy valid coupon number_  
![apps](/doc/img/apps.png) | o:Sales | m:Orders | o:Cotizaciones | b:Crear | _a:Enter quotation data_ | b:Guardar | b:Confirm  
b:Apply Coupon | w:EnterCouponCode | f:Coupon | _a:Paste valid coupon number_ | b:Apply Coupon   
w:Cotización Number | _a:Verify discount appearing as a new negative detail row_

- [Cupón de Producto Gratis](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=2m7s&end=3m48s&rel=0)  
_a:Crear Promotion Program as above with Rewards: Free Product_ | _a:Copy valid coupon number_ 
d:The reward products should be in the sales order lines to apply the discount  
_a:Abrir quotation_ | _a:Add the free product_ | b:Guardar  
b:Apply Coupon | w:Enter Coupon Code | f:Coupon | _a:Paste valid coupon number_ | b:Apply Coupon   
_a:Verify discount appearing as a new negative detail row_  

- [Promoción Paga tres y Llévate uno completamente gratis](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=3m48s&end=5m20s&rel=0)  
![apps](/doc/img/apps.png) | o:Sales | m:Products | o:Promotion Programs | \[ b:Crear || b:Editar \]  
i:Conditions | _a:Generate Program with f:BasedOnProducts data_  
f:FieldName &#x25BC; | f:Operator &#x25BC; | f:RuleText | _a:Verify it's something like i:name contains xxx_  
\[ _a:Use ![add](/doc/img/button_add.png) to add more conditions_ | _a:Add rule as above_ ]&#x207F; \] | _a:Configurar Validity & Rewards_ | b:Guardar  
![apps](/doc/img/apps.png) | o:Sales | m:Orders | o:Cotizaciones | b:Crear | _a:Enter quotation_ | b:Guardar  
b:Update Promotions | _a:Verify order_ | b:Confirm   

- [Promoción de descuento del 10%](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=5m20s&end=0&rel=0)  
![apps](/doc/img/apps.png) | o:Sales | m:Products | o:Promotion Programs | \[ b:Crear || b:Editar \] | _a:Crear program as above with f:BasedOnProducts_  
f:FieldName &#x25BC; | f:Operator &#x25BC; | f:RuleText | _a:Verify it's something like i:Can be Sold is set (true)_  
![apps](/doc/img/apps.png) | o:Sales | m:Orders | o:Cotizaciones | b:Crear | _a:Enter Cotización_ | b:Guardar | b:Update Promotions | _a:Verify order_ | b:Confirm   

<br>

###### Guías Odoo - v4_01 &nbsp; 2019-07-31  
**[_&#x23CE; menu_](/es-mx/o13/ee/es-mx-o13-ee-guides-menu.md)**  
