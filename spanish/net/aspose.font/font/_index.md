---
title: Font
second_title: Referencia de la API de Aspose.Font para .NET
description: Representa la clase de fuente base.
type: docs
weight: 120
url: /es/net/aspose.font/font/
---
## Font class

Representa la clase de fuente base.

```csharp
public abstract class Font : IFont, IFontSaver, IGlyphAccessor
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| abstract [Encoding](../../aspose.font/font/encoding) { get; } | Obtiene la codificación de fuentes. |
| abstract [FontDefinition](../../aspose.font/font/fontdefinition) { get; } | Obtiene definición de fuente. |
| abstract [FontFamily](../../aspose.font/font/fontfamily) { get; set; } | Obtiene o establece la familia de fuentes. |
| abstract [FontName](../../aspose.font/font/fontname) { get; set; } | Obtiene o establece el nombre de la cara de la fuente. |
| abstract [FontNames](../../aspose.font/font/fontnames) { get; } | Obtiene los nombres de las fuentes. |
| [FontSaver](../../aspose.font/font/fontsaver) { get; } | Obtiene la función de guardar fuentes. |
| abstract [FontStyle](../../aspose.font/font/fontstyle) { get; } | Obtiene el estilo de fuente. Este es un valor calculado y representado en tipo generalizado. |
| abstract [FontType](../../aspose.font/font/fonttype) { get; } | Obtiene Tipo de fuente. Tipo1, TrueType, etc. |
| [GlyphAccessor](../../aspose.font/font/glyphaccessor) { get; } | Accesorio de glifo de fuente. Recupera glifos e identificadores de glifos. |
| abstract [GlyphIdType](../../aspose.font/font/glyphidtype) { get; } | Especificación de tipo de ID de glifo. Para consumidores que necesitan saber el tipo real de 'bytes[]'. |
| abstract [Metrics](../../aspose.font/font/metrics) { get; } | Obtiene métricas de fuentes. |
| abstract [NumGlyphs](../../aspose.font/font/numglyphs) { get; } | Obtiene el número de glifos en la Fuente. |
| abstract [PostscriptNames](../../aspose.font/font/postscriptnames) { get; } | Obtiene nombres de fuentes postscript. |
| abstract [Style](../../aspose.font/font/style) { get; set; } | Obtiene o establece el estilo de fuente. Este es un valor de cadena sin formato proporcionado por el archivo de fuente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Open](../../aspose.font/font/open#open_3)(FontDefinition) | Abre una fuente, utilizando el objeto FontDefinition. |
| static [Open](../../aspose.font/font/open#open_1)(FontType, byte[]) | Abre una fuente, utilizando el tipo de fuente y la matriz de bytes de datos de fuente. |
| static [Open](../../aspose.font/font/open#open)(FontType, StreamSource) | Abre una fuente, usando el tipo de fuente y la fuente de transmisión. |
| static [Open](../../aspose.font/font/open#open_2)(FontType, string) | Abre una fuente, usando el tipo de fuente y el nombre del archivo de fuente. |
| abstract [Convert](../../aspose.font/font/convert)(FontType) | Convierte la Fuente a otro formato. |
| abstract [GetAllGlyphIds](../../aspose.font/font/getallglyphids)() | Devuelve todos los identificadores de glifo, disponibles en la fuente. El identificador de glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: El identificador de Tipo1 es un nombre de glifo, instancia de ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) class. El id de TTF es un índice int, instancia de ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) clase. |
| abstract [GetGlyphById](../../aspose.font/font/getglyphbyid)(GlyphId) | Devuelve el glifo por id. de glifo. El id. de glifo es un número único para un glifo, que depende del tipo de fuente. GlyphId - objeto derivado. Por ejemplo: El id de Type1 es un nombre de glifo, instancia de ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) class. El id de TTF es un índice int, instancia de ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) clase. |
| virtual [GetGlyphsForText](../../aspose.font/font/getglyphsfortext)(string) | Obtiene representación de glifos para texto. |
| virtual [Save](../../aspose.font/font/save#save)(Stream) | Guarda la fuente en el formato original. |
| virtual [Save](../../aspose.font/font/save#save_1)(string) | Guarda la fuente en el formato original. |
| [SaveToFormat](../../aspose.font/font/savetoformat)(Stream, FontSavingFormats) | Guarda la fuente en el formato especificado. |

### Ver también

* interface [IFont](../ifont)
* interface [IFontSaver](../ifontsaver)
* interface [IGlyphAccessor](../../aspose.font.glyphs/iglyphaccessor)
* espacio de nombres [Aspose.Font](../../aspose.font)
* asamblea [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->