---
title: "System::Threading::TimerQueue clase"
linktitle: "TimerQueue"
second_title: "Aspose.Font para C++"
description: "System::Threading::TimerQueue clase. Cola que maneja objetos Timer. Esto es solo una implementación. Los objetos Timer se registran allí por sí mismos, no tienes que hacerlo para utilizarlos - usa la API de la clase Timer en su lugar. Este es un tipo singleton con gestión de memoria realizada mediante función(es) de acceso. Nunca debe crear instancias de él directamente en C++."
type: docs
weight: 1600
url: /es/cpp/system.threading/timerqueue/
---
## TimerQueue class


Cola que maneja objetos [Timer](../timer/). Esto es solo una implementación. Los objetos [Timer](../timer/) se registran allí por sí mismos, no tienes que hacerlo para utilizarlos - usa la API de la clase [Timer](../timer/) en su lugar. Este es un tipo singleton con gestión de memoria realizada mediante función(es) de acceso. Nunca debe crear instancias de él directamente.

```cpp
class TimerQueue
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(Timer *) | Registra el temporizador en la cola. |
| [Delete](./delete/)(Timer *) | Elimina el temporizador de la cola. |
| static [GetInstance](./getinstance/)() | Singleton de implementación. |
| static [JoinWorkerThread](./joinworkerthread/)() | Une el hilo de trabajo. Espera indefinidamente si es necesario. |
| [operator=](./operator=/)(const TimerQueue\&) | Sin copia. |
| [TimerQueue](./timerqueue/)(const TimerQueue\&) | Sin copia. |
## Ver también

* Namespace [System::Threading](../)
* Library [Aspose.Font for C++](../../)
