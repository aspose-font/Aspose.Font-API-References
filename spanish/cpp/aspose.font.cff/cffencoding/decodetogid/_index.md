---
title: "Método Aspose::Font::Cff::CffEncoding::DecodeToGid"
linktitle: "DecodeToGid"
second_title: "Aspose.Font para C++"
description: "Método Aspose::Font::Cff::CffEncoding::DecodeToGid. Obtiene el Gid para el charCode proporcionado. Este método está diseñado para CFF CIDFonts, donde el charCode debe ser un valor CID válido. El id del glifo es un número único para un glifo, que depende del tipo de fuente. El id del glifo de una fuente CFF puede ser una instancia de la clase (GlyphStringId) o de la clase (GlyphUInt32Id) en C++."
type: docs
weight: 100
url: /es/cpp/aspose.font.cff/cffencoding/decodetogid/
---
## CffEncoding::DecodeToGid method


Obtiene el Gid para el charCode proporcionado. Este método está diseñado para CFF CIDFonts, donde el charCode debe ser un valor CID válido. El id del glifo es un número único para un glifo, que depende del tipo de fuente. El id del glifo de una [Font](../../../aspose.font/font/) CFF puede ser una instancia de la clase ([GlyphStringId](../)) o de la clase ([GlyphUInt32Id](../)).

```cpp
System::SharedPtr<Glyphs::GlyphId> Aspose::Font::Cff::CffEncoding::DecodeToGid(uint32_t charCode) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| charCode | uint32_t | Código de carácter (CID) para obtener el identificador de glifo. |

### ReturnValue

Identificador de glifo relacionado con el CID proporcionado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [CffEncoding](../)
* Namespace [Aspose::Font::Cff](../../)
* Library [Aspose.Font for C++](../../../)
