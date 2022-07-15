---
title: UnicodeToGid
second_title: Aspose.Font for .NET API 参考
description: 解码一个 unicode 并返回 glyph id Glyph id 是字形的唯一编号它取决于字体类型 例如 Type1 的 id 是一个字形名称是 GlyphStringIdaspose.font.glyphs/glyphstringid 类的实例 TTF 的 id 是一个 int 索引是 GlyphUInt32Idaspose.font.glyphs/glyphuint32id 类的实例
type: docs
weight: 50
url: /zh/net/aspose.font/ifontencoding/unicodetogid/
---
## IFontEncoding.UnicodeToGid method

解码一个 unicode 并返回 glyph id。 Glyph id 是字形的唯一编号，它取决于字体类型。 例如： Type1 的 id 是一个字形名称，是 ([`GlyphStringId`](../../../aspose.font.glyphs/glyphstringid)) 类的实例。 TTF 的 id 是一个 int 索引，是 ([`GlyphUInt32Id`](../../../aspose.font.glyphs/glyphuint32id)) 类的实例。

```csharp
public GlyphId UnicodeToGid(uint unicode)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| unicode | UInt32 | Unicode 获取字形标识符。 |

### 返回值

与 unicode 相关的字形标识符已通过。

### 也可以看看

* class [GlyphId](../../../aspose.font.glyphs/glyphid)
* interface [IFontEncoding](../../ifontencoding)
* 命名空间 [Aspose.Font](../../ifontencoding)
* 部件 [Aspose.Font](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->