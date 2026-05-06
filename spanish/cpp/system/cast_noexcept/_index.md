---
title: "Método System::Cast_noexcept"
linktitle: "Cast_noexcept"
second_title: "Aspose.Font para C++"
description: "Método System::Cast_noexcept. Realiza una conversión en objetos SmartPtr en C++."
type: docs
weight: 15500
url: /es/cpp/system/cast_noexcept/
---
## System::Cast_noexcept method


Realiza cast en objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```


| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo del punteado objetivo. |
| TFrom | Tipo del punteado de origen. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Puntero de origen. |

### ReturnValue

Resultado del casting si el casting está permitido o nullptr en caso contrario.

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.Font for C++](../../)
