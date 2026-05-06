---
title: "System::IO::BufferedStream::Read método"
linktitle: "Read"
second_title: "Aspose.Font para C++"
description: "System::IO::BufferedStream::Read método. Lee la cantidad especificada de bytes del flujo subyacente y los escribe en el arreglo de bytes especificado en C++."
type: docs
weight: 900
url: /es/cpp/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Lee la cantidad especificada de bytes del flujo subyacente y los escribe en la matriz de bytes especificada.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | El arreglo de bytes donde escribir los bytes leídos |
| desplazamiento | int32_t | Una posición basada en cero en **buffer** para comenzar a escribir |
| count | int32_t | El número de bytes a leer |

### ReturnValue

El número de bytes leídos

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Font for C++](../../../)
## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Lee la cantidad especificada de bytes del flujo subyacente y los escribe en la matriz de bytes especificada.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | El arreglo de bytes donde escribir los bytes leídos |
| desplazamiento | int32_t | Una posición basada en cero en **buffer** para comenzar a escribir |
| count | int32_t | El número de bytes a leer |

### ReturnValue

El número de bytes leídos

## Ver también

* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Font for C++](../../../)
