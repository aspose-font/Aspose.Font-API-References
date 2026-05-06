---
title: "Aspose::Font::IFontEncoding class"
linktitle: "IFontEncoding"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::IFontEncoding class. Define una interfaz para la codificación de fuentes en C++."
type: docs
weight: 1400
url: /es/cpp/aspose.font/ifontencoding/
---
## IFontEncoding class


Define una interfaz para la codificación de [Font](../font/).

```cpp
class IFontEncoding : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [DecodeToGid](./decodetogid/)(uint32_t) | Decodifica un código de carácter y devuelve el id del glifo. El id del glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: [Type1](../../aspose.font.type1/)'s id es un nombre de glifo, instancia de la clase ([GlyphStringId](../)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../)). Nota: el código de carácter no es necesariamente unicode. El código de carácter es un índice de caracteres en la codificación "tabla" de [Font](../font/). |
| virtual [DecodeToGidParameterized](./decodetogidparameterized/)(System::SharedPtr\<IEncodingParameters\>, uint32_t) | Método de decodificación parametrizado. |
| virtual [Encode](./encode/)(uint32_t, uint32_t) | Codifica el glifo. Para fuentes TTF, el charCode es unicode. |
| virtual [GidToUnicode](./gidtounicode/)(System::SharedPtr\<Glyphs::GlyphId\>) | Decodifica Gid a unicode. El id del glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: [Type1](../../aspose.font.type1/)'s id es un nombre de glifo, instancia de la clase ([GlyphStringId](../)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../)). |
| virtual [UnicodeToGid](./unicodetogid/)(uint32_t) | Decodifica un unicode y devuelve el id del glifo. El id del glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: [Type1](../../aspose.font.type1/)'s id es un nombre de glifo, instancia de la clase ([GlyphStringId](../)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../)). |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Font](../)
* Library [Aspose.Font for C++](../../)
