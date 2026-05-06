---
title: "Aspose::Font::TextUtils::IFontMorseDecoder::Decode method"
linktitle: "Decode"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::TextUtils::IFontMorseDecoder::Decode method. Decifra código Morse y dibuja el resultado en formato PNG en C++."
type: docs
weight: 100
url: /es/cpp/aspose.font.textutils/ifontmorsedecoder/decode/
---
## IFontMorseDecoder::Decode(System::String, System::SharedPtr\<IFont\>, double, Renderers::RenderingUtils::LineSpacingType, int32_t, int32_t, MorseAlphabets, char16_t, char16_t) method


Descifra código Morse y dibuja el resultado en formato PNG.

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Font::TextUtils::IFontMorseDecoder::Decode(System::String morseText, System::SharedPtr<IFont> font, double fontSize, Renderers::RenderingUtils::LineSpacingType lineSpacingType, int32_t lineSpacingValue, int32_t maxWidth, MorseAlphabets alphabet=Aspose::Font::TextUtils::MorseAlphabets::Latin, char16_t inputSeparator=u' ', char16_t outputSeparator=u'/')=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| morseText | System::String | Texto codificado en código Morse, es decir texto como "... --- ..." (SOS) |
| font | System::SharedPtr\<IFont\> | [Font](../../../aspose.font/font/) para obtener los glifos relacionados con el texto decodificado de |
| fontSize | double | [Fuente](../../../aspose.font/font/) tamaño |
| lineSpacingType | Renderers::RenderingUtils::LineSpacingType | Tipo de interlineado. Número de píxeles o porcentaje de la altura de la fuente |
| lineSpacingValue | int32_t | Valor del interlineado |
| maxWidth | int32_t | Ancho máximo en píxeles para la imagen |
| alfabeto | MorseAlphabets | Alfabeto del código Morse |
| inputSeparator | char16_t | Símbolo usado para separar palabras en el texto codificado |
| outputSeparator | char16_t | Símbolo usado para separar palabras en el texto decodificado |

### ReturnValue

Texto decodificado en formato PNG como flujo de bytes

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [IFont](../../../aspose.font/ifont/)
* Enum [LineSpacingType](../../../aspose.font.renderers/renderingutils/linespacingtype/)
* Enum [MorseAlphabets](../../morsealphabets/)
* Class [IFontMorseDecoder](../)
* Namespace [Aspose::Font::TextUtils](../../)
* Library [Aspose.Font for C++](../../../)
## IFontMorseDecoder::Decode(System::String, System::SharedPtr\<IFont\>, MorseAlphabets, char16_t, char16_t) method


Descifra código Morse en glifos de la fuente especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<Glyphs::GlyphId>> Aspose::Font::TextUtils::IFontMorseDecoder::Decode(System::String morseText, System::SharedPtr<IFont> font, MorseAlphabets alphabet=Aspose::Font::TextUtils::MorseAlphabets::Latin, char16_t inputSeparator=u' ', char16_t outputSeparator=u'/')=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| morseText | System::String | Texto codificado en código Morse, es decir texto como "... --- ..." (SOS) |
| font | System::SharedPtr\<IFont\> | [Font](../../../aspose.font/font/) para obtener los glifos relacionados con el texto decodificado de |
| alfabeto | MorseAlphabets | Alfabeto del código Morse |
| inputSeparator | char16_t | Símbolo usado para separar palabras en el texto codificado |
| outputSeparator | char16_t | Símbolo usado para separar palabras en el texto decodificado |

### ReturnValue

[Glyphs](../../../aspose.font.glyphs/) (glyph identifiers) related to decoded text

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [String](../../../system/string/)
* Class [IFont](../../../aspose.font/ifont/)
* Enum [MorseAlphabets](../../morsealphabets/)
* Class [IFontMorseDecoder](../)
* Namespace [Aspose::Font::TextUtils](../../)
* Library [Aspose.Font for C++](../../../)
