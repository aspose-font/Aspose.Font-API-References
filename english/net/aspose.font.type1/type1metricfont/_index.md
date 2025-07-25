---
title: Class Type1MetricFont
second_title: Aspose.Font for .NET API Reference
description: Aspose.Font.Type1.Type1MetricFont class. Type1 metric font implementation. This type1 font is created using metrics only. Glyphs retrieval functions and some other that require real font are not allowed not allowed functions throw exception Type1NotSupportedException. Other properties FontName Weight Metrics and Encoding are used from metrics file
type: docs
weight: 1480
url: /net/aspose.font.type1/type1metricfont/
---
## Type1MetricFont class

Type1 metric font implementation. This type1 font is created using metrics only. Glyphs retrieval functions and some other that require real font are not allowed, not allowed functions throw exception Type1NotSupportedException. Other properties (FontName, Weight, Metrics and Encoding) are used from metrics file.

```csharp
public class Type1MetricFont : Type1Font
```

## Properties

| Name | Description |
| --- | --- |
| override [Encoding](../../aspose.font.type1/type1metricfont/encoding/) { get; } | Encoding is defined in metrics file. StandardAdobeEncoding: the encoding is populated automatically |
| override [FontDefinition](../../aspose.font.type1/type1font/fontdefinition/) { get; } | Gets Font definition. |
| override [FontFamily](../../aspose.font.type1/type1metricfont/fontfamily/) { get; } | Gets Font family. |
| override [FontName](../../aspose.font.type1/type1metricfont/fontname/) { get; } | Gets Font name. |
| override [FontNames](../../aspose.font.type1/type1font/fontnames/) { get; } | Gets Font names. |
| [FontSaver](../../aspose.font/font/fontsaver/) { get; } | Gets Font save functionality. |
| override [FontStyle](../../aspose.font.type1/type1metricfont/fontstyle/) { get; } | Gets Font style. This is a value computed and represented in generalized type. |
| override [FontType](../../aspose.font.type1/type1font/fonttype/) { get; } | Gets Font type. Returns FontType.Type1 value. |
| [GlyphAccessor](../../aspose.font/font/glyphaccessor/) { get; } | Font glyph accessor. Retrieves glyphs and glyph identifiers. |
| override [GlyphIdType](../../aspose.font.type1/type1font/glyphidtype/) { get; } | Glyph id type specification. |
| override [Metrics](../../aspose.font.type1/type1font/metrics/) { get; } | Gets Font metrics. |
| override [NumGlyphs](../../aspose.font.type1/type1metricfont/numglyphs/) { get; } | Gets number of glyphs in the Font. |
| override [PostscriptNames](../../aspose.font.type1/type1font/postscriptnames/) { get; } | Gets postscript Font names. |
| override [Style](../../aspose.font.type1/type1metricfont/style/) { get; } | Gets Font style. |

## Methods

| Name | Description |
| --- | --- |
| override [Convert](../../aspose.font.type1/type1font/convert/)(FontType) | Converts the Font into another format. |
| override [GetAllGlyphIds](../../aspose.font.type1/type1metricfont/getallglyphids/)() | Returns all glyph ids, available in the Font. Not supported for `Type1MetricFont` type. |
| override [GetGlyphById](../../aspose.font.type1/type1metricfont/getglyphbyid/#getglyphbyid)(GlyphId) | Returns glyph by glyph id. Not supported for `Type1MetricFont` type. |
| override [GetGlyphById](../../aspose.font.type1/type1metricfont/getglyphbyid/#getglyphbyid_1)(string) | Returns glyph by glyph id. Not supported for `Type1MetricFont` type. |
| [GetGlyphById](../../aspose.font.type1/type1font/getglyphbyid/)(uint) | Returns glyph by glyph id. |
| virtual [GetGlyphsForText](../../aspose.font/font/getglyphsfortext/)(string) | Gets glyphs representation for text. |
| virtual [Save](../../aspose.font/font/save/)(Stream) | Saves the Font into original format. |
| virtual [Save](../../aspose.font/font/save/)(string) | Saves the Font into original format. |
| [SaveToFormat](../../aspose.font/font/savetoformat/)(Stream, FontSavingFormats) | Saves the Font into format specified. |

## Examples

Note: If metrics file defines Encoding as "FontSpecific", user should provide the specific encoding with following way:

```csharp
string[] zapfDingbatsEncoding = new string[256] {null, null, ... , "space", "a1", ...};
FontEnvironment.Current.FontSpecificEncodings.RegisterEncoding("ZapfDingbats", zapfDingbatsEncoding);
```

System::ArrayPtr&lt;System::String&gt; zapfDingbatsEncoding = System::MakeArray&lt;System::String&gt;({nullptr, nullptr, ..., u"space", u"a1", ...}); FontEnvironment::get_Current()-&gt;get_FontSpecificEncodings()-&gt;RegisterEncoding(u"ZapfDingbats", zapfDingbatsEncoding);

### See Also

* class [Type1Font](../type1font/)
* namespace [Aspose.Font.Type1](../../aspose.font.type1/)
* assembly [Aspose.Font](../../)


