---
title: TtfEncoding
second_title: Aspose.Font for .NET API 参考
description: 表示 TTF 字体编码
type: docs
weight: 610
url: /zh/net/aspose.font.ttf/ttfencoding/
---
## TtfEncoding class

表示 TTF 字体编码。

```csharp
public class TtfEncoding : IFontEncoding
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| [DecodeToGid](../../aspose.font.ttf/ttfencoding/decodetogid)(uint) | TTF Font 的 DecodeToGlyphId 实现查找 unicode 表并返回 unicode char 的 glyph id。 glyph id 是一个字形的唯一编号，它取决于字体类型。 例如： Type1 的 id 是一个字形名称，实例为 ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) class. TTF 的 id 是一个 int 索引，实例为 ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) 类. |
| [DecodeToGidParameterized](../../aspose.font.ttf/ttfencoding/decodetogidparameterized)(IEncodingParameters, uint) | 参数化版本允许使用特定的 CMap 表（不是 unicode）。 |
| [Encode](../../aspose.font.ttf/ttfencoding/encode)(uint, uint) | 对字形进行编码。 对于 TTF 字体，字符代码是 unicode。 |
| [GidToUnicode](../../aspose.font.ttf/ttfencoding/gidtounicode)(GlyphId) | 将字形 id 解码为 unicode。 字形 id 是一个字形的唯一编号，它取决于字体类型。 例如： type1 的 id 是一个字形名称，例如 ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) class. TTF 的 id 是一个 int 索引，实例为 ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) 类. |
| [UnicodeToGid](../../aspose.font.ttf/ttfencoding/unicodetogid)(uint) | 解码一个 unicode 并返回字形 id。 |

### 也可以看看

* interface [IFontEncoding](../../aspose.font/ifontencoding)
* 命名空间 [Aspose.Font.Ttf](../../aspose.font.ttf)
* 部件 [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
