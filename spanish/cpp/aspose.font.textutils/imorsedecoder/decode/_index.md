---
title: "Aspose::Font::TextUtils::IMorseDecoder::Decode method"
linktitle: "Decode"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::TextUtils::IMorseDecoder::Decode method. Descifra el código Morse en C++."
type: docs
weight: 100
url: /es/cpp/aspose.font.textutils/imorsedecoder/decode/
---
## IMorseDecoder::Decode method


Descifra código Morse.

```cpp
virtual System::String Aspose::Font::TextUtils::IMorseDecoder::Decode(System::String morseText, MorseAlphabets alphabet=Aspose::Font::TextUtils::MorseAlphabets::Latin, char16_t inputSeparator=u'/', char16_t outputSeparator=u' ')=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| morseText | System::String | Texto codificado en código Morse, es decir texto como "... --- ..." (SOS) |
| alfabeto | MorseAlphabets | Alfabeto del código Morse |
| inputSeparator | char16_t | Símbolo usado para separar palabras en el texto codificado |
| outputSeparator | char16_t | Símbolo usado para separar palabras en el texto decodificado |

### ReturnValue

Texto decodificado

## Ver también

* Class [String](../../../system/string/)
* Enum [MorseAlphabets](../../morsealphabets/)
* Class [IMorseDecoder](../)
* Namespace [Aspose::Font::TextUtils](../../)
* Library [Aspose.Font for C++](../../../)
