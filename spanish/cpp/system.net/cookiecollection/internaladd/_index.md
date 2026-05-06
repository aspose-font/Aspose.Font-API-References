---
title: "Método System::Net::CookieCollection::InternalAdd"
linktitle: "InternalAdd"
second_title: "Aspose.Font para C++"
description: "Método System::Net::CookieCollection::InternalAdd. Añade la cookie especificada a la colección en C++."
type: docs
weight: 1000
url: /es/cpp/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd method


Añade la cookie especificada a la colección.

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cookie | System::SharedPtr\<Cookie\> | La cookie a agregar. |
| isStrict | bool | True cuando la cookie especificada debe reemplazar a la anterior, de lo contrario false. |

### ReturnValue

0 cuando la cookie especificada reemplazó a la anterior, de lo contrario 1.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieCollection](../)
* Namespace [System::Net](../../)
* Library [Aspose.Font for C++](../../../)
