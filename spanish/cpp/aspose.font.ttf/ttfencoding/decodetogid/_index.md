---
title: "Método Aspose::Font::Ttf::TtfEncoding::DecodeToGid"
linktitle: "DecodeToGid"
second_title: "Aspose.Font para C++"
description: "Método Aspose::Font::Ttf::TtfEncoding::DecodeToGid. La implementación DecodeToGlyphId de la fuente TTF encuentra la tabla unicode y devuelve el id del glifo para el carácter unicode. El id del glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de Type1 es un nombre de glifo, instancia de la clase (GlyphStringId). El id de TTF es un índice entero, instancia de la clase (GlyphUInt32Id) en C++."
type: docs
weight: 100
url: /es/cpp/aspose.font.ttf/ttfencoding/decodetogid/
---
## TtfEncoding::DecodeToGid method


La implementación DecodeToGlyphId de TTF [Font](../../../aspose.font/font/) encuentra la tabla unicode y devuelve el id del glifo para el carácter unicode. El id del glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de [Type1](../../../aspose.font.type1/) es un nombre de glifo, instancia de la clase ([GlyphStringId](../)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../)).

```cpp
System::SharedPtr<Glyphs::GlyphId> Aspose::Font::Ttf::TtfEncoding::DecodeToGid(uint32_t unicode) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| unicode | uint32_t | Código de carácter para obtener el identificador de glifo. |

### ReturnValue

Identificador de glifo relacionado con el código de carácter proporcionado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [TtfEncoding](../)
* Namespace [Aspose::Font::Ttf](../../)
* Library [Aspose.Font for C++](../../../)
