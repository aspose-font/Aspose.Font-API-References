---
title: "System::Diagnostics::TraceListener clase"
linktitle: "TraceListener"
second_title: "Aspose.Font para C++"
description: "System::Diagnostics::TraceListener clase. Interfaz para reaccionar a información de depuración y trazado. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 800
url: /es/cpp/system.diagnostics/tracelistener/
---
## TraceListener class


Interfaz para reaccionar a información de depuración y trazado. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class TraceListener : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Fail](./fail/)(System::String) | Escribe mensaje de fallo en el depurador. |
| virtual [Fail](./fail/)(System::String, System::String) | Escribe mensaje de fallo en el depurador. |
| virtual [Write](./write/)(System::String) | Información RTTI. |
| virtual [WriteLine](./writeline/)(System::String) | Escribe una línea en el depurador. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.Font for C++](../../)
