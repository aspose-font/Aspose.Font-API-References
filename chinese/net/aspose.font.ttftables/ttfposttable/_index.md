---
title: TtfPostTable
second_title: Aspose.Font for .NET API 参考
description: 代表TTF字体文件的post表
type: docs
weight: 1000
url: /zh/net/aspose.font.ttftables/ttfposttable/
---
## TtfPostTable class

代表TTF字体文件的“post”表。

```csharp
public class TtfPostTable : TtfTableBase
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Format](../../aspose.font.ttftables/ttfposttable/format) { get; } | 获取此表的固定格式（版本）。 |
| [HasNoPostScriptNames](../../aspose.font.ttftables/ttfposttable/hasnopostscriptnames) { get; } | 表示没有为此字体文件中的字形提供 PostScript 名称信息。 |
| [IsFixedPitch](../../aspose.font.ttftables/ttfposttable/isfixedpitch) { get; } | 获取 uint32 isFixedPitch。如果字体是按比例间隔的，则为 0，如果字体不是按比例 间隔（即等宽），则为非零。 |
| [ItalicAngle](../../aspose.font.ttftables/ttfposttable/italicangle) { get; } | 获取固定的 italicAngle 斜体角度，以度为单位。 |
| [MaxMemType1](../../aspose.font.ttftables/ttfposttable/maxmemtype1) { get; } | 获取 uint32 maxMemType1 将 TrueType 字体下载为 Type 1 字体时的最大内存使用量。 |
| [MaxMemType42](../../aspose.font.ttftables/ttfposttable/maxmemtype42) { get; } | 获取 uint32 maxMemType42 将 TrueType 字体下载为 Type 42 字体时的最大内存使用量。 |
| [MinMemType1](../../aspose.font.ttftables/ttfposttable/minmemtype1) { get; } | 获取 uint32 minMemType1 将 TrueType 字体下载为 Type 1 字体时的最小内存使用量。 |
| [MinMemType42](../../aspose.font.ttftables/ttfposttable/minmemtype42) { get; } | 获取 uint32 minMemType42 将 TrueType 字体下载为 Type 42 字体时的最小内存使用量。 |
| [Offset](../../aspose.font.ttftables/ttftablebase/offset) { get; } | 获取从 sfnt 开始的偏移量。 |
| [TtfTables](../../aspose.font.ttftables/ttftablebase/ttftables) { get; } | 对 TTF 表存储库的引用。 |
| [UnderlinePosition](../../aspose.font.ttftables/ttfposttable/underlineposition) { get; } | 获取 FWord underlinePosition 值。 |
| [UnderlineThickness](../../aspose.font.ttftables/ttfposttable/underlinethickness) { get; } | 获取 FWord underlineThickness 值。 |
| static [Tag](../../aspose.font.ttftables/ttfposttable/tag) { get; } | 获取表标签。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetGlyphIndex](../../aspose.font.ttftables/ttfposttable/getglyphindex)(string) | 通过字形名称获取字形索引。 |
| [GetGlyphName](../../aspose.font.ttftables/ttfposttable/getglyphname)(uint) | 通过字形索引获取字形名称。 |

### 也可以看看

* class [TtfTableBase](../ttftablebase)
* 命名空间 [Aspose.Font.TtfTables](../../aspose.font.ttftables)
* 部件 [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
