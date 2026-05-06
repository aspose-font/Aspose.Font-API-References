---
title: "Clase System::Collections::Generic::DefaultComparer"
linktitle: "DefaultComparer"
second_title: "Aspose.Font para C++"
description: "Clase System::Collections::Generic::DefaultComparer. Clase comparadora predeterminada. Utiliza los operadores < y == para comparar valores. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1000
url: /es/cpp/system.collections.generic/defaultcomparer/
---
## DefaultComparer class


Clase comparadora predeterminada. Utiliza los operadores < y == para comparar valores. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
template<class T>class DefaultComparer : public System::Collections::Generic::IComparer<T>
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo que se está comparando. |
## Métodos

| Método | Descripción |
| --- | --- |
| [Compare](./compare/)(typename ThisType::args_type, typename ThisType::args_type) const override | Información RTTI. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [BaseType](./basetype/) | Interfaz implementada. |
| [ThisType](./thistype/) | Tipo actual. |

## Ver también

* Class [IComparer](../icomparer/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Font for C++](../../)
