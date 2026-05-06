---
title: "System::Net::WebRequest::RegisterPrefix método"
linktitle: "RegisterPrefix"
second_title: "Aspose.Font para C++"
description: "System::Net::WebRequest::RegisterPrefix método. Registra el descendiente WebRequest para la URI especificada en C++."
type: docs
weight: 600
url: /es/cpp/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix method


Registra el descendiente [WebRequest](../) para la URI especificada.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefijo | Cadena | La URI o el prefijo de la URI. |
| creator | System::SharedPtr\<IWebRequestCreate\> | Crea nuevas instancias de la clase [WebRequest](../). |

### ReturnValue

Verdadero cuando el descendiente [WebRequest](../) se registra correctamente para la URI especificada, de lo contrario falso.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWebRequestCreate](../../iwebrequestcreate/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Font for C++](../../../)
