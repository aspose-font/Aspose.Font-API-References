---
title: "Método System::String::Equals"
linktitle: "Igual"
second_title: "Aspose.Font para C++"
description: "Método System::String::Equals. Comparación de igualdad de cadenas. Utiliza el modo de comparación System::StringComparison::Ordinal en C++."
type: docs
weight: 1100
url: /es/cpp/system/string/equals/
---
## String::Equals(const String\&) const method


[String](../) equality comparison. Uses [System::StringComparison::Ordinal](../../stringcomparison/) comparison mode.

```cpp
bool System::String::Equals(const String &str) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const String\& | [String](../) para comparar con la actual. |

### ReturnValue

true si las cadenas coinciden, false en caso contrario.

## Ver también

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## String::Equals(const String\&, System::StringComparison) const method


[String](../) equality comparison. Several modes provided by [StringComparison](../../stringcomparison/) enumeration are supported.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const String\& | [String](../) para comparar con la actual. |
| comparison_type | System::StringComparison | Modo [Comparison](../../comparison/) (ver [System::StringComparison](../../stringcomparison/) para más detalles). |

### ReturnValue

true si las cadenas coinciden usando el tipo de comparación seleccionado, false de lo contrario.

## Ver también

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## String::Equals(const String\&, const String\&) method


Equal-compares dos cadenas usando el modo de comparación Ordial.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| strA | const String\& | Primera cadena a comparar. |
| strB | const String\& | Segunda cadena a comparar. |

### ReturnValue

true si las cadenas coinciden, false en caso contrario.

## Ver también

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## String::Equals(const String\&, const String\&, System::StringComparison) method


Equal-compares dos cadenas.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| strA | const String\& | Primera cadena a comparar. |
| strB | const String\& | Segunda cadena a comparar. |
| comparison_type | System::StringComparison | Modo [Comparison](../../comparison/). |

### ReturnValue

true si las cadenas coinciden, false en caso contrario.

## Ver también

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
