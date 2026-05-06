---
title: "Aspose::Font::Font clase"
linktitle: "Font"
second_title: "Aspose.Font para C++"
description: "Clase Aspose::Font::Font. Representa la clase base Font en C++."
type: docs
weight: 400
url: /es/cpp/aspose.font/font/
---
## Font class


Representa la clase base [Font](./).

```cpp
class Font : public virtual Aspose::Font::IFont,
             public Aspose::Font::Glyphs::IGlyphAccessor,
             public Aspose::Font::IFontSaver,
             public Aspose::Font::Licensing::IVentureLicenseTarget
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Convert](./convert/)(Aspose::Font::FontType) | Convierte el [Font](./) a otro formato. |
| virtual [get_Encoding](./get_encoding/)() | Obtiene la codificación del [Font](./). |
| virtual [get_FontDefinition](./get_fontdefinition/)() | Obtiene la definición del [Font](./). |
| virtual [get_FontFamily](./get_fontfamily/)() | Obtiene o establece la familia del [Font](./). |
| virtual [get_FontName](./get_fontname/)() | Obtiene o establece el nombre de la cara del [Font](./). |
| virtual [get_FontNames](./get_fontnames/)() | Obtiene los nombres del [Font](./). |
| [get_FontSaver](./get_fontsaver/)() override | Obtiene la funcionalidad de guardado del [Font](./). |
| virtual [get_FontStyle](./get_fontstyle/)() | Obtiene el estilo del [Font](./). Este es un valor calculado y representado en un tipo generalizado. |
| virtual [get_FontType](./get_fonttype/)() | Obtiene el tipo del [Font](./). |
| [get_GlyphAccessor](./get_glyphaccessor/)() override | Accesor de glifos del [Font](./). Recupera glifos e identificadores de glifos. |
| virtual [get_GlyphIdType](./get_glyphidtype/)() | Especificación del tipo de id de glifo. Para los consumidores que necesitan conocer el tipo real de 'bytes[]'. |
| virtual [get_Metrics](./get_metrics/)() | Obtiene las métricas del [Font](./). |
| virtual [get_NumGlyphs](./get_numglyphs/)() | Obtiene el número de glifos en el [Font](./). |
| virtual [get_PostscriptNames](./get_postscriptnames/)() | Obtiene los nombres PostScript del [Font](./). |
| virtual [get_Style](./get_style/)() | Obtiene o establece el estilo del [Font](./). Este es un valor de cadena sin procesar proporcionado por el archivo [Font](./). |
| virtual [GetAllGlyphIds](./getallglyphids/)() | Devuelve todos los ids de glifos disponibles en el [Font](./). El id de glifo es un número único para un glifo, que depende del tipo de fuente. Por ejemplo: el id de [Type1](../../aspose.font.type1/) es un nombre de glifo, instancia de la clase ([GlyphStringId](../)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../)). |
| virtual [GetGlyphById](./getglyphbyid/)(System::SharedPtr\<Glyphs::GlyphId\>) | Devuelve el glifo por id de glifo. El id de glifo es un número único para un glifo, que depende del tipo de fuente. GlyphId: objeto derivado. Por ejemplo: el id de [Type1](../../aspose.font.type1/) es un nombre de glifo, instancia de la clase ([GlyphStringId](../)). El id de TTF es un índice entero, instancia de la clase ([GlyphUInt32Id](../)). |
| [GetGlyphsForText](./getglyphsfortext/)(System::String) override | Obtiene la representación de glifos para texto. |
| static [Open](./open/)(System::SharedPtr\<Aspose::Font::Sources::FontDefinition\>) | Abre una fuente, usando el objeto FontDefinition. |
| static [Open](./open/)(Aspose::Font::FontType, System::SharedPtr\<Sources::StreamSource\>) | Abre una fuente, usando el tipo de fuente y la fuente de flujo. |
| static [Open](./open/)(Aspose::Font::FontType, System::String) | Abre una fuente, usando el tipo de fuente y el nombre del archivo de fuente. |
| static [Open](./open/)(Aspose::Font::FontType, System::ArrayPtr\<uint8_t\>) | Abre una fuente, usando el tipo de fuente y la matriz de bytes de datos de la fuente. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Guarda el [Font](./) en su formato original. |
| [Save](./save/)(System::String) override | Guarda el [Font](./) en su formato original. |
| [SaveToFormat](./savetoformat/)(System::SharedPtr\<System::IO::Stream\>, FontSavingFormats) override | Guarda el [Font](./) en el formato especificado. |
| virtual [set_FontFamily](./set_fontfamily/)(System::String) | Obtiene o establece la familia del [Font](./). |
| virtual [set_FontName](./set_fontname/)(System::String) | Obtiene o establece el nombre de la cara del [Font](./). |
| virtual [set_Style](./set_style/)(System::String) | Obtiene o establece el estilo del [Font](./). Este es un valor de cadena sin procesar proporcionado por el archivo [Font](./). |
## Ver también

* Class [IFont](../ifont/)
* Class [IGlyphAccessor](../../aspose.font.glyphs/iglyphaccessor/)
* Class [IFontSaver](../ifontsaver/)
* Class [IVentureLicenseTarget](../../aspose.font.licensing/iventurelicensetarget/)
* Namespace [Aspose::Font](../)
* Library [Aspose.Font for C++](../../)
