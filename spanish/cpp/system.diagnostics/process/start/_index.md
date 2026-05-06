---
title: "Método System::Diagnostics::Process::Start"
linktitle: "Iniciar"
second_title: "Aspose.Font para C++"
description: "Método System::Diagnostics::Process::Start. Inicia el proceso con parámetros predefinidos en C++."
type: docs
weight: 1200
url: /es/cpp/system.diagnostics/process/start/
---
## Process::Start() method


Inicia el proceso con parámetros predefinidos.

```cpp
bool System::Diagnostics::Process::Start()
```

## Ver también

* Class [Process](../)
* Namespace [System::Diagnostics](../../)
* Library [Aspose.Font for C++](../../../)
## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) method


Inicia el proceso con la ruta y los argumentos especificados.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| start_info | const SharedPtr\<ProcessStartInfo\>\& | Información sobre el proceso a iniciar. |

### ReturnValue

[Object](../../../system/object/) attached to newly started process.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Process](../)
* Class [ProcessStartInfo](../../processstartinfo/)
* Class [Process](../)
* Namespace [System::Diagnostics](../../)
* Library [Aspose.Font for C++](../../../)
## Process::Start(const String\&, const String\&) method


Inicia el proceso con la ruta y los argumentos especificados.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const String\& | [Process](../) ruta. |
| arguments | const String\& | [Process](../) parámetros. |

### ReturnValue

[Object](../../../system/object/) attached to newly started process.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Process](../)
* Class [String](../../../system/string/)
* Class [Process](../)
* Namespace [System::Diagnostics](../../)
* Library [Aspose.Font for C++](../../../)
