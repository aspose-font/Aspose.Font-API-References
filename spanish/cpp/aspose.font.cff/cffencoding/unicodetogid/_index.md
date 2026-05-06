---
title: "Método Aspose::Font::Cff::CffEncoding::UnicodeToGid"
linktitle: "UnicodeToGid"
second_title: "Aspose.Font para C++"
description: "Método Aspose::Font::Cff::CffEncoding::UnicodeToGid. Decodifica un unicode y devuelve el id del glifo. El id del glifo es un número único para un glifo, que depende del tipo de fuente. El id del glifo de una fuente CFF puede ser una instancia de la clase (GlyphStringId) o de la clase (GlyphUInt32Id) en C++."
type: docs
weight: 900
url: /es/cpp/aspose.font.cff/cffencoding/unicodetogid/
---
## CffEncoding::UnicodeToGid method


Decodifica un unicode y devuelve el id del glifo. El id del glifo es un número único para un glifo, que depende del tipo de fuente. El id del glifo de una [Font](../../../aspose.font/font/) CFF puede ser una instancia de la clase ([GlyphStringId](../)) o de la clase ([GlyphUInt32Id](../)).

```cpp
System::SharedPtr<Glyphs::GlyphId> Aspose::Font::Cff::CffEncoding::UnicodeToGid(uint32_t unicode) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| unicode | uint32_t | Unicode para obtener el identificador de glifo. |

### ReturnValue

Identificador de glifo relacionado con el unicode proporcionado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [CffEncoding](../)
* Namespace [Aspose::Font::Cff](../../)
* Library [Aspose.Font for C++](../../../)
