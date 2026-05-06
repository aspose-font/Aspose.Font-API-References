---
title: "System::DynamicCastArray método"
linktitle: "ConversiónDinámicaArray"
second_title: "Aspose.Font para C++"
description: "System::DynamicCastArray método. Realiza el casting de los elementos del array especificado a un tipo diferente en C++."
type: docs
weight: 18000
url: /es/cpp/system/dynamiccastarray/
---
## System::DynamicCastArray method


Realiza el casting de los elementos del array especificado a un tipo diferente.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```


| Parámetro | Descripción |
| --- | --- |
| To | El tipo al que se deben convertir los elementos del array especificado |
| From | El tipo de los elementos del array cuyos elementos se van a convertir |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| from | const SharedPtr\<Array\<From\>\>\& | Puntero compartido al array que contiene los elementos a convertir |

### ReturnValue

Un puntero a un nuevo array que contiene elementos del tipo **To** equivalentes a los elementos de **from**

## Deprecated
Añadido para compatibilidad retroactiva. Use ExplicitCast en su lugar.

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.Font for C++](../../)
