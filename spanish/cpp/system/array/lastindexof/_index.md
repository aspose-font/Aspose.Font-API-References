---
title: "System::Array::LastIndexOf method"
linktitle: "LastIndexOf"
second_title: "Aspose.Font para C++"
description: "System::Array::LastIndexOf method. Determina el índice de la última aparición del elemento especificado en un rango de elementos del array definido por el índice de inicio y el número de elementos en el rango en C++."
type: docs
weight: 5500
url: /es/cpp/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) method


Determina el índice de la última aparición del elemento especificado en un rango de elementos del array especificado por el índice de inicio y el número de elementos en el rango.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```


| Parámetro | Descripción |
| --- | --- |
| ArrayType | Tipo de elementos en el array de destino |
| ValueType | tipo del elemento a buscar en el array |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const ArrayPtr\<ArrayType\>\& | [Array](../) para buscar el elemento especificado en |
| valor | const ValueType\& | Índice del elemento que se debe determinar |
| startIndex | int | Índice en el que se inicia la búsqueda |
| count | int | Número de elementos del rango en el que buscar |

### ReturnValue

Índice de la última aparición del elemento especificado si se encuentra, de lo contrario -1

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) method


Determina el índice de la última aparición del elemento especificado en el array.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```


| Parámetro | Descripción |
| --- | --- |
| ArrayType | Tipo de elementos en el array de destino |
| ValueType | tipo del elemento a buscar en el array |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| items | const ArrayPtr\<ArrayType\>\& | [Array](../) para buscar el elemento especificado en |
| valor | const ValueType\& | Índice del elemento que se debe determinar |

### ReturnValue

Índice de la última aparición del elemento especificado si se encuentra, de lo contrario -1

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) method


Determina el índice de la última aparición del elemento especificado en el array a partir del índice especificado.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```


| Parámetro | Descripción |
| --- | --- |
| ArrayType | Tipo de elementos en el array de destino |
| ValueType | tipo del elemento a buscar en el array |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| items | const ArrayPtr\<ArrayType\>\& | [Array](../) para buscar el elemento especificado en |
| valor | const ValueType\& | Índice del elemento que se debe determinar |
| startIndex | int | Índice en el que se inicia la búsqueda |

### ReturnValue

Índice de la última aparición del elemento especificado si se encuentra, de lo contrario -1

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
