---
title: "Aspose::Font::IFontEncoding::UnicodeToGid method"
linktitle: "UnicodeToGid"
second_title: "Aspose.Font para C++"
description: "Método Aspose::Font::IFontEncoding::UnicodeToGid. Decodifica un unicode y devuelve el id de glifo. El id de glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de Type1 es un nombre de glifo, instancia de la clase (GlyphStringId). El id de TTF es un índice entero, instancia de la clase (GlyphUInt32Id) en C++."
type: docs
weight: 500
url: /es/cpp/aspose.font/ifontencoding/unicodetogid/
---
## IFontEncoding::UnicodeToGid method


Decodifica un unicode y devuelve el id de glifo. El id de glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de [Type1](../../../aspose.font.type1/) es un nombre de glifo, instancia de la clase ([GlyphStringId](../)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../)).

```cpp
virtual System::SharedPtr<Glyphs::GlyphId> Aspose::Font::IFontEncoding::UnicodeToGid(uint32_t unicode)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| unicode | uint32_t | Unicode para obtener el identificador de glifo. |

### ReturnValue

Identificador de glifo relacionado con el unicode proporcionado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [IFontEncoding](../)
* Namespace [Aspose::Font](../../)
* Library [Aspose.Font for C++](../../../)
