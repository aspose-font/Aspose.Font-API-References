---
title: TtfHmtxTable
second_title: Aspose.Font for .NET API 参考
description: 表示 TTF 字体文件的hmtx表
type: docs
weight: 830
url: /zh/net/aspose.font.ttftables/ttfhmtxtable/
---
## TtfHmtxTable class

表示 TTF 字体文件的“hmtx”表。

```csharp
public class TtfHmtxTable : TtfTableBase
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AdditionalAdvanceWidth](../../aspose.font.ttftables/ttfhmtxtable/additionaladvancewidth) { get; } | 在 hmtx 表中可能是字形总数不等于 hhea.numberOfHMetrics 的情况。对于这些情况，hmtx 表包含额外的数组 'leftSideBearing' 对应于属性[`LeftSidebearings`](./leftsidebearings)。 但是索引从 hhea.numOfLongHorMetrics 到 maxp.numGlyphs 的字形也有宽度。 根据 hmtx 表的规范，这些宽度具有这样的值： “这里的 advanceWidth 假定与上面最后一个条目的 AdvanceWidth 相同”。 |
| [HMetrics](../../aspose.font.ttftables/ttfhmtxtable/hmetrics) { get; } | 获取水平指标。 |
| [LeftSidebearings](../../aspose.font.ttftables/ttfhmtxtable/leftsidebearings) { get; } | 获取左侧轴承。 |
| [Offset](../../aspose.font.ttftables/ttftablebase/offset) { get; } | 从 sfnt 开始处获取偏移量。 |
| [TtfTables](../../aspose.font.ttftables/ttftablebase/ttftables) { get; } | 对 TTF 表存储库的引用。 |
| static [Tag](../../aspose.font.ttftables/ttfhmtxtable/tag) { get; } | 获取表标签。 |

### 也可以看看

* class [TtfTableBase](../ttftablebase)
* 命名空间 [Aspose.Font.TtfTables](../../aspose.font.ttftables)
* 部件 [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->