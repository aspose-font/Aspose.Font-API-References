---
title: "System::Diagnostics::StackTrace class"
linktitle: "StackTrace"
second_title: "Aspose.Font para C++"
description: "Clase System::Diagnostics::StackTrace. Colección de marcos de pila. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 600
url: /es/cpp/system.diagnostics/stacktrace/
---
## StackTrace class


Colección de marcos de pila. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class StackTrace : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_FrameCount](./get_framecount/)() const | Obtiene el recuento de marcos en la traza de pila. |
| virtual [GetFrame](./getframe/)(uint32_t) | Obtiene el marco de pila. |
| [operator=](./operator=/)(const StackTrace\&) const | Sin asignación. |
| [StackTrace](./stacktrace/)() | Crea una traza de pila que describe el estado actual de la pila. |
| [StackTrace](./stacktrace/)(bool) | Crea una traza de pila que describe el estado actual de la pila. |
| [StackTrace](./stacktrace/)(const StackTrace\&) | Sin copia. |
| virtual [~StackTrace](./~stacktrace/)() | Destructor. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.Font for C++](../../)
