---
title: "Método System::Default"
linktitle: "Predeterminado"
second_title: "Aspose.Font para C++"
description: "Método System::Default. Devuelve la referencia a la única instancia construida por defecto del tipo de excepción en C++."
type: docs
weight: 16300
url: /es/cpp/system/default/
---
## System::Default() method


Devuelve la referencia a la única instancia construida por defecto del tipo de excepción.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo cuya instancia se devuelve |

## Ver también

* Namespace [System](../)
* Library [Aspose.Font for C++](../../)
## System::Default() method


Devuelve la referencia a la única instancia construida por defecto del tipo que no es una excepción.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo cuya instancia se devuelve |

## Ver también

* Namespace [System](../)
* Library [Aspose.Font for C++](../../)
