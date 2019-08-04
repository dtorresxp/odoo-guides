# O13 - EE - PYR - Nómina &nbsp;&nbsp;&nbsp;&nbsp; [![en-uk](/doc/img/en-uk_flag_button_small.png)](/en-uk/o13/ee/pyr/en-uk-o13-ee-pyr-payroll-guides.md) [ ![es-mx](/doc/img/es-mx_flag_button_small.png)](/es-mx/o13/ee/pyr/es-mx-o13-ee-pyr-payroll-guides.md)
#### [_&#x23CE; menu_](/es-mx/o13/ee/es-mx-o13-ee-guides-menu.md)  
### ![pyr](/doc/img/hr_payroll.png)

#### [La app de Nómina se ha eliminado de la Edición de la Comunidad &nbsp;&nbsp; (O13 - CE - Odoo Mates - xx-xx - 01:24)](https://youtube.com/embed/ssrMiPrdbQQ?autoplay=1&start=0&end=0&rel=0)  
[***Sync***]: # (es-mx-o13-ce-pyr-payroll-guides)  
![apps](/doc/img/apps.png) | o:Apps | _a:Ya no aparece la app de Nómina en CE_

#### [Nómina &nbsp;&nbsp; (O13 - EE - Odoo Mates - xx-xx - 03:53)](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=0&end=0&rel=0&nocount)  

- [Configuración](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=112&end=134&rel=0)  
  ![apps](/doc/img/apps.png) | o:Nómina | m:Configuración |  
  - o:TiposDeTrabajoDeNuevoIngreso |  
  - o:TiposDeEstructura | f:TipoDeEstructura | f:País |  
    f:DefaultPagoProgramado | f:DefaultHorasTrabajadas | f:DefaultTipoDeTrabajoDeNuevoIngreso |  
  - o:Estructuras | f:Nombre | f:ReglasDeSalario | f:País | f:PagoNormal |  
  - o:Reglas | f:Nombre | f:Código | f:Categoría | f:Distribuidor |  
  - o:RuleParámetros | f:Nombre | f:Código |  
  - o:OtrosTiposDeIngreso | f:Descripción | f:Código | f:DisponibilidadEnEstructura  
  
- [Configurar los Roles de Usuarios de Nómina](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=199&end=218&rel=0)  
  ![apps](/doc/img/apps.png) | o:Configuración | m:Usuarios&Companies | o:Usuarios |  
  _a:Seleccionar Usuario_ | t:DerechosDeAcceso | _a:Desplazar hacia abajo hasta i:RecursosHumanos | f:Nómina &#x2BC6; | \[ Ninguno || Administrador || Oficial ]  
  
- [Contratos](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=0&end=74&rel=0)  
  - ![apps](/doc/img/apps.png) | o:Nómina | m:Empleados | o:Contratos | _a:Seleccionar Contrato_ | b:Editar |  
  - f:Empleado | f:Departmento | f:Compañía | f:SalarioTipoDeEstructura | f:ContratoTipo | f:PuestoDeTrabajo | f:PlantillaDeContrato |  
  - t:AdjuntoDeSalario | i:Contabilidad |  
    - t:DetallesDelContrato | i:TérminosDelContrato | f:FechaDeInicio | f:FechaDeFin | f:FinDePeriodoDePrueba | f:ResponsibleDeRRHH |  
      f:PlantillaDeNuevoContrato | PlantillaParaActualizarContrato | f:Notas |  
      f:HorarioDeTrabajo ![show_catalog](/doc/img/show_catalog.png) | w:Abrir:HorarioDeTrabajo | t:HorasTrabajadas | t:DefaultDeTiempoGlobal | _a:Cerrar ventana_ &#x2716; |  
    - t:InformaciónDeSalario | i:BonosMensualesEnDinero | i:CostoDelEmpleado | i:BeneficiosMensualesEnEspecie | i:BeneficiosAnuales |  
    - t:DocumentosPersonales | f:CopiaDeIdentificaciónOficial | f:Foto | f:LicenciaDeManejo |  
    - t:EmbargosAlSalario | f:Descripción | f:TipoDeDeducción | f:De | f:A | f:Monto |  
  - b:Guardar  

- [Asistencias](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=75&end=94&rel=0)  
  ![apps](/doc/img/apps.png) | o:Nómina | m:RegistroDeEntradas | o:RegistroDeEntradas |  
  b:Previo &#x1F870; | b:Hoy | &#x1F872; b:Siguiente | b:Día | b:Semana | b:Mes | b:GenerarRecibos |  
  b:VerMalla | b:VerCalendario | b:VerLista | b:VerTablaDinámica  
  
- [Incidencias](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=95&end=105&rel=0)  
  ![apps](/doc/img/apps.png) | o:Nómina | m:RegistroDeEntradas | o:Incidencias |  
  b:Medidas | &#x21C4; b:TablaDinámica_RotarEjes | &#x2725; b:TablaDinámica_ExpandirTodo | **&#x2B73;** b:TablaDinámica_DescargarXLS  
  
- [Menú de Recibos](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=223&end=228&rel=0)  
  ![apps](/doc/img/apps.png) | o:Nómina | m:Recibos |  
  - o:APagar | b:Crear | b:Importar | b:Imprimir |  
    f:Referencia | f:Empleado | f:NombreDelLote | f:De | f:A | f:IngresoBásico | f:StatusDeIngresoNeto | f:Compañía |  
  - o:All Recibos | b:Crear | b:Importar | b:Imprimir |  
    f:Referencia | f:Empleado | f:NombreDelLote | f:De | f:A | f:IngresoBásico | f:StatusDeIngresoNeto | f:Compañía |  
  - o:Lotes | b:Crear | b:Importar | f:Nombre | f:FechaDe | f:FechaA | f:NotaDeCrédito | f:Status | f:Compañía

- [Recibos](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=105&end=112&rel=0)  
  ![apps](/doc/img/apps.png) | o:Nómina | m:RegistroDeEntradas | o:APagar |  
  _a:Seleccionar Empleado_ | _a:Revisar Recibo_ |  
  b:CalcularHoja | b:CancelarRecibo | b:Imprimir  
  
- [Generar Recibos](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=169&end=196&rel=0)  
  ![apps](/doc/img/apps.png) | o:Nómina | m:RegistroDeEntradas | o:RegistroDeEntradas |  
  _a:Seleccionar periodo de Nómina_ | b:Semana | b:GenerarRecibos |  
  b:CrearPrevioDeEntrada | s:Recibos | _a:Seleccionar Recibo_ |  
  _a:Revisar Recibo_ | t:DíasEIngresosTrabajados | t:CálculoSalario | t:InformaciónDeLaCuenta | t:ReembolsoDeGastos |  
  \[ b:CancelarRecibo | b:Imprimir ]  
  
- [Reportes de Nómina](https://youtube.com/embed/AOuV7cD0PE0?autoplay=1&start=135&end=223&rel=0)  
  ![apps](/doc/img/apps.png) | o:Nómina | m:Reporting |  
  - o:Nómina | b:VerTablero | b:VerTablaDinámica | b:VerGráfica |  
  - o:AsignaciónDePermisosConGoceDeSueldo | w:AsignaciónDePermisosConGoceDeSueldo | i:PeriodoDeReferencia | f:De | f:A | f:TipoDeEstructura |  
    f:Empleado | f:WorkedDías | f:PermisosPagados | f:TipoDePermiso | \[ b:GenerarAsignacionesDePermisos || b:Descartar ] |  
  - o:ValesDeComida | b:Medidas | &#x21C4; b:TablaDinámica_RotarEjes | &#x2725; b:TablaDinámica_ExpandirTodo | **&#x2B73;** b:TablaDinámica_DescargarXLS |  
  - o:AdjuntoDeSalario | b:Medidas | b: &#x21C4; | b:&#x2725; | **&#x2B73;** |  
  - o:DMFA | b:Crear | b:Importar | f:Referencia | f:Año | f:Trimestre | f:ValidarEstado
 
<br>
	
###### Guías Odoo - V2_01 &nbsp; 2019-08-01  
**[_&#x23CE; menu_](/es-mx/o13/ee/es-mx-o13-ee-guides-menu.md)**  
