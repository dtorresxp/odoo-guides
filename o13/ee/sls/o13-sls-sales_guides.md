## O13 - SLS - Sales (Ventas)
#### [_&#x23CE; menu_](https://github.com/oldyguy/odoo-guides/blob/master/README.md)<br><br>

[Product Configurator in Odoo13 (Odoo Mates - n/v - 01:26 - Configurador de Productos en Odoo 13)](https://youtube.com/embed/W9Ncu2mwqHQ?autoplay=1&start=0&end=0&rel=0)<br>
&#x229E; | sales | Products | Products | Edit | Configure a product | Product | &#x25BC; | { select product }<br>
\[ { select optional features } \]&#x207F; | add<br>
\< low stock warning \> | ok<br>
Quotations | &#x1F4BE;

#### Coupons & Promotions

[Sales Coupon and Promotion Program in Odoo13 (Odoo Mates - n/v - 06:54 - Cupones y Promociones en Odoo 13)](https://youtube.com/embed/W9Ncu2mwqHQ?autoplay=1&start=0&end=0&rel=0)<br>

- [Settings (Configuración)](https://youtube.com/embed/W9Ncu2mwqHQ?autoplay=1&start=0&end=31&rel=0)<br>
&#x229E; | apps | \< search for \> coupon | &#x274C; apps<br>
{ install modules } \< Coupons & Promotions || Sale Coupon || Sale Coupon Delivery || Free Delivery with Coupon \><br>
&#x229E; | sales | Configuration | Settings<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\[ Pricing | Coupons & Promotions | &#x1F872; Promotion Programs || Products | Promotion Programs \]<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\[ Pricing | Coupons & Promotions | &#x1F872; Coupon Programs &nbsp;&nbsp;&nbsp; || Coupons | Coupon Programs \]<br>

- [Discount Coupon (Cupón de Descuento)](https://youtube.com/embed/W9Ncu2mwqHQ?autoplay=1&start=31&end=2m7s&rel=0)<br>
&#x229E; | sales | Products | Coupon Programs | \[ Create || Edit \]<br>
{ capture } < Program name > | < Conditions > | <Validity > | < Rewards: Discount > | &#x1F4BE;<br>
Generate Coupon | Generation Type | { define number of coupons } | Generate Coupons | { copy valid coupon }<br>
&#x229E; | sales | Orders | Quotations | Create | { input quotation } | &#x1F4BE;<br>
Apply Coupon | Enter Coupon Code | { paste valid coupon number } | Apply Coupon <br>
{ discount will appear as a new negative detail row }

- [Free Product Coupon (Cupón de Producto Grátis)](https://youtube.com/embed/W9Ncu2mwqHQ?autoplay=1&start=2m7s&end=3m48s&rel=0)<br>
{ create program as above with Rewards: Free Product }<br>
{ the reward products should be in the sales order lines to apply the discount }<br>
{ open quotation } | { add the free product } | &#x1F4BE;<br>
Apply Coupon | Enter Coupon Code | { paste valid coupon number } | Apply Coupon <br>
{ discount will appear as a new negative detail row }

- [Buy 3 & get one free Promotion (Promoción de paga 3 y llévate 4)](https://youtube.com/embed/W9Ncu2mwqHQ?autoplay=1&start=3m48s&end=5m20s&rel=0)<br>
&#x229E; | sales | Products | Promotion Programs | \[ Create || Edit \] | { create program with < Based on Products ><br>
&#x25BC; { select field } | &#x25BC; { select operator } | &#x25BC; { select text } | { i.e.: name contains xxx }<br>
{ set other conditions } | { set validity & rewards } | &#x1F4BE;<br>
&#x229E; | sales | Orders | Quotations | Create | { input quotation } | &#x1F4BE;<br>
Update Promotions | { verify order } | Confirm <br>

- [10% off in orders Promotion (Promoción de descuento de 10%)](https://youtube.com/embed/W9Ncu2mwqHQ?autoplay=1&start=5m20s&end=0&rel=0)<br>
&#x229E; | sales | Products | Promotion Programs | \[ Create || Edit \] | { create program with < Based on Products ><br>
&#x25BC; { select field } | &#x25BC; { select operator } | &#x25BC; { select text } | { i.e.: Can be Sold is set (true) }<br>
Promo Code Usage: Use a Code | Promotion Code (i.e.: 10pc) | Rewards: Apply Discount: Percentage: xx%<br>
{ set other conditions } | { set validity & other rewards } | &#x1F4BE;<br>
&#x229E; | sales | Orders | Quotations | Create | { input quotation } | &#x1F4BE; | Update Promotions { verify order } | Confirm <br>


###### <br><br>Odoo Guides - v1_02 &nbsp; 2019-07-20<br>[_&#x23CE; menu_](https://github.com/oldyguy/odoo-guides/blob/master/README.md)<br><br>
