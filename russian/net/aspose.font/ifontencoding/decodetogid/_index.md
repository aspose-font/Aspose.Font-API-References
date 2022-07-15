---
title: DecodeToGid
second_title: Справочник по API Aspose.Font для .NET
description: Декодирует код символа и возвращает идентификатор глифа. Идентификатор глифа  это уникальный номер глифа который зависит от типа шрифта. Например Идентификатор Type1  это имя глифа экземпляр класса GlyphStringIdaspose.font.glyphs/glyphstringid. Идентификатор TTF является индексом int экземпляром класса GlyphUInt32Idaspose.font.glyphs/glyphuint32id. Примечание код символа в юникоде не обязателен. Код символа представляет собой индекс символа в таблице кодирования шрифта.
type: docs
weight: 10
url: /ru/net/aspose.font/ifontencoding/decodetogid/
---
## IFontEncoding.DecodeToGid method

Декодирует код символа и возвращает идентификатор глифа. Идентификатор глифа — это уникальный номер глифа, который зависит от типа шрифта. Например: Идентификатор Type1 — это имя глифа, экземпляр класса ([`GlyphStringId`](../../../aspose.font.glyphs/glyphstringid)). Идентификатор TTF является индексом int, экземпляром класса ([`GlyphUInt32Id`](../../../aspose.font.glyphs/glyphuint32id)). Примечание: код символа в юникоде не обязателен. Код символа представляет собой индекс символа в «таблице кодирования шрифта».

```csharp
public GlyphId DecodeToGid(uint charCode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| charCode | UInt32 | Код символа, для которого нужно получить идентификатор глифа. |

### Возвращаемое значение

Идентификатор глифа, связанный с переданным charCode.

### Смотрите также

* class [GlyphId](../../../aspose.font.glyphs/glyphid)
* interface [IFontEncoding](../../ifontencoding)
* пространство имен [Aspose.Font](../../ifontencoding)
* сборка [Aspose.Font](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->