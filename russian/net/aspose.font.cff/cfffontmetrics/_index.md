---
title: CffFontMetrics
second_title: Справочник по API Aspose.Font для .NET
description: Представляет метрики шрифта CFF.
type: docs
weight: 40
url: /ru/net/aspose.font.cff/cfffontmetrics/
---
## CffFontMetrics class

Представляет метрики шрифта CFF.

```csharp
public class CffFontMetrics : FontMetrics
```

## Характеристики

| Имя | Описание |
| --- | --- |
| override [Ascender](../../aspose.font.cff/cfffontmetrics/ascender) { get; } | Получает значение по возрастанию. |
| override [Descender](../../aspose.font.cff/cfffontmetrics/descender) { get; } | Получает значение Descender. |
| override [FontBBox](../../aspose.font.cff/cfffontmetrics/fontbbox) { get; } | Получает значение FontBBox. |
| override [FontMatrix](../../aspose.font.cff/cfffontmetrics/fontmatrix) { get; } | Получает значение FontMatrix. |
| [IsFixedPitch](../../aspose.font/fontmetrics/isfixedpitch) { get; } | Получает значение IsFixedPitch. |
| virtual [LineGap](../../aspose.font/fontmetrics/linegap) { get; } | Получает значение LineGap. |
| virtual [TypoAscender](../../aspose.font/fontmetrics/typoascender) { get; set; } | Получает значение TypoAscender. |
| virtual [TypoDescender](../../aspose.font/fontmetrics/typodescender) { get; set; } | Получает значение TypoDescender. |
| virtual [TypoLineGap](../../aspose.font/fontmetrics/typolinegap) { get; } | Получает значение TypoLineGap. |
| override [UnitsPerEM](../../aspose.font.cff/cfffontmetrics/unitsperem) { get; } | Получает значение UnitsPerEM. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetAscender](../../aspose.font/fontmetrics/getascender)(double) | Возвращает восходящий элемент для определенного размера шрифта. |
| virtual [GetDescender](../../aspose.font/fontmetrics/getdescender)(double) | Возвращает выносной элемент для определенного размера шрифта. |
| [GetFontMatrixForGlyph](../../aspose.font.cff/cfffontmetrics/getfontmatrixforglyph)(GlyphId) | Вычисляет матрицу преобразования для глифа, заданного идентификатором. |
| virtual [GetGlyphBBox](../../aspose.font/fontmetrics/getglyphbbox)(GlyphId) | Возвращает глиф BBox. Возвращает FontBBox, если BBox не был определен для глифа. Может быть переопределен определенными наследниками кодировки шрифта. |
| override [GetGlyphWidth](../../aspose.font.cff/cfffontmetrics/getglyphwidth)(GlyphId) | Возвращает ширину глифа. Может быть переопределен определенными наследниками кодировки шрифта. |
| virtual [GetKerningValue](../../aspose.font/fontmetrics/getkerningvalue)(GlyphId, GlyphId) | Возвращает значение кернинга для пары глифов. |
| virtual [GetTypoAscender](../../aspose.font/fontmetrics/gettypoascender)(double) | Возвращает выносной элемент для определенного размера шрифта. |
| virtual [GetTypoDescender](../../aspose.font/fontmetrics/gettypodescender)(double) | Возвращает выносной элемент для определенного размера шрифта. |
| virtual [GetTypoLineGap](../../aspose.font/fontmetrics/gettypolinegap)(double) | Возвращает межстрочный интервал для определенного размера шрифта. |
| override [MeasureString](../../aspose.font.cff/cfffontmetrics/measurestring)(string, double) | Измеряет строку и возвращает ширину строки. |

### Смотрите также

* class [FontMetrics](../../aspose.font/fontmetrics)
* пространство имен [Aspose.Font.Cff](../../aspose.font.cff)
* сборка [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->