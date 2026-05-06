---
title: "Aspose::Font::Cff::CffFontMetrics class"
linktitle: "CffFontMetrics"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::Cff::CffFontMetrics class. Representa métricas de fuentes CFF en C++."
type: docs
weight: 300
url: /es/cpp/aspose.font.cff/cfffontmetrics/
---
## CffFontMetrics class


Representa métricas de CFF [Font](../../aspose.font/font/).

```cpp
class CffFontMetrics : public Aspose::Font::FontMetrics
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Ascender](./get_ascender/)() override | Obtiene el valor Ascender. |
| [get_Descender](./get_descender/)() override | Obtiene el valor Descender. |
| [get_FontBBox](./get_fontbbox/)() override | Obtiene el valor de [FontBBox](../../aspose.font/fontbbox/). |
| [get_FontMatrix](./get_fontmatrix/)() override | Obtiene el valor FontMatrix. |
| [get_UnitsPerEM](./get_unitsperem/)() override | Obtiene el valor de UnitsPerEM. |
| [GetFontMatrixForGlyph](./getfontmatrixforglyph/)(System::SharedPtr\<Glyphs::GlyphId\>) | Calcula la matriz de transformación para el glifo especificado por id. |
| [GetGlyphWidth](./getglyphwidth/)(System::SharedPtr\<Glyphs::GlyphId\>) override | Devuelve el ancho del glifo. Puede ser sobrescrito por herederos de codificación de [Font](../../aspose.font/font/) específicos. |
| [MeasureString](./measurestring/)(System::String, double) override | Mide la cadena y devuelve el ancho de la cadena. |
| [SetGlyphWidth](./setglyphwidth/)(System::SharedPtr\<Glyphs::GlyphId\>, double) override | Establece el ancho del glifo. |
## Ver también

* Class [FontMetrics](../../aspose.font/fontmetrics/)
* Namespace [Aspose::Font::Cff](../)
* Library [Aspose.Font for C++](../../)
