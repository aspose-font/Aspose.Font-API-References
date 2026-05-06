---
title: "Clase Aspose::Font::Type1::Type1MetricFont"
linktitle: "Type1MetricFont"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::Type1::Type1MetricFont class. Implementación de fuente métrica Type1. Esta fuente type1 se crea solo usando métricas. Las funciones de recuperación de glifos y otras que requieren una fuente real no están permitidas; las funciones no permitidas lanzan la excepción Type1NotSupportedException. Otras propiedades (FontName, Weight, Metrics y Encoding) se utilizan del archivo de métricas en C++."
type: docs
weight: 500
url: /es/cpp/aspose.font.type1/type1metricfont/
---
## Type1MetricFont class


[Type1](../) metric font implementation. This type1 font is created using metrics only. [Glyphs](../../aspose.font.glyphs/) retrieval functions and some other that require real font are not allowed, not allowed functions throw exception [Type1NotSupportedException](../). Other properties (FontName, Weight, Metrics and Encoding) are used from metrics file.

```cpp
class Type1MetricFont : public Aspose::Font::Type1::Type1Font
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Encoding](./get_encoding/)() override | La codificación se define en el archivo de métricas. StandardAdobeEncoding: la codificación se completa automáticamente. |
| [get_FontFamily](./get_fontfamily/)() override | Obtiene la familia del [Font](../../aspose.font/font/). |
| [get_FontName](./get_fontname/)() override | Obtiene el nombre del [Font](../../aspose.font/font/). |
| [get_FontStyle](./get_fontstyle/)() override | Obtiene el estilo de la [Font](../../aspose.font/font/). Este es un valor calculado y representado en tipo generalizado. |
| [get_NumGlyphs](./get_numglyphs/)() override | Obtiene el número de glifos en la [Font](../../aspose.font/font/). |
| [get_Style](./get_style/)() override | Obtiene el estilo del [Font](../../aspose.font/font/). |
| [GetAllGlyphIds](./getallglyphids/)() override | Devuelve todos los IDs de glifos, disponibles en el [Font](../../aspose.font/font/). No compatible con el tipo [Type1MetricFont](./). |
| [GetGlyphById](./getglyphbyid/)(System::String) override | Devuelve el glifo por ID de glifo. No compatible con el tipo [Type1MetricFont](./). |
| [GetGlyphById](./getglyphbyid/)(System::SharedPtr\<Glyphs::GlyphId\>) override | Devuelve el glifo por ID de glifo. No compatible con el tipo [Type1MetricFont](./). |
## Ver también

* Class [Type1Font](../type1font/)
* Namespace [Aspose::Font::Type1](../)
* Library [Aspose.Font for C++](../../)
