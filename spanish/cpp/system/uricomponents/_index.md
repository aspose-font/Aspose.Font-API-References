---
title: "Enumeración System::UriComponents"
linktitle: "UriComponents"
second_title: "Aspose.Font para C++"
description: "Enumeración System::UriComponents. Representa los componentes URI en C++."
type: docs
weight: 8900
url: /es/cpp/system/uricomponents/
---
## UriComponents enum


Representa los componentes de URI.

```cpp
enum class UriComponents
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Esquema | 1 | Los datos de Scheme. |
| UserInfo | 2 | Los datos de UserInfo. |
| Host | 4 | Los datos de Host. |
| Puerto | 8 | Los datos de Port. |
| SchemeAndServer | n/a | Los datos de Scheme, Host y Port. |
| Ruta | 16 | Los datos de LocalPath. |
| Consulta | 32 | Los datos de Query. |
| PathAndQuery | n/a | Los datos de LocalPath y Query. |
| HttpRequestUrl | n/a | Los datos de Scheme, Host, Port, Query y LocalPath. |
| Fragment | 64 | Los datos de Fragment. |
| AbsoluteUri | n/a | Los datos de Scheme, Host, Port, Quer, LocalPath y Fragment. |
| StrongPort | 128 | Los datos de Port; si los datos de port no están presentes en el [Uri](../uri/) y se ha asignado un puerto predeterminado al Scheme, se devuelve el puerto predeterminado; si no hay puerto predeterminado, se devuelve -1. |
| HostAndPort | n/a | Los datos de Host y Port; si los datos de Port no están presentes en el [Uri](../uri/) y se ha asignado un puerto predeterminado al Esquema, se devuelve el puerto predeterminado. Si no hay puerto predeterminado, se devuelve -1. |
| StrongAuthority | n/a | Los datos de UserInfo, Host y Port. Si no hay datos de Port en el [Uri](../uri/) y se ha asignado un puerto predeterminado al Esquema, se devuelve el puerto predeterminado. Si no hay puerto predeterminado, se devuelve -1. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | Especifica que el delimitador debe incluirse. |
| SerializationInfoString | n/a | El contexto completo del [Uri](../uri/) que se necesita para los Serializadores de [Uri](../uri/). El contexto incluye el ámbito IPv6. |

## Ver también

* Namespace [System](../)
* Library [Aspose.Font for C++](../../)
