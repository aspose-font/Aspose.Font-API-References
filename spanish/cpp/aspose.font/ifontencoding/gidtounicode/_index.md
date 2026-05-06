---
title: "Aspose::Font::IFontEncoding::GidToUnicode method"
linktitle: "GidToUnicode"
second_title: "Aspose.Font para C++"
description: "Método Aspose::Font::IFontEncoding::GidToUnicode. Decodifica Gid a unicode. El id de glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de Type1 es un nombre de glifo, instancia de la clase (GlyphStringId). El id de TTF es un índice entero, instancia de la clase (GlyphUInt32Id) en C++."
type: docs
weight: 400
url: /es/cpp/aspose.font/ifontencoding/gidtounicode/
---
## IFontEncoding::GidToUnicode method


Decodifica Gid a unicode. El id de glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de [Type1](../../../aspose.font.type1/) es un nombre de glifo, instancia de la clase ([GlyphStringId](../)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../)).

```cpp
virtual uint32_t Aspose::Font::IFontEncoding::GidToUnicode(System::SharedPtr<Glyphs::GlyphId> gid)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gid | System::SharedPtr\<Glyphs::GlyphId\> | Identificador de glifo del símbolo a decodificar. |

### ReturnValue

Valor Unicode relacionado con el id de glifo proporcionado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [IFontEncoding](../)
* Namespace [Aspose::Font](../../)
* Library [Aspose.Font for C++](../../../)
