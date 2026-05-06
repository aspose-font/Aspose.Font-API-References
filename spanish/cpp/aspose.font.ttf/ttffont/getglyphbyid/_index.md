---
title: "Aspose::Font::Ttf::TtfFont::GetGlyphById método"
linktitle: "GetGlyphById"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::Ttf::TtfFont::GetGlyphById método. Devuelve el glifo por id de glifo. El id de glifo es un número único para un glifo, que depende del tipo de fuente. El id de glifo de una fuente TTF puede ser una instancia de la clase (GlyphStringId) o de la clase (GlyphUInt32Id). La dirección de glifo por nombre (string) es compatible con fuentes TTF mediante el mapeo de la tabla Post. En caso de una fuente CFF interna, se utilizan las estructuras CFF para direccionar glifos por nombre en C++."
type: docs
weight: 1800
url: /es/cpp/aspose.font.ttf/ttffont/getglyphbyid/
---
## TtfFont::GetGlyphById(System::SharedPtr\<Glyphs::GlyphId\>) method


Devuelve el glifo por id de glifo. El id de glifo es un número único para un glifo, que depende del tipo de fuente. El id de glifo de una fuente TTF [Font](../../../aspose.font/font/) puede ser una instancia de la clase ([GlyphStringId](../)) o de la clase ([GlyphUInt32Id](../)). La dirección de glifo por nombre (string) es compatible con fuentes TTF mediante el mapeo de la tabla Post. En caso de una [Font](../../../aspose.font/font/) CFF interna, se utilizan las estructuras CFF para direccionar glifos por nombre.

```cpp
System::SharedPtr<Glyphs::Glyph> Aspose::Font::Ttf::TtfFont::GetGlyphById(System::SharedPtr<Glyphs::GlyphId> id) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | System::SharedPtr\<Glyphs::GlyphId\> | Id del glifo. |

### ReturnValue

Glifo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Glyph](../../../aspose.font.glyphs/glyph/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [TtfFont](../)
* Namespace [Aspose::Font::Ttf](../../)
* Library [Aspose.Font for C++](../../../)
## TtfFont::GetGlyphById(System::String) method


Devuelve el glifo por nombre de glifo. La dirección de glifo por nombre (string) es compatible con fuentes TTF mediante el mapeo de la tabla Post. En caso de una [Font](../../../aspose.font/font/) CFF interna, se utilizan las estructuras CFF para direccionar glifos por nombre.

```cpp
System::SharedPtr<Glyphs::Glyph> Aspose::Font::Ttf::TtfFont::GetGlyphById(System::String glyphName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| glyphName | System::String | Identificador de cadena de glifo. |

### ReturnValue

Glifo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Glyph](../../../aspose.font.glyphs/glyph/)
* Class [String](../../../system/string/)
* Class [TtfFont](../)
* Namespace [Aspose::Font::Ttf](../../)
* Library [Aspose.Font for C++](../../../)
## TtfFont::GetGlyphById(uint32_t) method


Devuelve el glifo por su id.

```cpp
System::SharedPtr<Glyphs::Glyph> Aspose::Font::Ttf::TtfFont::GetGlyphById(uint32_t id)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | uint32_t | Índice del glifo. |

### ReturnValue

Glifo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Glyph](../../../aspose.font.glyphs/glyph/)
* Class [TtfFont](../)
* Namespace [Aspose::Font::Ttf](../../)
* Library [Aspose.Font for C++](../../../)
