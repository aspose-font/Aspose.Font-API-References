---
title: GetGlyphById
second_title: Справочник по API Aspose.Font для .NET
description: Возвращает глиф по идентификатору глифа. Идентификатор глифа  это уникальный номер глифа который зависит от типа шрифта. Идентификатор глифа шрифта TTF может быть экземпляром класса GlyphStringIdaspose.font.glyphs/glyphstringid или класса GlyphUInt32Idaspose.font.glyphs/glyphuint32id . Адресация глифа имени строки поддерживается для шрифтов TTF через сопоставление таблицы Post. В случае если CFF Font внутри структуры CFF используются для адресации глифов по имени.
type: docs
weight: 180
url: /ru/net/aspose.font.ttf/ttffont/getglyphbyid/
---
## GetGlyphById(GlyphId) {#getglyphbyid}

Возвращает глиф по идентификатору глифа. Идентификатор глифа — это уникальный номер глифа, который зависит от типа шрифта. Идентификатор глифа шрифта TTF может быть экземпляром класса ([`GlyphStringId`](../../../aspose.font.glyphs/glyphstringid)) или класса ([`GlyphUInt32Id`](../../../aspose.font.glyphs/glyphuint32id)) . Адресация глифа имени (строки) поддерживается для шрифтов TTF через сопоставление таблицы Post. В случае, если CFF Font внутри, структуры CFF используются для адресации глифов по имени.

```csharp
public override Glyph GetGlyphById(GlyphId id)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| id | GlyphId | Идентификатор глифа. |

### Возвращаемое значение

Глиф.

### Смотрите также

* class [Glyph](../../../aspose.font.glyphs/glyph)
* class [GlyphId](../../../aspose.font.glyphs/glyphid)
* class [TtfFont](../../ttffont)
* пространство имен [Aspose.Font.Ttf](../../ttffont)
* сборка [Aspose.Font](../../../)

---

## GetGlyphById(string) {#getglyphbyid_1}

Возвращает глиф по имени глифа. Адресация глифа имени (строки) поддерживается для шрифтов TTF через сопоставление таблицы Post. В случае, если CFF Font внутри, структуры CFF используются для адресации глифов по имени.

```csharp
public Glyph GetGlyphById(string glyphName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| glyphName | String | Идентификатор строки глифа. |

### Возвращаемое значение

Глиф.

### Смотрите также

* class [Glyph](../../../aspose.font.glyphs/glyph)
* class [TtfFont](../../ttffont)
* пространство имен [Aspose.Font.Ttf](../../ttffont)
* сборка [Aspose.Font](../../../)

---

## GetGlyphById(uint) {#getglyphbyid_2}

Возвращает глиф по идентификатору глифа.

```csharp
public Glyph GetGlyphById(uint id)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| id | UInt32 | Индекс глифа. |

### Возвращаемое значение

Глиф.

### Смотрите также

* class [Glyph](../../../aspose.font.glyphs/glyph)
* class [TtfFont](../../ttffont)
* пространство имен [Aspose.Font.Ttf](../../ttffont)
* сборка [Aspose.Font](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->