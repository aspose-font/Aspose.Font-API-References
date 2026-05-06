---
title: "Aspose::Font::TtfTables::TtfNameTable clase"
linktitle: "TtfNameTable"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::TtfTables::TtfNameTable clase. Representa la tabla \"name\" del archivo de fuente TTF en C++."
type: docs
weight: 1300
url: /es/cpp/aspose.font.ttftables/ttfnametable/
---
## TtfNameTable class


Representa la tabla "name" del archivo TTF [Font](../../aspose.font/font/).

```cpp
class TtfNameTable : public Aspose::Font::TtfTables::TtfTableBase
```

## Nested classes

* Class [NameRecord](./namerecord/)
## Enums

| Enumeración | Descripción |
| --- | --- |
| [MacLanguageId](./maclanguageid/) | Enumeración de identificadores de idioma de la plataforma Macintosh. |
| [MacPlatformSpecificId](./macplatformspecificid/) | Representa la enumeración PlatformSpecificId de la plataforma Macintosh. |
| [MSLanguageId](./mslanguageid/) | Enumeración de identificadores de idioma de la plataforma Microsoft. |
| [MSPlatformSpecificId](./msplatformspecificid/) | Representa la enumeración PlatformSpecificId de la plataforma Microsoft. |
| [NameId](./nameid/) | Representa [NameId](./nameid/). |
| [PlatformId](./platformid/) | Representa la enumeración [PlatformId](./platformid/). |
| [UnicodePlatformSpecificId](./unicodeplatformspecificid/) | Representa la enumeración específica de plataforma Unicode. |
## Métodos

| Método | Descripción |
| --- | --- |
| [AddMultiLanguageNames](./addmultilanguagenames/)(System::SharedPtr\<MultiLanguageString\>, TtfNameTable::PlatformId, uint16_t, TtfNameTable::NameId) | Extrae todas las cadenas multilingües del objeto *mlNames* pasado y crea la estructura [NameRecord](./namerecord/) correspondiente para cada cadena extraída usando los parámetros pasados *platformId*, *platformSpecificId* y *nameId*. El valor del campo languageID se extrae del objeto *mlNames*. El registro recién creado se añade a la tabla. Si se encuentra un registro que coincide con el recién creado por los campos platformID, platformSpecificID, nameID y languageId, entonces el registro nuevo no se añadirá y solo se actualizarán los datos de cadena del registro existente. |
| [AddName](./addname/)(TtfNameTable::NameId, TtfNameTable::PlatformId, int32_t, int32_t, System::String) | Añade una entrada a la tabla. La categoría de datos de cadena a añadir se especifica mediante el parámetro *name*. |
| [DeleteRecords](./deleterecords/)(TtfNameTable::PlatformId, uint16_t, TtfNameTable::NameId) | Elimina todos los registros relacionados con los parámetros pasados. |
| [DeleteRecords](./deleterecords/)(TtfNameTable::PlatformId, uint16_t) | Elimina todos los registros relacionados con la plataforma especificada. |
| [DeleteRecords](./deleterecords/)(TtfNameTable::PlatformId, uint16_t, TtfNameTable::NameId, uint16_t) | Elimina el/los registro(s) relacionado(s) con los parámetros especificados. |
| [DeleteRecordsByNameId](./deleterecordsbynameid/)(TtfNameTable::NameId) | Elimina todos los registros relacionados con el parámetro nameId pasado. |
| static [get_Tag](./get_tag/)() | Obtiene la etiqueta de la tabla. |
| [GetAllNameRecords](./getallnamerecords/)() | Devuelve todas las estructuras [NameRecord](./namerecord/) de la tabla. |
| [GetMultiLanguageNameById](./getmultilanguagenamebyid/)(TtfNameTable::NameId) | Devuelve un nombre por nameId. |
| [GetMultiLanguageNameById](./getmultilanguagenamebyid/)(TtfNameTable::NameId, TtfNameTable::PlatformId) | Devuelve un nombre por nameId usando el identificador de plataforma pasado. |
| [GetMultiLanguageNameById](./getmultilanguagenamebyid/)(TtfNameTable::NameId, TtfNameTable::PlatformId, uint16_t) | Devuelve un nombre como objeto del tipo [MultiLanguageString](../../aspose.font/multilanguagestring/). El método recopila todas las estructuras [NameRecord](./namerecord/) que coinciden con los parámetros pasados nameId, platformId y platformSpecificId y luego construye el objeto resultante basándose en esta lista de estructuras. |
| [GetNameById](./getnamebyid/)(TtfNameTable::NameId) | Devuelve un nombre por nameId si se encuentra, null en caso contrario. |
| [GetNameRecordsByNameId](./getnamerecordsbynameid/)(TtfNameTable::NameId) | Devuelve todas las estructuras [NameRecord](./namerecord/) cuyo campo [NameId](./nameid/) sea igual al valor *nameId* pasado. Si no se encuentran registros, se devolverá una matriz vacía. |
| [UpdateName](./updatename/)(TtfNameTable::PlatformId, uint16_t, TtfNameTable::NameId, uint16_t, System::String) | Actualiza el nombre en el/los registro(s) que están relacionados con la plataforma especificada (combinación de platformId y platformSpecificId), la categoría (nameId) y el idioma (languageId). |
| [UpdateNamesByNameId](./updatenamesbynameid/)(TtfNameTable::NameId, System::String) | Selecciona todos los registros que están relacionados con la categoría lógica de cadena, especificada por el parámetro nameId, y actualiza el campo name (datos de cadena) en esos registros. Los campos relacionados con la plataforma (platformID, Platform-specific encoding ID) y el idioma (Language ID) no se ven afectados por este método. Sólo los datos de cadena del nombre se reemplazan con un nuevo nombre. Utilice este método con precaución, ya que reemplazará los nombres originales para todas las plataformas y los idiomas relacionados con nameId. Puede generar conflictos en casos donde los nombres originales tenían valores diferentes, porque la operación de reemplazo cambia todos esos valores por uno único. Y este nuevo valor puede presentar una inconsistencia lógica con algunas plataformas y algunos idiomas. Este método es útil en casos donde el nombre original tiene una única representación para todas las plataformas y los idiomas, por ejemplo, cuando los datos de cadena del nombre están en idioma inglés. |
## Ver también

* Class [TtfTableBase](../ttftablebase/)
* Namespace [Aspose::Font::TtfTables](../)
* Library [Aspose.Font for C++](../../)
