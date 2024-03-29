---
title: Type1MetricFont
second_title: Справочник по API Aspose.Font для .NET
description: Реализация метрического шрифта Type1. Этот шрифт type1 создан с использованием только метрик. Функции извлечения глифов и некоторые другие требующие реального шрифта не разрешены не разрешенные функции вызывают исключениеType1NotSupportedException . Другие свойства Имя шрифта Вес Метрики и Кодировка используются из файла метрик.
type: docs
weight: 1080
url: /ru/net/aspose.font.type1/type1metricfont/
---
## Type1MetricFont class

Реализация метрического шрифта Type1. Этот шрифт type1 создан с использованием только метрик. Функции извлечения глифов и некоторые другие, требующие реального шрифта, не разрешены, не разрешенные функции вызывают исключениеType1NotSupportedException . Другие свойства (Имя шрифта, Вес, Метрики и Кодировка) используются из файла метрик.

```csharp
public class Type1MetricFont : Type1Font
```

## Характеристики

| Имя | Описание |
| --- | --- |
| override [Encoding](../../aspose.font.type1/type1metricfont/encoding) { get; } | Кодировка определяется в файле метрик. StandardAdobeEncoding: кодировка заполняется автоматически |
| override [FontDefinition](../../aspose.font.type1/type1font/fontdefinition) { get; } | Получает определение шрифта. |
| override [FontFamily](../../aspose.font.type1/type1metricfont/fontfamily) { get; } | Получает семейство шрифтов. |
| override [FontName](../../aspose.font.type1/type1metricfont/fontname) { get; } | Получает имя шрифта. |
| override [FontNames](../../aspose.font.type1/type1font/fontnames) { get; } | Получает имена шрифтов. |
| [FontSaver](../../aspose.font/font/fontsaver) { get; } | Получает функцию сохранения шрифта. |
| override [FontStyle](../../aspose.font.type1/type1metricfont/fontstyle) { get; } | Получает стиль шрифта. Это значение вычисляется и представляется в обобщенном виде. |
| override [FontType](../../aspose.font.type1/type1font/fonttype) { get; } | Получает тип шрифта. Возвращает значение FontType.Type1. |
| [GlyphAccessor](../../aspose.font/font/glyphaccessor) { get; } | Аксессуар глифа шрифта. Извлекает глифы и идентификаторы глифов. |
| override [GlyphIdType](../../aspose.font.type1/type1font/glyphidtype) { get; } | Спецификация типа идентификатора глифа. |
| override [Metrics](../../aspose.font.type1/type1font/metrics) { get; } | Получает метрики шрифта. |
| override [NumGlyphs](../../aspose.font.type1/type1metricfont/numglyphs) { get; } | Получает количество глифов в шрифте. |
| override [PostscriptNames](../../aspose.font.type1/type1font/postscriptnames) { get; } | Получает имена шрифтов postscript. |
| override [Style](../../aspose.font.type1/type1metricfont/style) { get; } | Получает стиль шрифта. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Convert](../../aspose.font.type1/type1font/convert)(FontType) | Преобразует шрифт в другой формат. |
| override [GetAllGlyphIds](../../aspose.font.type1/type1metricfont/getallglyphids)() | Возвращает все идентификаторы глифов, доступные в шрифте. Не поддерживается для[`Type1MetricFont`](../type1metricfont)тип. |
| override [GetGlyphById](../../aspose.font.type1/type1metricfont/getglyphbyid#getglyphbyid)(GlyphId) | Возвращает глиф по идентификатору глифа. Не поддерживается для[`Type1MetricFont`](../type1metricfont)тип. |
| override [GetGlyphById](../../aspose.font.type1/type1metricfont/getglyphbyid#getglyphbyid_1)(string) | Возвращает глиф по идентификатору глифа. Не поддерживается для[`Type1MetricFont`](../type1metricfont)тип. |
| [GetGlyphById](../../aspose.font.type1/type1font/getglyphbyid)(uint) | Возвращает глиф по идентификатору глифа. |
| virtual [GetGlyphsForText](../../aspose.font/font/getglyphsfortext)(string) | Получает представление глифов для текста. |
| virtual [Save](../../aspose.font/font/save)(Stream) | Сохраняет шрифт в исходном формате. |
| virtual [Save](../../aspose.font/font/save)(string) | Сохраняет шрифт в исходном формате. |
| [SaveToFormat](../../aspose.font/font/savetoformat)(Stream, FontSavingFormats) | Сохраняет шрифт в указанном формате. |

### Примеры

Примечание. Если файл метрик определяет кодировку как «FontSpecific», пользователь должен указать конкретную кодировку следующим образом:  System::ArrayPtr&lt;System::String&gt; zapfDingbatsEncoding = System::MakeArray&lt;System::String&gt;({nullptr, nullptr, ..., u"space", u"a1", ...}); FontEnvironment::get_Current()-&gt;get_FontSpecificEncodings()-&gt;RegisterEncoding(u"ZapfDingbats", zapfDingbatsEncoding);

```csharp
string[] zapfDingbatsEncoding = new string[256] {null, null, ... , "space", "a1", ...};
FontEnvironment.Current.FontSpecificEncodings.RegisterEncoding("ZapfDingbats", zapfDingbatsEncoding);
```

### Смотрите также

* class [Type1Font](../type1font)
* пространство имен [Aspose.Font.Type1](../../aspose.font.type1)
* сборка [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
