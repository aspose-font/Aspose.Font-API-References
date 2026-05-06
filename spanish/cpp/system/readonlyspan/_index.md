---
title: "Clase System::ReadOnlySpan"
linktitle: "ReadOnlySpan"
second_title: "Aspose.Font para C++"
description: "Clase System::ReadOnlySpan. Se utiliza dentro de la clase Span en C++."
type: docs
weight: 5300
url: /es/cpp/system/readonlyspan/
---
## ReadOnlySpan class


Se utiliza dentro de la clase [Span](../span/).

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span. Esta clase proporciona una forma segura de tipos para trabajar con secuencias contiguas de objetos en modo de solo lectura. Puede usarse para envolver arrays, arrays de pila o punteros sin procesar mientras mantiene la verificación de límites. El [ReadOnlySpan](./) no posee la memoria a la que apunta; es solo una vista de la memoria existente. |
## Métodos

| Método | Descripción |
| --- | --- |
| [ReadOnlySpan](./readonlyspan/)(const Span\<T\>\&) | Construye un span de solo lectura a partir de un span regular. |
| static [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | Convierte un array a un [ReadOnlySpan](./). |
## Observaciones


Representa una región contigua de memoria arbitraria de solo lectura.

## Ver también

* Namespace [System](../)
* Library [Aspose.Font for C++](../../)
