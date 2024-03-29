---
title: Type1Encoding
second_title: Referencia de la API de Aspose.Font para .NET
description: Representa la codificación de fuente Type1.
type: docs
weight: 1050
url: /es/net/aspose.font.type1/type1encoding/
---
## Type1Encoding class

Representa la codificación de fuente Type1.

```csharp
public class Type1Encoding : IFontEncoding, ISupportsNameAddressing
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [DecodeToGid](../../aspose.font.type1/type1encoding/decodetogid)(uint) | Decodifica Gid a Unicode. Glyph id es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: Type1's id es un nombre de glifo, instancia de ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) class. El id de TTF es un índice int, instancia de ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) clase. |
| [DecodeToGidParameterized](../../aspose.font.type1/type1encoding/decodetogidparameterized)(IEncodingParameters, uint) | Método de decodificación parametrizado. No compatible con el tipo de fuente Type1. |
| [Encode](../../aspose.font.type1/type1encoding/encode)(uint, uint) | Codifica el glifo. Para fuentes TTF, el código de carácter es unicode. No compatible con tipos de fuente Type1. |
| [GetNameToCharCodeIndex](../../aspose.font.type1/type1encoding/getnametocharcodeindex)() | Devuelve el nombre al mapa de codificación del código de caracteres. Nota: el código de caracteres no es unicode. El código de caracteres es un índice de caracteres en la "tabla" de codificación de fuentes. |
| [GidToUnicode](../../aspose.font.type1/type1encoding/gidtounicode)(GlyphId) | Decodifica Gid a Unicode. Glyph id es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: Type1's id es un nombre de glifo, instancia de ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) class. El id de TTF es un índice int, instancia de ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) clase. |
| [UnicodeToGid](../../aspose.font.type1/type1encoding/unicodetogid)(uint) | Devuelve GlyphId para Unicode. O notdef si la fuente no contiene glifo para Unicode. Glyph id es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: Type1's id es un nombre de glifo, instancia de ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) class. El id de TTF es un índice int, instancia de ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) clase. |

### Ver también

* interface [IFontEncoding](../../aspose.font/ifontencoding)
* interface [ISupportsNameAddressing](../../aspose.font/isupportsnameaddressing)
* espacio de nombres [Aspose.Font.Type1](../../aspose.font.type1)
* asamblea [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
