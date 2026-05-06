---
title: "Clase System::Collections::Generic::ListPtr"
linktitle: "ListPtr"
second_title: "Aspose.Font para C++"
description: "Clase System::Collections::Generic::ListPtr. Puntero de lista con operadores de acceso. Este tipo es un puntero para gestionar la eliminación del objeto de otro objeto. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante en C++."
type: docs
weight: 3500
url: /es/cpp/system.collections.generic/listptr/
---
## ListPtr class


[List](../list/) pointer with access operators. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class ListPtr : public System::SmartPtr<T0>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ListPtr](./listptr/)(std::nullptr_t) | Inicializa un puntero nulo. |
| [ListPtr](./listptr/)(const SharedPtr\<List\<T\>\>\&) | Inicializa un puntero a la lista especificada. |
| [operator==](./operator==/)(std::nullptr_t) const | Comprueba si el puntero [List](../list/) es nulo. |
| [operator[]](./operator[]/)(int) | Accesor. |
| [operator[]](./operator[]/)(int) const | Accesor. |
## Ver también

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Font for C++](../../)
