---
title: "System::Threading::ThreadPool::QueueUserWorkItem método"
linktitle: "QueueUserWorkItem"
second_title: "Aspose.Font para C++"
description: "System::Threading::ThreadPool::QueueUserWorkItem método. Inserta un elemento de trabajo en la cola que está presente con una devolución de llamada sin parámetros en C++."
type: docs
weight: 600
url: /es/cpp/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) method


Inserta el elemento de trabajo en la cola que está presente con una devolución de llamada sin parámetros.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | WaitCallback | Función de devolución de llamada a usar como trabajo. |

### ReturnValue

Siempre devuelve true.

## Ver también

* Typedef [WaitCallback](../../waitcallback/)
* Class [ThreadPool](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Font for C++](../../../)
## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) method


Inserta el elemento de trabajo en la cola que está presente con una devolución de llamada sin parámetros.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | WaitCallback | Función de devolución de llamada a usar como trabajo. |
| estado | const System::SharedPtr\<System::Object\>\& | Parámetro de la función de trabajo. |

### ReturnValue

Siempre devuelve true.

## Ver también

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ThreadPool](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Font for C++](../../../)
