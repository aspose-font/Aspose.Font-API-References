---
title: DecodeToGid
second_title: Aspose.Font for .NET API 参考
description: 将 Gid 解码为 unicode 字形 id 是字形的唯一编号取决于字体类型 例如 Type1 的 id 是字形名称实例为 GlyphStringIdaspose.font.glyphs/glyphstringid class. TTF 的 id 是一个 int 索引实例为 GlyphUInt32Idaspose.font.glyphs/glyphuint32id 类.
type: docs
weight: 10
url: /zh/net/aspose.font.type1/type1encoding/decodetogid/
---
## Type1Encoding.DecodeToGid method

将 Gid 解码为 unicode。 字形 id 是字形的唯一编号，取决于字体类型。 例如： Type1 的 id 是字形名称，实例为 ([`GlyphStringId`](../../../aspose.font.glyphs/glyphstringid)) class. TTF 的 id 是一个 int 索引，实例为 ([`GlyphUInt32Id`](../../../aspose.font.glyphs/glyphuint32id) 类.

```csharp
public GlyphId DecodeToGid(uint charCode)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| charCode | UInt32 | 获取字形标识符的字符代码。 |

### 返回值

与传递的字符代码相关的字形标识符。

### 也可以看看

* class [GlyphId](../../../aspose.font.glyphs/glyphid)
* class [Type1Encoding](../../type1encoding)
* 命名空间 [Aspose.Font.Type1](../../type1encoding)
* 部件 [Aspose.Font](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
