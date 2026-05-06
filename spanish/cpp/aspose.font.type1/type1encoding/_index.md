---
title: "Clase Aspose::Font::Type1::Type1Encoding"
linktitle: "Type1Encoding"
second_title: "Aspose.Font para C++"
description: "Clase Aspose::Font::Type1::Type1Encoding. Representa la codificación Type1Font en C++."
type: docs
weight: 200
url: /es/cpp/aspose.font.type1/type1encoding/
---
## Type1Encoding class


Representa la codificación [Type1](../)[Font](../../aspose.font/font/).

```cpp
class Type1Encoding : public Aspose::Font::IFontEncoding,
                      public Aspose::Font::ISupportsNameAddressing
```

## Métodos

| Método | Descripción |
| --- | --- |
| [DecodeToGid](./decodetogid/)(uint32_t) override | Decodifica Gid a unicode. El id del glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de [Type1](../) es un nombre de glifo, instancia de la clase ([GlyphStringId](../)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../)). |
| [DecodeToGidParameterized](./decodetogidparameterized/)(System::SharedPtr\<IEncodingParameters\>, uint32_t) override | Método de decodificación parametrizada. No compatible con el tipo [Type1](../)[Font](../../aspose.font/font/). |
| [Encode](./encode/)(uint32_t, uint32_t) override | Codifica el glifo. Para fuentes TTF el código de carácter es unicode. No compatible con los tipos [Type1](../)[Font](../../aspose.font/font/). |
| [GetNameToCharCodeIndex](./getnametocharcodeindex/)() override | Devuelve el mapa de codificación de nombre a código de carácter. Nota: el código de carácter no es Unicode. El código de carácter es un índice de carácter en la "tabla" de codificación de [Font](../../aspose.font/font/). |
| [GidToUnicode](./gidtounicode/)(System::SharedPtr\<Glyphs::GlyphId\>) override | Decodifica Gid a Unicode. El id del glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de [Type1](../) es un nombre de glifo, instancia de la clase ([GlyphStringId](../)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../)). |
| [UnicodeToGid](./unicodetogid/)(uint32_t) override | Devuelve GlyphId para unicode. O notdef si la fuente no contiene un glifo para el unicode. El id del glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de [Type1](../) es un nombre de glifo, instancia de la clase ([GlyphStringId](../)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../)). |
## Ver también

* Class [IFontEncoding](../../aspose.font/ifontencoding/)
* Class [ISupportsNameAddressing](../../aspose.font/isupportsnameaddressing/)
* Namespace [Aspose::Font::Type1](../)
* Library [Aspose.Font for C++](../../)
