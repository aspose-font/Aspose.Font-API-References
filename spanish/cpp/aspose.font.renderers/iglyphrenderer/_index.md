---
title: "Clase Aspose::Font::Renderers::IGlyphRenderer"
linktitle: "IGlyphRenderer"
second_title: "Aspose.Font para C++"
description: "Clase Aspose::Font::Renderers::IGlyphRenderer. Interfaz utilizada para renderizar glifos en C++."
type: docs
weight: 300
url: /es/cpp/aspose.font.renderers/iglyphrenderer/
---
## IGlyphRenderer class


Interfaz utilizada para renderizar glifos.

```cpp
class IGlyphRenderer : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [RenderGlyph](./renderglyph/)(System::SharedPtr\<IFont\>, uint32_t) | Renderiza glifo. |
| virtual [RenderGlyph](./renderglyph/)(System::SharedPtr\<IFont\>, uint32_t, System::SharedPtr\<TransformationMatrix\>) | Renderiza glifo. |
| virtual [RenderGlyph](./renderglyph/)(System::SharedPtr\<IFont\>, System::SharedPtr\<Glyphs::GlyphId\>) | Renderiza glifo. |
| virtual [RenderGlyph](./renderglyph/)(System::SharedPtr\<IFont\>, System::SharedPtr\<Glyphs::GlyphId\>, System::SharedPtr\<TransformationMatrix\>) | Renderiza glifo. |
| virtual [RenderGlyph](./renderglyph/)(System::SharedPtr\<IFont\>, System::SharedPtr\<Glyphs::GlyphId\>, System::SharedPtr\<Glyphs::Glyph\>, System::SharedPtr\<TransformationMatrix\>) | Renderiza glifo, un objetivo de esta versión sobrecargada - para ser usada con caché de glifos. |
| virtual [RenderIndependentGlyphPath](./renderindependentglyphpath/)(System::SharedPtr\<IFont\>, System::SharedPtr\<Glyphs::GlyphId\>, System::SharedPtr\<Glyphs::Glyph\>, System::SharedPtr\<TransformationMatrix\>) | Renderiza glifo usando una ruta de glifo independiente. La familia de funciones [RenderGlyph()](./renderglyph/) cambia la ruta del glifo al renderizar. Luego conduce a la necesidad de recargar este glifo nuevamente. Esta función usa una copia de la ruta del glifo y no cambia la ruta original del glifo, por lo que el mismo glifo puede reutilizarse varias veces. Esta versión de la función está destinada al uso con caché de glifos. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Font::Renderers](../)
* Library [Aspose.Font for C++](../../)
