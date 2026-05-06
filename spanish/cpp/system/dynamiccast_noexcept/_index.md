---
title: "Método System::DynamicCast_noexcept"
linktitle: "ConversiónDinámica_noexcept"
second_title: "Aspose.Font para C++"
description: "Método System::DynamicCast_noexcept. Casts antiguos obsoletos. Será eliminado en versiones futuras de C++."
type: docs
weight: 17700
url: /es/cpp/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) method


Conversiones antiguas obsoletas. Se eliminarán en versiones futuras.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```


| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo objetivo [Exception](../exception/). |
| TFrom | Tipo origen [Exception](../exception/). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const TFrom\& | Puntero de origen. |

### ReturnValue

Resultado del casting si el casting está permitido o nullptr en caso contrario.
## Observaciones


Realiza un cast dinámico en objetos [Exception](../exception/). ## Deprecated
Se mantiene por compatibilidad hacia atrás. Use AsCast en su lugar.

## Ver también

* Namespace [System](../)
* Library [Aspose.Font for C++](../../)
## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) method


Realiza un cast dinámico en objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
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

## Deprecated
Se mantiene por compatibilidad hacia atrás. Use AsCast en su lugar.

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.Font for C++](../../)
## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) method


Realiza un cast dinámico de objetos a objetos [Exception](../exception/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo objetivo [Exception](../exception/). |
| TFrom | Tipo [Object](../object/). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> | Puntero de origen. |

### ReturnValue

Resultado del casting si el casting está permitido o nullptr en caso contrario.

## Deprecated
Se mantiene por compatibilidad hacia atrás. Use AsCast en su lugar.

## Ver también

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.Font for C++](../../)
