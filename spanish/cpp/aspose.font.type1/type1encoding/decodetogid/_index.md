---
title: "Método Aspose::Font::Type1::Type1Encoding::DecodeToGid"
linktitle: "DecodeToGid"
second_title: "Aspose.Font para C++"
description: "Método Aspose::Font::Type1::Type1Encoding::DecodeToGid. Decodifica Gid a Unicode. El id del glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de Type1 es un nombre de glifo, instancia de la clase (GlyphStringId). El id de TTF es un índice entero, instancia de la clase (GlyphUInt32Id) en C++."
type: docs
weight: 100
url: /es/cpp/aspose.font.type1/type1encoding/decodetogid/
---
## Type1Encoding::DecodeToGid method


Decodifica Gid a Unicode. El id del glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de [Type1](../../) es un nombre de glifo, instancia de la clase ([GlyphStringId](../)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../)).

```cpp
System::SharedPtr<Glyphs::GlyphId> Aspose::Font::Type1::Type1Encoding::DecodeToGid(uint32_t charCode) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| charCode | uint32_t | Código de carácter para obtener el identificador de glifo. |

### ReturnValue

Identificador de glifo relacionado con el código de carácter proporcionado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [Type1Encoding](../)
* Namespace [Aspose::Font::Type1](../../)
* Library [Aspose.Font for C++](../../../)
