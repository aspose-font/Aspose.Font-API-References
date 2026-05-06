---
title: "System::IO::StringReader::Read método"
linktitle: "Read"
second_title: "Aspose.Font para C++"
description: "System::IO::StringReader::Read método. Lee un solo carácter del flujo en C++."
type: docs
weight: 500
url: /es/cpp/system.io/stringreader/read/
---
## StringReader::Read() method


Lee un solo carácter del flujo.

```cpp
virtual int System::IO::StringReader::Read() override
```


### ReturnValue

Un carácter leído o -1 si no se ha leído ningún carácter

## Ver también

* Class [StringReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Font for C++](../../../)
## StringReader::Read(ArrayPtr\<char_t\>, int, int) method


Lee el número especificado de caracteres del flujo al arreglo de caracteres especificado comenzando en la posición especificada.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | ArrayPtr\<char_t\> | La matriz de caracteres donde escribir los caracteres leídos del flujo |
| índice | int | Un índice basado en 0 en **buffer** donde comenzar a escribir |
| count | int | El número de caracteres a leer del flujo |

### ReturnValue

El número de caracteres leídos del flujo

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Font for C++](../../../)
