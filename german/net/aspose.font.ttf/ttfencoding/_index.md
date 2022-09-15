---
title: TtfEncoding
second_title: Aspose.Font für .NET-API-Referenz
description: Stellt die TTFSchriftartkodierung dar.
type: docs
weight: 610
url: /de/net/aspose.font.ttf/ttfencoding/
---
## TtfEncoding class

Stellt die TTF-Schriftartkodierung dar.

```csharp
public class TtfEncoding : IFontEncoding
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [DecodeToGid](../../aspose.font.ttf/ttfencoding/decodetogid)(uint) | Die DecodeToGlyphId-Implementierung von TTF Font findet eine Unicode-Tabelle und gibt die Glyph-ID für ein Unicode-Zeichen zurück. Die Glyph-ID ist eine eindeutige Nummer für ein Glyph, die vom Schriftarttyp abhängig ist. Zum Beispiel: Die ID von Typ1 ist ein Glyphname, Instanz von ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) class. TTF-ID ist ein int-Index, Instanz von ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) Klasse. |
| [DecodeToGidParameterized](../../aspose.font.ttf/ttfencoding/decodetogidparameterized)(IEncodingParameters, uint) | Parametrisierte Version ermöglicht die Verwendung einer bestimmten CMap-Tabelle (nicht Unicode). |
| [Encode](../../aspose.font.ttf/ttfencoding/encode)(uint, uint) | Kodiert die Glyphe. Für TTF-Schriftarten ist der Zeichencode Unicode. |
| [GidToUnicode](../../aspose.font.ttf/ttfencoding/gidtounicode)(GlyphId) | Dekodiert die Glyphen-ID in Unicode. Die Glyphen-ID ist eine eindeutige Nummer für eine Glyphe, die vom Schriftarttyp abhängig ist. Zum Beispiel: Die ID von Typ1 ist ein Glyphenname, Instanz von ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) class. TTF-ID ist ein int-Index, Instanz von ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) Klasse. |
| [UnicodeToGid](../../aspose.font.ttf/ttfencoding/unicodetogid)(uint) | Dekodiert einen Unicode und gibt die Glyphen-ID zurück. |

### Siehe auch

* interface [IFontEncoding](../../aspose.font/ifontencoding)
* namensraum [Aspose.Font.Ttf](../../aspose.font.ttf)
* Montage [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->