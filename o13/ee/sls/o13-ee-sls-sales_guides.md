## O13 - SLS - Sales (Ventas)
#### [_&#x23CE; menu_](/o13/ee/o13-ee-guides_menu.md)  

#### [Product Configurator (O13 - EE - Odoo Mates - n/v - 01:26 - Configurador de Productos)](https://youtube.com/embed/W9Ncu2mwqHQ?autoplay=1&start=0&end=0&rel=0)
&#x229E; | sales | Products | Products | Edit | Configure a product | Product | &#x25BC; | { select product }  
\[ { select optional features } \]&#x207F; | add  
\< low stock warning \> | ok  
Quotations | &#x1F4BE;

<br>

#### Coupons & Promotions

<br><br>
#### [Sales Coupon and Promotion Program (O13 - EE - Odoo Mates - n/v - 06:54 - Cupones y Promociones)](https://youtube.com/embed/W9Ncu2mwqHQ?autoplay=1&start=0&end=0&rel=0)

- [Settings (Configuración)](https://youtube.com/embed/W9Ncu2mwqHQ?autoplay=1&start=0&end=31&rel=0)
&#x229E; | apps | \< search for \> coupon | &#x2716; apps  
{ install modules } \< Coupons & Promotions || Sale Coupon || Sale Coupon Delivery || Free Delivery with Coupon \>  
&#x229E; | sales | Configuration | Settings  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\[ Pricing | Coupons & Promotions | &#x1F872; Promotion Programs || Products | Promotion Programs \]  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\[ Pricing | Coupons & Promotions | &#x1F872; Coupon Programs &nbsp;&nbsp;&nbsp; || Coupons | Coupon Programs \]  

- [Discount Coupon (Cupón de Descuento)](https://youtube.com/embed/W9Ncu2mwqHQ?autoplay=1&start=31&end=2m7s&rel=0)
&#x229E; | sales | Products | Coupon Programs | \[ Create || Edit \]  
{ capture } < Program name > | < Conditions > | <Validity > | < Rewards: Discount > | &#x1F4BE;  
Generate Coupon | Generation Type | { define number of coupons } | Generate Coupons | { copy valid coupon }  
&#x229E; | sales | Orders | Quotations | Create | { input quotation } | &#x1F4BE;  
Apply Coupon | Enter Coupon Code | { paste valid coupon number } | Apply Coupon   
{ discount will appear as a new negative detail row }

- [Free Product Coupon (Cupón de Producto Grátis)](https://youtube.com/embed/W9Ncu2mwqHQ?autoplay=1&start=2m7s&end=3m48s&rel=0)
{ create program as above with Rewards: Free Product }  
{ the reward products should be in the sales order lines to apply the discount }  
{ open quotation } | { add the free product } | &#x1F4BE;  
Apply Coupon | Enter Coupon Code | { paste valid coupon number } | Apply Coupon   
{ discount will appear as a new negative detail row }

- [Buy 3 & get one free Promotion (Promoción de paga 3 y llévate 4)](https://youtube.com/embed/W9Ncu2mwqHQ?autoplay=1&start=3m48s&end=5m20s&rel=0)
&#x229E; | sales | Products | Promotion Programs | \[ Create || Edit \] | { create program with < Based on Products >  
&#x25BC; { select field } | &#x25BC; { select operator } | &#x25BC; { select text } | { i.e.: name contains xxx }  
{ set other conditions } | { set validity & rewards } | &#x1F4BE;  
&#x229E; | sales | Orders | Quotations | Create | { input quotation } | &#x1F4BE;  
Update Promotions | { verify order } | Confirm   

- [10% off in orders Promotion (Promoción de descuento de 10%)](https://youtube.com/embed/W9Ncu2mwqHQ?autoplay=1&start=5m20s&end=0&rel=0)
&#x229E; | sales | Products | Promotion Programs | \[ Create || Edit \] | { create program with < Based on Products >  
&#x25BC; { select field } | &#x25BC; { select operator } | &#x25BC; { select text } | { i.e.: Can be Sold is set (true) }  
Promo Code Usage: Use a Code | Promotion Code (i.e.: 10pc) | Rewards: Apply Discount: Percentage: xx%  
{ set other conditions } | { set validity & other rewards } | &#x1F4BE;  
&#x229E; | sales | Orders | Quotations | Create | { input quotation } | &#x1F4BE; | Update Promotions { verify order } | Confirm   

<br>

###### Odoo Guides - v1_03 &nbsp; 2019-07-23  [_&#x23CE; menu_](/o13/ee/o13-ee-guides_menu.md)  
