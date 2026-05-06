---
title: "Aspose::Font::TextUtils::IFontMorseEncoder class"
linktitle: "IFontMorseEncoder"
second_title: "Aspose.Font para C++"
description: "Clase Aspose::Font::TextUtils::IFontMorseEncoder. Declara la funcionalidad para codificar texto mediante código Morse y obtener el resultado como glifos de fuente en C++."
type: docs
weight: 200
url: /es/cpp/aspose.font.textutils/ifontmorseencoder/
---
## IFontMorseEncoder class


Declara la funcionalidad para codificar texto mediante código Morse y obtener el resultado como glifos de fuente.

```cpp
class IFontMorseEncoder : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Encode](./encode/)(System::String, System::SharedPtr\<IFont\>, MorseAlphabets, char16_t, char16_t) | Codifica texto mediante código Morse y devuelve el resultado como conjunto de glifos (identificadores de glifos). |
| virtual [Encode](./encode/)(System::String, System::SharedPtr\<IFont\>, char16_t, char16_t) | Codifica texto en código Morse y devuelve el resultado como conjunto de glifos (glyphId). Se utiliza análisis heurístico para calcular el alfabeto del texto de entrada. |
| virtual [Encode](./encode/)(System::String, System::SharedPtr\<IFont\>, double, Renderers::RenderingUtils::LineSpacingType, int32_t, int32_t, MorseAlphabets, char16_t, char16_t) | Codifica texto mediante código Morse y dibuja el resultado en formato PNG. |
| virtual [Encode](./encode/)(System::String, System::SharedPtr\<IFont\>, double, Renderers::RenderingUtils::LineSpacingType, int32_t, int32_t, char16_t, char16_t) | Codifica texto en código Morse y dibuja el resultado en formato PNG. Se utiliza análisis heurístico para calcular el alfabeto del texto de entrada. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Font::TextUtils](../)
* Library [Aspose.Font for C++](../../)
