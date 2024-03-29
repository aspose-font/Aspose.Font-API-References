---
title: CffEncoding
second_title: Aspose.Font für .NET-API-Referenz
description: Stellt die CFFSchriftartkodierung dar.
type: docs
weight: 20
url: /de/net/aspose.font.cff/cffencoding/
---
## CffEncoding class

Stellt die CFF-Schriftartkodierung dar.

```csharp
public class CffEncoding : IFontEncoding, ISupportsNameAddressing
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [DecodeToGid](../../aspose.font.cff/cffencoding/decodetogid)(uint) | Ruft Gid für übergebenen charCode ab. Diese Methode wurde für eine CFF-CIDFonts entwickelt, wobei charCode ein gültiger CID-Wert sein muss. Die Glyph-ID ist eine eindeutige Nummer für eine Glyphe, die vom Schriftarttyp abhängig ist. Die Glyph-ID der CFF-Schriftart kann eine Instanz von sein ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) Klasse oder ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) Klasse. |
| [DecodeToGidParameterized](../../aspose.font.cff/cffencoding/decodetogidparameterized)(IEncodingParameters, uint) | Parametrisierte Dekodierungsmethode. Nicht unterstützt für CFF-Schrifttyp. |
| [Encode](../../aspose.font.cff/cffencoding/encode)(uint, uint) | Kodiert die Glyphe. Nicht unterstützt für CFF-Schriftarten. |
| [GetNameToCharCodeIndex](../../aspose.font.cff/cffencoding/getnametocharcodeindex)() | Gibt den Namen an die Zeichencode-Codierungszuordnung zurück. Hinweis: Der Zeichencode ist kein Unicode. Der Zeichencode ist ein Zeichenindex in der Schriftcodierung "table". |
| [GetNameToGidIndex](../../aspose.font.cff/cffencoding/getnametogidindex)() | Gibt den Namen an die Zeichencode-Codierungszuordnung zurück. Hinweis: Der Zeichencode ist kein Unicode. Der Zeichencode ist ein Zeichenindex in der Schriftcodierung "table". |
| [GetNameToSidIndex](../../aspose.font.cff/cffencoding/getnametosidindex)() | Gibt den Namen an die Zeichencode-Codierungszuordnung zurück. Hinweis: Der Zeichencode ist kein Unicode. Der Zeichencode ist ein Zeichenindex in der Schriftcodierung "table". |
| [GetSidName](../../aspose.font.cff/cffencoding/getsidname)(int) | Ruft den Namen für die angegebene SID ab. |
| [GidToUnicode](../../aspose.font.cff/cffencoding/gidtounicode)(GlyphId) | Dekodiert Gid in Unicode. Glyph-ID ist eine eindeutige Nummer für ein Glyph, die vom Schriftarttyp abhängig ist. CFF-Schriftart-Glyph-ID kann Instanz von sein ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) Klasse oder ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) Klasse. |
| [UnicodeToGid](../../aspose.font.cff/cffencoding/unicodetogid)(uint) | Dekodiert einen Unicode und gibt die Glyphen-ID zurück. Die Glyphen-ID ist eine eindeutige Nummer für eine Glyphe, die vom Schriftarttyp abhängig ist. Die Glyphen-ID der CFF-Schriftart kann eine Instanz von sein ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) Klasse oder ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) Klasse. |

### Siehe auch

* interface [IFontEncoding](../../aspose.font/ifontencoding)
* interface [ISupportsNameAddressing](../../aspose.font/isupportsnameaddressing)
* namensraum [Aspose.Font.Cff](../../aspose.font.cff)
* Montage [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
