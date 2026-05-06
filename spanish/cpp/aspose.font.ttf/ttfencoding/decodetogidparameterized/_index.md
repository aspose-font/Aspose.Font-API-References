---
title: "Método Aspose::Font::Ttf::TtfEncoding::DecodeToGidParameterized"
linktitle: "DecodeToGidParameterized"
second_title: "Aspose.Font para C++"
description: "Método Aspose::Font::Ttf::TtfEncoding::DecodeToGidParameterized. La versión parametrizada permite usar una tabla CMap específica (no unicode) en C++."
type: docs
weight: 200
url: /es/cpp/aspose.font.ttf/ttfencoding/decodetogidparameterized/
---
## TtfEncoding::DecodeToGidParameterized method


La versión parametrizada permite usar una tabla CMap específica (no unicode).

```cpp
System::SharedPtr<Glyphs::GlyphId> Aspose::Font::Ttf::TtfEncoding::DecodeToGidParameterized(System::SharedPtr<IEncodingParameters> parameters, uint32_t charCode) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parameters | System::SharedPtr\<IEncodingParameters\> | Implementación de la interfaz [IEncodingParameters](../../../aspose.font/iencodingparameters/). |
| charCode | uint32_t | Código de carácter para obtener el identificador de glifo. |

### ReturnValue

Identificador de glifo relacionado con el código de carácter proporcionado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [IEncodingParameters](../../../aspose.font/iencodingparameters/)
* Class [TtfEncoding](../)
* Namespace [Aspose::Font::Ttf](../../)
* Library [Aspose.Font for C++](../../../)
