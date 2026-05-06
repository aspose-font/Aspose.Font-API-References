---
title: "System::Array::ConstrainedCopy método"
linktitle: "ConstrainedCopy"
second_title: "Aspose.Font para C++"
description: "System::Array::ConstrainedCopy método. Copia un rango de elementos de un System.Array que comienza en la fuente especificada en C++."
type: docs
weight: 4700
url: /es/cpp/system/array/constrainedcopy/
---
## Array::ConstrainedCopy method


Copia un rango de elementos de un [System.Array](../) que comienza en la fuente especificada.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
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
## Observaciones


¡IMPLEMENTACIÓN CRUDA TEMPORAL SIN NINGUNA REVERSIÓN!
## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
