---
title: "Aspose::Font::Cff::CffFont::GetGlyphById método"
linktitle: "GetGlyphById"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::Cff::CffFont::GetGlyphById método. Devuelve el glifo por su id. El id del glifo es un número único para un glifo, que depende del tipo de fuente. El id de glifo de la fuente CFF puede ser una instancia de la clase (GlyphStringId) o de la clase (GlyphUInt32Id) en C++."
type: docs
weight: 1800
url: /es/cpp/aspose.font.cff/cfffont/getglyphbyid/
---
## CffFont::GetGlyphById(System::SharedPtr\<Glyphs::GlyphId\>) method


Devuelve el glifo por su id. El id del glifo es un número único para un glifo, que depende del tipo de fuente. El id de glifo del CFF [Font](../../../aspose.font/font/) puede ser una instancia de la clase ([GlyphStringId](../)) o de la clase ([GlyphUInt32Id](../)).

```cpp
System::SharedPtr<Glyphs::Glyph> Aspose::Font::Cff::CffFont::GetGlyphById(System::SharedPtr<Glyphs::GlyphId> id) override
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
* Class [CffFont](../)
* Namespace [Aspose::Font::Cff](../../)
* Library [Aspose.Font for C++](../../../)
## CffFont::GetGlyphById(System::String) method


Devuelve el glifo por nombre de glifo.

```cpp
System::SharedPtr<Glyphs::Glyph> Aspose::Font::Cff::CffFont::GetGlyphById(System::String glyphName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| glyphName | System::String | Nombre del glifo. |

### ReturnValue

Glifo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Glyph](../../../aspose.font.glyphs/glyph/)
* Class [String](../../../system/string/)
* Class [CffFont](../)
* Namespace [Aspose::Font::Cff](../../)
* Library [Aspose.Font for C++](../../../)
## CffFont::GetGlyphById(uint32_t) method


Devuelve el glifo por su id.

```cpp
System::SharedPtr<Glyphs::Glyph> Aspose::Font::Cff::CffFont::GetGlyphById(uint32_t id)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | uint32_t | Id del glifo. |

### ReturnValue

Glifo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Glyph](../../../aspose.font.glyphs/glyph/)
* Class [CffFont](../)
* Namespace [Aspose::Font::Cff](../../)
* Library [Aspose.Font for C++](../../../)
