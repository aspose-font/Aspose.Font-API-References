---
title: "Clase Aspose::Font::Ttf::TtfEncoding"
linktitle: "TtfEncoding"
second_title: "Aspose.Font para C++"
description: "Clase Aspose::Font::Ttf::TtfEncoding. Representa la codificación de fuentes TTF en C++."
type: docs
weight: 400
url: /es/cpp/aspose.font.ttf/ttfencoding/
---
## TtfEncoding class


Representa la codificación de la [Font](../../aspose.font/font/) TTF.

```cpp
class TtfEncoding : public Aspose::Font::IFontEncoding
```

## Métodos

| Método | Descripción |
| --- | --- |
| [DecodeToGid](./decodetogid/)(uint32_t) override | La implementación DecodeToGlyphId de la [Font](../../aspose.font/font/) TTF busca la tabla unicode y devuelve el id de glifo para el carácter unicode. El id de glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de la [Type1](../../aspose.font.type1/) es un nombre de glifo, instancia de la clase ([GlyphStringId](../)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../)). |
| [DecodeToGidParameterized](./decodetogidparameterized/)(System::SharedPtr\<IEncodingParameters\>, uint32_t) override | La versión parametrizada permite usar una tabla CMap específica (no unicode). |
| [Encode](./encode/)(uint32_t, uint32_t) override | Codifica el glifo. Para fuentes TTF el código de carácter es unicode. |
| [GidToUnicode](./gidtounicode/)(System::SharedPtr\<Glyphs::GlyphId\>) override | Decodifica el id del glifo a Unicode. El id del glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: [Type1](../../aspose.font.type1/)'s id es un nombre de glifo, instancia de la clase ([GlyphStringId](../)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../)). |
| [UnicodeToGid](./unicodetogid/)(uint32_t) override | Decodifica un Unicode y devuelve el id del glifo. |
## Ver también

* Class [IFontEncoding](../../aspose.font/ifontencoding/)
* Namespace [Aspose::Font::Ttf](../)
* Library [Aspose.Font for C++](../../)
