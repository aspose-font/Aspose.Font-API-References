---
title: "Aspose::Font::TtfTables::TtfNameTable::AddMultiLanguageNames método"
linktitle: "AddMultiLanguageNames"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::TtfTables::TtfNameTable::AddMultiLanguageNames método. Extrae todas las cadenas multilingües del objeto mlNames pasado y crea una estructura NameRecord correspondiente para cada cadena extraída usando los parámetros pasados platformId, platformSpecificId y nameId. El valor del campo languageID se extrae del objeto mlNames. El registro recién creado se añade a la tabla. Si se encuentra un registro que coincide con el recién creado por los campos platformID, platformSpecificID, nameID y languageId, entonces el registro nuevo no se añadirá y solo se actualizarán los datos de cadena del registro existente en C++."
type: docs
weight: 200
url: /es/cpp/aspose.font.ttftables/ttfnametable/addmultilanguagenames/
---
## TtfNameTable::AddMultiLanguageNames method


Extrae todas las cadenas multilingües del objeto *mlNames* pasado y crea una estructura [NameRecord](../namerecord/) correspondiente para cada cadena extraída usando los parámetros *platformId*, *platformSpecificId* y *nameId*. El valor del campo languageID se extrae del objeto *mlNames*. El registro recién creado se añade a la tabla. Si se encuentra un registro que coincide con el recién creado por los campos platformID, platformSpecificID, nameID y languageId, entonces el registro nuevo no se añadirá y solo se actualizarán los datos de cadena del registro existente.

```cpp
void Aspose::Font::TtfTables::TtfNameTable::AddMultiLanguageNames(System::SharedPtr<MultiLanguageString> mlNames, TtfNameTable::PlatformId platformId, uint16_t platformSpecificId, TtfNameTable::NameId nameId)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mlNames | System::SharedPtr\<MultiLanguageString\> | Cadena multilingüe |
| platformId | TtfNameTable::PlatformId | Identificador de plataforma |
| platformSpecificId | uint16_t | Identificador de codificación específica de plataforma |
| nameId | TtfNameTable::NameId | Identificador de nombre, categoría de cadena lógica, especificado por la enumeración [NameId](../nameid/) |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MultiLanguageString](../../../aspose.font/multilanguagestring/)
* Enum [PlatformId](../platformid/)
* Enum [NameId](../nameid/)
* Class [TtfNameTable](../)
* Namespace [Aspose::Font::TtfTables](../../)
* Library [Aspose.Font for C++](../../../)
