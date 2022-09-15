---
title: CffFont
second_title: Aspose.Font för .NET API-referens
description: Representerar Compact Font Format CFF.
type: docs
weight: 30
url: /sv/net/aspose.font.cff/cfffont/
---
## CffFont class

Representerar Compact Font Format (CFF).

```csharp
public class CffFont : Font
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [Encoding](../../aspose.font.cff/cfffont/encoding) { get; } | Får teckensnittskodning. |
| override [FontDefinition](../../aspose.font.cff/cfffont/fontdefinition) { get; } | Hämtar teckensnittsdefinition. |
| override [FontFamily](../../aspose.font.cff/cfffont/fontfamily) { get; set; } | Hämtar teckensnittsfamilj. Teckensnittsfamiljen är inte implementerad ännu. |
| override [FontName](../../aspose.font.cff/cfffont/fontname) { get; set; } | Får teckensnittsnamn. Inställningen av teckensnittsnamn är inte implementerad ännu. |
| override [FontNames](../../aspose.font.cff/cfffont/fontnames) { get; } | Hämta teckensnittsnamn. |
| [FontSaver](../../aspose.font/font/fontsaver) { get; } | Får Font Save-funktionalitet. |
| override [FontStyle](../../aspose.font.cff/cfffont/fontstyle) { get; } | Gets Font style. Detta är ett värde som beräknas och representeras i generaliserad typ. |
| override [FontType](../../aspose.font.cff/cfffont/fonttype) { get; } | Hämtar teckensnittstyp. Returnerar FontType.CFF-värde. |
| [GlyphAccessor](../../aspose.font/font/glyphaccessor) { get; } | Font glyph accessor. Hämtar glyfer och glyph-identifierare. |
| override [GlyphIdType](../../aspose.font.cff/cfffont/glyphidtype) { get; } | Hämtar glyph id-typspecifikation. |
| [IsCidKeyedFont](../../aspose.font.cff/cfffont/iscidkeyedfont) { get; } | Får värde som indikerar att teckensnittet är cid-nyckel. |
| override [Metrics](../../aspose.font.cff/cfffont/metrics) { get; } | Får teckensnittsstatistik. |
| override [NumGlyphs](../../aspose.font.cff/cfffont/numglyphs) { get; } | Hämtar antal tecken i teckensnittet. |
| override [PostscriptNames](../../aspose.font.cff/cfffont/postscriptnames) { get; } | Får postscript-teckensnittsnamn. |
| override [Style](../../aspose.font.cff/cfffont/style) { get; set; } | Gets Font style. Detta är ett råsträngsvärde som tillhandahålls av Font file. Stilinställaren är inte implementerad ännu. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Convert](../../aspose.font.cff/cfffont/convert)(FontType) | Konverterar teckensnittet till ett annat format. |
| override [GetAllGlyphIds](../../aspose.font.cff/cfffont/getallglyphids)() | Returnerar array av alla glyph id, tillgängliga i Font. Glyph id är ett unikt nummer för en glyph, vilket är teckensnittsberoende. CFF Font glyph id kan vara en instans av ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) klass eller ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) class. |
| override [GetGlyphById](../../aspose.font.cff/cfffont/getglyphbyid#getglyphbyid)(GlyphId) | Returnerar glyph efter glyph id. Glyph id är ett unikt nummer för en glyph, vilket är teckensnittsberoende. CFF Font glyph id kan vara en instans av ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) klass eller ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) class. |
| [GetGlyphById](../../aspose.font.cff/cfffont/getglyphbyid#getglyphbyid_1)(string) | Returnerar glyf efter glyfnamn. |
| [GetGlyphById](../../aspose.font.cff/cfffont/getglyphbyid#getglyphbyid_2)(uint) | Returnerar glyph för glyph id. |
| virtual [GetGlyphsForText](../../aspose.font/font/getglyphsfortext)(string) | Får glyferrepresentation för text. |
| virtual [Save](../../aspose.font/font/save)(Stream) | Sparar teckensnittet i originalformat. |
| virtual [Save](../../aspose.font/font/save)(string) | Sparar teckensnittet i originalformat. |
| [SaveToFormat](../../aspose.font/font/savetoformat)(Stream, FontSavingFormats) | Sparar teckensnittet i det angivna formatet. |

### Se även

* class [Font](../../aspose.font/font)
* namnutrymme [Aspose.Font.Cff](../../aspose.font.cff)
* hopsättning [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->