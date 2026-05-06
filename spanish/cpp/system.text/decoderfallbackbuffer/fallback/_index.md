---
title: "System::Text::DecoderFallbackBuffer::Fallback method"
linktitle: "Fallback"
second_title: "Aspose.Font para C++"
description: "System::Text::DecoderFallbackBuffer::Fallback method. Implementa el procedimiento de reserva real en C++."
type: docs
weight: 100
url: /es/cpp/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback method


Implementa el procedimiento de reserva real.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytesUnknown | ArrayPtr\<uint8_t\> | [Array](../../../system/array/) de bytes que incluyen el que el decodificador no puede decodificar. |
| índice | int | Índice del byte que provocó el error. |

### ReturnValue

Verdadero si el búfer procesa bytes desconocidos, falso si los ignora.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DecoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.Font for C++](../../../)
