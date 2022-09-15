---
title: CffFont
second_title: Referencia de la API de Aspose.Font para .NET
description: Representa formato de fuente compacto CFF.
type: docs
weight: 30
url: /es/net/aspose.font.cff/cfffont/
---
## CffFont class

Representa formato de fuente compacto (CFF).

```csharp
public class CffFont : Font
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [Encoding](../../aspose.font.cff/cfffont/encoding) { get; } | Obtiene la codificación de fuentes. |
| override [FontDefinition](../../aspose.font.cff/cfffont/fontdefinition) { get; } | Obtiene definición de fuente. |
| override [FontFamily](../../aspose.font.cff/cfffont/fontfamily) { get; set; } | Obtiene la familia de fuentes. El configurador de la familia de fuentes aún no está implementado. |
| override [FontName](../../aspose.font.cff/cfffont/fontname) { get; set; } | Obtiene el nombre de la cara de la fuente. El configurador del nombre de la cara de la fuente aún no está implementado. |
| override [FontNames](../../aspose.font.cff/cfffont/fontnames) { get; } | Obtener nombres de fuentes. |
| [FontSaver](../../aspose.font/font/fontsaver) { get; } | Obtiene la función de guardar fuentes. |
| override [FontStyle](../../aspose.font.cff/cfffont/fontstyle) { get; } | Obtiene el estilo de fuente. Este es un valor calculado y representado en tipo generalizado. |
| override [FontType](../../aspose.font.cff/cfffont/fonttype) { get; } | Obtiene Tipo de fuente. Devuelve Tipo de fuente.Valor CFF. |
| [GlyphAccessor](../../aspose.font/font/glyphaccessor) { get; } | Accesorio de glifo de fuente. Recupera glifos e identificadores de glifos. |
| override [GlyphIdType](../../aspose.font.cff/cfffont/glyphidtype) { get; } | Obtiene la especificación del tipo de ID de glifo. |
| [IsCidKeyedFont](../../aspose.font.cff/cfffont/iscidkeyedfont) { get; } | Obtiene el valor que indica que la fuente tiene clave cid. |
| override [Metrics](../../aspose.font.cff/cfffont/metrics) { get; } | Obtiene métricas de fuentes. |
| override [NumGlyphs](../../aspose.font.cff/cfffont/numglyphs) { get; } | Obtiene el número de glifos en la Fuente. |
| override [PostscriptNames](../../aspose.font.cff/cfffont/postscriptnames) { get; } | Obtiene nombres de fuentes postscript. |
| override [Style](../../aspose.font.cff/cfffont/style) { get; set; } | Obtiene el estilo de fuente. Este es un valor de cadena sin procesar proporcionado por el archivo de fuente. El configurador de estilo aún no está implementado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Convert](../../aspose.font.cff/cfffont/convert)(FontType) | Convierte la Fuente a otro formato. |
| override [GetAllGlyphIds](../../aspose.font.cff/cfffont/getallglyphids)() | Devuelve una matriz de todos los identificadores de glifo, disponibles en la fuente. El identificador de glifo es un número único para un glifo, que depende del tipo de fuente. El identificador de glifo de fuente CFF puede ser una instancia de ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) clase o ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) clase. |
| override [GetGlyphById](../../aspose.font.cff/cfffont/getglyphbyid#getglyphbyid)(GlyphId) | Devuelve el glifo por ID de glifo. El ID de glifo es un número único para un glifo, que depende del tipo de fuente. El ID de glifo de fuente CFF puede ser una instancia de ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) clase o ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) clase. |
| [GetGlyphById](../../aspose.font.cff/cfffont/getglyphbyid#getglyphbyid_1)(string) | Devuelve glifo por nombre de glifo. |
| [GetGlyphById](../../aspose.font.cff/cfffont/getglyphbyid#getglyphbyid_2)(uint) | Devuelve el glifo por ID de glifo. |
| virtual [GetGlyphsForText](../../aspose.font/font/getglyphsfortext)(string) | Obtiene representación de glifos para texto. |
| virtual [Save](../../aspose.font/font/save)(Stream) | Guarda la fuente en el formato original. |
| virtual [Save](../../aspose.font/font/save)(string) | Guarda la fuente en el formato original. |
| [SaveToFormat](../../aspose.font/font/savetoformat)(Stream, FontSavingFormats) | Guarda la fuente en el formato especificado. |

### Ver también

* class [Font](../../aspose.font/font)
* espacio de nombres [Aspose.Font.Cff](../../aspose.font.cff)
* asamblea [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->