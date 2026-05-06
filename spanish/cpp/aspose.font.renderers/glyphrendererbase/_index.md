---
title: "Aspose::Font::Renderers::GlyphRendererBase class"
linktitle: "GlyphRendererBase"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::Renderers::GlyphRendererBase class. Representa la clase base para los renderizadores de glifos en C++."
type: docs
weight: 200
url: /es/cpp/aspose.font.renderers/glyphrendererbase/
---
## GlyphRendererBase class


Representa la clase base para renderizadores de glifos.

```cpp
class GlyphRendererBase : public Aspose::Font::Renderers::IGlyphRenderer
```

## Métodos

| Método | Descripción |
| --- | --- |
| [RenderGlyph](./renderglyph/)(System::SharedPtr\<IFont\>, uint32_t) override | Renderiza glifo. |
| [RenderGlyph](./renderglyph/)(System::SharedPtr\<IFont\>, uint32_t, System::SharedPtr\<TransformationMatrix\>) override | Renderiza glifo. |
| [RenderGlyph](./renderglyph/)(System::SharedPtr\<IFont\>, System::SharedPtr\<Glyphs::GlyphId\>) override | Renderiza glifo. |
| [RenderGlyph](./renderglyph/)(System::SharedPtr\<IFont\>, System::SharedPtr\<Glyphs::GlyphId\>, System::SharedPtr\<TransformationMatrix\>) override | Renderiza glifo. |
| [RenderGlyph](./renderglyph/)(System::SharedPtr\<IFont\>, System::SharedPtr\<Glyphs::GlyphId\>, System::SharedPtr\<Glyphs::Glyph\>, System::SharedPtr\<TransformationMatrix\>) override | Renderiza glifo, un objetivo de esta versión sobrecargada - para ser usada con caché de glifos. |
| [RenderIndependentGlyphPath](./renderindependentglyphpath/)(System::SharedPtr\<IFont\>, System::SharedPtr\<Glyphs::GlyphId\>, System::SharedPtr\<Glyphs::Glyph\>, System::SharedPtr\<TransformationMatrix\>) override | Renderiza glifo usando una ruta de glifo independiente. La familia de funciones [RenderGlyph()](./renderglyph/) cambia la ruta del glifo al renderizar. Luego conduce a la necesidad de recargar este glifo nuevamente. Esta función usa una copia de la ruta del glifo y no cambia la ruta original del glifo, por lo que el mismo glifo puede reutilizarse varias veces. Esta versión de la función está destinada al uso con caché de glifos. |
## Ver también

* Class [IGlyphRenderer](../iglyphrenderer/)
* Namespace [Aspose::Font::Renderers](../)
* Library [Aspose.Font for C++](../../)
