---
title: "System::Threading::EventWaitHandle clase"
linktitle: "EventWaitHandle"
second_title: "Aspose.Font para C++"
description: "Clase System::Threading::EventWaitHandle. Evento que puede ser enviado a un hilo en espera. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 500
url: /es/cpp/system.threading/eventwaithandle/
---
## EventWaitHandle class


[Event](../../system/event/) that can be sent to waiting thread. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EventWaitHandle : public System::Threading::WaitHandle
```

## Métodos

| Método | Descripción |
| --- | --- |
| [EventWaitHandle](./eventwaithandle/)(bool, EventResetMode) | Información RTTI. |
| virtual [Reset](./reset/)() | Establece el evento en estado no señalizador. |
| virtual [Set](./set/)() | Establece el evento en estado señalizador. |
| [~EventWaitHandle](./~eventwaithandle/)() | Destructor. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Valor especial que debe devolver la función, de lo contrario devuelve el índice del objeto señalizado en la matriz, si el tiempo de espera supera el límite y nada se señala. |
## Ver también

* Class [WaitHandle](../waithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.Font for C++](../../)
