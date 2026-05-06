---
title: "Método System::Web::Services::Protocols::SoapMessage::FindHeader"
linktitle: "FindHeader"
second_title: "Aspose.Font para C++"
description: "Método System::Web::Services::Protocols::SoapMessage::FindHeader. Encuentra la asignación de encabezado por el tipo de encabezado especificado en C++."
type: docs
weight: 300
url: /es/cpp/system.web.services.protocols/soapmessage/findheader/
---
## SoapMessage::FindHeader method


Encuentra el mapeo de la cabecera por el tipo de cabecera especificado.

```cpp
System::SharedPtr<SoapHeaderMapping> System::Web::Services::Protocols::SoapMessage::FindHeader(System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headersInfo, const TypeInfo &headerType)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| headersInfo | System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\> | La colección de las asignaciones de encabezados. |
| headerType | const TypeInfo\& | El tipo de encabezado a buscar. |

### ReturnValue

La asignación de encabezado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [SoapMessage](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.Font for C++](../../../)
