# iRAM/1088 - Expansión de RAM interna para Amstrad CPC 6128 (actualización a 1088K)
Licencia
La expansión y todos los recursos son de uso gratuito para uso personal.

Se publica bajo la misma licencia que el proyecto iRAM/640. El precio para ofertas comerciales puede ajustarse para incluir los dos SRAM, pero no debe superar un aumento del 20% en comparación con los precios permitidos para iRAM/640.

Diferencias con iRAM/640
Proporciona un total de 1088K de RAM (64K de RAM base + 1024 SRAM).

El segundo banco de 64K de RAM del 6128 no se utiliza.

Las diferencias de hardware son mínimas:

Usa 2 SRAM SMD AS6C4008 SOP32 (en lugar de 1 SRAM DIP).

Un condensador de 100nF adicional.

Construcción del iRAM/1088
Consigue la PCB en PCBWay aquí: https://www.pcbway.com/project/shareproject/CPC_iRAM_1088_1MB_internal_RAM_expansion_for_the_Amstrad_CPC_6128_ce7298f2.html

O usa los archivos gerber de la PCB que se encuentran en la carpeta files de este proyecto.

Archivos de programación CPLD: descarga los archivos JED de la carpeta files del proyecto iRAM/640. Esos archivos JED ya contienen la lógica necesaria para direccionar 1088MB.

Por lo demás, consulta las instrucciones de construcción del iRAM/640. El proceso es casi idéntico, excepto por dos pasos:

El segundo SRAM debe soldarse en la parte inferior de la PCB.

Asegúrate de cerrar el puente de 1MB en la parte inferior de la PCB.

Opción de 576K
Es posible usar solo un SRAM, lo que te dará un total de 576K de RAM. Para ello:

Solda un SRAM en la parte superior de la PCB y deja el espacio en la parte inferior vacío.

No cierres el puente de 1MB en la parte inferior.

En su lugar, añade la resistencia de 10K (una de 4.7K también sirve) a su lado.
