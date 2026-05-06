---
title: "Aspose::Font::Common_FontMerger::FontCharactersMerger::MergeFonts método"
linktitle: "MergeFonts"
second_title: "Aspose.Font para C++"
description: "Método Aspose::Font::Common_FontMerger::FontCharactersMerger::MergeFonts. Fusiona fuentes basándose en las listas de glifos proporcionadas. Busca un código de carácter para cada glifo proporcionado y agrega el código de carácter encontrado con el glifo correspondiente en la nueva fuente resultante en C++."
type: docs
weight: 300
url: /es/cpp/aspose.font.common_fontmerger/fontcharactersmerger/mergefonts/
---
## FontCharactersMerger::MergeFonts(System::ArrayPtr\<System::SharedPtr\<Glyphs::GlyphId\>\>, System::ArrayPtr\<System::SharedPtr\<Glyphs::GlyphId\>\>, System::String) method


Combina fuentes basándose en las listas de glifos proporcionadas. Busca un código de carácter para cada glifo pasado y agrega el código de carácter encontrado con el glifo correspondiente en la nueva fuente resultante.

```cpp
virtual System::SharedPtr<Font> Aspose::Font::Common_FontMerger::FontCharactersMerger::MergeFonts(System::ArrayPtr<System::SharedPtr<Glyphs::GlyphId>> primaryFontGlyphs, System::ArrayPtr<System::SharedPtr<Glyphs::GlyphId>> secondaryFontGlyphs, System::String newFontName)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| primaryFontGlyphs | System::ArrayPtr\<System::SharedPtr\<Glyphs::GlyphId\>\> | Lista de glifos a tomar de la fuente primaria |
| secondaryFontGlyphs | System::ArrayPtr\<System::SharedPtr\<Glyphs::GlyphId\>\> | Lista de glifos a tomar de la fuente secundaria |
| newFontName | System::String | Nombre deseado para la fuente resultante |

### ReturnValue

Fuente fusionada

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../../aspose.font/font/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [String](../../../system/string/)
* Class [FontCharactersMerger](../)
* Namespace [Aspose::Font::Common_FontMerger](../../)
* Library [Aspose.Font for C++](../../../)
## FontCharactersMerger::MergeFonts(System::ArrayPtr\<uint32_t\>, System::ArrayPtr\<uint32_t\>, System::String) method


Fusiona fuentes basándose en las listas de códigos de caracteres proporcionadas. Para crear la fuente resultante deseada, simplemente pase los códigos de símbolos de las fuentes originales que desea incluir en la fuente resultante. Los [Glyphs](../../../aspose.font.glyphs/) relacionados con los códigos proporcionados se encontrarán automáticamente. Por ejemplo, si desea incluir en la fuente resultante los glifos relacionados con las letras A y B de la primera fuente y los glifos relacionados con las letras C y D de la segunda fuente, simplemente llame a este método así: **MergeFonts(new uint[] { 'A', 'B' }, new uint[] { 'C', 'D' }, "NewFont")**

```cpp
virtual System::SharedPtr<Font> Aspose::Font::Common_FontMerger::FontCharactersMerger::MergeFonts(System::ArrayPtr<uint32_t> primaryFontCharCodes, System::ArrayPtr<uint32_t> secondaryFontCharCodes, System::String newFontName)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| primaryFontCharCodes | System::ArrayPtr\<uint32_t\> | Códigos a tomar de la fuente primaria |
| secondaryFontCharCodes | System::ArrayPtr\<uint32_t\> | Códigos a tomar de la fuente secundaria |
| newFontName | System::String | Nombre deseado para la fuente resultante |

### ReturnValue

Fuente fusionada

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../../aspose.font/font/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [FontCharactersMerger](../)
* Namespace [Aspose::Font::Common_FontMerger](../../)
* Library [Aspose.Font for C++](../../../)
## FontCharactersMerger::MergeFonts(System::SharedPtr\<System::Collections::Generic::IDictionary\<uint32_t, System::SharedPtr\<Glyphs::GlyphId\>\>\>, System::SharedPtr\<System::Collections::Generic::IDictionary\<uint32_t, System::SharedPtr\<Glyphs::GlyphId\>\>\>, System::String) method


Esta versión del método está diseñada para casos en los que desea establecer códigos de caracteres para los glifos en la fuente resultante de forma explícita. No es obligatorio que el código del glifo que proporcionó esté incluido en la fuente original. El sentido del código pasado es que se asociará con el identificador de glifo correspondiente en la fuente resultante. Por lo tanto, la regla para procesar cada par pasado mediante el parámetro de diccionario [code, glyph ideitifier] es que solo se tomará el identificador de glifo de la fuente original y luego se vinculará con el código correspondiente en la fuente resultante. Puede ser útil cuando algunos códigos de la primera fuente entran en conflicto con los mismos códigos de la segunda fuente.

```cpp
virtual System::SharedPtr<Font> Aspose::Font::Common_FontMerger::FontCharactersMerger::MergeFonts(System::SharedPtr<System::Collections::Generic::IDictionary<uint32_t, System::SharedPtr<Glyphs::GlyphId>>> primaryFontDict, System::SharedPtr<System::Collections::Generic::IDictionary<uint32_t, System::SharedPtr<Glyphs::GlyphId>>> secondaryFontDict, System::String newFontName)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| primaryFontDict | System::SharedPtr\<System::Collections::Generic::IDictionary\<uint32_t, System::SharedPtr\<Glyphs::GlyphId\>\>\> | Diccionario con pares [código de símbolo, identificador de glifo] de la fuente primaria |
| secondaryFontDict | System::SharedPtr\<System::Collections::Generic::IDictionary\<uint32_t, System::SharedPtr\<Glyphs::GlyphId\>\>\> | Diccionario con pares [código de símbolo, identificador de glifo] de la fuente secundaria |
| newFontName | System::String | Nombre deseado para la fuente resultante |

### ReturnValue

Fuente fusionada

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../../aspose.font/font/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [String](../../../system/string/)
* Class [FontCharactersMerger](../)
* Namespace [Aspose::Font::Common_FontMerger](../../)
* Library [Aspose.Font for C++](../../../)
