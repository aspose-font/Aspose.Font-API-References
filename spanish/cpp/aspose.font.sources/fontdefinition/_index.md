---
title: "Clase Aspose::Font::Sources::FontDefinition"
linktitle: "FontDefinition"
second_title: "Aspose.Font para C++"
description: "Clase Aspose::Font::Sources::FontDefinition. Representa la definición del conjunto de archivos de fuente. Esta clase contiene campos que no están relacionados con los datos internos de la fuente. Estos campos describen la ubicación de la fuente y otros datos necesarios para cargar la fuente desde alguna fuente de fuentes (archivo, memoria, etc.) en C++."
type: docs
weight: 300
url: /es/cpp/aspose.font.sources/fontdefinition/
---
## FontDefinition class


Representa la definición del conjunto de archivos de [Font](../../aspose.font/font/). Esta clase contiene campos que no están relacionados con los datos internos de la fuente. Estos campos describen la ubicación de la fuente y otros datos necesarios para cargar la fuente desde alguna fuente de fuentes (archivo, memoria, etc.).

```cpp
class FontDefinition : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [FontDefinition](./fontdefinition/)(Aspose::Font::FontType, System::String, System::SharedPtr\<StreamSource\>) | Crea una definición de [Font](../../aspose.font/font/) de un solo archivo. |
| [FontDefinition](./fontdefinition/)(Aspose::Font::FontType, System::SharedPtr\<StreamSource\>) | Crea una definición de [Font](../../aspose.font/font/) de un solo archivo. |
| [FontDefinition](./fontdefinition/)(System::String, Aspose::Font::FontType, System::String, System::SharedPtr\<StreamSource\>) | Crea una definición de [Font](../../aspose.font/font/) de un solo archivo. |
| [FontDefinition](./fontdefinition/)(Aspose::Font::FontType, System::SharedPtr\<FontFileDefinition\>) | Crea una definición de [Font](../../aspose.font/font/) de un solo archivo. |
| [FontDefinition](./fontdefinition/)(System::String, Aspose::Font::FontType, System::SharedPtr\<FontFileDefinition\>) | Crea una definición de [Font](../../aspose.font/font/) de un solo archivo. |
| [FontDefinition](./fontdefinition/)(System::String, System::String, Aspose::Font::FontType, System::SharedPtr\<FontFileDefinition\>) | Crea una definición de [Font](../../aspose.font/font/) de un solo archivo. |
| [FontDefinition](./fontdefinition/)(Aspose::Font::FontType, System::ArrayPtr\<System::SharedPtr\<FontFileDefinition\>\>) | Crea una definición de [Font](../../aspose.font/font/) de varios archivos. |
| [FontDefinition](./fontdefinition/)(System::String, System::String, Aspose::Font::FontType, System::ArrayPtr\<System::SharedPtr\<FontFileDefinition\>\>) | Crea una definición de [Font](../../aspose.font/font/) de varios archivos. |
| [FontDefinition](./fontdefinition/)(System::SharedPtr\<MultiLanguageString\>, System::SharedPtr\<MultiLanguageString\>, Aspose::Font::FontType, System::SharedPtr\<FontFileDefinition\>) | Crea una definición de [Font](../../aspose.font/font/) de varios archivos. |
| [FontDefinition](./fontdefinition/)(System::SharedPtr\<MultiLanguageString\>, System::SharedPtr\<MultiLanguageString\>, Aspose::Font::FontType, System::ArrayPtr\<System::SharedPtr\<FontFileDefinition\>\>) | Crea una definición de [Font](../../aspose.font/font/) de varios archivos. |
| [get_FileDefinitions](./get_filedefinitions/)() const | Obtiene la colección de definiciones de archivos. |
| virtual [get_FontName](./get_fontname/)() | Devuelve el nombre de [Font](../../aspose.font/font/). |
| virtual [get_FontNames](./get_fontnames/)() | Obtiene los nombres de [Font](../../aspose.font/font/) como un [MultiLanguageString](../../aspose.font/multilanguagestring/). |
| [get_FontType](./get_fonttype/)() const | Obtiene el tipo de [Font](../../aspose.font/font/). |
| virtual [get_PostscriptName](./get_postscriptname/)() | Obtiene el nombre postscript de [Font](../../aspose.font/font/). |
| [get_PostscriptNames](./get_postscriptnames/)() const | Obtiene los nombres postscript de [Font](../../aspose.font/font/) como un [MultiLanguageString](../../aspose.font/multilanguagestring/). |
| static [Open](./open/)(System::String, Aspose::Font::FontType) | Devuelve [FontDefinition](./) para el archivo de fuente y el tipo de fuente. |
| static [Open](./open/)(System::SharedPtr\<StreamSource\>, Aspose::Font::FontType) | Devuelve [FontDefinition](./) para la fuente de flujo de fuente y el tipo de fuente. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Font::Sources](../)
* Library [Aspose.Font for C++](../../)
