---
title: "Clase System::IEquatable"
linktitle: "IEquatable"
second_title: "Aspose.Font para C++"
description: "Clase System::IEquatable. Define un método que determina la igualdad de dos objetos. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 3700
url: /es/cpp/system/iequatable/
---
## IEquatable class


Define un método que determina la igualdad de dos objetos. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
template<typename T>class IEquatable : public virtual System::Object
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los objetos comparados |
## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Equals](./equals/)(T) | Determina si los objetos actual y especificado son iguales. |

## Ver también

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.Font for C++](../../)
