# Programaciones de ejemplo

Esta carpeta contiene archivos de prueba para seleccionar desde la aplicación. Se conservan los nombres y extensiones originales para que sea evidente de qué software procede cada muestra.

Al abrir `produccion/index.html` mediante un servidor, la demo importa automáticamente las cuatro muestras compatibles y crea un abonado demo por cada una. El `.dtlx` se conserva como documentación de un formato no importable directamente. El PDF original se ha excluido de la entrega pública porque no se puede anonimizar de forma segura editándolo como texto.

| Archivo | Procedencia / uso | Estado en el visor |
| --- | --- | --- |
| `cliente-1.xml` | XML de programación | Compatible como XML |
| `cliente-2.bcx` | Backup/exportación Risco | Se detecta y se normaliza si tiene la estructura esperada |
| `cliente-3.txt` | Informe de texto Paradox | Se convierte a una vista común |
| `cliente-4.html` | Informe HTML ATS8500 | Se detecta y se convierte a una vista común |
| `cliente-5.dtlx` | Archivo propietario de programación | Referencia; no se interpreta directamente |

## Importante

La aplicación puede mostrar configuración importada, pero eso no significa que el archivo cambie la central ni que informe de estado en tiempo real. Los formatos propietarios necesitan el software de origen o un exportador compatible.
