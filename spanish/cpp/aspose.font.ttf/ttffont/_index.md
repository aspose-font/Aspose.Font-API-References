---
title: "Aspose::Font::Ttf::TtfFont clase"
linktitle: "TtfFont"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::Ttf::TtfFont clase. Representa una fuente TrueType (TTF) en C++."
type: docs
weight: 600
url: /es/cpp/aspose.font.ttf/ttffont/
---
## TtfFont class


Representa una fuente TrueType [Font](../../aspose.font/font/) (TTF).

```cpp
class TtfFont : public Aspose::Font::Font
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Convert](./convert/)(Aspose::Font::FontType) override | Convierte el [Font](../../aspose.font/font/) a otro formato. |
| [Convert](./convert/)(Aspose::Font::FontType, System::SharedPtr\<System::Collections::Generic::ICollection\<uint32_t\>\>) | Convierte el [Font](../../aspose.font/font/) a otro formato con un conjunto de caracteres limitado. |
| virtual [get_CffFont](./get_cfffont/)() | Obtiene la [Font](../../aspose.font/font/) CFF si está presente. |
| [get_Encoding](./get_encoding/)() override | Obtiene la codificación de la [Font](../../aspose.font/font/). |
| [get_FontDefinition](./get_fontdefinition/)() override | Obtiene la definición de la [Font](../../aspose.font/font/). |
| [get_FontFamily](./get_fontfamily/)() override | Obtiene o establece la familia de la [Font](../../aspose.font/font/). |
| [get_FontName](./get_fontname/)() override | Obtiene o establece el nombre de la cara de la [Font](../../aspose.font/font/). |
| [get_FontNames](./get_fontnames/)() override | Obtiene los nombres de la [Font](../../aspose.font/font/). |
| [get_FontStyle](./get_fontstyle/)() override | Obtiene el estilo de la [Font](../../aspose.font/font/). Este es un valor calculado y representado en tipo generalizado. |
| [get_FontType](./get_fonttype/)() override | Obtiene el tipo de la [Font](../../aspose.font/font/). Devuelve el valor [FontType.TTF](../../aspose.font/fonttype/). |
| [get_GlyphIdType](./get_glyphidtype/)() override | Obtiene la especificación del tipo de id de glifo. |
| [get_IsSymbolic](./get_issymbolic/)() | Devuelve true en caso de que la [Font](../../aspose.font/font/) sea simbólica. |
| [get_Metrics](./get_metrics/)() override | Obtiene las métricas de la [Font](../../aspose.font/font/). |
| [get_NumGlyphs](./get_numglyphs/)() override | Obtiene el número de glifos en la [Font](../../aspose.font/font/). |
| [get_PostscriptNames](./get_postscriptnames/)() override | Obtiene los nombres Postscript de la [Font](../../aspose.font/font/). |
| [get_Style](./get_style/)() override | Obtiene o establece el estilo de la [Font](../../aspose.font/font/). Este es un valor de cadena sin procesar proporcionado por el archivo [Font](../../aspose.font/font/). |
| virtual [get_TtfTables](./get_ttftables/)() | Obtiene tablas TTF. |
| [GetAllGlyphIds](./getallglyphids/)() override | Devuelve una matriz de todos los ids de glifos, disponibles en la [Font](../../aspose.font/font/). El id de glifo es un número único para un glifo, que depende del tipo de fuente. El id de glifo de la [Font](../../aspose.font/font/) TTF puede ser una instancia de la clase ([GlyphStringId](../)) o de la clase ([GlyphUInt32Id](../)). La dirección de glifos por nombre (cadena) es compatible con fuentes TTF mediante el mapeo de la tabla Post. En caso de que haya una [Font](../../aspose.font/font/) CFF dentro, se utilizan las estructuras CFF para direccionar glifos por nombre. |
| [GetGlyphById](./getglyphbyid/)(System::SharedPtr\<Glyphs::GlyphId\>) override | Devuelve el glifo por su id. El id de glifo es un número único para un glifo, que depende del tipo de fuente. El id de glifo de la [Font](../../aspose.font/font/) TTF puede ser una instancia de la clase ([GlyphStringId](../)) o de la clase ([GlyphUInt32Id](../)). La dirección de glifos por nombre (cadena) es compatible con fuentes TTF mediante el mapeo de la tabla Post. En caso de que haya una [Font](../../aspose.font/font/) CFF dentro, se utilizan las estructuras CFF para direccionar glifos por nombre. |
| [GetGlyphById](./getglyphbyid/)(System::String) | Devuelve el glifo por su nombre. La dirección de glifos por nombre (cadena) es compatible con fuentes TTF mediante el mapeo de la tabla Post. En caso de que haya una [Font](../../aspose.font/font/) CFF dentro, se utilizan las estructuras CFF para direccionar glifos por nombre. |
| [GetGlyphById](./getglyphbyid/)(uint32_t) | Devuelve el glifo por su id. |
| virtual [GetGlyphComponentsById](./getglyphcomponentsbyid/)(System::SharedPtr\<Glyphs::GlyphId\>, System::SharedPtr\<Glyphs::GlyphIdList\>) | Obtiene un glifo mediante el identificador de glifo proporcionado y llena la lista de identificadores de glifos pasada con los componentes de este glifo. El id de glifo es un número único para un glifo, que depende del tipo de fuente. El id de glifo de la [Font](../../aspose.font/font/) TTF puede ser una instancia de la clase ([GlyphStringId](../)) o de la clase ([GlyphUInt32Id](../)). La dirección de glifos por nombre (cadena) es compatible con fuentes TTF mediante el mapeo de la tabla Post. En caso de que haya una [Font](../../aspose.font/font/) CFF dentro, se utilizan las estructuras CFF para direccionar glifos por nombre. |
| [GetGlyphComponentsById](./getglyphcomponentsbyid/)(System::String, System::SharedPtr\<Glyphs::GlyphIdList\>) | Obtiene un glifo por el nombre de glifo proporcionado y llena la lista de identificadores de glifos pasada con los componentes de este glifo. |
| [GetGlyphComponentsById](./getglyphcomponentsbyid/)(uint32_t, System::SharedPtr\<Glyphs::GlyphIdList\>) | Obtiene un glifo por el índice de glifo proporcionado y llena la lista de identificadores de glifos pasada con los componentes de este glifo. |
| [GetGlyphsForText](./getglyphsfortext/)(System::String) override | Obtenga la representación de glifos para el texto. |
| [set_FontFamily](./set_fontfamily/)(System::String) override | Obtiene o establece la familia de la [Font](../../aspose.font/font/). |
| [set_FontName](./set_fontname/)(System::String) override | Obtiene o establece el nombre de la cara de la [Font](../../aspose.font/font/). |
| [set_Style](./set_style/)(System::String) override | Obtiene o establece el estilo de la [Font](../../aspose.font/font/). Este es un valor de cadena sin procesar proporcionado por el archivo [Font](../../aspose.font/font/). |
## Ver también

* Class [Font](../../aspose.font/font/)
* Namespace [Aspose::Font::Ttf](../)
* Library [Aspose.Font for C++](../../)
