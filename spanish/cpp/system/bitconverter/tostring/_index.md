---
title: "Método System::BitConverter::ToString"
linktitle: "ToString"
second_title: "Aspose.Font para C++"
description: "Método System::BitConverter::ToString. Convierte todos los valores del arreglo de bytes especificado en su representación de cadena hexadecimal. El caso de las letras a usar en la notación hexadecimal y el separador insertado entre cada par de bytes adyacentes se especifican mediante los argumentos correspondientes en C++."
type: docs
weight: 1200
url: /es/cpp/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) method


Convierte todos los valores del arreglo de bytes especificado a su representación en cadena hexadecimal. El caso de las letras a usar en la notación hexadecimal y el separador insertado entre cada par de bytes vecinos se especifican mediante los argumentos correspondientes.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=true, const String &separator=u"-")
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const ArrayPtr\<uint8_t\>\& | [Array](../../array/) que contiene bytes para convertir |
| mayúsculas | bool | Especifica el caso de las letras a usar en la representación hexadecimal resultante |
| separador | const String\& | Una cadena utilizada como separador insertado entre cada par de bytes adyacentes en la cadena resultante |

### ReturnValue

[String](../../string/) containing hexadecimal representation of the specified byte array

## Ver también

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) method


Convierte los valores del arreglo de bytes especificado a su representación en cadena hexadecimal comenzando en el índice especificado.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const ArrayPtr\<uint8_t\>\& | [Array](../../array/) que contiene bytes para convertir |
| startIndex | int | Índice en el arreglo especificado en el que comenzar la conversión |

### ReturnValue

[String](../../string/) containing hexadecimal representation of the specified range of elements of the specified array

## Ver también

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) method


Convierte un rango de valores del arreglo de bytes especificado a su representación en cadena hexadecimal.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const ArrayPtr\<uint8_t\>\& | [Array](../../array/) que contiene bytes para convertir |
| startIndex | int | Índice en el arreglo especificado en el que comienza el rango de elementos del arreglo de bytes a convertir |
| longitud | int | La longitud del rango de los elementos del arreglo de bytes a convertir |

### ReturnValue

[String](../../string/) containing hexadecimal representation of the specified range of elements of the specified array

## Ver también

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
