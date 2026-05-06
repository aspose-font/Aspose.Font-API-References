---
title: "Aspose::Font::Font::GetGlyphById method"
linktitle: "GetGlyphById"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::Font::GetGlyphById method. Devuelve un glifo por su id de glifo. El id de glifo es un número único para un glifo, que depende del tipo de fuente. GlyphId - objeto derivado. Por ejemplo: el id de Type1 es un nombre de glifo, instancia de la clase (GlyphStringId). El id de TTF es un índice entero, instancia de la clase (GlyphUInt32Id) en C++."
type: docs
weight: 1700
url: /es/cpp/aspose.font/font/getglyphbyid/
---
## Font::GetGlyphById method


Devuelve el glifo por id de glifo. El id de glifo es un número único para un glifo, que depende del tipo de fuente. GlyphId - objeto derivado. Por ejemplo: el id de [Type1](../../../aspose.font.type1/) es un nombre de glifo, instancia de la clase ([GlyphStringId](../)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../)).

```cpp
System::SharedPtr<Glyphs::Glyph> Aspose::Font::Font::GetGlyphById(System::SharedPtr<Glyphs::GlyphId> id) override=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | System::SharedPtr\<Glyphs::GlyphId\> | Id del glifo. |

### ReturnValue

Glifo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Glyph](../../../aspose.font.glyphs/glyph/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [Font](../)
* Namespace [Aspose::Font](../../)
* Library [Aspose.Font for C++](../../../)
