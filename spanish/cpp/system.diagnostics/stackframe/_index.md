---
title: "Clase System::Diagnostics::StackFrame"
linktitle: "StackFrame"
second_title: "Aspose.Font para C++"
description: "Clase System::Diagnostics::StackFrame. Obtiene información sobre un único marco de pila. Solo MSVS. Los objetos de esta clase deben asignarse únicamente mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y utilice dicho puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 500
url: /es/cpp/system.diagnostics/stackframe/
---
## StackFrame class


Obtiene información sobre un único marco de pila. Solo MSVS. Los objetos de esta clase deben asignarse únicamente mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y utilice dicho puntero para pasarla a funciones como argumento.

```cpp
class StackFrame : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [GetFileColumnNumber](./getfilecolumnnumber/)() | Obtiene el número colnum. |
| virtual [GetFileLineNumber](./getfilelinenumber/)() | Obtiene el número de línea. |
| virtual [GetFileName](./getfilename/)() | Obtiene el nombre del archivo. |
| [GetMethod](./getmethod/)() | Obtiene información del método. |
| [operator=](./operator=/)(const StackFrame\&) const | Sin cambios. |
| [StackFrame](./stackframe/)(int) | Crea un marco de pila en el desplazamiento de pila actual. |
| [StackFrame](./stackframe/)(const StackFrame\&) | Sin copia. |
| virtual [~StackFrame](./~stackframe/)() | Destructor. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.Font for C++](../../)
