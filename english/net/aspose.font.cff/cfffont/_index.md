---
title: Class CffFont
second_title: Aspose.Font for .NET API Reference
description: Aspose.Font.Cff.CffFont class. Represents Compact Font Format CFF
type: docs
weight: 30
url: /net/aspose.font.cff/cfffont/
---
## CffFont class

Represents Compact Font Format (CFF).

```csharp
public class CffFont : Font
```

## Properties

| Name | Description |
| --- | --- |
| [CommonFontsSettings](../../aspose.font.cff/cfffont/commonfontssettings/) { get; set; } | Gets/sets settings common to CFF fonts. These settings are used in different scenarios and can be changed for each individual font. |
| override [Encoding](../../aspose.font.cff/cfffont/encoding/) { get; } | Gets Font encoding. |
| override [FontDefinition](../../aspose.font.cff/cfffont/fontdefinition/) { get; } | Gets Font definition. |
| override [FontFamily](../../aspose.font.cff/cfffont/fontfamily/) { get; set; } | Gets Font family. The Font family setter is not implemented yet. |
| override [FontName](../../aspose.font.cff/cfffont/fontname/) { get; set; } | Gets or sets Font face name. |
| override [FontNames](../../aspose.font.cff/cfffont/fontnames/) { get; } | Get Font names. |
| [FontSaver](../../aspose.font/font/fontsaver/) { get; } | Gets Font save functionality. |
| override [FontStyle](../../aspose.font.cff/cfffont/fontstyle/) { get; } | Gets Font style. This is a value computed and represented in generalized type. |
| override [FontType](../../aspose.font.cff/cfffont/fonttype/) { get; } | Gets Font type. Returns FontType.CFF value. |
| [GlyphAccessor](../../aspose.font/font/glyphaccessor/) { get; } | Font glyph accessor. Retrieves glyphs and glyph identifiers. |
| override [GlyphIdType](../../aspose.font.cff/cfffont/glyphidtype/) { get; } | Gets glyph id type specification. |
| [IsCidKeyedFont](../../aspose.font.cff/cfffont/iscidkeyedfont/) { get; } | Gets value indicating that the Font is cid-keyed. |
| override [Metrics](../../aspose.font.cff/cfffont/metrics/) { get; } | Gets Font metrics. |
| override [NumGlyphs](../../aspose.font.cff/cfffont/numglyphs/) { get; } | Gets number of glyphs in the Font. |
| override [PostscriptNames](../../aspose.font.cff/cfffont/postscriptnames/) { get; } | Gets postscript Font names. |
| override [Style](../../aspose.font.cff/cfffont/style/) { get; set; } | Gets or sets Font style. This is a raw string value provided by Font file. |
| [TopDictDataProvider](../../aspose.font.cff/cfffont/topdictdataprovider/) { get; } | Gets accessor for the first top-level DICT in Top DICT INDEX structure. |

## Methods

| Name | Description |
| --- | --- |
| override [Convert](../../aspose.font.cff/cfffont/convert/)(FontType) | Converts the Font into another format. |
| override [GetAllGlyphIds](../../aspose.font.cff/cfffont/getallglyphids/)() | Returns array of all glyph ids, available in the Font. Glyph id is a unique number for a glyph, which is font type dependent. CFF Font glyph id can be instance of ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid/)) class or ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id/)) class. |
| override [GetGlyphById](../../aspose.font.cff/cfffont/getglyphbyid/#getglyphbyid)(GlyphId) | Returns glyph by glyph id. Glyph id is a unique number for a glyph, which is font type dependent. CFF Font glyph id can be instance of ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid/)) class or ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id/)) class. |
| [GetGlyphById](../../aspose.font.cff/cfffont/getglyphbyid/#getglyphbyid_1)(string) | Returns glyph by glyph name. |
| [GetGlyphById](../../aspose.font.cff/cfffont/getglyphbyid/#getglyphbyid_2)(uint) | Returns glyph by glyph id. |
| virtual [GetGlyphsForText](../../aspose.font/font/getglyphsfortext/)(string) | Gets glyphs representation for text. |
| [GetIndexDataProvider](../../aspose.font.cff/cfffont/getindexdataprovider/)(CffIndexProviderType) | Gets provider for the specified CFF INDEX structure type. |
| virtual [Save](../../aspose.font/font/save/)(Stream) | Saves the Font into original format. |
| virtual [Save](../../aspose.font/font/save/)(string) | Saves the Font into original format. |
| [SaveToFormat](../../aspose.font/font/savetoformat/)(Stream, FontSavingFormats) | Saves the Font into format specified. |

### See Also

* class [Font](../../aspose.font/font/)
* namespace [Aspose.Font.Cff](../../aspose.font.cff/)
* assembly [Aspose.Font](../../)


