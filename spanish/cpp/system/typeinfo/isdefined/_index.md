---
title: "Método System::TypeInfo::IsDefined"
linktitle: "IsDefined"
second_title: "Aspose.Font para C++"
description: "Método System::TypeInfo::IsDefined. NO IMPLEMENTADO. Indica si uno o más atributos del tipo especificado o de sus tipos derivados se aplican a este miembro en C++."
type: docs
weight: 4400
url: /es/cpp/system/typeinfo/isdefined/
---
## TypeInfo::IsDefined method


NO IMPLEMENTADO. Indica si uno o más atributos del tipo especificado o de sus tipos derivados se aplican a este miembro.

```cpp
bool System::TypeInfo::IsDefined(const TypeInfo &attributeType, bool inherit) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| attributeType | const TypeInfo\& | El tipo de atributo personalizado a buscar. La búsqueda incluye tipos derivados. |
| inherit | bool | true para buscar en la cadena de herencia de este miembro y encontrar los atributos; de lo contrario, false. Este parámetro se ignora para propiedades y eventos. |

### ReturnValue

true si una o más instancias de attributeType o cualquiera de sus tipos derivados se aplican a este miembro; de lo contrario, false.

## Ver también

* Class [TypeInfo](../)
* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
