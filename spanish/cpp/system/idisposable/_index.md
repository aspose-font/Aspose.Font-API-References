---
title: "Clase System::IDisposable"
linktitle: "IDisposable"
second_title: "Aspose.Font para C++"
description: "Clase System::IDisposable. Define un método que libera los recursos poseídos por el objeto actual. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 3600
url: /es/cpp/system/idisposable/
---
## IDisposable class


Define un método que libera los recursos poseídos por el objeto actual. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class IDisposable : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Dispose](./dispose/)() | No hace nada. |
## Ver también

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.Font for C++](../../)
