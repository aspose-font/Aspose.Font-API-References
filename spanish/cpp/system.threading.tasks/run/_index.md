---
title: "Método System::Threading::Tasks::Run"
linktitle: "Run"
second_title: "Aspose.Font para C++"
description: "Método System::Threading::Tasks::Run. Encola el trabajo especificado para ejecutarse en el pool de subprocesos y devuelve un controlador Task para ese trabajo en C++."
type: docs
weight: 1600
url: /es/cpp/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) method


Encola el trabajo especificado para ejecutarse en el pool de subprocesos y devuelve un controlador [Task](../task/) para ese trabajo.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| action | const Action<>\& | El trabajo a ejecutar de forma asíncrona. |

### ReturnValue

Un [Task](../task/) que representa el trabajo encolado para ejecutarse en el pool de subprocesos.

## Ver también

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Font for C++](../../)
## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) method


Encola el trabajo especificado para ejecutarse en el pool de subprocesos y devuelve un controlador [Task](../task/) para ese trabajo.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| action | const Action<>\& | El trabajo a ejecutar de forma asíncrona. |
| cancellationToken | const CancellationToken\& | Un token de cancelación que puede usarse para cancelar el trabajo si aún no ha comenzado. |

### ReturnValue

Un [Task](../task/) que representa el trabajo encolado para ejecutarse en el pool de subprocesos.

## Ver también

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Font for C++](../../)
## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) method


Encola el trabajo especificado para ejecutarse en el pool de subprocesos y devuelve un proxy para el [Task](../task/) devuelto por la función.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| function | const Func\<TaskPtr\>\& | El trabajo a ejecutar de forma asíncrona, que devuelve un [Task](../task/). |

### ReturnValue

Un [Task](../task/) que representa un proxy para el [Task](../task/) devuelto por la función.

## Ver también

* Typedef [TaskPtr](../../system/taskptr/)
* Class [Func](../../system/func/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Font for C++](../../)
## System::Threading::Tasks::Run(const Func\<TResult\>\&) method


Encola el trabajo especificado para ejecutarse en el grupo de subprocesos y devuelve un manejador [Task<TResult>](../task/) para ese trabajo.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```


| Parámetro | Descripción |
| --- | --- |
| TResult | El tipo del resultado devuelto por la tarea. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| función | const Func\<TResult\>\& | El trabajo a ejecutar de forma asíncrona. |

### ReturnValue

Un [Task<TResult>](../task/) que representa el trabajo encolado para ejecutarse en el grupo de subprocesos.

## Ver también

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Class [Func](../../system/func/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Font for C++](../../)
