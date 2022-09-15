---
title: Type1Encoding
second_title: Aspose.Font per Riferimento API .NET
description: Rappresenta la codifica del carattere Type1.
type: docs
weight: 1050
url: /it/net/aspose.font.type1/type1encoding/
---
## Type1Encoding class

Rappresenta la codifica del carattere Type1.

```csharp
public class Type1Encoding : IFontEncoding, ISupportsNameAddressing
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [DecodeToGid](../../aspose.font.type1/type1encoding/decodetogid)(uint) | Decodifica Gid in unicode. Glyph id è un numero univoco per un glifo, che dipende dal tipo di carattere. Ad esempio: L'id di Type1 è un nome di glifo, istanza di ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) class. L'id di TTF è un int index, istanza di ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) classe. |
| [DecodeToGidParameterized](../../aspose.font.type1/type1encoding/decodetogidparameterized)(IEncodingParameters, uint) | Metodo di decodifica parametrizzato. Non supportato per il tipo di carattere Type1. |
| [Encode](../../aspose.font.type1/type1encoding/encode)(uint, uint) | Codifica il glifo. Per i font TTF il codice del carattere è unicode. Non supportato per i tipi di font Type1. |
| [GetNameToCharCodeIndex](../../aspose.font.type1/type1encoding/getnametocharcodeindex)() | Restituisce il nome alla mappa di codifica del codice carattere. Nota: il codice carattere non è un unicode. Il codice carattere è un indice di caratteri nella codifica dei caratteri "tabella". |
| [GidToUnicode](../../aspose.font.type1/type1encoding/gidtounicode)(GlyphId) | Decodifica Gid in Unicode. Glyph id è un numero univoco per un glifo, che dipende dal tipo di carattere. Ad esempio: L'id di Type1 è un nome di glifo, istanza di ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) class. L'id di TTF è un int index, istanza di ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) classe. |
| [UnicodeToGid](../../aspose.font.type1/type1encoding/unicodetogid)(uint) | Restituisce GlyphId per unicode. Oppure notdef se il carattere non contiene glifo per l'unicode. L'ID glifo è un numero univoco per un glifo, che dipende dal tipo di carattere. Ad esempio: L'ID di Type1 è un nome di glifo, istanza di ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) class. L'id di TTF è un int index, istanza di ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) classe. |

### Guarda anche

* interface [IFontEncoding](../../aspose.font/ifontencoding)
* interface [ISupportsNameAddressing](../../aspose.font/isupportsnameaddressing)
* spazio dei nomi [Aspose.Font.Type1](../../aspose.font.type1)
* assemblea [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->