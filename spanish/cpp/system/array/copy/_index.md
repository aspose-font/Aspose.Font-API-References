---
title: "Método System::Array::Copy"
linktitle: "Copy"
second_title: "Aspose.Font para C++"
description: "Método System::Array::Copy. Copia el número especificado de elementos del arreglo fuente al arreglo de destino en C++."
type: docs
weight: 4900
url: /es/cpp/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) method


Copia la cantidad especificada de elementos de la matriz origen a la matriz destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Array de origen |
| dstArray | const ArrayPtr\<DstType\>\& | Array de destino |
| count | int64_t | El número de elementos a copiar |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method


Copia una cantidad especificada de elementos de la matriz origen a partir del índice especificado hacia la posición especificada en la matriz destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


| Parámetro | Descripción |
| --- | --- |
| SrcType | Tipo de elementos en el array de origen |
| DstType | Tipo de elementos en el array de destino |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Array de origen |
| srcIndex | int64_t | Índice en el array de origen que designa el comienzo del rango de elementos a copiar |
| dstArray | const ArrayPtr\<DstType\>\& | Array de destino |
| dstIndex | int64_t | Índice en el array de destino donde comenzar a insertar los elementos copiados |
| count | int64_t | El número de elementos a copiar |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method


Copia una cantidad especificada de elementos de la matriz origen a partir del índice especificado hacia la posición especificada en la vista de la matriz destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


| Parámetro | Descripción |
| --- | --- |
| SrcType | Tipo de elementos en el array de origen |
| DstType | Tipo de elementos en la vista del array de destino |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Array de origen |
| srcIndex | int64_t | Índice en el array de origen que designa el comienzo del rango de elementos a copiar |
| dstArray | System::Details::ArrayView\<DstType\> | Vista del arreglo de destino |
| dstIndex | int64_t | Índice en la vista del arreglo de destino donde comenzar a insertar los elementos copiados |
| count | int64_t | El número de elementos a copiar |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) method


Copia una cantidad especificada de elementos de la matriz origen a partir del índice especificado hacia la posición especificada en la matriz destino en la pila.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```


| Parámetro | Descripción |
| --- | --- |
| SrcType | Tipo de elementos en el array de origen |
| DstType | Tipo de elementos en el arreglo de destino en la pila |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Array de origen |
| srcIndex | int64_t | Índice en el array de origen que designa el comienzo del rango de elementos a copiar |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Arreglo de destino en la pila |
| dstIndex | int64_t | Índice en el arreglo de destino en la pila donde comenzar a insertar los elementos copiados |
| count | int64_t | El número de elementos a copiar |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) method


Copia la cantidad especificada de elementos de la matriz origen a la vista de la matriz destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Array de origen |
| dstArray | System::Details::ArrayView\<DstType\> | Vista del arreglo de destino |
| count | int64_t | El número de elementos a copiar |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) method


Copia la cantidad especificada de elementos de la matriz origen a la matriz destino en la pila.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Array de origen |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Arreglo de destino en la pila |
| count | int64_t | El número de elementos a copiar |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method


Copia una cantidad especificada de elementos de la vista de la matriz origen a partir del índice especificado hacia la posición especificada en la matriz destino en la pila.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


| Parámetro | Descripción |
| --- | --- |
| SrcType | Tipo de elementos en el arreglo fuente en la pila |
| DstType | Tipo de elementos en el arreglo de destino en la pila |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | Vista del arreglo fuente |
| srcIndex | int64_t | Índice en la vista del arreglo fuente que designa el comienzo del rango de elementos a copiar |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Arreglo de destino en la pila |
| dstIndex | int64_t | Índice en el arreglo de destino en la pila donde comenzar a insertar los elementos copiados |
| count | int64_t | El número de elementos a copiar |

## Ver también

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) method


Copia la cantidad especificada de elementos de la vista de la matriz origen a la matriz destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Vista del arreglo fuente |
| dstArray | const ArrayPtr\<DstType\>\& | Array de destino |
| count | int64_t | El número de elementos a copiar |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method


Copia una cantidad especificada de elementos de la vista de la matriz origen a partir del índice especificado hacia la posición especificada en la matriz destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


| Parámetro | Descripción |
| --- | --- |
| SrcType | Tipo de elementos en la vista del arreglo fuente |
| DstType | Tipo de elementos en el array de destino |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Vista del arreglo fuente |
| srcIndex | int64_t | Índice en la vista del arreglo fuente que designa el comienzo del rango de elementos a copiar |
| dstArray | const ArrayPtr\<DstType\>\& | Array de destino |
| dstIndex | int64_t | Índice en el array de destino donde comenzar a insertar los elementos copiados |
| count | int64_t | El número de elementos a copiar |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method


Copia una cantidad especificada de elementos de la vista de la matriz origen a partir del índice especificado hacia la posición especificada en la vista de la matriz destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


| Parámetro | Descripción |
| --- | --- |
| SrcType | Tipo de elementos en la vista del arreglo fuente |
| DstType | Tipo de elementos en la vista del array de destino |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Vista del arreglo fuente |
| srcIndex | int64_t | Índice en la vista del arreglo fuente que designa el comienzo del rango de elementos a copiar |
| dstArray | System::Details::ArrayView\<DstType\> | Vista del arreglo de destino |
| dstIndex | int64_t | Índice en la vista del arreglo de destino donde comenzar a insertar los elementos copiados |
| count | int64_t | El número de elementos a copiar |

## Ver también

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) method


Copia la cantidad especificada de elementos de la vista de la matriz origen a la vista de la matriz destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Vista del arreglo fuente |
| dstArray | System::Details::ArrayView\<DstType\> | Vista del arreglo de destino |
| count | int64_t | El número de elementos a copiar |

## Ver también

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) method


Copia la cantidad especificada de elementos de la matriz origen en la pila a la matriz destino.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Arreglo fuente en la pila |
| dstArray | const ArrayPtr\<DstType\>\& | Array de destino |
| count | int64_t | El número de elementos a copiar |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method


Copia una cantidad especificada de elementos de la matriz origen en la pila a partir del índice especificado hacia la posición especificada en la matriz destino.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


| Parámetro | Descripción |
| --- | --- |
| SrcType | Tipo de elementos en el arreglo fuente en la pila |
| DstType | Tipo de elementos en el array de destino |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Arreglo fuente en la pila |
| srcIndex | int64_t | Índice en el arreglo fuente en la pila que designa el comienzo del rango de elementos a copiar |
| dstArray | const ArrayPtr\<DstType\>\& | Array de destino |
| dstIndex | int64_t | Índice en el array de destino donde comenzar a insertar los elementos copiados |
| count | int64_t | El número de elementos a copiar |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method


Copia una cantidad especificada de elementos de la matriz origen en la pila a partir del índice especificado hacia la posición especificada en la matriz destino en la pila.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


| Parámetro | Descripción |
| --- | --- |
| SrcType | Tipo de elementos en el arreglo fuente en la pila |
| DstType | Tipo de elementos en el arreglo de destino en la pila |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Arreglo fuente en la pila |
| srcIndex | int64_t | Índice en el arreglo fuente en la pila que designa el comienzo del rango de elementos a copiar |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Arreglo de destino en la pila |
| dstIndex | int64_t | Índice en el arreglo de destino en la pila donde comenzar a insertar los elementos copiados |
| count | int64_t | El número de elementos a copiar |

## Ver también

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) method


Copia la cantidad especificada de elementos de la matriz origen en la pila a la matriz destino en la pila.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Arreglo fuente en la pila |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Arreglo de destino en la pila |
| count | int64_t | El número de elementos a copiar |

## Ver también

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
