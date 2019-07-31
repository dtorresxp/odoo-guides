## O13 - EE - PYR - Payroll (Nómina)
#### [_&#x23CE; menu_](/o13/ee/o13-ee-guides_menu.md)  
### ![pyr](/doc/img/hr_payroll.png)

#### [HR Payroll (O13 - EE - Odoo Mates - n/v - 03:53 - Nómina)](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=0&end=0&rel=0&nocount)  

- [Settings (Configuración)](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=1m52s&end=2m14s&rel=0)  
  ![apps](/doc/img/apps.png) | o:Payroll | m:Settings  
  - o:WorkEntryTypes  
  - o:StructureTypes | f:StructureType | f:Country | f:DefaultScheduledPay | f:DefaultWorkingHours | f:DefaultWorkEntryType  
  - o:Structures | f:Name | f:SalaryRules | f:Country | f:RegularPay  
  - o:Rules | f:Name | f:Code | f:Category | f:Partner  
  - o:RuleParameters | f:Name | f:Code  
  - o:OtherInputTypes | f:Description | f:Code | f:AvailabilityInStructure  
  
- [Configure Payroll User Rol (Configurar rol del Usuario en Nómina)](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=3m19s&end=3m38s&rel=0)  
  ![apps](/doc/img/apps.png) | o:Settings | m:Users&Companies | o:Users  
  _a:Select User_ | t:AccessRights | _a:Scroll down to i:HumanResources | f:Payroll &#x25BC; | \[ None || Administrator || Officer ]  
  
- [Contracts (Contratos)](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=0&end=1m14s&rel=0)  
  - ![apps](/doc/img/apps.png) | o:Payroll | m:Employees | o:Contracts | _a:Select Contract_ | b:Edit  
  - f:Employee | f:Department | f:Company | f:SalaryStructureType | f:ContractType | f:JobPosition | f:ContractTemplate  
  - t:AttachmentOfSalary | i:Accounting  
    - t:ContractDetails | i:Contract Terms | f:StartDate | f:EndDate | f:EndOfTrialPeriod | f:HRResponsible  
      f:NewContractDocumentTempalte | ContractUpdateDocumentTemplate | f:Notes  
      f:WorkSchedule ![show_catalog](/doc/img/show_catalog.png) | w:Open:WorkingSchedule | t:WorkingHours | t:GlobalTimeOff | _a:Close window_ &#x2716;  
    - t:SalaryInformation | i:MonthlyAdvantagesInCash | i:EmployeeCosts | i:MonthlyBenefitInKind | i:YearlyAdvantages  
    - t:PersonalDocuments | f:IdCardCopy | f:Photo | f:DrivingLicense  
    - t:AttachmentOfSalary | f:Description | f:GarnishedType | f:From | f:To | f:Amount  
  - b:Save  

- [Work Entries (Asistencias)](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=1m15s&end=1m34s&rel=0)  
  ![apps](/doc/img/apps.png) | o:Payroll | m:WorkEntries | o:WorkEntries  
  b:Prev &#x1F870; | b:Today | &#x1F872; b:Next | b:Day | b:Week | b:Month | b:Generate Payslips  
  b:ViewGrid | b:ViewCalendar | b:ViewList | b:ViewPivot  
  
- [Conflicts (Incidencias)](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=1m35s&end=1m45s&rel=0)  
  ![apps](/doc/img/apps.png) | o:Payroll | m:WorkEntries | o:Conflicts  
  b:Measures | &#x21C4; b:Pivot_FlipAxis | &#x2725; b:Pivot_ExpandAll | **&#x2B73;** b:Pivot_DownloadXLS  
  
- [Payslips Menu (Menú de Recibos)](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=2m43s&end=2m48s&rel=0)  
  ![apps](/doc/img/apps.png) | o:Payroll | m:Payslips  
  - o:ToPay | b:Create | b:Import | b:Print  
    f:Reference | f:Employee | f:BatchName | f:From | f:To | f:BasicWage | f:NetWageStatus | f:Company  
  - o:All Payslips | b:Create | b:Import | b:Print  
    f:Reference | f:Employee | f:BatchName | f:From | f:To | f:BasicWage | f:NetWageStatus | f:Company  
  - o:Batches | b:Create | b:Import | f:Name | f:DateFrom | f:DateTo | f:CreditNote | f:Status | f:Company  

- [Payslips (Recibos)](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=1m45s&end=1m52s&rel=0)  
  ![apps](/doc/img/apps.png) | o:Payroll | m:WorkEntries | o:ToPay  
  _a:Select Employee_ | _a:Review Payslip_  
  b:ComputeSheet | b:CancelPayslip | b:Print  
  
- [Generate Payslips (Generar Recibos)](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=2m49&end=3m16s&rel=0)  
  ![apps](/doc/img/apps.png) | o:Payroll | m:WorkEntries | o:WorkEntries  
  _a:Select Payroll period_ | b:Week | b:GeneratePayslips  
  b:CreateDraftEntry | s:Payslips | _a:Select Payslip_  
  _a:Review Payslip_ | t:WorkedDays&Inputs | t:SalaryComputation | t:AccountInformation | t:ReimbursmentOfExpenses  
  \[ b:CancelPayslip | b:Print ]  
  
- [Reporting (Reportes)](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=2m15s&end=2m43s&rel=0)  
  ![apps](/doc/img/apps.png) | o:Payroll | m:Reporting  
  - o:Payroll | b:ViewDashboard | b:ViewPivot | b:ViewGraph  
  - o:PaidTimeOffAllocation | w:PaidTimeOffAllocation | i:ReferencePeriod | f:From | f:To | f:StructureType  
    f:Employee | f:WorkedDays | f:PaidTimeOff | f:TimeOffType | \[ b:GenerateTimeOffAllocations || b:Discard ]  
  - o:MealVouchers | b:Measures | &#x21C4; b:Pivot_FlipAxis | &#x2725; b:Pivot_ExpandAll | **&#x2B73;** b:Pivot_DownloadXLS  
  - o:AttachmentOfSalary | b:Measures | b: &#x21C4; | b:&#x2725; | **&#x2B73;**  
  - o:DMFA | b:Create | b:Import | f:Reference | f:Year | f:Quarter | f:ValidationState  
 
<br>
	
###### Odoo Guides - v1_01 &nbsp; 2019-07-31  [_&#x23CE; menu_](/o13/ee/o13-ee-guides_menu.md)  
