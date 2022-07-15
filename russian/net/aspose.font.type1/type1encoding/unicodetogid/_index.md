---
title: UnicodeToGid
second_title: Справочник по API Aspose.Font для .NET
description: Возвращает GlyphId для Юникода. Или notdef если шрифт не содержит глифа для юникода. Идентификатор глифа  это уникальный номер глифа который зависит от типа шрифта. Например Идентификатор Type1  это имя глифа экземпляр класса GlyphStringIdaspose.font.glyphs/glyphstringid. Идентификатор TTF является индексом int экземпляром класса GlyphUInt32Idaspose.font.glyphs/glyphuint32id.
type: docs
weight: 60
url: /ru/net/aspose.font.type1/type1encoding/unicodetogid/
---
## Type1Encoding.UnicodeToGid method

Возвращает GlyphId для Юникода. Или notdef, если шрифт не содержит глифа для юникода. Идентификатор глифа — это уникальный номер глифа, который зависит от типа шрифта. Например: Идентификатор Type1 — это имя глифа, экземпляр класса ([`GlyphStringId`](../../../aspose.font.glyphs/glyphstringid)). Идентификатор TTF является индексом int, экземпляром класса ([`GlyphUInt32Id`](../../../aspose.font.glyphs/glyphuint32id)).

```csharp
public GlyphId UnicodeToGid(uint unicode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| unicode | UInt32 | Юникод, для которого нужно получить идентификатор глифа. |

### Возвращаемое значение

Идентификатор глифа, связанный с переданным юникодом.

### Смотрите также

* class [GlyphId](../../../aspose.font.glyphs/glyphid)
* class [Type1Encoding](../../type1encoding)
* пространство имен [Aspose.Font.Type1](../../type1encoding)
* сборка [Aspose.Font](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->