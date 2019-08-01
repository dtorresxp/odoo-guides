# O13 - EE - PYR - Nómina &nbsp;&nbsp;&nbsp;&nbsp; [![en-uk](/doc/img/en-uk_flag_button_small.png)](/en-uk/o13/ee/pyr/en-uk-o13-ee-pyr-payroll-guides.md) [ ![es-mx](/doc/img/es-mx_flag_button_small.png)](/es-mx/o13/ee/pyr/es-mx-o13-ee-pyr-payroll-guides.md)
#### [_&#x23CE; menu_](/es-mx/o13/ee/es-mx-o13-ee-guides-menu.md)  
### ![pyr](/doc/img/hr_payroll.png)

#### [La app de Nómina se ha eliminado de la Edición de la Comunidad &nbsp;&nbsp; (O13 - CE - Odoo Mates - xx-xx - 01:24 - Nómina eliminada de Ed. Comunidad)](https://youtube.com/embed/ssrMiPrdbQQ?autoplay=1&start=0&end=0&rel=0)  
![apps](/doc/img/apps.png) | o:Apps | _a:There is no more HR Payroll app on CE_

#### [Nómina &nbsp;&nbsp; (O13 - EE - Odoo Mates - xx-xx - 03:53)](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=0&end=0&rel=0&nocount)  

- [Configuración](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=1m52s&end=2m14s&rel=0)  
  ![apps](/doc/img/apps.png) | o:Payroll | m:Configuración  
  - o:WorkEntradaTipos  
  - o:StructureTipos | f:StructureTipo | f:Country | f:DefaultScheduledPay | f:DefaultWorkingHours | f:DefaultWorkEntradaTipo  
  - o:Structures | f:Name | f:SalaryRules | f:Country | f:RegularPay  
  - o:Rules | f:Name | f:Code | f:Category | f:Partner  
  - o:RuleParameters | f:Name | f:Code  
  - o:OtherInputTipos | f:Descripción | f:Code | f:AvailabilityInStructure  
  
- [Configurar los Roles de Usuarios de Nómina](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=3m19s&end=3m38s&rel=0)  
  ![apps](/doc/img/apps.png) | o:Configuración | m:Users&Companies | o:Users  
  _a:Seleccionar User_ | t:AccessRights | _a:Scroll down to i:HumanResources | f:Payroll &#x25BC; | \[ Ninguno || Administrator || Officer ]  
  
- [Contratos](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=0&end=1m14s&rel=0)  
  - ![apps](/doc/img/apps.png) | o:Payroll | m:Empleados | o:Contracts | _a:Seleccionar Contract_ | b:Editar  
  - f:Empleado | f:Department | f:Company | f:SalaryStructureTipo | f:ContractTipo | f:JobPosition | f:ContractTemplate  
  - t:AdjuntoOfSalary | i:Accounting  
    - t:ContractDetails | i:Contract Terms | f:IniciarDate | f:EndDate | f:EndOfTrialPeriod | f:HRResponsible  
      f:NewContractDocumentTempalte | ContractUpdateDocumentTemplate | f:Notes  
      f:WorkSchedule ![show_catalog](/doc/img/show_catalog.png) | w:Abrir:WorkingSchedule | t:WorkingHours | t:GlobalTimeOff | _a:Cerrar window_ &#x2716;  
    - t:SalaryInformation | i:MonthlyAdvantagesInCash | i:EmpleadoCosts | i:MonthlyBenefitInKind | i:YearlyAdvantages  
    - t:PersonalDocumentos | f:IdCardCopy | f:Photo | f:DrivingLicense  
    - t:AdjuntoOfSalary | f:Descripción | f:GarnishedTipo | f:From | f:To | f:Amount  
  - b:Guardar  

- [Asistencias](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=1m15s&end=1m34s&rel=0)  
  ![apps](/doc/img/apps.png) | o:Payroll | m:WorkEntries | o:WorkEntries  
  b:Prev &#x1F870; | b:Today | &#x1F872; b:Next | b:Day | b:Week | b:Month | b:Generate Payslips  
  b:VerGrid | b:VerCalendar | b:VerList | b:VerPivot  
  
- [Incidencias](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=1m35s&end=1m45s&rel=0)  
  ![apps](/doc/img/apps.png) | o:Payroll | m:WorkEntries | o:Conflicts  
  b:Measures | &#x21C4; b:Pivot_FlipAxis | &#x2725; b:Pivot_ExpandAll | **&#x2B73;** b:Pivot_DownloadXLS  
  
- [Menú de Recibos](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=2m43s&end=2m48s&rel=0)  
  ![apps](/doc/img/apps.png) | o:Payroll | m:Payslips  
  - o:ToPay | b:Crear | b:Import | b:Print  
    f:Reference | f:Empleado | f:BatchName | f:From | f:To | f:BasicWage | f:NetWageStatus | f:Company  
  - o:All Payslips | b:Crear | b:Import | b:Print  
    f:Reference | f:Empleado | f:BatchName | f:From | f:To | f:BasicWage | f:NetWageStatus | f:Company  
  - o:Batches | b:Crear | b:Import | f:Name | f:DateFrom | f:DateTo | f:CreditNote | f:Status | f:Company  

- [Recibos](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=1m45s&end=1m52s&rel=0)  
  ![apps](/doc/img/apps.png) | o:Payroll | m:WorkEntries | o:ToPay  
  _a:Seleccionar Empleado_ | _a:Revisar Payslip_  
  b:ComputeSheet | b:CancelPayslip | b:Print  
  
- [Generar Recibos](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=2m49&end=3m16s&rel=0)  
  ![apps](/doc/img/apps.png) | o:Payroll | m:WorkEntries | o:WorkEntries  
  _a:Seleccionar Payroll period_ | b:Week | b:GeneratePayslips  
  b:CrearDraftEntrada | s:Payslips | _a:Seleccionar Payslip_  
  _a:Revisar Payslip_ | t:WorkedDays&Inputs | t:SalaryComputation | t:AccountInformation | t:ReimbursmentOfExpenses  
  \[ b:CancelPayslip | b:Print ]  
  
- [Reportes de Nómina](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=2m15s&end=2m43s&rel=0)  
  ![apps](/doc/img/apps.png) | o:Payroll | m:Reporting  
  - o:Payroll | b:VerDashboard | b:VerPivot | b:VerGráfica  
  - o:PaidTimeOffAllocation | w:PaidTimeOffAllocation | i:ReferencePeriod | f:From | f:To | f:StructureTipo  
    f:Empleado | f:WorkedDays | f:PaidTimeOff | f:TimeOffTipo | \[ b:GenerateTimeOffAllocations || b:Discard ]  
  - o:MealVouchers | b:Measures | &#x21C4; b:Pivot_FlipAxis | &#x2725; b:Pivot_ExpandAll | **&#x2B73;** b:Pivot_DownloadXLS  
  - o:AdjuntoOfSalary | b:Measures | b: &#x21C4; | b:&#x2725; | **&#x2B73;**  
  - o:DMFA | b:Crear | b:Import | f:Reference | f:Year | f:Quarter | f:ValidarState  
 
<br>
	
###### Guías Odoo - V2_01 &nbsp; 2019-07-31  
**[_&#x23CE; menu_](/es-mx/o13/ee/es-mx-o13-ee-guides-menu.md)**  
