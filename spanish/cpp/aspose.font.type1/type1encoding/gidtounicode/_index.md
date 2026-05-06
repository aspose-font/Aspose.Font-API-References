---
title: "Método Aspose::Font::Type1::Type1Encoding::GidToUnicode"
linktitle: "GidToUnicode"
second_title: "Aspose.Font para C++"
description: "Método Aspose::Font::Type1::Type1Encoding::GidToUnicode. Decodifica Gid a Unicode. El id del glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de Type1 es un nombre de glifo, instancia de la clase (GlyphStringId). El id de TTF es un índice entero, instancia de la clase (GlyphUInt32Id) en C++."
type: docs
weight: 500
url: /es/cpp/aspose.font.type1/type1encoding/gidtounicode/
---
## Type1Encoding::GidToUnicode method


Decodifica Gid a Unicode. El id del glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de [Type1](../../) es un nombre de glifo, instancia de la clase ([GlyphStringId](../)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../)).

```cpp
uint32_t Aspose::Font::Type1::Type1Encoding::GidToUnicode(System::SharedPtr<Glyphs::GlyphId> gid) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gid | System::SharedPtr\<Glyphs::GlyphId\> | Identificador de glifo del símbolo a decodificar. |

### ReturnValue

Valor Unicode relacionado con el id de glifo proporcionado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [Type1Encoding](../)
* Namespace [Aspose::Font::Type1](../../)
* Library [Aspose.Font for C++](../../../)
