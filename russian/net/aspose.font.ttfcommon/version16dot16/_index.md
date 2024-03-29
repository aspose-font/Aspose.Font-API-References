---
title: Version16Dot16
second_title: Справочник по API Aspose.Font для .NET
description: Повторно отображает тип данных Version16Dot16
type: docs
weight: 730
url: /ru/net/aspose.font.ttfcommon/version16dot16/
---
## Version16Dot16 class

Повторно отображает тип данных Version16Dot16

```csharp
public class Version16Dot16 : ICloneable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Version16Dot16](version16dot16#constructor)() | Конструктор |
| [Version16Dot16](version16dot16#constructor_1)(ushort, ushort) | Конструктор |

## Характеристики

| Имя | Описание |
| --- | --- |
| [MajorNumber](../../aspose.font.ttfcommon/version16dot16/majornumber) { get; set; } | Получает или задает основной номер версии. Значение имеет смысл только в шестнадцатеричной записи, например версия 0.5 для 'maxp' в реальных файлах шрифтов составляет 4 байта: {0, 0, 80, 0}, что имеет шестнадцатеричное представление 0x00005000. После чтения этой версии из файла шрифта , Старший и младший номера для объекта[`Version16Dot16`](../version16dot16) будет 0 и 20480 соответственно. И эти значения в шестнадцатеричной форме 0x0000 и 0x5000. |
| [MinorNumber](../../aspose.font.ttfcommon/version16dot16/minornumber) { get; set; } | Получает или устанавливает младший номер версии Значение имеет смысл только в шестнадцатеричном представлении, например версия 0.5 для 'maxp' в реальных файлах шрифтов составляет 4 байта: {0, 0, 80, 0}, что имеет шестнадцатеричное представление 0x00005000. После чтение этой версии из файла шрифта, основные и второстепенные номера для объекта[`Version16Dot16`](../version16dot16) будет 0 и 20480 соответственно. И эти значения в шестнадцатеричной форме 0x0000 и 0x5000. |
| [RawBytes](../../aspose.font.ttfcommon/version16dot16/rawbytes) { get; } | Получает все необработанные биты для номера версии Version16Dot16 в виде массива байтов размером 4 байта. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Clone](../../aspose.font.ttfcommon/version16dot16/clone)() | Создать копию[`Version16Dot16`](../version16dot16) объект. |
| override [ToString](../../aspose.font.ttfcommon/version16dot16/tostring)() | Возвращает значение версии в виде форматированной строки Например, "0.5", "1.1", "3.0" и т. д. |

### Смотрите также

* пространство имен [Aspose.Font.TtfCommon](../../aspose.font.ttfcommon)
* сборка [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
