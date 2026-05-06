---
title: "Aspose::Font::Cff::CffEncoding::GidToUnicode método"
linktitle: "GidToUnicode"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::Cff::CffEncoding::GidToUnicode método. Decodifica Gid a unicode. El id del glifo es un número único para un glifo, que depende del tipo de fuente. El id de glifo CFF Font puede ser una instancia de la clase (GlyphStringId) o de la clase (GlyphUInt32Id) en C++."
type: docs
weight: 800
url: /es/cpp/aspose.font.cff/cffencoding/gidtounicode/
---
## CffEncoding::GidToUnicode method


Decodifica Gid a unicode. El id del glifo es un número único para un glifo, que depende del tipo de fuente. El id de glifo CFF [Font](../../../aspose.font/font/) puede ser una instancia de la clase ([GlyphStringId](../)) o de la clase ([GlyphUInt32Id](../)).

```cpp
uint32_t Aspose::Font::Cff::CffEncoding::GidToUnicode(System::SharedPtr<Glyphs::GlyphId> gid) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gid | System::SharedPtr\<Glyphs::GlyphId\> | Identificador de glifo del símbolo a decodificar. |

### ReturnValue

Valor Unicode relacionado con el id de glifo proporcionado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [CffEncoding](../)
* Namespace [Aspose::Font::Cff](../../)
* Library [Aspose.Font for C++](../../../)
