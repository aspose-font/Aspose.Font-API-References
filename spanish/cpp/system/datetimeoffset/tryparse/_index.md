---
title: "Método System::DateTimeOffset::TryParse"
linktitle: "TryParse"
second_title: "Aspose.Font para C++"
description: "Método System::DateTimeOffset::TryParse. Intenta convertir la cadena especificada a un objeto DateTimeOffset usando el proveedor de formato especificado y el estilo de formato en C++."
type: docs
weight: 5700
url: /es/cpp/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Intenta convertir la cadena especificada a un objeto [DateTimeOffset](../) usando el proveedor de formato especificado y el estilo de formato.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | [String](../../string/) para convertir. |
| proveedor | const SharedPtr\<IFormatProvider\>\& | Proveedor de formato. |
| estilos | Globalization::DateTimeStyles | Estilos de formato de fecha y hora. |
| result | DateTimeOffset\& | [DateTimeOffset](../) que es equivalente al **input**. |

### ReturnValue

true si el **input** se convierte correctamente, de lo contrario - false.

## Ver también

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTimeOffset](../)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) method


Intenta convertir la cadena especificada a un objeto [DateTimeOffset](../).

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | [String](../../string/) para convertir. |
| result | DateTimeOffset\& | [DateTimeOffset](../) que es equivalente al **input**. |

### ReturnValue

true si el **input** se convierte correctamente, de lo contrario - false.

## Ver también

* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
