---
title: "System::IO::TextReader::Read método"
linktitle: "Read"
second_title: "Aspose.Font para C++"
description: "System::IO::TextReader::Read método. Lee un solo carácter del flujo en C++."
type: docs
weight: 400
url: /es/cpp/system.io/textreader/read/
---
## TextReader::Read() method


Lee un solo carácter del flujo.

```cpp
virtual int System::IO::TextReader::Read()
```


### ReturnValue

Leer carácter codificado con codificación UTF-16; si el carácter leído está representado por dos puntos de código en la codificación UTF-16, solo se devuelve el surrogate alto.

## Ver también

* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Font for C++](../../../)
## TextReader::Read(ArrayPtr\<char_t\>, int, int) method


Lee la cantidad especificada de caracteres del flujo y los escribe en la matriz de caracteres especificada comenzando en la posición especificada.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | ArrayPtr\<char_t\> | La matriz de caracteres UTF-16 para escribir los caracteres leídos del flujo |
| índice | int | Un índice basado en 0 en **buffer** donde comenzar a escribir |
| count | int | El número de caracteres a leer del flujo |

### ReturnValue

El número de caracteres leídos del flujo

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Font for C++](../../../)
