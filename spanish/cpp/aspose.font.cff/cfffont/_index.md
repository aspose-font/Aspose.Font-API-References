---
title: "Aspose::Font::Cff::CffFont clase"
linktitle: "CffFont"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::Cff::CffFont clase. Representa Compact Font Format (CFF) en C++."
type: docs
weight: 200
url: /es/cpp/aspose.font.cff/cfffont/
---
## CffFont class


Representa Compact [Font](../../aspose.font/font/) Format (CFF).

```cpp
class CffFont : public Aspose::Font::Font
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Convert](./convert/)(Aspose::Font::FontType) override | Convierte el [Font](../../aspose.font/font/) a otro formato. |
| [get_CommonFontsSettings](./get_commonfontssettings/)() const | Obtiene/establece configuraciones comunes a fuentes CFF. Estas configuraciones se utilizan en diferentes escenarios y pueden cambiarse para cada fuente individual. |
| [get_Encoding](./get_encoding/)() override | Obtiene la codificación de la [Font](../../aspose.font/font/). |
| [get_FontDefinition](./get_fontdefinition/)() override | Obtiene la definición de la [Font](../../aspose.font/font/). |
| [get_FontFamily](./get_fontfamily/)() override | Obtiene la familia de [Font](../../aspose.font/font/). El establecedor de la familia de [Font](../../aspose.font/font/) aún no está implementado. |
| [get_FontName](./get_fontname/)() override | Obtiene el nombre de estilo de [Font](../../aspose.font/font/). |
| [get_FontNames](./get_fontnames/)() override | Obtiene los nombres de [Font](../../aspose.font/font/). |
| [get_FontStyle](./get_fontstyle/)() override | Obtiene el estilo de la [Font](../../aspose.font/font/). Este es un valor calculado y representado en tipo generalizado. |
| [get_FontType](./get_fonttype/)() override | Obtiene el tipo de [Font](../../aspose.font/font/). Devuelve el valor [FontType.CFF](../../aspose.font/fonttype/). |
| [get_GlyphIdType](./get_glyphidtype/)() override | Obtiene la especificación del tipo de id de glifo. |
| [get_IsCidKeyedFont](./get_iscidkeyedfont/)() | Obtiene un valor que indica que la [Font](../../aspose.font/font/) es cid-keyed. |
| [get_Metrics](./get_metrics/)() override | Obtiene las métricas de la [Font](../../aspose.font/font/). |
| [get_NumGlyphs](./get_numglyphs/)() override | Obtiene el número de glifos en la [Font](../../aspose.font/font/). |
| [get_PostscriptNames](./get_postscriptnames/)() override | Obtiene los nombres postscript de [Font](../../aspose.font/font/). |
| [get_Style](./get_style/)() override | Obtiene el estilo de [Font](../../aspose.font/font/). Este es un valor de cadena sin procesar proporcionado por el archivo [Font](../../aspose.font/font/). |
| [get_TopDictDataProvider](./get_topdictdataprovider/)() | Obtiene el accesor para el primer DICT de nivel superior en la estructura Top DICT INDEX. |
| [GetAllGlyphIds](./getallglyphids/)() override | Devuelve una matriz de todos los ids de glifos, disponibles en la [Font](../../aspose.font/font/). El id de glifo es un número único para un glifo, que depende del tipo de fuente. El id de glifo CFF [Font](../../aspose.font/font/) puede ser una instancia de la clase ([GlyphStringId](../)) o de la clase ([GlyphUInt32Id](../)). |
| [GetGlyphById](./getglyphbyid/)(System::SharedPtr\<Glyphs::GlyphId\>) override | Devuelve el glifo por id de glifo. El id de glifo es un número único para un glifo, que depende del tipo de fuente. El id de glifo CFF [Font](../../aspose.font/font/) puede ser una instancia de la clase ([GlyphStringId](../)) o de la clase ([GlyphUInt32Id](../)). |
| [GetGlyphById](./getglyphbyid/)(System::String) | Devuelve el glifo por nombre de glifo. |
| [GetGlyphById](./getglyphbyid/)(uint32_t) | Devuelve el glifo por su id. |
| [GetIndexDataProvider](./getindexdataprovider/)(CffDataProviders::CffIndexProviderType) | Obtiene el proveedor para el tipo de estructura CFF INDEX especificado. |
| [set_CommonFontsSettings](./set_commonfontssettings/)(System::SharedPtr\<CffFontsSettings\>) | Obtiene/establece configuraciones comunes a fuentes CFF. Estas configuraciones se utilizan en diferentes escenarios y pueden cambiarse para cada fuente individual. |
| [set_FontFamily](./set_fontfamily/)(System::String) override | Obtiene la familia de [Font](../../aspose.font/font/). El establecedor de la familia de [Font](../../aspose.font/font/) aún no está implementado. |
| [set_FontName](./set_fontname/)(System::String) override | Establece el nombre de estilo de [Font](../../aspose.font/font/). |
| [set_Style](./set_style/)(System::String) override | Establece el estilo de [Font](../../aspose.font/font/). Este es un valor de cadena sin procesar proporcionado por el archivo [Font](../../aspose.font/font/). |
## Ver también

* Class [Font](../../aspose.font/font/)
* Namespace [Aspose::Font::Cff](../)
* Library [Aspose.Font for C++](../../)
