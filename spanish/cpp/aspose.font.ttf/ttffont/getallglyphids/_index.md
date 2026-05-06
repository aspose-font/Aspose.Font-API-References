---
title: "Aspose::Font::Ttf::TtfFont::GetAllGlyphIds método"
linktitle: "GetAllGlyphIds"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::Ttf::TtfFont::GetAllGlyphIds método. Devuelve una matriz de todos los identificadores de glif, disponibles en la Fuente. El identificador de glif es un número único para un glif, que depende del tipo de fuente. El identificador de glif de una Fuente TTF puede ser una instancia de la clase (GlyphStringId) o de la clase (GlyphUInt32Id). La direccionamiento de glif por nombre (cadena) está soportado para Fuentes TTF mediante el mapeo de la tabla Post. En caso de que haya una Fuente CFF dentro, se utilizan las estructuras CFF para direccionar los glif por nombre en C++."
type: docs
weight: 1700
url: /es/cpp/aspose.font.ttf/ttffont/getallglyphids/
---
## TtfFont::GetAllGlyphIds method


Devuelve una matriz de todos los identificadores de glif, disponibles en la [Fuente](../../../aspose.font/font/). El identificador de glif es un número único para un glif, que depende del tipo de fuente. El identificador de glif de una [Fuente](../../../aspose.font/font/) TTF puede ser una instancia de la clase ([GlyphStringId](../)) o de la clase ([GlyphUInt32Id](../)). La direccionamiento de glif por nombre (cadena) está soportado para Fuentes TTF mediante el mapeo de la tabla Post. En caso de que haya una [Fuente](../../../aspose.font/font/) CFF dentro, se utilizan las estructuras CFF para direccionar los glif por nombre.

```cpp
System::ArrayPtr<System::SharedPtr<Glyphs::GlyphId>> Aspose::Font::Ttf::TtfFont::GetAllGlyphIds() override
```


### ReturnValue

Identificadores de glif.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [TtfFont](../)
* Namespace [Aspose::Font::Ttf](../../)
* Library [Aspose.Font for C++](../../../)
