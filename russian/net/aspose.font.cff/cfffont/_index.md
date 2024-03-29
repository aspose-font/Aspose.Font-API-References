---
title: CffFont
second_title: Справочник по API Aspose.Font для .NET
description: Представляет формат компактного шрифта CFF.
type: docs
weight: 30
url: /ru/net/aspose.font.cff/cfffont/
---
## CffFont class

Представляет формат компактного шрифта (CFF).

```csharp
public class CffFont : Font
```

## Характеристики

| Имя | Описание |
| --- | --- |
| override [Encoding](../../aspose.font.cff/cfffont/encoding) { get; } | Получает кодировку шрифта. |
| override [FontDefinition](../../aspose.font.cff/cfffont/fontdefinition) { get; } | Получает определение шрифта. |
| override [FontFamily](../../aspose.font.cff/cfffont/fontfamily) { get; set; } | Получает семейство шрифтов. Установщик семейства шрифтов еще не реализован. |
| override [FontName](../../aspose.font.cff/cfffont/fontname) { get; set; } | Получает имя начертания шрифта. Установщик имени начертания шрифта еще не реализован. |
| override [FontNames](../../aspose.font.cff/cfffont/fontnames) { get; } | Получить имена шрифтов. |
| [FontSaver](../../aspose.font/font/fontsaver) { get; } | Получает функцию сохранения шрифта. |
| override [FontStyle](../../aspose.font.cff/cfffont/fontstyle) { get; } | Получает стиль шрифта. Это значение вычисляется и представляется в обобщенном виде. |
| override [FontType](../../aspose.font.cff/cfffont/fonttype) { get; } | Получает тип шрифта. Возвращает значение FontType.CFF. |
| [GlyphAccessor](../../aspose.font/font/glyphaccessor) { get; } | Аксессуар глифа шрифта. Извлекает глифы и идентификаторы глифов. |
| override [GlyphIdType](../../aspose.font.cff/cfffont/glyphidtype) { get; } | Получает спецификацию типа идентификатора глифа. |
| [IsCidKeyedFont](../../aspose.font.cff/cfffont/iscidkeyedfont) { get; } | Получает значение, указывающее, что шрифт имеет ключ cid. |
| override [Metrics](../../aspose.font.cff/cfffont/metrics) { get; } | Получает метрики шрифта. |
| override [NumGlyphs](../../aspose.font.cff/cfffont/numglyphs) { get; } | Получает количество глифов в шрифте. |
| override [PostscriptNames](../../aspose.font.cff/cfffont/postscriptnames) { get; } | Получает имена шрифтов postscript. |
| override [Style](../../aspose.font.cff/cfffont/style) { get; set; } | Получает стиль шрифта. Это необработанное строковое значение, предоставленное файлом шрифта. Установщик стиля еще не реализован. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Convert](../../aspose.font.cff/cfffont/convert)(FontType) | Преобразует шрифт в другой формат. |
| override [GetAllGlyphIds](../../aspose.font.cff/cfffont/getallglyphids)() | Возвращает массив всех идентификаторов глифов, доступных в шрифте. Идентификатор глифа — это уникальный номер для глифа, который зависит от типа шрифта. CFF Идентификатор глифа шрифта может быть экземпляром ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) класс или ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) класс. |
| override [GetGlyphById](../../aspose.font.cff/cfffont/getglyphbyid#getglyphbyid)(GlyphId) | Возвращает глиф по идентификатору глифа. Идентификатор глифа — это уникальный номер для глифа, который зависит от типа шрифта. CFF Идентификатор глифа шрифта может быть экземпляром ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) класс или ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) класс. |
| [GetGlyphById](../../aspose.font.cff/cfffont/getglyphbyid#getglyphbyid_1)(string) | Возвращает глиф по имени глифа. |
| [GetGlyphById](../../aspose.font.cff/cfffont/getglyphbyid#getglyphbyid_2)(uint) | Возвращает глиф по идентификатору глифа. |
| virtual [GetGlyphsForText](../../aspose.font/font/getglyphsfortext)(string) | Получает представление глифов для текста. |
| virtual [Save](../../aspose.font/font/save)(Stream) | Сохраняет шрифт в исходном формате. |
| virtual [Save](../../aspose.font/font/save)(string) | Сохраняет шрифт в исходном формате. |
| [SaveToFormat](../../aspose.font/font/savetoformat)(Stream, FontSavingFormats) | Сохраняет шрифт в указанном формате. |

### Смотрите также

* class [Font](../../aspose.font/font)
* пространство имен [Aspose.Font.Cff](../../aspose.font.cff)
* сборка [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
