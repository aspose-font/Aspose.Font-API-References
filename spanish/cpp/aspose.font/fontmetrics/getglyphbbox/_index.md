---
title: "Aspose::Font::FontMetrics::GetGlyphBBox método"
linktitle: "GetGlyphBBox"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::FontMetrics::GetGlyphBBox método. Devuelve el BBox del glifo. Devuelve FontBBox si el BBox no estaba definido para el glifo. Puede ser sobrescrito por herederos de codificación de fuentes específicas en C++."
type: docs
weight: 1300
url: /es/cpp/aspose.font/fontmetrics/getglyphbbox/
---
## FontMetrics::GetGlyphBBox method


Devuelve el BBox del glifo. Devuelve [FontBBox](../../fontbbox/) si el BBox no estaba definido para el glifo. Puede ser sobrescrito por herederos de codificación de fuentes específicas.

```cpp
System::SharedPtr<Aspose::Font::FontBBox> Aspose::Font::FontMetrics::GetGlyphBBox(System::SharedPtr<Glyphs::GlyphId> glyphId) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| glyphId | System::SharedPtr\<Glyphs::GlyphId\> | Identificador de glifo. |

### ReturnValue

BBox del glifo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FontBBox](../../fontbbox/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [FontMetrics](../)
* Namespace [Aspose::Font](../../)
* Library [Aspose.Font for C++](../../../)
