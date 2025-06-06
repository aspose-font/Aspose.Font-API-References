---
title: IFontEncoding.GidToUnicode
second_title: Aspose.Font for .NET API Reference
description: IFontEncoding method. Decodes Gid to unicode. Glyph id is a unique number for a glyph which is font type dependent. For example Type1s id is a glyph name instance of GlyphStringId class. TTFs id is an int index instance of GlyphUInt32Id class
type: docs
weight: 40
url: /net/aspose.font/ifontencoding/gidtounicode/
---
## IFontEncoding.GidToUnicode method

Decodes Gid to unicode. Glyph id is a unique number for a glyph, which is font type dependent. For example: Type1's id is a glyph name, instance of ([`GlyphStringId`](../../../aspose.font.glyphs/glyphstringid/)) class. TTF's id is an int index, instance of ([`GlyphUInt32Id`](../../../aspose.font.glyphs/glyphuint32id/)) class.

```csharp
public uint GidToUnicode(GlyphId gid)
```

| Parameter | Type | Description |
| --- | --- | --- |
| gid | GlyphId | Glyph identifier of symbol to decode. |

### Return Value

Unicode value related to glyph id passed.

### See Also

* class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* interface [IFontEncoding](../)
* namespace [Aspose.Font](../../../aspose.font/)
* assembly [Aspose.Font](../../../)


