---
title: "Método Aspose::Font::Type1::Type1Encoding::UnicodeToGid"
linktitle: "UnicodeToGid"
second_title: "Aspose.Font para C++"
description: "Método Aspose::Font::Type1::Type1Encoding::UnicodeToGid. Devuelve GlyphId para Unicode. O notdef si la fuente no contiene un glifo para el Unicode. El id del glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de Type1 es un nombre de glifo, instancia de la clase (GlyphStringId). El id de TTF es un índice entero, instancia de la clase (GlyphUInt32Id) en C++."
type: docs
weight: 600
url: /es/cpp/aspose.font.type1/type1encoding/unicodetogid/
---
## Type1Encoding::UnicodeToGid method


Devuelve GlyphId para Unicode. O notdef si la fuente no contiene un glifo para el Unicode. El id del glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de [Type1](../../) es un nombre de glifo, instancia de la clase ([GlyphStringId](../)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../)).

```cpp
System::SharedPtr<Glyphs::GlyphId> Aspose::Font::Type1::Type1Encoding::UnicodeToGid(uint32_t unicode) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| unicode | uint32_t | Unicode para obtener el identificador de glifo. |

### ReturnValue

Identificador de glifo relacionado con el unicode proporcionado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [Type1Encoding](../)
* Namespace [Aspose::Font::Type1](../../)
* Library [Aspose.Font for C++](../../../)
