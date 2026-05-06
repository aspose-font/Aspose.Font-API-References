---
title: "Clase System::Threading::ManualResetEvent"
linktitle: "ManualResetEvent"
second_title: "Aspose.Font para C++"
description: "Clase System::Threading::ManualResetEvent. Evento que notifica al hilo en espera y no se restablece automáticamente. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 700
url: /es/cpp/system.threading/manualresetevent/
---
## ManualResetEvent class


[Event](../../system/event/) to notify waiting thread that does not reset automatically. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ManualResetEvent : public System::Threading::EventWaitHandle
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ManualResetEvent](./manualresetevent/)(bool) | Información RTTI. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Valor especial que debe devolver la función, de lo contrario devuelve el índice del objeto señalizado en la matriz, si el tiempo de espera supera el límite y nada se señala. |
## Ver también

* Class [EventWaitHandle](../eventwaithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.Font for C++](../../)
