---
title: "System::IO::Stream::BeginRead método"
linktitle: "BeginRead"
second_title: "Aspose.Font para C++"
description: "System::IO::Stream::BeginRead método. Inicia una operación de lectura asíncrona en C++."
type: docs
weight: 100
url: /es/cpp/system.io/stream/beginread/
---
## Stream::BeginRead method


Inicia una operación de lectura asíncrona.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Un búfer para leer |
| desplazamiento | int | Un desplazamiento basado en cero en **buffer** que indica la posición desde la cual comenzar a escribir los datos leídos. |
| count | int | El número de bytes a leer |
| callback | System::AsyncCallback | Una devolución de llamada que se invocará cuando la operación se complete. |
| estado | System::SharedPtr\<System::Object\> | Datos proporcionados por el usuario utilizados para identificar de forma única cada operación de lectura asíncrona. |

### ReturnValue

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de lectura asíncrona iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Font for C++](../../../)
