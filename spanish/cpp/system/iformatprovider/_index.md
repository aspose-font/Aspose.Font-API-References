---
title: "System::IFormatProvider clase"
linktitle: "IFormatProvider"
second_title: "Aspose.Font para C++"
description: "System::IFormatProvider clase. Define un método que proporciona información de formato. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 3800
url: /es/cpp/system/iformatprovider/
---
## IFormatProvider class


Define un método que proporciona información de formato. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class IFormatProvider : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [GetFormat](./getformat/)(const TypeInfo\&) | Devuelve un objeto que proporciona servicios de formato para el tipo especificado. |
## Ver también

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.Font for C++](../../)
