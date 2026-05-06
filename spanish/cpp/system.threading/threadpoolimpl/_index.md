---
title: "System::Threading::ThreadPoolImpl clase"
linktitle: "ThreadPoolImpl"
second_title: "Aspose.Font para C++"
description: "System::Threading::ThreadPoolImpl clase. Datos internos del grupo de subprocesos. Este es un tipo singleton con la gestión de memoria realizada por función(es) de acceso. Nunca deberías crear instancias de él directamente en C++."
type: docs
weight: 1400
url: /es/cpp/system.threading/threadpoolimpl/
---
## ThreadPoolImpl class


[Thread](../thread/) pool internal data. This is a singleton type with memory management done by access function(s). You should never create instances of it directly.

```cpp
class ThreadPoolImpl
```

## Métodos

| Método | Descripción |
| --- | --- |
| [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Obtiene el número de subprocesos disponibles. |
| static [GetInitialized](./getinitialized/)() | Obtiene el singleton del estado de inicialización. |
| [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Obtiene el número máximo de subprocesos concurrentes. |
| [GetMinThreads](./getminthreads/)(int\&, int\&) | Obtiene el número mínimo de subprocesos creados por el grupo. |
| [JoinAll](./joinall/)() | Une todos los subprocesos propios. Espera indefinidamente. |
| [QueueUserWorkItem](./queueuserworkitem/)(WaitCallback, const System::SharedPtr\<System::Object\>\&) | Agrega un elemento de trabajo a la cola. |
| [SetMaxThreads](./setmaxthreads/)(int, int) | Establece el número de subprocesos propios del grupo. |
| [SetMinThreads](./setminthreads/)(int, int) | Establece el número mínimo de subprocesos propios del grupo. |
| [ThreadPoolImpl](./threadpoolimpl/)() | Constructor. |
| [~ThreadPoolImpl](./~threadpoolimpl/)() | Destructor. Une todos los subprocesos si aún no se han terminado. |
## Ver también

* Namespace [System::Threading](../)
* Library [Aspose.Font for C++](../../)
