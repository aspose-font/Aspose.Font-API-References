---
title: "Aspose::Font::TtfTables::TtfNameTable::AddName método"
linktitle: "AddName"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::TtfTables::TtfNameTable::AddName método. Añade una entrada a la tabla. La categoría de datos de cadena a agregar se especifica mediante el parámetro name en C++."
type: docs
weight: 300
url: /es/cpp/aspose.font.ttftables/ttfnametable/addname/
---
## TtfNameTable::AddName method


Añade una entrada a la tabla. La categoría de datos de cadena a añadir se especifica mediante el parámetro *name*.

```cpp
void Aspose::Font::TtfTables::TtfNameTable::AddName(TtfNameTable::NameId nameId, TtfNameTable::PlatformId platformId, int32_t platformSpecificId, int32_t languageId, System::String name)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nameId | TtfNameTable::NameId | Identificador de nombre, categoría de cadena lógica, especificado por la enumeración [NameId](../nameid/) |
| platformId | TtfNameTable::PlatformId | Identificador de plataforma |
| platformSpecificId | int32_t | Identificador de codificación específico de la plataforma. Por favor, use un valor de una de estas enumeraciones - [UnicodePlatformSpecificId](../unicodeplatformspecificid/), [MacPlatformSpecificId](../macplatformspecificid/), [MSPlatformSpecificId](../msplatformspecificid/). La enumeración a usar se define por el contexto (*platformId*  parámetro) |
| languageId | int32_t | Identificador de idioma. Por favor, use un valor de las enumeraciones [MSLanguageId](../mslanguageid/) o [MacLanguageId](../maclanguageid/) que dependen del contexto, definido por el parámetro *platformId*. |
| nombre | System::String | Datos de cadena reales |

## Ver también

* Enum [NameId](../nameid/)
* Enum [PlatformId](../platformid/)
* Class [String](../../../system/string/)
* Class [TtfNameTable](../)
* Namespace [Aspose::Font::TtfTables](../../)
* Library [Aspose.Font for C++](../../../)
