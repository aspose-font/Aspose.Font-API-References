---
title: "Clase Aspose::Font::IFontMetrics"
linktitle: "IFontMetrics"
second_title: "Aspose.Font para C++"
description: "Clase Aspose::Font::IFontMetrics. Define una interfaz para herramientas de métricas de Font en C++."
type: docs
weight: 1600
url: /es/cpp/aspose.font/ifontmetrics/
---
## IFontMetrics class


Define una interfaz para herramientas de métricas de [Font](../font/).

```cpp
class IFontMetrics : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [get_Ascender](./get_ascender/)() | Obtiene el valor ascendente del [Font](../font/) en unidades de fuente. |
| virtual [get_Descender](./get_descender/)() | Obtiene el valor descendente del [Font](../font/) en unidades de fuente. |
| virtual [get_FontBBox](./get_fontbbox/)() | Obtiene el cuadro delimitador del [Font](../font/). |
| virtual [get_FontMatrix](./get_fontmatrix/)() | Obtiene la matriz de transformación del [Font](../font/). |
| virtual [get_IsFixedPitch](./get_isfixedpitch/)() | Verdadero, si el [Font](../font/) es monoespaciado. |
| virtual [get_LineGap](./get_linegap/)() | Obtiene el valor LineGap del [Font](../font/) en unidades de [Font](../font/). |
| virtual [get_TypoAscender](./get_typoascender/)() | Obtiene el valor ascendente tipográfico del [Font](../font/) en unidades de fuente. |
| virtual [get_TypoDescender](./get_typodescender/)() | Obtiene el valor descendente tipográfico del [Font](../font/) en unidades de [Font](../font/). |
| virtual [get_TypoLineGap](./get_typolinegap/)() | Obtiene el valor tipográfico LineGap del [Font](../font/) en unidades de [Font](../font/). |
| virtual [get_UnitsPerEM](./get_unitsperem/)() | Obtiene unidades por em. |
| virtual [GetAscender](./getascender/)(double) | Devuelve el ascendente para un tamaño específico de [Font](../font/). |
| virtual [GetDescender](./getdescender/)(double) | Devuelve el descendente para un tamaño específico de [Font](../font/). |
| virtual [GetGlyphBBox](./getglyphbbox/)(System::SharedPtr\<Glyphs::GlyphId\>) | Devuelve el BBox del glifo. |
| virtual [GetGlyphWidth](./getglyphwidth/)(System::SharedPtr\<Glyphs::GlyphId\>) | Devuelve el ancho del glifo. |
| virtual [GetKerningValue](./getkerningvalue/)(System::SharedPtr\<Glyphs::GlyphId\>, System::SharedPtr\<Glyphs::GlyphId\>) | Devuelve el valor de kerning para el par de glifos. |
| virtual [GetTypoAscender](./gettypoascender/)(double) | Devuelve el ascendente tipográfico para un tamaño específico de [Font](../font/). |
| virtual [GetTypoDescender](./gettypodescender/)(double) | Devuelve el descendente tipográfico para un tamaño específico de [Font](../font/). |
| virtual [GetTypoLineGap](./gettypolinegap/)(double) | Devuelve el espacio entre líneas para un tamaño específico de [Font](../font/). |
| virtual [MeasureString](./measurestring/)(System::String, double) | Mide la cadena y devuelve el ancho de la cadena. |
| virtual [set_Ascender](./set_ascender/)(double) | Obtiene el valor ascendente del [Font](../font/) en unidades de fuente. |
| virtual [set_Descender](./set_descender/)(double) | Obtiene el valor descendente del [Font](../font/) en unidades de fuente. |
| virtual [set_TypoAscender](./set_typoascender/)(double) | Obtiene el valor ascendente tipográfico del [Font](../font/) en unidades de fuente. |
| virtual [set_TypoDescender](./set_typodescender/)(double) | Obtiene el valor descendente tipográfico del [Font](../font/) en unidades de [Font](../font/). |
| virtual [set_UnitsPerEM](./set_unitsperem/)(uint32_t) | Obtiene unidades por em. |
| virtual [SetGlyphWidth](./setglyphwidth/)(System::SharedPtr\<Glyphs::GlyphId\>, double) | Establece el ancho del glifo. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Font](../)
* Library [Aspose.Font for C++](../../)
