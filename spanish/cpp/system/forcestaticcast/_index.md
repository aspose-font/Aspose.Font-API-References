---
title: "System::ForceStaticCast método"
linktitle: "ForzarConversiónEstática"
second_title: "Aspose.Font para C++"
description: "System::ForceStaticCast método. Realiza un cast estático real sobre objetos SmartPtr en C++."
type: docs
weight: 20500
url: /es/cpp/system/forcestaticcast/
---
## System::ForceStaticCast method


Realiza un cast estático real sobre objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```


| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo del punteado objetivo. |
| TFrom | Tipo del punteado de origen. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Puntero de origen. |

### ReturnValue

Resultado del cast si el cast está permitido, de lo contrario el comportamiento es indefinido.

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.Font for C++](../../)
