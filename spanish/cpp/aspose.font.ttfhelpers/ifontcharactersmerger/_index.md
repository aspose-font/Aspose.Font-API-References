---
title: "Aspose::Font::TtfHelpers::IFontCharactersMerger clase"
linktitle: "IFontCharactersMerger"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::TtfHelpers::IFontCharactersMerger clase. Declara la funcionalidad de ayuda para combinar fuentes TrueType. La fuente que se pasa como parámetro font1 se considera primaria. Esto significa que muchas características, relacionadas con la fuente combinada final, como métricas, estructura de codificación y otras, se tomarán de esta fuente primaria en C++."
type: docs
weight: 200
url: /es/cpp/aspose.font.ttfhelpers/ifontcharactersmerger/
---
## IFontCharactersMerger class


Declara la funcionalidad de ayuda para combinar fuentes TrueType. [Font](../../aspose.font/font/) que se pasa como parámetro font1 se considera primaria. Significa que muchas características, relacionadas con la fuente combinada final, como métricas, estructura de codificación y otras, se tomarán de esta fuente primaria.

```cpp
class IFontCharactersMerger : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [MergeFonts](./mergefonts/)(System::ArrayPtr\<System::SharedPtr\<Glyphs::GlyphId\>\>, System::ArrayPtr\<System::SharedPtr\<Glyphs::GlyphId\>\>, System::String) | Combina fuentes basándose en listas de glifos proporcionadas. Busca un código de carácter para cada glifo pasado y agrega el código de carácter encontrado con el glifo correspondiente en la fuente nueva resultante. |
| virtual [MergeFonts](./mergefonts/)(System::ArrayPtr\<uint32_t\>, System::ArrayPtr\<uint32_t\>, System::String) | Combina fuentes basándose en las listas de códigos de caracteres proporcionadas. Para crear la fuente resultante deseada, simplemente pase los códigos de símbolos de las fuentes originales que desea incluir en la fuente resultante. [Glyphs](../../aspose.font.glyphs/) relacionados con los códigos proporcionados se encontrarán automáticamente. Por ejemplo, si desea incluir en la fuente resultante glifos relacionados con las letras A y B de la primera fuente y glifos relacionados con las letras C y D de la segunda fuente, simplemente llame a este método así: **MergeFonts(new uint[] { 'A', 'B' }, new uint[] { 'C', 'D' }, "NewFont")** |
| virtual [MergeFonts](./mergefonts/)(System::SharedPtr\<System::Collections::Generic::IDictionary\<uint32_t, System::SharedPtr\<Glyphs::GlyphId\>\>\>, System::SharedPtr\<System::Collections::Generic::IDictionary\<uint32_t, System::SharedPtr\<Glyphs::GlyphId\>\>\>, System::String) | Esta versión del método está diseñada para casos en los que desea establecer códigos de caracteres para los glifos en la fuente resultante de forma explícita. No es obligatorio que el código del glifo que proporcionó esté incluido en la fuente original. El sentido del código pasado es que se asociará con el identificador de glifo correspondiente en la fuente resultante. Por lo tanto, la regla para procesar cada par pasado mediante el parámetro de diccionario [code, glyph ideitifier] es que solo se tomará el identificador de glifo de la fuente original y luego se vinculará con el código correspondiente en la fuente resultante. Puede ser útil cuando algunos códigos de la primera fuente entran en conflicto con los mismos códigos de la segunda fuente. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Font::TtfHelpers](../)
* Library [Aspose.Font for C++](../../)
