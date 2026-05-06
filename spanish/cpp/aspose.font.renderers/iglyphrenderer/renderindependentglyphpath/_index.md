---
title: "Método Aspose::Font::Renderers::IGlyphRenderer::RenderIndependentGlyphPath"
linktitle: "RenderIndependentGlyphPath"
second_title: "Aspose.Font para C++"
description: "Método Aspose::Font::Renderers::IGlyphRenderer::RenderIndependentGlyphPath. Renderiza el glifo usando una ruta de glifo independiente. La familia de funciones RenderGlyph() cambia la ruta del glifo durante el renderizado. Esto lleva a la necesidad de recargar este glifo nuevamente. Esta función usa una copia de la ruta del glifo y no cambia la ruta original, por lo que el mismo glifo puede reutilizarse varias veces. Esta versión de la función está destinada al uso con caché de glifos en C++."
type: docs
weight: 200
url: /es/cpp/aspose.font.renderers/iglyphrenderer/renderindependentglyphpath/
---
## IGlyphRenderer::RenderIndependentGlyphPath method


Renderiza el glifo usando una ruta de glifo independiente. La familia de funciones [RenderGlyph()](../renderglyph/) cambia la ruta del glifo al renderizar. Esto lleva a la necesidad de recargar este glifo nuevamente. Esta función usa una copia de la ruta del glifo y no cambia la ruta original del glifo, por lo que el mismo glifo puede reutilizarse múltiples veces. Esta versión de la función está destinada al uso con caché de glifos.

```cpp
virtual void Aspose::Font::Renderers::IGlyphRenderer::RenderIndependentGlyphPath(System::SharedPtr<IFont> font, System::SharedPtr<Glyphs::GlyphId> glyphId, System::SharedPtr<Glyphs::Glyph> glyph, System::SharedPtr<TransformationMatrix> glyphPlacementMatrix)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fuente | System::SharedPtr<IFont> | La fuente que contiene el glifo. |
| glyphId | System::SharedPtr\<Glyphs::GlyphId\> | Índice físico del glifo dentro de la fuente. Tenga en cuenta que esto no es un unicode. |
| glifo | System::SharedPtr<Glyphs::Glyph> | Glifo a renderizar. |
| glyphPlacementMatrix | System::SharedPtr<TransformationMatrix> | Matriz que se aplica a las coordenadas del glifo. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFont](../../../aspose.font/ifont/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [Glyph](../../../aspose.font.glyphs/glyph/)
* Class [TransformationMatrix](../../../aspose.font/transformationmatrix/)
* Class [IGlyphRenderer](../)
* Namespace [Aspose::Font::Renderers](../../)
* Library [Aspose.Font for C++](../../../)
