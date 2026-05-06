---
title: "Método Aspose::Font::Renderers::IGlyphRenderer::RenderGlyph"
linktitle: "RenderGlyph"
second_title: "Aspose.Font para C++"
description: "Método Aspose::Font::Renderers::IGlyphRenderer::RenderGlyph. Renderiza glifo en C++."
type: docs
weight: 100
url: /es/cpp/aspose.font.renderers/iglyphrenderer/renderglyph/
---
## IGlyphRenderer::RenderGlyph(System::SharedPtr\<IFont\>, System::SharedPtr\<Glyphs::GlyphId\>) method


Renderiza glifo.

```cpp
virtual void Aspose::Font::Renderers::IGlyphRenderer::RenderGlyph(System::SharedPtr<IFont> font, System::SharedPtr<Glyphs::GlyphId> glyphId)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fuente | System::SharedPtr<IFont> | La fuente que contiene el glifo. |
| glyphId | System::SharedPtr\<Glyphs::GlyphId\> | Índice físico del glifo dentro de la fuente. Tenga en cuenta que esto no es un unicode. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFont](../../../aspose.font/ifont/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [IGlyphRenderer](../)
* Namespace [Aspose::Font::Renderers](../../)
* Library [Aspose.Font for C++](../../../)
## IGlyphRenderer::RenderGlyph(System::SharedPtr\<IFont\>, System::SharedPtr\<Glyphs::GlyphId\>, System::SharedPtr\<Glyphs::Glyph\>, System::SharedPtr\<TransformationMatrix\>) method


Renderiza glifo, un objetivo de esta versión sobrecargada - para ser usada con caché de glifos.

```cpp
virtual void Aspose::Font::Renderers::IGlyphRenderer::RenderGlyph(System::SharedPtr<IFont> font, System::SharedPtr<Glyphs::GlyphId> glyphId, System::SharedPtr<Glyphs::Glyph> glyph, System::SharedPtr<TransformationMatrix> glyphPlacementMatrix)=0
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
## IGlyphRenderer::RenderGlyph(System::SharedPtr\<IFont\>, System::SharedPtr\<Glyphs::GlyphId\>, System::SharedPtr\<TransformationMatrix\>) method


Renderiza glifo.

```cpp
virtual void Aspose::Font::Renderers::IGlyphRenderer::RenderGlyph(System::SharedPtr<IFont> font, System::SharedPtr<Glyphs::GlyphId> glyphId, System::SharedPtr<TransformationMatrix> glyphPlacementMatrix)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fuente | System::SharedPtr<IFont> | La fuente que contiene el glifo. |
| glyphId | System::SharedPtr\<Glyphs::GlyphId\> | Índice físico del glifo dentro de la fuente. Tenga en cuenta que esto no es un unicode. |
| glyphPlacementMatrix | System::SharedPtr<TransformationMatrix> | Matriz que se aplica a las coordenadas del glifo. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFont](../../../aspose.font/ifont/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [TransformationMatrix](../../../aspose.font/transformationmatrix/)
* Class [IGlyphRenderer](../)
* Namespace [Aspose::Font::Renderers](../../)
* Library [Aspose.Font for C++](../../../)
## IGlyphRenderer::RenderGlyph(System::SharedPtr\<IFont\>, uint32_t) method


Renderiza glifo.

```cpp
virtual void Aspose::Font::Renderers::IGlyphRenderer::RenderGlyph(System::SharedPtr<IFont> font, uint32_t glyphIndex)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fuente | System::SharedPtr<IFont> | La fuente que contiene el glifo. |
| glyphIndex | uint32_t | Índice físico del glifo dentro de la fuente. Tenga en cuenta que esto no es un unicode. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFont](../../../aspose.font/ifont/)
* Class [IGlyphRenderer](../)
* Namespace [Aspose::Font::Renderers](../../)
* Library [Aspose.Font for C++](../../../)
## IGlyphRenderer::RenderGlyph(System::SharedPtr\<IFont\>, uint32_t, System::SharedPtr\<TransformationMatrix\>) method


Renderiza glifo.

```cpp
virtual void Aspose::Font::Renderers::IGlyphRenderer::RenderGlyph(System::SharedPtr<IFont> font, uint32_t glyphIndex, System::SharedPtr<TransformationMatrix> glyphPlacementMatrix)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fuente | System::SharedPtr<IFont> | La fuente que contiene el glifo. |
| glyphIndex | uint32_t | Índice físico del glifo dentro de la fuente. Tenga en cuenta que esto no es un unicode. |
| glyphPlacementMatrix | System::SharedPtr<TransformationMatrix> | Matriz que se aplica a las coordenadas del glifo. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFont](../../../aspose.font/ifont/)
* Class [TransformationMatrix](../../../aspose.font/transformationmatrix/)
* Class [IGlyphRenderer](../)
* Namespace [Aspose::Font::Renderers](../../)
* Library [Aspose.Font for C++](../../../)
