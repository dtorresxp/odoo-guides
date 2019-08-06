# O13 - EE - IVC - Invoicing &nbsp;&nbsp;&nbsp;&nbsp; [![en-uk](/doc/img/en-uk_flag_button_small.png)](/en-uk/o13/ee/ivc/en-uk-o13-ee-ivc-invoicing-guides.md) [ ![es-mx](/doc/img/es-mx_flag_button_small.png)](/es-mx/o13/ee/ivc/es-mx-o13-ee-ivc-invoicing-guides.md)
#### [_&#x23CE; menu_](/en-uk/o13/ee/en-uk-o13-ee-guides-menu.md)  
### ![ivc](/doc/img/account_invoicing.png)

#### [Accounting Overview &nbsp;&nbsp; (O13 - EE - Odoo Mates - xx-xx - 08:58)](https://youtube.com/embed/hA6KSbR7YVI?autoplay=1&start=6&end=58&rel=0&nocount)
[***Sync***]: # (o13-ee-inv-invoicing-guides)  

- **Configuration:**  
  - [Configuration](https://youtube.com/embed/hA6KSbR7YVI?autoplay=1&start=6&end=54&rel=0)  
    ![apps](/doc/img/apps.png) | o:Settings | i:ActivateTheDeveloperMode |  
    ![apps](/doc/img/apps.png) | o:Settings | m:Users&Companies | o:Users | _a:Select User_ |  
    _a:Scroll Down_ | i:TechnicalSettings | f:ShowFullAccountingFeatures &#x1F5F9; | b:Save  

  - [Company Data](https://youtube.com/embed/hA6KSbR7YVI?autoplay=1&start=55&end=79&rel=0)  
    ![apps](/doc/img/apps.png) | o:Invoicing | i:CompanyData | b:Let'sStart |  
    w:SetYourCompanyData | f:Logo | f:Name |  
    t:GeneralInformation | f:Partner Address | f:WebsiteLink | f:Phone | f:LocalNumbers | f:Email | f:VAT |  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    f:CompanyRegistry | f:Currency | f:ParentCompany | f:CompanyFavicon |  
    b:Apply | _a:Notice Company Data now shows:_ **&#x2713;** All done!  

  - [Bank Account](https://youtube.com/embed/hA6KSbR7YVI?autoplay=1&start=80&end=92&rel=0)  
    ![apps](/doc/img/apps.png) | o:Invoicing | i:BankAccount | b:AddABank |  
    w:CreateBankAccount | f:AccountNumber | f:Bank &#x2BC6; | f:Code | f:Journal | b:Create |  
    _a:Notice Bank Account now shows:_ **&#x2713;** Step Completed!  

  - [Chart of Accounts](https://youtube.com/embed/hA6KSbR7YVI?autoplay=1&start=93&end=100&rel=0)  
    ![apps](/doc/img/apps.png) | o:Invoicing | i:ChartOfAccounts | b:Review |  
    &#x23BD;/&#x23BD;/:AccountingOverview |  
    _a:Notice Chart of Accounts now shows:_ **&#x2713;** Step Completed!  

  - [Fiscal Year](https://youtube.com/embed/hA6KSbR7YVI?autoplay=1&start=100&end=108&rel=0)   
    ![apps](/doc/img/apps.png) | o:Invoicing | i:Fiscal Year | b:Configure |  
    w:FiscalYear | f:OpeningDate &#x1F4C5; | f:FiscalYearEnd | f:Day | f:Month | b:Apply |  
    _a:Notice Fiscal Year now shows:_ **&#x2713;** Step Completed!  

  - i:NiceWork!YourConfigurationIsDone | b:Close  
    _a: You can find these setup guides also in [Accounting](/en-uk/o13/ee/inv/en-uk-o13-ee-acc-accounting-guides.md#accounting-overview--o13---ee---odoo-mates---xx-xx---0858) app_  

  - [Review new **account.move** model](https://youtube.com/embed/hA6KSbR7YVI?autoplay=1&start=108&end=144&rel=0)  
    ![apps](/doc/img/apps.png) | o:Invoicing | m:Customers | o:Invoices | _a:Select Invoice_ |  
	t:JournalItems | _a:Review Journal registers_ |  
	t:InvoiceLines | &#x1F41E; | o:EditView:Form | w:EditView:Form |  
	_a:Review f:Model is **account.move**, actually there isn't invoice model anymore_ |  
	w:EditView:Form &#x2716;  
    
  - [Create a New Invoice & Payment](https://youtube.com/embed/hA6KSbR7YVI?autoplay=1&start=148&end=218&rel=0)  
    ![apps](/doc/img/apps.png) | o:Invoicing | b:Create | f:Customer &#x2BC6; |  
	t:InvoiceLines |  
	i:AddALine | f:Product &#x2BC6; | _a:Select a Product_ |  
	i:AddASection | _a:Enter Section Text_ |  
	i:AddALine | f:Product &#x2BC6; | _a:Select a Product_ |  
	b:Save | b:Validate |  
	b:RegisterPayment | w:RegisterPayment | f:Memo | f:PaymentDate &#x1F4C5; | f:PaymentAmount |  
	f:PaymentJournal &#x2BC6; | _a:Select Journal_ |  
	b:Validate | _a:Notice green **Paid** ribbon shown on Invoice number (top-left corner)_  

  - [Review Customer's Bank & Accounting Data](https://youtube.com/embed/hA6KSbR7YVI?autoplay=1&start=247&end=270&rel=0)  
    ![apps](/doc/img/apps.png) | o:Invoicing | m:Customers | o:Customers | b:Edit | t:Invoicing |  
	f:Bank | f:AccountNumber | f:AccountReceivable | f:AccountPayble | _a:Review data | \[ b:Save \|\| b:Discard ]  
	
  - [Review Vendors' Bills & Payments](https://youtube.com/embed/hA6KSbR7YVI?autoplay=1&start=247&end=296&rel=0)  
    ![apps](/doc/img/apps.png) | o:Invoicing | m:Vendors | o:Bills | _a:Select Unposted Non-Paid Bill_ | b:Validate |  
	b:RegisterPayment | w:RegisterPayment | _a:Accept Defaults_ | b:Validate | _a:Notice green **Paid** ribbon shown on Bill number (top-left corner)_   
	
  - [Review Journal Entries](https://youtube.com/embed/hA6KSbR7YVI?autoplay=1&start=310&end=355&rel=0)  
    ![apps](/doc/img/apps.png) | o:Invoicing | m:Accounting | i:Miscellaneous | o:JournalEntries | f:Search... | ![filter](/doc/img/filter.png) _(MiscellaneousOperations)_ &#x2716; |  
    _a:Select Posted Entry_ | m:Accounting | i:Miscellaneous |
    - **Journals**
      m:Accounting | i:Journals | o:JournalItems | _a:Review Item data_ |  
      m:Accounting | i:Journals | o:Sales | _a:Review Sales data_ |  
      m:Accounting | i:Journals | o:Purchase | _a:Review Purchase data_ |  
      m:Accounting | i:Journals | o:Bank&Cash | _a:Open desired item's rows_ &#x2BC8; |  
    _a:Check other data views_ \[ ![view_list](/doc/img/view_list.png) \|\| ![view_graph](/doc/img/view_graph.png) \|\| ![view_pivot](/doc/img/view_pivot.png) \|\| ![view_kanban](/doc/img/view_kanban.png) ]
    - **Ledgers**
      m:Accounting | i:Ledgers | o:GeneralLedger | _a:Open desired account's rows_ &#x2BC8; |  
    _a:Check other data views_ \[ ![view_list](/doc/img/view_list.png) \|\| ![view_graph](/doc/img/view_graph.png) \|\| ![view_pivot](/doc/img/view_pivot.png) \|\| ![view_kanban](/doc/img/view_kanban.png) ]
      m:Accounting | i:Ledgers | o:PartnerLedger | _a:Open desired account's rows_ &#x2BC8;
    - **Actions**
      m:Accounting | i:Ledgers | o:GeneralLedger | _a:Open desired account's rows_ &#x2BC8; |  
	
	
	
	
	
   
  
[***cocacola 1:59***]: # (Odoo13 Accounting Overview)  


#### [New Widget Ribbon &nbsp;&nbsp; (O13 - EE - Odoo Mates - xx-xx - 01:26)](https://youtube.com/embed/Adg5rrfXl0Y?autoplay=1&start=0&end=71&rel=0)  
![apps](/doc/img/apps.png) | o:Invoicing | _a:Select PAID invoice_ | _a:Notice the green PAID ribbon on top right of preview_ |  
&#x23BD;/&#x23BD;/:Invoices | _a:Select NOT PAID invoice_ | _a:Notice there is no ribbon on preview_ |  
_a:Test:_  
  - b:RegisterPayment | w:RegisterPayment | _a:Verify payment fields_ | b:Validate |  
  - _a:Notice the green PAID ribbon on preview_  
  
<br>

###### Odoo Guides - v2_02 &nbsp; 2019-08-04  
**[_&#x23CE; menu_](/en-uk/o13/ee/en-uk-o13-ee-guides-menu.md)**  
