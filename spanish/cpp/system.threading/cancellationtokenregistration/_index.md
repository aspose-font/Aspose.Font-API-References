---
title: "System::Threading::CancellationTokenRegistration clase"
linktitle: "CancellationTokenRegistration"
second_title: "Aspose.Font para C++"
description: "System::Threading::CancellationTokenRegistration clase. Representa un registro para una devolución de llamada de token de cancelación en C++."
type: docs
weight: 300
url: /es/cpp/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration class


Representa un registro para una devolución de llamada de token de cancelación.

```cpp
class CancellationTokenRegistration
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Dispose](./dispose/)() | Dispone del registro y elimina la devolución de llamada del [CancellationTokenSource](../cancellationtokensource/) asociado. Después de llamar a este método, la devolución de llamada registrada ya no se invocará cuando el [CancellationTokenSource](../cancellationtokensource/) asociado se cancele. |
## Observaciones


Esta clase permite la anulación del registro de una devolución de llamada de un token de cancelación. Cuando se dispone, elimina la devolución de llamada del [CancellationTokenSource](../cancellationtokensource/) asociado.
Esta clase no debe crearse directamente - es devuelta por los métodos de registro de [CancellationToken](../cancellationtoken/).

## Ver también

* Namespace [System::Threading](../)
* Library [Aspose.Font for C++](../../)
