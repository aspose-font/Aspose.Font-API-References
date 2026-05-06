---
title: "Clase System::Collections::Generic::IComparer"
linktitle: "IComparer"
second_title: "Aspose.Font para C++"
description: "Clase System::Collections::Generic::IComparer. Interfaz que compara dos objetos en sentido mayor-igual-menor. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 2000
url: /es/cpp/system.collections.generic/icomparer/
---
## IComparer class


Interfaz que compara dos objetos en sentido mayor-igual-menor. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
template<typename T>class IComparer : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Compare](./compare/)(args_type, args_type) const | Función [Comparison](../../system/comparison/). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [args_type](./args_type/) | Información RTTI. |

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Font for C++](../../)
