---
title: "Método System::ConstCast"
linktitle: "ConstCast"
second_title: "Aspose.Font para C++"
description: "Método System::ConstCast. Fin de los casts obsoletos en C++."
type: docs
weight: 16200
url: /es/cpp/system/constcast/
---
## System::ConstCast method


Fin de los casts obsoletos.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```


| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo del punteado objetivo. |
| TFrom | Tipo del punteado de origen. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const SmartPtr\<TFrom\>\& | Puntero de origen. |

### ReturnValue

Resultado del casting si el casting está permitido o nullptr en caso contrario.
## Observaciones


Realiza un cast const en objetos [SmartPtr](../smartptr/).
## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.Font for C++](../../)
