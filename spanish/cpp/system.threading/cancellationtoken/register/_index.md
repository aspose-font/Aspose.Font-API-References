---
title: "Método System::Threading::CancellationToken::Register"
linktitle: "Registrar"
second_title: "Aspose.Font para C++"
description: "Método System::Threading::CancellationToken::Register. Registra una devolución de llamada que se invocará cuando se solicite la cancelación en C++."
type: docs
weight: 400
url: /es/cpp/system.threading/cancellationtoken/register/
---
## CancellationToken::Register method


Registra una devolución de llamada que se invocará cuando se solicite la cancelación.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | const Action<>\& | El [Action<>](../../../system/action/) que se ejecutará cuando se solicite la cancelación. |

### ReturnValue

Un objeto [CancellationTokenRegistration](../../cancellationtokenregistration/) que puede usarse para anular el registro de la devolución de llamada.
## Observaciones



Si la cancelación ya ha sido solicitada, la devolución de llamada se invocará inmediatamente.

## Ver también

* Class [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Typedef [Action](../../../system/action/)
* Class [CancellationToken](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Font for C++](../../../)
