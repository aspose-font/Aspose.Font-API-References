---
title: "System::Delegate< ReturnType(ArgumentTypes...)> clase"
linktitle: "Delegate< ReturnType(ArgumentTypes...)>"
second_title: "Aspose.Font para C++"
description: "System::Delegate< ReturnType(ArgumentTypes...)> clase. Representa un puntero a una función, método o un objeto función. Este tipo debe ser asignado en la pila y pasado a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo en C++."
type: docs
weight: 2100
url: /es/cpp/system/delegate_returntype(argumenttypes...)_/
---
## Delegate< ReturnType(ArgumentTypes...)> class


Representa un puntero a una función, método o un objeto función. Este tipo debe ser asignado en la pila y pasado a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


| Parámetro | Descripción |
| --- | --- |
| ReturnType | El tipo de retorno de una función, método o un puntero a objeto función que está representado por la clase |
| ArgumentTypes | La lista de argumentos de una función, método o un puntero a objeto función que está representado por la clase |
## Métodos

| Método | Descripción |
| --- | --- |
| [Delegate](./delegate/)() | Constructor predeterminado. Construye el objeto delegado que no apunta a nada. |
| [Delegate](./delegate/)(const Delegate\&) |  |
| [Delegate](./delegate/)(Delegate\&&) | Constructor de copia con movimiento. Toma la propiedad de una entidad a la que apunta el delegado especificado. |
| [Delegate](./delegate/)(T, typename std::enable_if<!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | Constructor. Construye un objeto delegado a partir del puntero especificado a una función libre o método estático. |
| [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | Constructor. Construye un delegado a partir del puntero especificado al objeto función generado por std::bind(). |
| [Delegate](./delegate/)(int, T\&) | Constructor. Construye un delegado a partir del objeto función especificado. |
| [Delegate](./delegate/)(long, T\&&) | Constructor con movimiento. Construye un delegado a partir del objeto función especificado. |
| [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | Constructor. Construye un delegado que apunta al método no estático especificado del objeto especificado. |
| [Delegate](./delegate/)(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) | Constructor. Construye un delegado que apunta al método no estático especificado del objeto especificado. |
| [Delegate](./delegate/)(std::function\<R(Args...)>) | Construye un objeto delegado que apunta a un objeto función std::function. |
| [Empty](./empty/)() const | Determina si el objeto delegado actual está vacío, p. ej. no apunta a ninguna entidad. |
| [operator()](./operator()/)(ArgumentTypes...) const | Invoca una función, método o un objeto función al que apunta el objeto delegado actual. |
| [operator=](./operator=/)(const Delegate\&) |  |
| [operator=](./operator=/)(Delegate\&&) | Operador de asignación con movimiento. Toma la propiedad de una entidad a la que apunta el delegado especificado. |
| [operator==](./operator==/)(const Delegate\&) const | Compara dos objetos delegados para verificar si apuntan a la misma entidad. |
## Observaciones



```cpp
#include "system/delegate.h"
#include <iostream>

// Declarar el delegado.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // Asignar a la variable la dirección de la función PrintMessage.
  Message mes = Message(&PrintMessage);

  // Llamar a la función.
  mes();

  return 0;
}
/*
This code example produces the following output:
Hello, world!
*/
```

## Ver también

* Namespace [System](../)
* Library [Aspose.Font for C++](../../)
