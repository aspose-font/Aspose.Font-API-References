---
title: "Aspose::Font::IFontEncoding::DecodeToGid method"
linktitle: "DecodeToGid"
second_title: "Aspose.Font para C++"
description: "Método Aspose::Font::IFontEncoding::DecodeToGid. Decodifica un código de carácter y devuelve el id de glifo. El id de glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de Type1 es un nombre de glifo, instancia de la clase (GlyphStringId). El id de TTF es un índice entero, instancia de la clase (GlyphUInt32Id). Nota: el código de carácter no es necesariamente un unicode. El código de carácter es un índice de carácter en la \\\"tabla\\\" de codificación de Font en C++."
type: docs
weight: 100
url: /es/cpp/aspose.font/ifontencoding/decodetogid/
---
## IFontEncoding::DecodeToGid method


Decodifica un código de carácter y devuelve el id de glifo. El id de glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de [Type1](../../../aspose.font.type1/) es un nombre de glifo, instancia de la clase ([GlyphStringId](../)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../)). Nota: el código de carácter no es necesariamente un unicode. El código de carácter es un índice de carácter en la codificación \"tabla\" de [Font](../../font/).

```cpp
virtual System::SharedPtr<Glyphs::GlyphId> Aspose::Font::IFontEncoding::DecodeToGid(uint32_t charCode)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| charCode | uint32_t | Código de carácter para obtener el identificador de glifo. |

### ReturnValue

Identificador de glifo relacionado con el charCode proporcionado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [IFontEncoding](../)
* Namespace [Aspose::Font](../../)
* Library [Aspose.Font for C++](../../../)
