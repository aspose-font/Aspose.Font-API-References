---
title: "Aspose::Font::TextUtils::IMorseEncoder::Encode method"
linktitle: "Encode"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::TextUtils::IMorseEncoder::Encode method. Codifica texto mediante código Morse. Se utiliza análisis heurístico para calcular el alfabeto del texto de entrada. El alfabeto se selecciona por la primera palabra en C++."
type: docs
weight: 100
url: /es/cpp/aspose.font.textutils/imorseencoder/encode/
---
## IMorseEncoder::Encode(System::String, char16_t, char16_t) method


Codifica texto mediante código Morse. Se utiliza análisis heurístico para calcular el alfabeto del texto de entrada. El alfabeto se selecciona por la primera palabra.

```cpp
virtual System::String Aspose::Font::TextUtils::IMorseEncoder::Encode(System::String text, char16_t inputSeparator=u' ', char16_t outputSeparator=u'/')=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| texto | System::String | Texto a codificar en código Morse |
| inputSeparator | char16_t | Símbolo usado para separar palabras en el texto de entrada |
| outputSeparator | char16_t | Símbolo usado para separar palabras en el texto codificado |

### ReturnValue

Texto codificado, p.ej. "... --- ..." para el texto de entrada "SOS"

## Ver también

* Class [String](../../../system/string/)
* Class [IMorseEncoder](../)
* Namespace [Aspose::Font::TextUtils](../../)
* Library [Aspose.Font for C++](../../../)
## IMorseEncoder::Encode(System::String, MorseAlphabets, char16_t, char16_t) method


Codifica texto mediante código Morse.

```cpp
virtual System::String Aspose::Font::TextUtils::IMorseEncoder::Encode(System::String text, MorseAlphabets alphabet, char16_t inputSeparator=u' ', char16_t outputSeparator=u'/')=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| texto | System::String | Texto a codificar en código Morse |
| alfabeto | MorseAlphabets | Alfabeto del código Morse |
| inputSeparator | char16_t | Símbolo usado para separar palabras en el texto de entrada |
| outputSeparator | char16_t | Símbolo usado para separar palabras en el texto codificado |

### ReturnValue

Texto codificado, p.ej. "... --- ..." para el texto de entrada "SOS"

## Ver también

* Class [String](../../../system/string/)
* Enum [MorseAlphabets](../../morsealphabets/)
* Class [IMorseEncoder](../)
* Namespace [Aspose::Font::TextUtils](../../)
* Library [Aspose.Font for C++](../../../)
