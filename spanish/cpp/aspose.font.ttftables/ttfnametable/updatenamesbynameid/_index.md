---
title: "Aspose::Font::TtfTables::TtfNameTable::UpdateNamesByNameId method"
linktitle: "UpdateNamesByNameId"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::TtfTables::TtfNameTable::UpdateNamesByNameId method. Selecciona todos los registros que están relacionados con la categoría de cadena lógica, especificada por el parámetro nameId, y actualiza el campo name (datos de cadena) en esos registros. Los campos relacionados con la plataforma (platformID, Platform-specific encoding ID) y el idioma (Language ID) no se ven afectados por este método. Sólo los datos de cadena name se reemplazan con un nuevo nombre. Use este método con precaución, ya que reemplazará los nombres originales para todas las plataformas e idiomas relacionados con nameId. Puede generar conflictos en casos donde los nombres originales tenían valores diferentes, porque la operación de reemplazo cambia todos esos valores por uno único. Y este nuevo valor puede presentar una inconsistencia lógica con algunas plataformas e idiomas. Este método es útil en casos donde el nombre original tiene una única representación para todas las plataformas e idiomas, por ejemplo, cuando los datos de cadena name están en inglés en C++."
type: docs
weight: 1100
url: /es/cpp/aspose.font.ttftables/ttfnametable/updatenamesbynameid/
---
## TtfNameTable::UpdateNamesByNameId method


Selecciona todos los registros que están relacionados con la categoría lógica de cadena, especificada por el parámetro nameId, y actualiza el campo name (datos de cadena) en esos registros. Los campos relacionados con la plataforma (platformID, Platform-specific encoding ID) y el idioma (Language ID) no se ven afectados por este método. Sólo los datos de cadena del nombre se reemplazan con un nuevo nombre. Utilice este método con precaución, ya que reemplazará los nombres originales para todas las plataformas y los idiomas relacionados con nameId. Puede generar conflictos en casos donde los nombres originales tenían valores diferentes, porque la operación de reemplazo cambia todos esos valores por uno único. Y este nuevo valor puede presentar una inconsistencia lógica con algunas plataformas y algunos idiomas. Este método es útil en casos donde el nombre original tiene una única representación para todas las plataformas y los idiomas, por ejemplo, cuando los datos de cadena del nombre están en idioma inglés.

```cpp
void Aspose::Font::TtfTables::TtfNameTable::UpdateNamesByNameId(TtfNameTable::NameId nameId, System::String newName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nameId | TtfNameTable::NameId | Identificador de nombre, categoría de cadena lógica, especificado por la enumeración [NameId](../nameid/) |
| newName | System::String | Nuevo nombre o nuevos datos de cadena |

## Ver también

* Enum [NameId](../nameid/)
* Class [String](../../../system/string/)
* Class [TtfNameTable](../)
* Namespace [Aspose::Font::TtfTables](../../)
* Library [Aspose.Font for C++](../../../)
