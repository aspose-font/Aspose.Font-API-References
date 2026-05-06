---
title: "Clase System::Span"
linktitle: "Span"
second_title: "Aspose.Font para C++"
description: "Clase System::Span. Representa una región contigua de memoria arbitraria similar a std::span de C++20 en C++."
type: docs
weight: 5700
url: /es/cpp/system/span/
---
## Span class


Representa una región contigua de memoria arbitraria similar a std::span de C++20.

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span. Esta clase proporciona una forma segura de tipos para trabajar con secuencias contiguas de objetos. Puede usarse para envolver matrices, matrices en pila o punteros crudos mientras se mantiene la verificación de límites. El [Span](./) no posee la memoria a la que apunta, solo es una vista de la memoria existente. |
## Métodos

| Método | Descripción |
| --- | --- |
| [Clear](./clear/)() const | Borra el contenido del span estableciendo todos los elementos al valor predeterminado. |
| [Fill](./fill/)(const T\&) const | Llena el span con el valor especificado. |
| static [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | Convierte una matriz a un [Span](./). |

## Ver también

* Namespace [System](../)
* Library [Aspose.Font for C++](../../)
