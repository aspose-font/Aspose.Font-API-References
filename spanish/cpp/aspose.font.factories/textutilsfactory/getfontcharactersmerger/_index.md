---
title: "Aspose::Font::Factories::TextUtilsFactory::GetFontCharactersMerger método"
linktitle: "GetFontCharactersMerger"
second_title: "Aspose.Font para C++"
description: "Método Aspose::Font::Factories::TextUtilsFactory::GetFontCharactersMerger. Obtiene una instancia de la clase FontCharactersMerger en C++."
type: docs
weight: 200
url: /es/cpp/aspose.font.factories/textutilsfactory/getfontcharactersmerger/
---
## TextUtilsFactory::GetFontCharactersMerger method


Obtiene una instancia de la clase [FontCharactersMerger](../).

```cpp
System::SharedPtr<Common_FontMerger::FontCharactersMerger> Aspose::Font::Factories::TextUtilsFactory::GetFontCharactersMerger(System::SharedPtr<Font> primaryFont, System::SharedPtr<Font> secondaryFont, FontType outType)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| primaryFont | System::SharedPtr\<Font\> | Fuente primaria de la cual obtener glifos |
| secondaryFont | System::SharedPtr\<Font\> | Fuente secundaria de la cual obtener glifos |
| outType | FontType | El formato de la fuente combinada de salida. |

### ReturnValue

Interfaz de combinación de fuentes o null si no se encuentra una combinación adecuada para el formato de fuente de entrada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FontCharactersMerger](../../../aspose.font.common_fontmerger/fontcharactersmerger/)
* Class [Font](../../../aspose.font/font/)
* Enum [FontType](../../../aspose.font/fonttype/)
* Class [TextUtilsFactory](../)
* Namespace [Aspose::Font::Factories](../../)
* Library [Aspose.Font for C++](../../../)
