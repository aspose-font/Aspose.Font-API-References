---
title: "Aspose::Font::FontMetrics clase"
linktitle: "FontMetrics"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::FontMetrics clase. Representa métricas de fuente en C++."
type: docs
weight: 800
url: /es/cpp/aspose.font/fontmetrics/
---
## FontMetrics class


Representa métricas de [Font](../font/).

```cpp
class FontMetrics : public Aspose::Font::IFontMetrics
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Ascender](./get_ascender/)() override | Obtiene el valor Ascender. |
| [get_Descender](./get_descender/)() override | Obtiene el valor Descender. |
| [get_FontBBox](./get_fontbbox/)() override | Obtiene el valor de [FontBBox](../fontbbox/). |
| [get_FontMatrix](./get_fontmatrix/)() override | Obtiene el valor FontMatrix. |
| [get_IsFixedPitch](./get_isfixedpitch/)() override | Obtiene el valor de IsFixedPitch. |
| [get_LineGap](./get_linegap/)() override | Obtiene el valor de LineGap. |
| [get_TypoAscender](./get_typoascender/)() override | Obtiene el valor de TypoAscender. |
| [get_TypoDescender](./get_typodescender/)() override | Obtiene el valor de TypoDescender. |
| [get_TypoLineGap](./get_typolinegap/)() override | Obtiene el valor de TypoLineGap. |
| [get_UnitsPerEM](./get_unitsperem/)() override | Obtiene el valor de UnitsPerEM. |
| [GetAscender](./getascender/)(double) override | Devuelve el ascendente para un tamaño específico de [Font](../font/). |
| [GetDescender](./getdescender/)(double) override | Devuelve el descendente para un tamaño específico de [Font](../font/). |
| [GetGlyphBBox](./getglyphbbox/)(System::SharedPtr\<Glyphs::GlyphId\>) override | Devuelve el BBox del glifo. Devuelve [FontBBox](../fontbbox/) si el BBox no estaba definido para el glifo. Puede ser sobrescrito por herederos de codificación de fuentes específicos. |
| [GetGlyphWidth](./getglyphwidth/)(System::SharedPtr\<Glyphs::GlyphId\>) override | Devuelve el ancho del glifo. Puede ser sobrescrito por herederos de codificación de fuentes específicos. |
| [GetKerningValue](./getkerningvalue/)(System::SharedPtr\<Glyphs::GlyphId\>, System::SharedPtr\<Glyphs::GlyphId\>) override | Devuelve el valor de kerning para el par de glifos. |
| [GetTypoAscender](./gettypoascender/)(double) override | Devuelve el descendente para un tamaño específico de [Font](../font/). |
| [GetTypoDescender](./gettypodescender/)(double) override | Devuelve el descendente para un tamaño específico de [Font](../font/). |
| [GetTypoLineGap](./gettypolinegap/)(double) override | Devuelve el espacio entre líneas para un tamaño específico de [Font](../font/). |
| virtual [MeasureString](./measurestring/)(System::String, double) | Mide la cadena y devuelve el ancho de la cadena. |
| [set_Ascender](./set_ascender/)(double) override | Obtiene el valor Ascender. |
| [set_Descender](./set_descender/)(double) override | Obtiene el valor Descender. |
| [set_TypoAscender](./set_typoascender/)(double) override | Obtiene el valor de TypoAscender. |
| [set_TypoDescender](./set_typodescender/)(double) override | Obtiene el valor de TypoDescender. |
| [set_UnitsPerEM](./set_unitsperem/)(uint32_t) override | Obtiene el valor de UnitsPerEM. |
| virtual [SetGlyphWidth](./setglyphwidth/)(System::SharedPtr\<Glyphs::GlyphId\>, double) | Establece el ancho del glifo. |
## Ver también

* Class [IFontMetrics](../ifontmetrics/)
* Namespace [Aspose::Font](../)
* Library [Aspose.Font for C++](../../)
