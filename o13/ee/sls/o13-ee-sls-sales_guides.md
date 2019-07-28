## O13 - EE - SLS - Sales (Ventas)
#### [_&#x23CE; menu_](/o13/ee/o13-ee-guides_menu.md)  

#### [Product Configurator (O13 - EE - Odoo Mates - n/v - 01:27 - Configurador de Productos)](https://youtube.com/embed/W9Ncu2mwqHQ?autoplay=1&start=0&end=0&rel=0)
&#x25A6; | o:Sales | m:Products | o:Products | b:Edit | o:ConfigureAProduct | w:ConfigureAProduct | f:Product &#x25BC; | _a:Select product_  
\[ _a:Select optional features_ | b:Add | w:Configure \]&#x207F; | b:Confirm | d:LowStockWarning | b:Ok | w:Quotations | b:Save  

<br>

#### Coupons & Promotions

#### [Sales Coupon and Promotion Program (O13 - EE - Odoo Mates - n/v - 06:55 - Cupones y Promociones)](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=0&end=0&rel=0)

- [Settings (Configuración)](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=0&end=31&rel=0)  
&#x25A6; | o:Apps | f:Search... coupon | &#x2716; apps  
_a:Install modules_ \[ Coupons & Promotions || Sale Coupon || Sale Coupon Delivery || Free Delivery with Coupon \]  
&#x25A6; | o:Sales | m:Configuration | o:Settings | i:Pricing | f:Coupons&Promotions &#x1F5F9;  
\[ &#x1F872; Promotion Programs || Coupon Programs \]

- [Discount Coupon (Cupón de Descuento)](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=31&end=2m7s&rel=0)  
&#x25A6; | o:Sales | m:Products | o:Coupon Programs | \[ b:Create || b:Edit \]  
f:ProgramName | i:Conditions | i:Validity | i:Rewards: Discount | b:Save | b:Generate Coupon  
w:NumberoOfCouponsToGenerate | f:Generation Type | f:NumberOfCoupons | b:Generate Coupons  
w:CouponName | s:Coupons | _a:Select coupon_ | _a:Copy valid coupon number_  
&#x25A6; | o:Sales | m:Orders | o:Quotations | b:Create | _a:Enter quotation data_ | b:Save | b:Confirm  
b:Apply Coupon | w:EnterCouponCode | f:Coupon | _a:Paste valid coupon number_ | b:Apply Coupon   
w:Quotation Number | _a:Verify discount appearing as a new negative detail row_

- [Free Product Coupon (Cupón de Producto Grátis)](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=2m7s&end=3m48s&rel=0)  
_a:Create Promotion Program as above with Rewards: Free Product_ | _a:Copy valid coupon number_ 
d:The reward products should be in the sales order lines to apply the discount  
_a:Open quotation_ | _a:Add the free product_ | b:Save  
b:Apply Coupon | w:Enter Coupon Code | f:Coupon | _a:Paste valid coupon number_ | b:Apply Coupon   
_a:Verify discount appearing as a new negative detail row_  

- [Buy 3 & get one free Promotion (Promoción de paga 3 y llévate 4)](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=3m48s&end=5m20s&rel=0)  
&#x25A6; | o:Sales | m:Products | o:Promotion Programs | \[ b:Create || b:Edit \]  
i:Conditions | _a:Generate Program with f:BasedOnProducts data_  
f:FieldName &#x25BC; | f:Operator &#x25BC; | f:RuleText | _a:Verify it's something like i:name contains xxx_  
\[ _a:Use **&#x2A01;** to add more conditions_ | _a:Add rule as above_ ]&#x207F; \] | _a:Set Validity & Rewards_ | b:Save  
&#x25A6; | o:Sales | m:Orders | o:Quotations | b:Create | _a:Enter quotation_ | b:Save  
b:Update Promotions | _a:Verify order_ | b:Confirm   

- [10% off in orders Promotion (Promoción de descuento de 10%)](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=5m20s&end=0&rel=0)  
&#x25A6; | o:Sales | m:Products | o:Promotion Programs | \[ b:Create || b:Edit \] | _a:Create program as above with f:BasedOnProducts_  
f:FieldName &#x25BC; | f:Operator &#x25BC; | f:RuleText | _a:Verify it's something like i:Can be Sold is set (true)_  
&#x25A6; | o:Sales | m:Orders | o:Quotations | b:Create | _a:Enter Quotation_ | b:Save | b:Update Promotions | _a:Verify order_ | b:Confirm   

<br>

###### Odoo Guides - v2_02 &nbsp; 2019-07-25  [_&#x23CE; menu_](/o13/ee/o13-ee-guides_menu.md)  
