## O13 - SLS - Sales (Ventas)
#### [_&#x23CE; menu_](/o13/ee/o13-ee-guides_menu.md)  

#### [Product Configurator (O13 - EE - Odoo Mates - n/v - 01:26 - Configurador de Productos)](https://youtube.com/embed/W9Ncu2mwqHQ?autoplay=1&start=0&end=0&rel=0)
&#x25A6; | o:sales | m:Products | o:Products | b:Edit | o:ConfigureAProduct | w:ConfigureAProduct | f:Product &#x25BC; | a:Select product  
\[ a:Select optional features | b:Add | w:Configure \]&#x207F; | b:Confirm | d:LowStockWarning | b:Ok | w:Quotations | b:Save  

<br>

#### Coupons & Promotions

#### [Sales Coupon and Promotion Program (O13 - EE - Odoo Mates - n/v - 06:54 - Cupones y Promociones)](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=0&end=0&rel=0)

- [Settings (Configuración)](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=0&end=31&rel=0)  
&#x25A6; | o:apps | f:Search... coupon | &#x2716; apps  
a:Install modules \[ Coupons & Promotions || Sale Coupon || Sale Coupon Delivery || Free Delivery with Coupon \]  
&#x25A6; | o:sales | m:Configuration | o:Settings | i:Pricing | f:Coupons&Promotions &#x1F5F9;  
\[ &#x1F872; Promotion Programs || Coupon Programs \]

- [Discount Coupon (Cupón de Descuento)](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=31&end=2m7s&rel=0)  
&#x25A6; | o:sales | m:Products | o:Coupon Programs | \[ b:Create || b:Edit \]  
f:ProgramName | i:Conditions | i:Validity | i:Rewards: Discount | b:Save | b:Generate Coupon  
w:NumberoOfCouponsToGenerate | f:Generation Type | f:NumberOfCoupons | b:Generate Coupons  
w:CouponName | s:Coupons | a:Select coupon | a:Copy valid coupon number  
&#x25A6; | o:sales | m:Orders | o:Quotations | b:Create | a:Enter quotation data | b:Save | b:Confirm  
b:Apply Coupon | w:EnterCouponCode | f:Coupon | a:Paste valid coupon number | b:Apply Coupon   
w:Quotation Number | a:Verify discount appearing as a new negative detail row

- [Free Product Coupon (Cupón de Producto Grátis)](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=2m7s&end=3m48s&rel=0)  
a:Create Promotion Program as above with Rewards: Free Product | a:Copy valid coupon number 
d:The reward products should be in the sales order lines to apply the discount  
a:Open quotation | a:Add the free product | b:Save  
b:Apply Coupon | w:Enter Coupon Code | f:Coupon | a:Paste valid coupon number | b:Apply Coupon   
a:Verify discount appearing as a new negative detail row

- [Buy 3 & get one free Promotion (Promoción de paga 3 y llévate 4)](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=3m48s&end=5m20s&rel=0)  
&#x25A6; | o:sales | m:Products | o:Promotion Programs | \[ b:Create || b:Edit \]  
i:Conditions | a:Generate Program with f:BasedOnProducts data  
f:FieldName &#x25BC; | f:Operator &#x25BC; | f:RuleText | a:Verify it's something like i:name contains xxx  
\[ a:Use **&#x2A01;** to add more conditions | a:Add rule as above ]&#x207F; \] | a:Set Validity & Rewards | b:Save  
&#x25A6; | o:sales | m:Orders | o:Quotations | b:Create | a:Enter quotation | b:Save  
b:Update Promotions | a:Verify order | b:Confirm   

- [10% off in orders Promotion (Promoción de descuento de 10%)](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=5m20s&end=0&rel=0)  
&#x25A6; | o:sales | m:Products | o:Promotion Programs | \[ b:Create || b:Edit \] | a:Create program as above with f:BasedOnProducts  
f:FieldName &#x25BC; | f:Operator &#x25BC; | f:RuleText | a:Verify it's something like i:Can be Sold is set (true)  
&#x25A6; | o:sales | m:Orders | o:Quotations | b:Create | a:Enter Quotation | b:Save | b:Update Promotions | a:Verify order | b:Confirm   

<br>

###### Odoo Guides - v2_01 &nbsp; 2019-07-24  [_&#x23CE; menu_](/o13/ee/o13-ee-guides_menu.md)  
