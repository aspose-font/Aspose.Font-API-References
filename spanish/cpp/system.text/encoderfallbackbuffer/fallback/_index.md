---
title: "Método System::Text::EncoderFallbackBuffer::Fallback"
linktitle: "Fallback"
second_title: "Aspose.Font para C++"
description: "Método System::Text::EncoderFallbackBuffer::Fallback. Implementa el procedimiento de reserva real en C++."
type: docs
weight: 100
url: /es/cpp/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) method


Implementa el procedimiento de reserva real.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| charUnknown | char_t | El codificador de caracteres falla al codificar. |
| índice | int | Índice del carácter que provocó el error. |

### ReturnValue

Verdadero si el búfer procesa caracteres desconocidos, falso si los ignora.

## Ver también

* Class [EncoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.Font for C++](../../../)
## EncoderFallbackBuffer::Fallback(char_t, char_t, int) method


Implementa el procedimiento de reserva real.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| charUnknownHigh | char_t | Parte alta del par sustituto que provocó el error. |
| charUnknownLow | char_t | Parte baja del par sustituto que provocó el error. |
| índice | int | Índice del carácter que provocó el error. |

### ReturnValue

Verdadero si el búfer procesa caracteres desconocidos, falso si los ignora.

## Ver también

* Class [EncoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.Font for C++](../../../)
