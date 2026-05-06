---
title: "Método Aspose::Font::Cff::CffEncoding::DecodeToGidParameterized"
linktitle: "DecodeToGidParameterized"
second_title: "Aspose.Font para C++"
description: "Método Aspose::Font::Cff::CffEncoding::DecodeToGidParameterized. Método de decodificación parametrizada. No compatible con el tipo de fuente CFF en C++."
type: docs
weight: 200
url: /es/cpp/aspose.font.cff/cffencoding/decodetogidparameterized/
---
## CffEncoding::DecodeToGidParameterized method


Método de decodificación parametrizada. No compatible con el tipo CFF [Font](../../../aspose.font/font/).

```cpp
System::SharedPtr<Glyphs::GlyphId> Aspose::Font::Cff::CffEncoding::DecodeToGidParameterized(System::SharedPtr<IEncodingParameters> parameters, uint32_t charCode) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parameters | System::SharedPtr\<IEncodingParameters\> | Implementación de la interfaz [IEncodingParameters](../../../aspose.font/iencodingparameters/). |
| charCode | uint32_t | Código de carácter para obtener el identificador de glifo. |

### ReturnValue

Identificador de glifo relacionado con el charCode proporcionado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [IEncodingParameters](../../../aspose.font/iencodingparameters/)
* Class [CffEncoding](../)
* Namespace [Aspose::Font::Cff](../../)
* Library [Aspose.Font for C++](../../../)
