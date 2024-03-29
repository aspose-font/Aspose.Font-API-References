---
title: TtfHeadTable
second_title: Aspose.Font for .NET API 参考
description: 表示 TTF 字体文件的头表
type: docs
weight: 820
url: /zh/net/aspose.font.ttftables/ttfheadtable/
---
## TtfHeadTable class

表示 TTF 字体文件的“头”表。

```csharp
public class TtfHeadTable : TtfTableBase
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CheckSumAdjustment](../../aspose.font.ttftables/ttfheadtable/checksumadjustment) { get; } | 获取 uint32 checkSumAdjustment。计算：将其设置为 0，计算 'head' 表的校验和并将其放入表目录中，将整个字体求和为 uint32，然后存储 B1B0AFBA - sum。 “头”表的校验和不会出错。没关系。 |
| [Created](../../aspose.font.ttftables/ttfheadtable/created) { get; } | 获取 longDateTime 创建的国际日期。 |
| [Flags](../../aspose.font.ttftables/ttfheadtable/flags) { get; } | 获取 uint16 标志。 |
| [FontDirectionHint](../../aspose.font.ttftables/ttfheadtable/fontdirectionhint) { get; } | 获取 int16 fontDirectionHint. 0 混合方向字形； 1 仅强烈从左到右的字形； 2 与 1 相似但也包含中性； -1 仅从右到左强烈字形； -2 与 -1 相似但也包含中性。 |
| [FontRevision](../../aspose.font.ttftables/ttfheadtable/fontrevision) { get; } | 获取字体制造商设置的固定 fontRevision。 |
| [GlyphDataFormat](../../aspose.font.ttftables/ttfheadtable/glyphdataformat) { get; } | 获取当前格式的 int16 glyphDataFormat 0。 |
| [IndexToLocFormat](../../aspose.font.ttftables/ttfheadtable/indextolocformat) { get; } | 获取 int16 indexToLocFormat 0 表示短偏移，1 表示长偏移。 |
| [LowestRecPPEM](../../aspose.font.ttftables/ttfheadtable/lowestrecppem) { get; } | 获取 uint16 minimumRecPPEM 最小可读大小（以像素为单位）。 |
| [MacStyle](../../aspose.font.ttftables/ttfheadtable/macstyle) { get; } | 获取 uint16 macStyle. |
| [MagicNumber](../../aspose.font.ttftables/ttfheadtable/magicnumber) { get; } | 获取 uint32 magicNumber 设置为 0x5F0F3CF5. |
| [Modified](../../aspose.font.ttftables/ttfheadtable/modified) { get; } | 获取 longDateTime 修改的国际日期。 |
| [Offset](../../aspose.font.ttftables/ttftablebase/offset) { get; } | 获取从 sfnt 开始的偏移量。 |
| [TtfTables](../../aspose.font.ttftables/ttftablebase/ttftables) { get; } | 对 TTF 表存储库的引用。 |
| [UnitsPerEM](../../aspose.font.ttftables/ttfheadtable/unitsperem) { get; } | 获取 uint16 unitsPerEm 范围从 64 到 16384。 |
| [Version](../../aspose.font.ttftables/ttfheadtable/version) { get; } | 固定版本 0x00010000 if (version 1.0). |
| [XMax](../../aspose.font.ttftables/ttfheadtable/xmax) { get; } | 获取所有字形边界框的 FWord xMax。 |
| [XMin](../../aspose.font.ttftables/ttfheadtable/xmin) { get; } | 获取所有字形边界框的 FWord xMin。 |
| [YMax](../../aspose.font.ttftables/ttfheadtable/ymax) { get; } | 获取所有字形边界框的 FWord yMax。 |
| [YMin](../../aspose.font.ttftables/ttfheadtable/ymin) { get; } | 获取所有字形边界框的 FWord yMin。 |
| static [Tag](../../aspose.font.ttftables/ttfheadtable/tag) { get; } | 获取表标签。 |

### 也可以看看

* class [TtfTableBase](../ttftablebase)
* 命名空间 [Aspose.Font.TtfTables](../../aspose.font.ttftables)
* 部件 [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
