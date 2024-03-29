---
title: IGlyphAccessor
second_title: Referencia de la API de Aspose.Font para .NET
description: Define la funcionalidad para recuperar identificadores de glifos y glifos específicos.
type: docs
weight: 300
url: /es/net/aspose.font.glyphs/iglyphaccessor/
---
## IGlyphAccessor interface

Define la funcionalidad para recuperar identificadores de glifos y glifos específicos.

```csharp
public interface IGlyphAccessor
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [GlyphIdType](../../aspose.font.glyphs/iglyphaccessor/glyphidtype) { get; } | Especificación de tipo de id de glifo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetAllGlyphIds](../../aspose.font.glyphs/iglyphaccessor/getallglyphids)() | Devuelve todos los identificadores de glifo, disponibles en la fuente. El identificador de glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: El identificador de Tipo1 es un nombre de glifo, instancia de ([`GlyphStringId`](../glyphstringid)) class. El id de TTF es un índice int, instancia de ([`GlyphUInt32Id`](../glyphuint32id) clase. |
| [GetGlyphById](../../aspose.font.glyphs/iglyphaccessor/getglyphbyid)(GlyphId) | Devuelve el glifo por id. de glifo. El id. de glifo es un número único para un glifo, que depende del tipo de fuente. GlyphId - objeto derivado. Por ejemplo: El id de Type1 es un nombre de glifo, instancia de ([`GlyphStringId`](../glyphstringid)) class. El id de TTF es un índice int, instancia de ([`GlyphUInt32Id`](../glyphuint32id) clase. |
| [GetGlyphsForText](../../aspose.font.glyphs/iglyphaccessor/getglyphsfortext)(string) | Obtener representación de glifos para texto. |

### Ver también

* espacio de nombres [Aspose.Font.Glyphs](../../aspose.font.glyphs)
* asamblea [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
