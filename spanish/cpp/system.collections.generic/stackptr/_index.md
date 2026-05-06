---
title: "Clase System::Collections::Generic::StackPtr"
linktitle: "StackPtr"
second_title: "Aspose.Font para C++"
description: "Clase System::Collections::Generic::StackPtr. Puntero de pila. Este tipo es un puntero para gestionar la eliminación del objeto de otro objeto. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante en C++."
type: docs
weight: 4700
url: /es/cpp/system.collections.generic/stackptr/
---
## StackPtr class


[Stack](../stack/) pointer. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class StackPtr : public System::SmartPtr<T0>
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elemento. |
## Métodos

| Método | Descripción |
| --- | --- |
| [StackPtr](./stackptr/)() | Construye un puntero nulo. |
| [StackPtr](./stackptr/)(const SharedPtr\<Stack\<T\>\>\&) | Construye un puntero que referencia una pila específica. |

## Ver también

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Font for C++](../../)
