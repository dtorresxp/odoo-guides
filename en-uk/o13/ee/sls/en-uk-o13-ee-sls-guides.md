# O13 - EE - SLS - Sales &nbsp;&nbsp;&nbsp;&nbsp; [![en-uk](/doc/img/flg/en-uk-flg-btn-sml.png)](/en-uk/o13/ee/sls/en-uk-o13-ee-sls-guides.md) [ ![es-mx](/doc/img/flg/es-mx-flg-btn-sml.png)](/es-mx/o13/ee/sls/es-mx-o13-ee-sls-guides.md)
#### [_&#x23CE; menu_](/en-uk/o13/ee/en-uk-o13-ee-guides-menu.md "Back to EE menu")  
### ![sls](/doc/img/app/big/sls.png)
[ⱽ¹²³⁴⁵⁶⁷⁸⁹⁰⁻]: # (ⱽ¹²³⁴⁵⁶⁷⁸⁹⁰⁻)

<br>

## Sales

#### [Multi level Quotation approval process based on Discount (O13 - EE - PinakinNayi - xx-in - 03:09)](https://youtube.com/embed/my1BzTVzehg?autoplay=1&start=0&end=0&rel=0)  
- ###### Test different discounts
  ![apps](/doc/img/apps.png) | o:Sales | m:Orders | o:Quotations | b:Create | f:Customer &#x2BC6; | t:OrderLines | i:AddAProduct | f:Prod | _a:Notice_ f:UnitPrice | f:Disc% | _a:Enter **20**_ | b:Save |  
  b:Confirm | d:OdooServerError | _a:Notice You haven't enough access to confirm the order (you've given more then 15% discount) message_ | b:Ok |  
  b:Edit | f:Disc% | _a:Enter **30**_ | b:Confirm | d:OdooServerError | _Notice same error as before_ | b:Ok |  
  b:Edit | f:Disc% | _a:Enter **35**_ | b:Confirm | d:OdooServerError | _a:Notice now message is No one allowed to give discount more than 30%_ | b:Ok |  
  b:Edit | f:Disc% | _a:Enter **12**_ | b:Confirm | d:OdooServerError | _a:Notice error message now is about 10% discount_ | b:Ok |  
  b:Edit | f:Disc% | _a:Enter **10**_ | b:Confirm | _a:Notice Order now is confirmed_ | b:Ok |  
- ###### Review Discount Ranges
  ![apps](/doc/img/apps.png) | o:set | i:ManageAccessRights | _a:Click on_ f:Name _to open | _a:Scroll down the form_ |  
  _a:Review Permissions_ | f:AllowDiscountUpTo10% &#x1F5F9; | f:AllowDiscountUpTo30% &#x2610; |  
- ###### Test discounts by decreasing unitary price
  ![apps](/doc/img/apps.png) | o:Sales | m:Orders | o:Quotations | b:Create | f:Customer &#x2BC6; | t:OrderLines | i:AddAProduct | f:Prod | f:UnitPrice | _a:Enter **60** (equivalent to a 40% discount)_ | b:Save |  
  b:Confirm | d:OdooServerError | _a:Notice message is No one allowed to give discount more than 30%_ | b:Ok |  
  b:Edit | f:UnitPrice | _a:Enter **85** (15% equivalent)_ | b:Confirm | d:OdooServerError | _Notice same error as before_ | b:Ok |  
  b:Edit | f:UnitPrice | _a:Enter **95** (5% equivalent)_ | b:Confirm | _a:Notice Order now is confirmed_ | b:Ok |  
- ###### Allow up to 15% Discounts
  ![apps](/doc/img/apps.png) | o:set | i:ManageAccessRights | _a:Click on_ f:Name _to open | _a:Scroll down the form_ |  
  _a:Review Permissions_ | f:AllowDiscountUpTo15% &#x1F5F9; | b:Save |  
- ###### Test a higher than 10% discount again
  ![apps](/doc/img/apps.png) | o:Sales | m:Orders | o:Quotations | b:Create | f:Customer &#x2BC6; | t:OrderLines | i:AddAProduct | f:Prod | f:UnitPrice | _a:Enter **60** (equivalent to a 40% discount)_ | b:Save |  
  b:Edit | f:Disc% | _a:Enter **13**_ | b:Confirm | _a:Notice Order now is confirmed_ | b:Ok

## Product Configurator

#### [How to Activate the Product Configurator &nbsp;&nbsp; (O13 - EE - Odoo Mates - xx-in - 02:34)](https://youtube.com/embed/DWmOGxmof_U?autoplay=1&start=0&end=0&rel=0)
- _a:Deactivated behavior:_  
  ![apps](/doc/img/apps.png) | o:Sales | m:Configuration | o:Settings | f:ProductConfigurator &#x2610; |  
  m:Orders | o:Quotations | b:Create | f:Customer &#x2BC6; | t:OrderLines | i:AddAProduct &#x2BC6; |  
  _a:Notice there aren't configurable products listed_ |  
  _a:Close creating product warning dialog_ | _a:Accept warning dialog because of unsaved order_ |  
- _a:Activated behavior:_  
  \[ ![apps](/doc/img/apps.png) | o:Sales ] |  
  m:Configuration | o:Settings | _a:Activate configurator_ f:ProductConfigurator &#x1F5F9; | b:Save |  
  m:Orders | o:Quotations | b:Create | f:Customer &#x2BC6; | t:OrderLines | i:AddAProduct &#x2BC6; |  
  _a:Notice now there are configurable products in list_ | _a:Select configurable product |  
  w:ConfigureAProduct | _a:Configure product_ | b:Add | b:Confirm | b:Save  
  ⱽ¹⁻⁰¹ &nbsp;²⁰¹⁹⁻⁰⁸⁻⁰⁴

#### [Product Configurator &nbsp;&nbsp; (O13 - EE - Odoo Mates - xx-in - 01:27)](https://youtube.com/embed/W9Ncu2mwqHQ?autoplay=1&start=0&end=0&rel=0)
  ![apps](/doc/img/apps.png) | o:Sales | m:Products | o:Products | b:Edit | o:ConfigureAProduct | w:ConfigureAProduct | f:Product &#x2BC6; | _a:Select product_ |  
  \[ _a:Select optional features_ | b:Add | w:Configure \]&#x207F; | b:Confirm | d:LowStockWarning | b:Ok | w:Quotations | b:Save  
  ⱽ¹⁻⁰¹ &nbsp;²⁰¹⁹⁻⁰⁸⁻⁰⁴

#### [New Product Configurator &nbsp;&nbsp; (O13 - EE - Odoo Mates - xx-in - 04:51)](https://youtube.com/embed/TgAbV7xG2wo?autoplay=1&start=18&end=0&rel=0)
  ![apps](/doc/img/apps.png) | o:Sales | m:Products | o:Products | f:Search... desk | _a:Select item with variants |  
  t:Variants | _a:Review data_ | m:Orders | o:Quotations | b:Create |  
  f:Customer | &#x2BC6; | f:Expiration &#x1F4C5; | t:OrderLines | i:AddAProduct |  
  f:Product &#x1F4C5; | _a:Select Product with Variants_ | w:ConfigureAProduct | f:Product | _a:Configure variants_ | b:Add | b:Close |  
  b: ![edit](/doc/img/edit.png) | _a:Opens the same product configurator window_ | b:Confirm |  
  _a:Notice Odoo can check if desired combination is available_ |  
  _a:Review your product configuration on Order Line_ |  
  _a:Configurator also shows optional products_ |  
  b:Save  
  ⱽ¹⁻⁰¹ &nbsp;²⁰¹⁹⁻⁰⁸⁻⁰⁴

<br>

## Coupons & Promotions

#### [Sales Coupon and Promotion Program &nbsp;&nbsp; (O13 - EE - Odoo Mates - xx-in - 06:55)](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=0&end=0&rel=0&nocount)

- [Settings](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=0&end=31&rel=0)  
  ![apps](/doc/img/apps.png) | o:Apps | f:Search... coupon | ![filter](/doc/img/filter.png) _(apps) &#x2716; |  
  _a:Install modules_ \[ Coupons & Promotions || Sale Coupon || Sale Coupon Delivery || Free Delivery with Coupon \] |  
  ![apps](/doc/img/apps.png) | o:Sales | m:Configuration | o:Settings | i:Pricing | f:Coupons&Promotions &#x1F5F9; |  
  \[ &#x1F872; Promotion Programs || Coupon Programs \]  
  ⱽ¹⁻⁰¹ &nbsp;²⁰¹⁹⁻⁰⁸⁻⁰⁴

- [Discount Coupon](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=31&end=127&rel=0)  
  ![apps](/doc/img/apps.png) | o:Sales | m:Products | o:Coupon Programs | \[ b:Create || b:Edit \] |  
  f:ProgramName | i:Conditions | i:Validity | i:Rewards: Discount | b:Save | b:Generate Coupon |  
  w:NumberoOfCouponsToGenerate | f:Generation Type | f:NumberOfCoupons | b:Generate Coupons |  
  w:CouponName | s:Coupons | _a:Select coupon_ | _a:Copy valid coupon number_ |  
  ![apps](/doc/img/apps.png) | o:Sales | m:Orders | o:Quotations | b:Create | _a:Enter quotation data_ | b:Save | b:Confirm |  
  b:Apply Coupon | w:EnterCouponCode | f:Coupon | _a:Paste valid coupon number_ | b:Apply Coupon  |  
  w:Quotation Number | _a:Verify discount appearing as a new negative detail row_  
  ⱽ¹⁻⁰¹ &nbsp;²⁰¹⁹⁻⁰⁸⁻⁰⁴

- [Free Product Coupon](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=127&end=228&rel=0)  
  _a:Create Promotion Program as above with Rewards: Free Product_ | _a:Copy valid coupon number_|  
  d:The reward products should be in the sales order lines to apply the discount |  
  _a:Open quotation_ | _a:Add the free product_ | b:Save |  
  b:Apply Coupon | w:Enter Coupon Code | f:Coupon | _a:Paste valid coupon number_ | b:Apply Coupon  |  
  _a:Verify discount appearing as a new negative detail row_  
  ⱽ¹⁻⁰¹ &nbsp;²⁰¹⁹⁻⁰⁸⁻⁰⁴

- [Buy 3 & get one free Promotion](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=228&end=320&rel=0)  
  ![apps](/doc/img/apps.png) | o:Sales | m:Products | o:Promotion Programs | \[ b:Create || b:Edit \] |  
  i:Conditions | _a:Generate Program with f:BasedOnProducts data_ |  
  f:FieldName &#x2BC6; | f:Operator &#x2BC6; | f:RuleText | _a:Verify it's something like i:name contains xxx_ |  
  \[ _a:Use ![add](/doc/img/button_add.png) to add more conditions_ | _a:Add rule as above_ ]&#x207F; \] | _a:Set Validity & Rewards_ | b:Save |  
  ![apps](/doc/img/apps.png) | o:Sales | m:Orders | o:Quotations | b:Create | _a:Enter quotation_ | b:Save |  
  b:Update Promotions | _a:Verify order_ | b:Confirm   
  ⱽ¹⁻⁰¹ &nbsp;²⁰¹⁹⁻⁰⁸⁻⁰⁴

- [10% off in orders Promotion](https://youtube.com/embed/JF5JYktZV3E?autoplay=1&start=320&end=0&rel=0)  
  ![apps](/doc/img/apps.png) | o:Sales | m:Products | o:Promotion Programs | \[ b:Create || b:Edit \] | _a:Create program as above with f:BasedOnProducts_ |  
  f:FieldName &#x2BC6; | f:Operator &#x2BC6; | f:RuleText | _a:Verify it's something like i:Can be Sold is set (true)_ |  
  ![apps](/doc/img/apps.png) | o:Sales | m:Orders | o:Quotations | b:Create | _a:Enter Quotation_ | b:Save | b:Update Promotions | _a:Verify order_ | b:Confirm   
  ⱽ¹⁻⁰¹ &nbsp;²⁰¹⁹⁻⁰⁸⁻⁰⁴

<br>

###### Odoo Guides - v5_03 &nbsp; 2019-08-11  
**[_&#x23CE; menu_](/en-uk/o13/ee/en-uk-o13-ee-guides-menu.md)**  
