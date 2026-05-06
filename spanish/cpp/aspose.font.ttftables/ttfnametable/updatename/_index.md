---
title: "Aspose::Font::TtfTables::TtfNameTable::UpdateName method"
linktitle: "UpdateName"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::TtfTables::TtfNameTable::UpdateName method. Actualiza el nombre en los registros que están relacionados con la plataforma especificada (combinación de platformId y platformSpecificId), la categoría (nameId) y el idioma (languageId) en C++."
type: docs
weight: 1000
url: /es/cpp/aspose.font.ttftables/ttfnametable/updatename/
---
## TtfNameTable::UpdateName method


Actualiza el nombre en el/los registro(s) que están relacionados con la plataforma especificada (combinación de platformId y platformSpecificId), la categoría (nameId) y el idioma (languageId).

```cpp
void Aspose::Font::TtfTables::TtfNameTable::UpdateName(TtfNameTable::PlatformId platformId, uint16_t platformSpecificId, TtfNameTable::NameId nameId, uint16_t languageId, System::String newName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| platformId | TtfNameTable::PlatformId | Identificador de plataforma |
| platformSpecificId | uint16_t | Identificador de codificación específica de plataforma |
| nameId | TtfNameTable::NameId | Identificador de nombre, categoría de cadena lógica, especificado por la enumeración [NameId](../nameid/) |
| languageId | uint16_t | Identificador de idioma |
| newName | System::String | Nuevo nombre o nuevos datos de cadena |

## Ver también

* Enum [PlatformId](../platformid/)
* Enum [NameId](../nameid/)
* Class [String](../../../system/string/)
* Class [TtfNameTable](../)
* Namespace [Aspose::Font::TtfTables](../../)
* Library [Aspose.Font for C++](../../../)
