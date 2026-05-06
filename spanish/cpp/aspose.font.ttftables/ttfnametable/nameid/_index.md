---
title: "Aspose::Font::TtfTables::TtfNameTable::NameId enumeración"
linktitle: "NameId"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::TtfTables::TtfNameTable::NameId enumeración. Representa NameId en C++."
type: docs
weight: 1600
url: /es/cpp/aspose.font.ttftables/ttfnametable/nameid/
---
## NameId enum


Representa [NameId](./).

```cpp
enum class NameId : uint16_t
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| CopyrightNotice | 0 | 0 Aviso de copyright. |
| FontFamily | 1 | 1 [Font](../../../aspose.font/font/) Familia. Esta cadena es el nombre de familia del [Font](../../../aspose.font/font/) que el usuario ve en plataformas Macintosh. |
| FontSubfamily | 2 | 2 [Font](../../../aspose.font/font/) Subfamilia. Esta cadena es la subfamilia del [Font](../../../aspose.font/font/) que el usuario ve en plataformas Macintosh. |
| UniqueFontId | 3 | 3 Identificación única de subfamilia (especificación Apple). 3 Identificador único de [Font](../../../aspose.font/font/) (especificación MS). |
| FullName | 4 | 4 Nombre completo del [Font](../../../aspose.font/font/). |
| Versión | 5 | 5 Versión de la tabla de nombres. |
| PostScriptName | 6 | 6 Nombre PostScript del [Font](../../../aspose.font/font/). Nota: Un [Font](../../../aspose.font/font/) puede tener solo un nombre PostScript y ese nombre debe ser ASCII. |
| TrademarkNotice | 7 | 7 Aviso de marca registrada. |
| ManufacturerName | 8 | 8 Nombre del fabricante. |
| DesignerName | 9 | 9 Diseñador; nombre del diseñador del tipo de letra. |
| Descripción | 10 | 10 Descripción; descripción del tipo de letra. Puede contener información de revisión, recomendaciones de uso, historia, características, etc. |
| UrlVendor | 11 | 11 URL del [Font](../../../aspose.font/font/) del proveedor (con protocolo, p.ej., [http://](http://), [ftp://](ftp://)). Si un número de serie único está incrustado en la URL, puede usarse para registrar el [Font](../../../aspose.font/font/). |
| UrlDesigner | 12 | 12 URL del [Font](../../../aspose.font/font/) del diseñador (con protocolo, p.ej., [http://](http://), [ftp://](ftp://)) |
| LicenseDescription | 13 | 13 descripción del [License](../../../aspose.font/license/); descripción de cómo el [Font](../../../aspose.font/font/) puede usarse legalmente, o diferentes escenarios de ejemplo para uso con licencia. Este campo debe escribirse en lenguaje claro, no en jerga legal. |
| LicenseInfoUrl | 14 | 14 URL de información del [License](../../../aspose.font/license/), donde se puede encontrar información adicional de licencias. |
| PreferredFamily | 16 | 15 Reservado 16 Familia Preferida (solo Windows); En Windows, el nombre de la familia se muestra en el menú del [Font](../../../aspose.font/font/); el nombre de la subfamilia se presenta como el nombre de estilo. Por razones históricas, las familias de [Font](../../../aspose.font/font/) han contenido un máximo de cuatro estilos, pero los diseñadores de [Font](../../../aspose.font/font/) pueden agrupar más de cuatro fuentes en una sola familia. Los IDs de Familia Preferida y Subfamilia Preferida permiten a los diseñadores de [Font](../../../aspose.font/font/) incluir los agrupamientos de familia/subfamilia preferidos. Estos IDs solo están presentes si difieren de los IDs 1 y 2. |
| PreferredSubfamily | 17 | 17 Subfamilia Preferida (solo Windows); En Windows, el nombre de la familia se muestra en el menú del [Font](../../../aspose.font/font/); el nombre de la subfamilia se presenta como el nombre de estilo. Por razones históricas, las familias de [Font](../../../aspose.font/font/) han contenido un máximo de cuatro estilos, pero los diseñadores de [Font](../../../aspose.font/font/) pueden agrupar más de cuatro fuentes en una sola familia. Los IDs de Familia Preferida y Subfamilia Preferida permiten a los diseñadores de [Font](../../../aspose.font/font/) incluir los agrupamientos de familia/subfamilia preferidos. Estos IDs solo están presentes si difieren de los IDs 1 y 2. |
| CompatibleFull | 18 | 18 Compatible Full (solo Macintosh); En Macintosh, el nombre del menú se construye usando el recurso del [Font](../../../aspose.font/font/). Esto usualmente coincide con el Nombre Completo. Si desea que el nombre del [Font](../../../aspose.font/font/) aparezca diferente al Nombre Completo, puede insertar el Nombre Compatible Completo en el ID 18. Este nombre no lo usa el propio Mac OS, pero puede ser usado por desarrolladores de aplicaciones (p.ej., Adobe). |
| SampleText | 19 | 19 Texto de muestra. Esto puede ser el nombre del [Font](../../../aspose.font/font/), o cualquier otro texto que el diseñador considere la mejor muestra para mostrar cómo se ve el [Font](../../../aspose.font/font/). |
| PostScriptCID | 20 | Su presencia en una fuente significa que el nameID 6 contiene un nombre de fuente PostScript que está destinado a usarse con la invocación “composefont” para invocar la fuente en un intérprete PostScript. |
| WwsFamilyName | 21 | Utilizado para proporcionar un nombre de familia conforme a WWS en caso de que las entradas de los IDs 16 y 17 no cumplan con el modelo WWS. |
| WwsSubfamilyName | 22 | Utilizado junto con el ID 21, este ID proporciona un nombre de subfamilia conforme a WWS (reflejando solo atributos de peso, ancho y pendiente) en caso de que las entradas de los IDs 16 y 17 no cumplan con el modelo WWS. |
| LightBackground | 23 | Este ID, si se usa en la Matriz de Etiquetas de Paleta de la tabla CPAL, especifica que la paleta de colores correspondiente en la tabla CPAL es adecuada para usar con la fuente al mostrarla sobre un fondo claro como blanco. |
| DarkBackground | 24 | Este ID, si se usa en la Matriz de Etiquetas de Paleta de la tabla CPAL, especifica que la paleta de colores correspondiente en la tabla CPAL es adecuada para usar con la fuente al mostrarla sobre un fondo oscuro como negro. |
| VariationsPostScriptNamePrefix | 25 | Si está presente en una fuente variable, puede usarse como prefijo de familia en el algoritmo de Generación de Nombre PostScript para Fuentes de Variación. |

## Ver también

* Class [TtfNameTable](../)
* Namespace [Aspose::Font::TtfTables](../../)
* Library [Aspose.Font for C++](../../../)
