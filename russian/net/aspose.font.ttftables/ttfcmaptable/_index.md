---
title: TtfCMapTable
second_title: Справочник по API Aspose.Font для .NET
description: Представляет таблицу cmap файла шрифта TTF.
type: docs
weight: 750
url: /ru/net/aspose.font.ttftables/ttfcmaptable/
---
## TtfCMapTable class

Представляет таблицу "cmap" файла шрифта TTF.

```csharp
public class TtfCMapTable : TtfTableBase
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Offset](../../aspose.font.ttftables/ttftablebase/offset) { get; } | Получает смещение от начала sfnt. |
| [TtfTables](../../aspose.font.ttftables/ttftablebase/ttftables) { get; } | Ссылка на репозиторий таблиц TTF. |
| static [Tag](../../aspose.font.ttftables/ttfcmaptable/tag) { get; } | Получает тег таблицы. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindUnicodeTable](../../aspose.font.ttftables/ttfcmaptable/findunicodetable)() | Ищет и возвращает CMap в формате Юникод. если есть ucs-4 CMap - сначала возвращает его; в противном случае возвращает любую Unicode cmap, которую может найти. |
| [GetAllSubtables](../../aspose.font.ttftables/ttfcmaptable/getallsubtables)() | Возвращает все подтаблицы из таблицы CMap. |
| [GetPlatformTables](../../aspose.font.ttftables/ttfcmaptable/getplatformtables)(ushort, ushort) | Возвращает подтаблицы CMap для planformId и platformSpecificId. |

## Другие члены

| Имя | Описание |
| --- | --- |
| abstract class [TtfCMapSubtableDescription](ttfcmaptable.ttfcmapsubtabledescription) | Предоставляет краткую информацию о подтаблице CMap. |

### Смотрите также

* class [TtfTableBase](../ttftablebase)
* пространство имен [Aspose.Font.TtfTables](../../aspose.font.ttftables)
* сборка [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
