---
title: "System::Array::CopyTo método"
linktitle: "CopyTo"
second_title: "Aspose.Font para C++"
description: "System::Array::CopyTo método. Copia todos los elementos del array actual al array de destino especificado. Los elementos se insertan en el array de destino comenzando en el índice especificado por el argumento arrayIndex en C++."
type: docs
weight: 900
url: /es/cpp/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) method


Copia todos los elementos de la matriz actual a la matriz destino especificada. Los elementos se insertan en la matriz destino a partir del índice especificado por el argumento arrayIndex.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | ArrayPtr\<T\> | Array de destino |
| arrayIndex | int | Índice en el array de destino donde comenzar a insertar los elementos copiados |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const method


Copia todos los elementos de la matriz actual a la matriz destino especificada. Los elementos se insertan en la matriz destino a partir del índice especificado por el argumento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```


| Parámetro | Descripción |
| --- | --- |
| DstType | Tipo de elementos en el array de destino |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dstArray | const ArrayPtr\<DstType\>\& | Array de destino |
| dstIndex | int64_t | Índice en el array de destino donde comenzar a insertar los elementos copiados |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const method


Copia una cantidad especificada de elementos de la matriz actual a partir de la posición especificada hacia la matriz destino especificada. Los elementos se insertan en la matriz destino a partir del índice especificado por el argumento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


| Parámetro | Descripción |
| --- | --- |
| DstType | Tipo de elementos en el array de destino |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dstArray | const ArrayPtr\<DstType\>\& | Array de destino |
| srcIndex | int64_t | Índice en el array de origen donde comenzar a copiar los elementos |
| dstIndex | int64_t | Índice en el array de destino donde comenzar a insertar los elementos copiados |
| count | int64_t | Número de elementos a copiar |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const method


Copia todos los elementos de la matriz actual a la vista de la matriz destino especificada. Los elementos se insertan en la vista de la matriz destino a partir del índice especificado por el argumento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```


| Parámetro | Descripción |
| --- | --- |
| DstType | Tipo de elementos en la vista del array de destino |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Vista del arreglo de destino |
| dstIndex | int64_t | Índice en la vista del arreglo de destino donde comenzar a insertar los elementos copiados |

## Ver también

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const method


Copia un número especificado de elementos del arreglo actual comenzando en la posición especificada hacia la vista del arreglo de destino especificada. Los elementos se insertan en la vista del arreglo de destino comenzando en el índice especificado por el argumento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


| Parámetro | Descripción |
| --- | --- |
| DstType | Tipo de elementos en la vista del array de destino |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Vista del arreglo de destino |
| srcIndex | int64_t | Índice en el array de origen donde comenzar a copiar los elementos |
| dstIndex | int64_t | Índice en la vista del arreglo de destino donde comenzar a insertar los elementos copiados |
| count | int64_t | Número de elementos a copiar |

## Ver también

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
