---
title: "Clase Aspose::Font::Glyphs::GlyphId"
linktitle: "GlyphId"
second_title: "Aspose.Font para C++"
description: "Clase Aspose::Font::Glyphs::GlyphId. Representa los ids de glifo, disponibles en la Fuente. El id de glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de Type1'' es un nombre de glifo, instancia de la clase (GlyphStringId). El id de TTF'' es un índice entero, instancia de la clase (GlyphUInt32Id) en C++."
type: docs
weight: 500
url: /es/cpp/aspose.font.glyphs/glyphid/
---
## GlyphId class


Representa los ids de glifo, disponibles en el [Font](../../aspose.font/font/). El id del [Glyph](../glyph/) es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de [Type1](../../aspose.font.type1/)'s es un nombre de glifo, instancia de la clase ([GlyphStringId](../glyphstringid/)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../glyphuint32id/)).

```cpp
class GlyphId : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [CompareTo](./compareto/)(System::SharedPtr\<GlyphId\>) |  |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Devuelve true si dos identificadores de glifo no son iguales. |
| virtual [GetHashCode](./gethashcode/)() const | Devuelve el código hash del objeto. |
| virtual [ToGlyphStringId](./toglyphstringid/)() | Conversión virtual a [GlyphUInt32Id](../glyphuint32id/). [GlyphUInt32Id](../glyphuint32id/) sobrescribe para devolver la instancia. |
| virtual [ToGlyphUInt32Id](./toglyphuint32id/)() | Conversión virtual a [GlyphUInt32Id](../glyphuint32id/). [GlyphUInt32Id](../glyphuint32id/) sobrescribe para devolver la instancia. |
| virtual [ToString](./tostring/)() const | Devuelve la representación en cadena del id del glifo. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Font::Glyphs](../)
* Library [Aspose.Font for C++](../../)
