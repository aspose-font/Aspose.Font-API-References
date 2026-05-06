---
title: "Método TryGetBuffer de System::IO::MemoryStream"
linktitle: "TryGetBuffer"
second_title: "Aspose.Font para C++"
description: "Método TryGetBuffer de System::IO::MemoryStream. Devuelve la matriz de bytes sin signo con la que se creó este flujo en C++."
type: docs
weight: 1800
url: /es/cpp/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer method


Devuelve la matriz de bytes sin signo a partir de la cual se creó este flujo.

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | ArraySegment\<uint8_t\>\& | matriz de bytes - parámetro de salida. Cuando este método devuelve true, el segmento de matriz de bytes con el que se creó este flujo; cuando devuelve false, este parámetro se establece al valor predeterminado. |

### ReturnValue

True si la conversión tuvo éxito.

## Ver también

* Class [ArraySegment](../../../system/arraysegment/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Font for C++](../../../)
