# O13 - EE - CRM - Customer Relationships Management &nbsp;&nbsp;&nbsp;&nbsp; [![en-uk](/doc/img/flg/en-uk-flg-btn-sml.png)](/en-uk/o13/ee/crm/en-uk-o13-ee-crm-guides.md) [ ![es-mx](/doc/img/flg/es-mx-flg-btn-sml.png)](/es-mx/o13/ee/crm/es-mx-o13-ee-crm-guides.md)
#### [_&#x23CE; menu_](/en-uk/o13/ee/en-uk-o13-ee-guides-menu.md "Back to EE menu")  
### ![crm](/doc/img/app/big/crm.png)
[ⱽ¹²³⁴⁵⁶⁷⁸⁹⁰⁻]: # (ⱽ¹²³⁴⁵⁶⁷⁸⁹⁰⁻)

#### [Lead generation through IAP Service (O13 - EE - PinakinNayi - xx-in - 03:22)](https://youtube.com/embed/4xbXk5flAds?autoplay=1&start=0&end=0&rel=0)  
- ###### Configuring IAP for Leads generation
  ![apps](/doc/img/apps.png) | o:CRM | m:Configuration | o:Settings |  
  _a:Verify_ f:WebsiteLeadGeneration _is enabled_ | _a:Review_ i:CheckingRemainingCredit |  
  _a:If you've remaining credits continue, otherwise goto &#x1F872; i:BuyMoreCredits |  
  _a:Notice the number of remaining credits in your account_ |  
  m:Configuration | o:LeadGenerationRules | b:Create | f:RuleName | f:DataTracking &#x25C9; o:Companies+Contacts |  
  &nbsp;**&#x26AC;**&nbsp;&nbsp; i:WebsiteTrafficConditions |  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; f:Countries | _a:Add (India) (United States) (Belgium) for test_ |  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; f:URLExpressions | f:Sequence | _a:Type **1**_ |  
  &nbsp;**&#x26AC;**&nbsp;&nbsp; i:OpportunityGenerationConditions | f:IndustryTags | f:MinCompanySize | f:MaxCompanySize |  
  &nbsp;**&#x26AC;**&nbsp;&nbsp; i:ContactFilter | f:PreferredRole | f:Seniority | f:ExtraContacts | _a:Type **2**_ |  
  &nbsp;**&#x26AC;**&nbsp;&nbsp; i:OpportunityData | f:SalesChannel | f:Salesperson| f:Tags | f:Priority | f:Suffix | _a:Enter **Website**_ |  
  d:Credits:  
  &nbsp;&nbsp; No credit is consumed if the company is not found.  
  &nbsp;&nbsp; 1 credit is consumed if the company is found.  
  &nbsp;&nbsp; 2 credits are consumed if the company matches the rule.  
  &nbsp;&nbsp; _a:Notice after increasing extra Contacts to 2,_  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _consumed credits step up to **4** whenever a_  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _company matches the rule._  
  b:Save  
- ###### Test Leads generation from Website visits  
  _a:Start your Internet Browser_ | _a:Enter your website address_ | _a:Return to Odoo window_ |  
  ![apps](/doc/img/apps.png) | o:Settings | i:ActivateTheDeveloperMode | _a:Type **sched** to enter Scheduler_ | i:ScheduledActions |  
  _a:Click on_ f:ActionName _**Lead Generation: Leads/Opportunities Generation**_ | b:RunMannually |  
  ![apps](/doc/img/apps.png) | o:CRM | f:Search... _(MyPipeline)_ &#x2716; |  
  _a:Notice on **New** now there is a new **Odoo-Website** Lead_ | _a:Click on_ i:Odoo-Website |  
  _a:Review_ t:InternalNotes | _a:Scroll down the page_ | _Review the new Opportunity created by Odoo Lead Generation_ |  
  m:Reporting | o:LeadGenerationViews | m:Configuration | o:LeadGenerationRules |  
  _a:Click on_ f:RuleName _**AllVisitors**_ | s:Opportunities | m:Configuration | o:Settings |  
  _a:Notice now there is on less credit remaining in your account because of last Lead Generation_  
    ⱽ¹⁻⁰¹ &nbsp;²⁰¹⁹⁻⁰⁸⁻¹²

<br>

###### Odoo Guides - V2_03 &nbsp; 2019-08-12  
**[_&#x23CE; menu_](/en-uk/o13/ee/en-uk-o13-ee-guides-menu.md)**  


