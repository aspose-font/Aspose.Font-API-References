---
title: "Clase Aspose::Font::Glyphs::IGlyphAccessor"
linktitle: "IGlyphAccessor"
second_title: "Aspose.Font para C++"
description: "Clase Aspose::Font::Glyphs::IGlyphAccessor. Define la funcionalidad para recuperar identificadores de glifos especificados y glifos en C++."
type: docs
weight: 1000
url: /es/cpp/aspose.font.glyphs/iglyphaccessor/
---
## IGlyphAccessor class


Define la funcionalidad para recuperar los identificadores de glifos especificados y los glifos.

```cpp
class IGlyphAccessor : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [get_GlyphIdType](./get_glyphidtype/)() | [Glyph](../glyph/) especificación del tipo de id. |
| virtual [GetAllGlyphIds](./getallglyphids/)() | Devuelve todos los IDs de glifos, disponibles en la [Font](../../aspose.font/font/). El ID de [Glyph](../glyph/) es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el ID de [Type1](../../aspose.font.type1/) es un nombre de glifo, instancia de la clase ([GlyphStringId](../glyphstringid/)). El ID de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../glyphuint32id/)). |
| virtual [GetGlyphById](./getglyphbyid/)(System::SharedPtr\<GlyphId\>) | Devuelve el glifo por su ID de glifo. El ID de [Glyph](../glyph/) es un número único para un glifo, que depende del tipo de fuente. [GlyphId](../glyphid/) - objeto derivado. Por ejemplo: el ID de [Type1](../../aspose.font.type1/) es un nombre de glifo, instancia de la clase ([GlyphStringId](../glyphstringid/)). El ID de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../glyphuint32id/)). |
| virtual [GetGlyphsForText](./getglyphsfortext/)(System::String) | Obtenga la representación de glifos para el texto. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Font::Glyphs](../)
* Library [Aspose.Font for C++](../../)
