---
title: "Aspose::Font::IFontEncoding::DecodeToGidParameterized method"
linktitle: "DecodeToGidParameterized"
second_title: "Aspose.Font para C++"
description: "Método Aspose::Font::IFontEncoding::DecodeToGidParameterized. Método de decodificación parametrizada en C++."
type: docs
weight: 200
url: /es/cpp/aspose.font/ifontencoding/decodetogidparameterized/
---
## IFontEncoding::DecodeToGidParameterized method


Método de decodificación parametrizado.

```cpp
virtual System::SharedPtr<Glyphs::GlyphId> Aspose::Font::IFontEncoding::DecodeToGidParameterized(System::SharedPtr<IEncodingParameters> parameters, uint32_t charCode)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parameters | System::SharedPtr\<IEncodingParameters\> | Implementación de la interfaz [IEncodingParameters](../../iencodingparameters/). |
| charCode | uint32_t | Código de carácter para obtener el identificador de glifo. |

### ReturnValue

Identificador de glifo relacionado con el código de carácter proporcionado.
## Observaciones


Algunos tipos de fuentes pueden tener múltiples algoritmos/mapas de codificación. Por lo tanto, la interfaz [IEncodingParameters](../../iencodingparameters/) se utiliza para crear parámetros concretos de codificación de fuentes.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [IEncodingParameters](../../iencodingparameters/)
* Class [IFontEncoding](../)
* Namespace [Aspose::Font](../../)
* Library [Aspose.Font for C++](../../../)
