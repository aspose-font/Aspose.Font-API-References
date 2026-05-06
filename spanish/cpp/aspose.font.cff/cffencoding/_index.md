---
title: "Aspose::Font::Cff::CffEncoding class"
linktitle: "CffEncoding"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::Cff::CffEncoding class. Representa la codificación de fuentes CFF en C++."
type: docs
weight: 100
url: /es/cpp/aspose.font.cff/cffencoding/
---
## CffEncoding class


Representa la codificación de CFF [Font](../../aspose.font/font/).

```cpp
class CffEncoding : public Aspose::Font::IFontEncoding,
                    public Aspose::Font::ISupportsNameAddressing
```

## Métodos

| Método | Descripción |
| --- | --- |
| [DecodeToGid](./decodetogid/)(uint32_t) override | Obtiene el Gid para el charCode proporcionado. Este método está diseñado para CFF CIDFonts, donde charCode debe ser un valor CID válido. El id del glifo es un número único para un glifo, que depende del tipo de fuente. El id de glifo CFF [Font](../../aspose.font/font/) puede ser una instancia de la clase ([GlyphStringId](../)) o de la clase ([GlyphUInt32Id](../)). |
| [DecodeToGidParameterized](./decodetogidparameterized/)(System::SharedPtr\<IEncodingParameters\>, uint32_t) override | Método de decodificación parametrizada. No compatible con el tipo CFF [Font](../../aspose.font/font/). |
| [Encode](./encode/)(uint32_t, uint32_t) override | Codifica el glifo. No compatible con los tipos CFF [Font](../../aspose.font/font/). |
| [GetNameToCharCodeIndex](./getnametocharcodeindex/)() override | Devuelve el mapa de codificación de nombre a código de carácter. Nota: el código de carácter no es Unicode. El código de carácter es un índice de carácter en la "tabla" de codificación de [Font](../../aspose.font/font/). |
| [GetNameToGidIndex](./getnametogidindex/)() | Devuelve el mapa de codificación de nombre a código de carácter. Nota: el código de carácter no es Unicode. El código de carácter es un índice de carácter en la "tabla" de codificación de [Font](../../aspose.font/font/). |
| [GetNameToSidIndex](./getnametosidindex/)() | Devuelve el mapa de codificación de nombre a código de carácter. Nota: el código de carácter no es Unicode. El código de carácter es un índice de carácter en la "tabla" de codificación de [Font](../../aspose.font/font/). |
| [GetSidName](./getsidname/)(int32_t) | Obtiene el nombre para el SID especificado. |
| [GidToUnicode](./gidtounicode/)(System::SharedPtr\<Glyphs::GlyphId\>) override | Decodifica Gid a Unicode. El id del glifo es un número único para un glifo, que depende del tipo de fuente. El id de glifo CFF [Font](../../aspose.font/font/) puede ser una instancia de la clase ([GlyphStringId](../)) o de la clase ([GlyphUInt32Id](../)). |
| [UnicodeToGid](./unicodetogid/)(uint32_t) override | Decodifica un Unicode y devuelve el id del glifo. El id del glifo es un número único para un glifo, que depende del tipo de fuente. El id de glifo CFF [Font](../../aspose.font/font/) puede ser una instancia de la clase ([GlyphStringId](../)) o de la clase ([GlyphUInt32Id](../)). |
## Ver también

* Class [IFontEncoding](../../aspose.font/ifontencoding/)
* Class [ISupportsNameAddressing](../../aspose.font/isupportsnameaddressing/)
* Namespace [Aspose::Font::Cff](../)
* Library [Aspose.Font for C++](../../)
