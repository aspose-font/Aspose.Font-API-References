---
title: "Método Aspose::Font::Renderers::GlyphRendererBase::RenderGlyph"
linktitle: "RenderGlyph"
second_title: "Aspose.Font para C++"
description: "Método Aspose::Font::Renderers::GlyphRendererBase::RenderGlyph. Renderiza un glifo en C++."
type: docs
weight: 100
url: /es/cpp/aspose.font.renderers/glyphrendererbase/renderglyph/
---
## GlyphRendererBase::RenderGlyph(System::SharedPtr\<IFont\>, System::SharedPtr\<Glyphs::GlyphId\>) method


Renderiza glifo.

```cpp
void Aspose::Font::Renderers::GlyphRendererBase::RenderGlyph(System::SharedPtr<IFont> font, System::SharedPtr<Glyphs::GlyphId> glyphId) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| font | System::SharedPtr\<IFont\> | La [Font](../../../aspose.font/font/) que contiene el glifo. |
| glyphId | System::SharedPtr\<Glyphs::GlyphId\> | Índice físico del glifo dentro de [Font](../../../aspose.font/font/). Tenga en cuenta que esto no es un unicode. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFont](../../../aspose.font/ifont/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [GlyphRendererBase](../)
* Namespace [Aspose::Font::Renderers](../../)
* Library [Aspose.Font for C++](../../../)
## GlyphRendererBase::RenderGlyph(System::SharedPtr\<IFont\>, System::SharedPtr\<Glyphs::GlyphId\>, System::SharedPtr\<Glyphs::Glyph\>, System::SharedPtr\<TransformationMatrix\>) method


Renderiza glifo, un objetivo de esta versión sobrecargada - para ser usada con caché de glifos.

```cpp
void Aspose::Font::Renderers::GlyphRendererBase::RenderGlyph(System::SharedPtr<IFont> font, System::SharedPtr<Glyphs::GlyphId> glyphId, System::SharedPtr<Glyphs::Glyph> glyph, System::SharedPtr<TransformationMatrix> glyphPlacementMatrix) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fuente | System::SharedPtr<IFont> | La fuente que contiene el glifo. |
| glyphId | System::SharedPtr\<Glyphs::GlyphId\> | Índice físico del glifo dentro de [Font](../../../aspose.font/font/). Tenga en cuenta que esto no es un unicode. |
| glifo | System::SharedPtr<Glyphs::Glyph> | Glifo a renderizar. |
| glyphPlacementMatrix | System::SharedPtr<TransformationMatrix> | Matriz que se aplica a las coordenadas del glifo. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFont](../../../aspose.font/ifont/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [Glyph](../../../aspose.font.glyphs/glyph/)
* Class [TransformationMatrix](../../../aspose.font/transformationmatrix/)
* Class [GlyphRendererBase](../)
* Namespace [Aspose::Font::Renderers](../../)
* Library [Aspose.Font for C++](../../../)
## GlyphRendererBase::RenderGlyph(System::SharedPtr\<IFont\>, System::SharedPtr\<Glyphs::GlyphId\>, System::SharedPtr\<TransformationMatrix\>) method


Renderiza glifo.

```cpp
void Aspose::Font::Renderers::GlyphRendererBase::RenderGlyph(System::SharedPtr<IFont> font, System::SharedPtr<Glyphs::GlyphId> glyphId, System::SharedPtr<TransformationMatrix> glyphPlacementMatrix) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| font | System::SharedPtr\<IFont\> | La [Font](../../../aspose.font/font/) que contiene el glifo. |
| glyphId | System::SharedPtr\<Glyphs::GlyphId\> | Índice físico del glifo dentro de [Font](../../../aspose.font/font/). Tenga en cuenta que esto no es un unicode. |
| glyphPlacementMatrix | System::SharedPtr<TransformationMatrix> | Matriz que se aplica a las coordenadas del glifo. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFont](../../../aspose.font/ifont/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [TransformationMatrix](../../../aspose.font/transformationmatrix/)
* Class [GlyphRendererBase](../)
* Namespace [Aspose::Font::Renderers](../../)
* Library [Aspose.Font for C++](../../../)
## GlyphRendererBase::RenderGlyph(System::SharedPtr\<IFont\>, uint32_t) method


Renderiza glifo.

```cpp
void Aspose::Font::Renderers::GlyphRendererBase::RenderGlyph(System::SharedPtr<IFont> font, uint32_t glyphIndex) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| font | System::SharedPtr\<IFont\> | La [Font](../../../aspose.font/font/) que contiene el glifo. |
| glyphIndex | uint32_t | Índice físico del glifo dentro de [Font](../../../aspose.font/font/). Tenga en cuenta que esto no es un unicode. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFont](../../../aspose.font/ifont/)
* Class [GlyphRendererBase](../)
* Namespace [Aspose::Font::Renderers](../../)
* Library [Aspose.Font for C++](../../../)
## GlyphRendererBase::RenderGlyph(System::SharedPtr\<IFont\>, uint32_t, System::SharedPtr\<TransformationMatrix\>) method


Renderiza glifo.

```cpp
void Aspose::Font::Renderers::GlyphRendererBase::RenderGlyph(System::SharedPtr<IFont> font, uint32_t glyphIndex, System::SharedPtr<TransformationMatrix> glyphPlacementMatrix) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| font | System::SharedPtr\<IFont\> | La [Font](../../../aspose.font/font/) que contiene el glifo. |
| glyphIndex | uint32_t | Índice físico del glifo dentro de [Font](../../../aspose.font/font/). Tenga en cuenta que esto no es un unicode. |
| glyphPlacementMatrix | System::SharedPtr<TransformationMatrix> | Matriz que se aplica a las coordenadas del glifo. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFont](../../../aspose.font/ifont/)
* Class [TransformationMatrix](../../../aspose.font/transformationmatrix/)
* Class [GlyphRendererBase](../)
* Namespace [Aspose::Font::Renderers](../../)
* Library [Aspose.Font for C++](../../../)
