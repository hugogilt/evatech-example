# Programaciones de ejemplo

Esta carpeta contiene archivos de prueba para seleccionar desde la aplicación. Se conservan los nombres y extensiones originales para que sea evidente de qué software procede cada muestra.

Al abrir `produccion/index.html` mediante un servidor, la demo importa automáticamente las cuatro muestras compatibles y crea un abonado demo por cada una. El PDF y el `.dtlx` se conservan como documentación de formatos no importables directamente.

| Archivo | Procedencia / uso | Estado en el visor |
| --- | --- | --- |
| `vickyfoods2.xml` | XML de programación | Compatible como XML |
| `risco.bcx` | Backup/exportación Risco | Se detecta y se normaliza si tiene la estructura esperada |
| `paradox.txt` | Informe de texto Paradox | Se convierte a una vista común |
| `Panel2026.9.23_19.14.html` | Informe HTML ATS8500 | Se detecta y se convierte a una vista común |
| `paradox.pdf` | Copia documental del informe | Referencia; no es entrada del importador |
| `cessna programacioj.dtlx` | Archivo propietario de programación | Referencia; no se interpreta directamente |

## Importante

La aplicación puede mostrar configuración importada, pero eso no significa que el archivo cambie la central ni que informe de estado en tiempo real. Los formatos propietarios necesitan el software de origen o un exportador compatible.
