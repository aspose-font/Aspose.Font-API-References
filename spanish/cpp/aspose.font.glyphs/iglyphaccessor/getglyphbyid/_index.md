---
title: "Aspose::Font::Glyphs::IGlyphAccessor::GetGlyphById método"
linktitle: "GetGlyphById"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::Glyphs::IGlyphAccessor::GetGlyphById método. Devuelve el glifo por su id de glifo. El id de glifo es un número único para un glifo, que depende del tipo de fuente. GlyphId - objeto derivado. Por ejemplo: el id de Type1 es un nombre de glifo, instancia de la clase (GlyphStringId). El id de TTF es un índice entero, instancia de la clase (GlyphUInt32Id) en C++."
type: docs
weight: 300
url: /es/cpp/aspose.font.glyphs/iglyphaccessor/getglyphbyid/
---
## IGlyphAccessor::GetGlyphById method


Devuelve el glifo por su id de glifo. El id de [Glyph](../../glyph/) es un número único para un glifo, que depende del tipo de fuente. [GlyphId](../../glyphid/) - objeto derivado. Por ejemplo: el id de [Type1](../../../aspose.font.type1/) es un nombre de glifo, instancia de la clase ([GlyphStringId](../../glyphstringid/)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../../glyphuint32id/)).

```cpp
virtual System::SharedPtr<Glyph> Aspose::Font::Glyphs::IGlyphAccessor::GetGlyphById(System::SharedPtr<GlyphId> id)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | System::SharedPtr\<GlyphId\> | ID de glifo. |

### ReturnValue

[Glyph](../../glyph/)

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Glyph](../../glyph/)
* Class [GlyphId](../../glyphid/)
* Class [IGlyphAccessor](../)
* Namespace [Aspose::Font::Glyphs](../../)
* Library [Aspose.Font for C++](../../../)
