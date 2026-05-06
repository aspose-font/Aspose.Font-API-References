---
title: "System::Threading::Thread::Join método"
linktitle: "Join"
second_title: "Aspose.Font para C++"
description: "System::Threading::Thread::Join método. Une el hilo administrado. Realiza una espera ilimitada si es necesario en C++."
type: docs
weight: 1400
url: /es/cpp/system.threading/thread/join/
---
## Thread::Join() method


Une el hilo gestionado. Realiza una espera ilimitada si es necesario.

```cpp
void System::Threading::Thread::Join()
```

## Ver también

* Class [Thread](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Font for C++](../../../)
## Thread::Join(int) method


Une el hilo gestionado. Realiza una espera limitada.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| millisecondsTimeout | int | Tiempo de espera en milisegundos. |

### ReturnValue

Verdadero si el hilo se unió correctamente, falso si se superó el tiempo de espera.

## Ver también

* Class [Thread](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Font for C++](../../../)
## Thread::Join(TimeSpan) method


Une el hilo gestionado. Realiza una espera limitada.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| timeout | TimeSpan | Un [TimeSpan](../../../system/timespan/) establecido a la cantidad de tiempo para esperar a que el hilo termine. |

### ReturnValue

Verdadero si el hilo se unió correctamente, falso si se superó el tiempo de espera.

## Ver también

* Class [TimeSpan](../../../system/timespan/)
* Class [Thread](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Font for C++](../../../)
