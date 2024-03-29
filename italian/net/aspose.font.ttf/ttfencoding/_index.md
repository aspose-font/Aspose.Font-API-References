---
title: TtfEncoding
second_title: Aspose.Font per Riferimento API .NET
description: Rappresenta la codifica dei caratteri TTF.
type: docs
weight: 610
url: /it/net/aspose.font.ttf/ttfencoding/
---
## TtfEncoding class

Rappresenta la codifica dei caratteri TTF.

```csharp
public class TtfEncoding : IFontEncoding
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [DecodeToGid](../../aspose.font.ttf/ttfencoding/decodetogid)(uint) | L'implementazione DecodeToGlyphId di TTF Font trova la tabella unicode e restituisce l'id del glifo per il carattere unicode. L'id del glifo è un numero univoco per un glifo, che dipende dal tipo di carattere. Ad esempio: L'id di Type1 è un nome di glifo, istanza di ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) class. L'id di TTF è un int index, istanza di ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) classe. |
| [DecodeToGidParameterized](../../aspose.font.ttf/ttfencoding/decodetogidparameterized)(IEncodingParameters, uint) | La versione parametrizzata permette di utilizzare specifiche tabelle CMap (non unicode). |
| [Encode](../../aspose.font.ttf/ttfencoding/encode)(uint, uint) | Codifica il glifo. Per i caratteri TTF il codice del carattere è unicode. |
| [GidToUnicode](../../aspose.font.ttf/ttfencoding/gidtounicode)(GlyphId) | Decodifica l'id del glifo in unicode. L'id del glifo è un numero univoco per un glifo, che dipende dal tipo di carattere. Ad esempio: L'id di Type1 è un nome di glifo, istanza di ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) class. L'id di TTF è un int index, istanza di ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) classe. |
| [UnicodeToGid](../../aspose.font.ttf/ttfencoding/unicodetogid)(uint) | Decodifica un unicode e restituisce glyph id. |

### Guarda anche

* interface [IFontEncoding](../../aspose.font/ifontencoding)
* spazio dei nomi [Aspose.Font.Ttf](../../aspose.font.ttf)
* assemblea [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
