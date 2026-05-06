---
title: "Aspose::Font::Ttf::TtfEncoding::GidToUnicode método"
linktitle: "GidToUnicode"
second_title: "Aspose.Font para C++"
description: "Método Aspose::Font::Ttf::TtfEncoding::GidToUnicode. Decodifica el id del glifo a unicode. El id del glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de Type1 es un nombre de glifo, instancia de la clase (GlyphStringId). El id de TTF es un índice entero, instancia de la clase (GlyphUInt32Id) en C++."
type: docs
weight: 400
url: /es/cpp/aspose.font.ttf/ttfencoding/gidtounicode/
---
## TtfEncoding::GidToUnicode method


Decodifica el id del glifo a unicode. El id del glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de [Type1](../../../aspose.font.type1/) es un nombre de glifo, instancia de la clase ([GlyphStringId](../)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../)).

```cpp
uint32_t Aspose::Font::Ttf::TtfEncoding::GidToUnicode(System::SharedPtr<Glyphs::GlyphId> glyphId) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| glyphId | System::SharedPtr\<Glyphs::GlyphId\> | Identificador de glifo del símbolo a decodificar. |

### ReturnValue

Valor Unicode relacionado con el id de glifo proporcionado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [TtfEncoding](../)
* Namespace [Aspose::Font::Ttf](../../)
* Library [Aspose.Font for C++](../../../)
