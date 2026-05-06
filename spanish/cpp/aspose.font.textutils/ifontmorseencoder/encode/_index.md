---
title: "Aspose::Font::TextUtils::IFontMorseEncoder::Encode method"
linktitle: "Encode"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::TextUtils::IFontMorseEncoder::Encode method. Codifica texto en código Morse y devuelve el resultado como un conjunto de glifos (glyphId). Se utiliza análisis heurístico para calcular el alfabeto del texto de entrada en C++."
type: docs
weight: 100
url: /es/cpp/aspose.font.textutils/ifontmorseencoder/encode/
---
## IFontMorseEncoder::Encode(System::String, System::SharedPtr\<IFont\>, char16_t, char16_t) method


Codifica texto en código Morse y devuelve el resultado como conjunto de glifos (glyphId). Se utiliza análisis heurístico para calcular el alfabeto del texto de entrada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<Glyphs::GlyphId>> Aspose::Font::TextUtils::IFontMorseEncoder::Encode(System::String text, System::SharedPtr<IFont> font, char16_t inputSeparator=u' ', char16_t outputSeparator=u'/')=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| texto | System::String | Texto a codificar en código Morse |
| font | System::SharedPtr\<IFont\> | [Font](../../../aspose.font/font/) para obtener los glifos relacionados con los símbolos punto y guión de |
| inputSeparator | char16_t | Símbolo usado para separar palabras en el texto de entrada |
| outputSeparator | char16_t | Símbolo usado para separar palabras en el texto codificado |

### ReturnValue

[Glyphs(glyphId)](../../../aspose.font.glyphs/) related to encoded text, ie "... --- ..." for the input text "SOS"

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [String](../../../system/string/)
* Class [IFont](../../../aspose.font/ifont/)
* Class [IFontMorseEncoder](../)
* Namespace [Aspose::Font::TextUtils](../../)
* Library [Aspose.Font for C++](../../../)
## IFontMorseEncoder::Encode(System::String, System::SharedPtr\<IFont\>, double, Renderers::RenderingUtils::LineSpacingType, int32_t, int32_t, char16_t, char16_t) method


Codifica texto en código Morse y dibuja el resultado en formato PNG. Se utiliza análisis heurístico para calcular el alfabeto del texto de entrada.

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Font::TextUtils::IFontMorseEncoder::Encode(System::String text, System::SharedPtr<IFont> font, double fontSize, Renderers::RenderingUtils::LineSpacingType lineSpacingType, int32_t lineSpacingValue, int32_t maxWidth, char16_t inputSeparator=u' ', char16_t outputSeparator=u'/')=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| texto | System::String | Texto a codificar en código Morse |
| font | System::SharedPtr\<IFont\> | [Font](../../../aspose.font/font/) para obtener los glifos relacionados con los símbolos punto y guión de |
| fontSize | double | [Fuente](../../../aspose.font/font/) tamaño |
| lineSpacingType | Renderers::RenderingUtils::LineSpacingType | Tipo de interlineado. Número de píxeles o porcentaje de la altura de la fuente |
| lineSpacingValue | int32_t | Valor del interlineado |
| maxWidth | int32_t | Ancho máximo en píxeles para la imagen |
| inputSeparator | char16_t | Símbolo usado para separar palabras en el texto de entrada |
| outputSeparator | char16_t | Símbolo usado para separar palabras en el texto codificado |

### ReturnValue

Texto, codificado en código Morse, en formato PNG como flujo de bytes

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [IFont](../../../aspose.font/ifont/)
* Enum [LineSpacingType](../../../aspose.font.renderers/renderingutils/linespacingtype/)
* Class [IFontMorseEncoder](../)
* Namespace [Aspose::Font::TextUtils](../../)
* Library [Aspose.Font for C++](../../../)
## IFontMorseEncoder::Encode(System::String, System::SharedPtr\<IFont\>, double, Renderers::RenderingUtils::LineSpacingType, int32_t, int32_t, MorseAlphabets, char16_t, char16_t) method


Codifica texto mediante código Morse y dibuja el resultado en formato PNG.

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Font::TextUtils::IFontMorseEncoder::Encode(System::String text, System::SharedPtr<IFont> font, double fontSize, Renderers::RenderingUtils::LineSpacingType lineSpacingType, int32_t lineSpacingValue, int32_t maxWidth, MorseAlphabets alphabet, char16_t inputSeparator=u' ', char16_t outputSeparator=u'/')=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| texto | System::String | Texto a codificar en código Morse |
| font | System::SharedPtr\<IFont\> | [Font](../../../aspose.font/font/) para obtener los glifos relacionados con los símbolos punto y guión de |
| fontSize | double | [Fuente](../../../aspose.font/font/) tamaño |
| lineSpacingType | Renderers::RenderingUtils::LineSpacingType | Tipo de interlineado. Número de píxeles o porcentaje de la altura de la fuente |
| lineSpacingValue | int32_t | Valor del interlineado |
| maxWidth | int32_t | Ancho máximo en píxeles para la imagen |
| alfabeto | MorseAlphabets | Alfabeto del código Morse |
| inputSeparator | char16_t | Símbolo usado para separar palabras en el texto de entrada |
| outputSeparator | char16_t | Símbolo usado para separar palabras en el texto codificado |

### ReturnValue

Texto, codificado en código Morse, en formato PNG como flujo de bytes

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [IFont](../../../aspose.font/ifont/)
* Enum [LineSpacingType](../../../aspose.font.renderers/renderingutils/linespacingtype/)
* Enum [MorseAlphabets](../../morsealphabets/)
* Class [IFontMorseEncoder](../)
* Namespace [Aspose::Font::TextUtils](../../)
* Library [Aspose.Font for C++](../../../)
## IFontMorseEncoder::Encode(System::String, System::SharedPtr\<IFont\>, MorseAlphabets, char16_t, char16_t) method


Codifica texto mediante código Morse y devuelve el resultado como conjunto de glifos (identificadores de glifos).

```cpp
virtual System::ArrayPtr<System::SharedPtr<Glyphs::GlyphId>> Aspose::Font::TextUtils::IFontMorseEncoder::Encode(System::String text, System::SharedPtr<IFont> font, MorseAlphabets alphabet, char16_t inputSeparator=u' ', char16_t outputSeparator=u'/')=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| texto | System::String | Texto a codificar en código Morse |
| font | System::SharedPtr\<IFont\> | [Font](../../../aspose.font/font/) para obtener los glifos relacionados con los símbolos punto y guión de |
| alfabeto | MorseAlphabets | Alfabeto del código Morse |
| inputSeparator | char16_t | Símbolo usado para separar palabras en el texto de entrada |
| outputSeparator | char16_t | Símbolo usado para separar palabras en el texto codificado |

### ReturnValue

[Glyphs(glyphId)](../../../aspose.font.glyphs/) related to encoded text, ie "... --- ..." for the input text "SOS"

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [String](../../../system/string/)
* Class [IFont](../../../aspose.font/ifont/)
* Enum [MorseAlphabets](../../morsealphabets/)
* Class [IFontMorseEncoder](../)
* Namespace [Aspose::Font::TextUtils](../../)
* Library [Aspose.Font for C++](../../../)
